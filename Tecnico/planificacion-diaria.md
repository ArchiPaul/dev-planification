# PLANIFICACION DIARIA OPERATIVA (28 SEMANAS)

Base: `NEW/main/semanal-ajustada.md`  
Objetivo: ejecutar la semanal con entregable diario y control de avance mensual.

---

## Horario Diario Fijo (fin 18:00)

- 07:00-07:15 Activacion
- 07:15-08:00 Ejercicio
- 08:00-08:30 Bano
- 08:30-09:30 Teoria T1 (temas principal del dia)
- 09:30-09:45 Pausa       
- 09:45-10:30 Teoria T2 (temas principal del dia)
- 10:30-10:45 Pausa
- 10:45-12:15 Practica (mismo tema)
- 12:15-12:30 Pausa
- 12:30-13:00 Consolidacion Temas nuevos (resumen + preguntas)
- 13:00-14:15 Alimentacion
- 14:15-15:00 Entrevista (preguntas/ejercicios)
- 15:00-15:15 Pausa
- 15:15-16:00 Ingles tecnico
- 16:15-17:15 Complementario (tests/CI/docs del mismo tema)
- 17:15-18:00 Cierre de dia

Regla: no introducir tema nuevo en el bloque complementario.

---

## Que Se Hace En Cada Bloque (alineado al temario semanal)

Fuente obligatoria diaria: `NEW/main/semanal-ajustada.md`
- De `### Bloques de temas` sale el **tema principal** del dia.
- De `### Bloque de practicas` sale la **practica aplicada** del dia.
- De `### Avance Producto Mensual` sale el **entregable** y el `% acumulado` esperado.

Distribucion L-V desde el temario:
- Lunes: primer grupo de temas de la semana (fundamentos).
- Martes: segundo grupo (continuacion tecnica).
- Miercoles: tercer grupo (aplicacion y validacion).
- Jueves: practica AWS/arquitectura o tema de mayor complejidad de la semana.
- Viernes: integracion + cierre de la meta semanal.

Ejecucion por bloque:
- 08:30-10:30 Teoria:
  - Estudiar SOLO el tema del dia tomado de `Bloques de temas`.
  - Objetivo: entender concepto + decisiones de uso (cuando si/cuando no).
- 10:45-12:15 Practica:
  - Implementar SOLO la practica vinculada al tema del dia.
  - Debe impactar el producto mensual de esa semana.
- 12:15-12:45 Consolidacion:
  - Resumen corto del tema del dia.
  - 3 preguntas de recuperacion activa del mismo tema.
- 14:15-15:00 Entrevista:
  - 3 preguntas del tema del dia (nivel entrevista).
  - 1 respuesta con trade-off tecnico.
- 15:15-16:00 Ingles tecnico:
  - 10 terminos del tema del dia.
  - Explicar el concepto en ingles 3-5 min.
- 16:15-17:15 Complementario:
  - Tests/CI/doc/refactor de lo implementado en la manana.
  - Prohibido abrir tema nuevo.
- 17:15-18:00 Cierre:
  - Commit + evidencia + actualizacion de `% acumulado` contra la meta semanal.
  - Plan exacto del tema de manana (segun orden de la semana).

Formato diario obligatorio:
- Tema principal (desde Bloques de temas):
- Practica del dia (desde Bloque de practicas):
- Entregable del dia (impacto al producto mensual):
- % esperado hoy:
- % real hoy:

---

## Definicion de Producto Diario

Cada dia debe cerrar con:
- 1 commit util (codigo o documentacion tecnica).
- 1 evidencia (test, captura, log, dashboard o mini-doc).
- 1 actualizacion de avance mensual (%).

Plantilla de cierre:
- Hoy avance:
- Entregable:
- Bloqueo:
- Solucion:
- Avance mensual acumulado:
- Manana prioridad #1:

Ficha diaria rapida:
- Tema del dia:
- Que voy a construir:
- Evidencia minima:
- Resultado esperado al cierre:

---

## Regla Semanal -> Diaria (obligatoria)

Esta planificacion diaria se construye **siempre** desde la semana activa en `semanal-ajustada.md`.

Mapeo fijo por dia (L-V):
- Lunes: Tema A del bloque semanal + practica minima.
- Martes: Tema B del bloque semanal + practica minima.
- Miercoles: Tema C del bloque semanal + practica minima.
- Jueves: Tema D del bloque semanal + practica minima.
- Viernes: consolidacion semanal + cierre de practicas + evidencia final.

Regla de foco:
- En un dia solo se trabaja el tema asignado de la semana (sin mezclar temas nuevos).
- El bloque complementario solo refuerza ese mismo tema (tests, CI/CD, docs).
- Si la semana trae lista anidada (ej. Auto Scaling, Failure Modeling), cada subtema cuenta como tema diario.

Checklist diario obligatorio (derivado de la semanal):
- Tema semanal trabajado:
- Practica asociada completada:
- Evidencia subida (commit/doc/test):
- % acumulado actualizado:

---

## Distribucion de Avance Mensual por Semana

- Mes 1: Semana 1 `20%`, Semana 2 `40%`, Semana 3 `65%`, Semana 4 `100%`
- Mes 2: Semana 5 `20%`, Semana 6 `45%`, Semana 7 `70%`, Semana 8 `100%`
- Mes 3: Semana 9 `20%`, Semana 10 `45%`, Semana 11 `65%`, Semana 12 `100%`
- Mes 4: Semana 13 `25%`, Semana 14 `50%`, Semana 15 `70%`, Semana 16 `100%`
- Mes 5: Semana 17 `25%`, Semana 18 `50%`, Semana 19 `75%`, Semana 20 `100%`
- Mes 6: Semana 21 `25%`, Semana 22 `50%`, Semana 23 `75%`, Semana 24 `100%`
- Mes 7: Semana 25 `25%`, Semana 26 `50%`, Semana 27 `75%`, Semana 28 `100%`

---

# MES 1 - core-engine-lab

## Semana 1 (meta acumulada 20%)

**Producto mensual:** `core-engine-lab`  
**Producto semanal:** base del repo + primera pieza POO testeada + practica IAM minima.

### Lunes (4%)
- Tema principal: setup tecnico del producto (`repo`, estructura, README base).
- Cross/complementario: Git profesional + conventional commits.
- Horario aplicado:
  - 08:30-10:30: definir arquitectura minima del repo y convenciones.
  - 10:45-12:15: crear estructura y README inicial.
  - 16:15-17:15: configurar plantilla de commit y checklist de PR.
- Producto diario: repo inicial funcional + README v1 + primer commit estandar.

### Martes (8%)
- Tema principal: POO (encapsulacion + abstraccion).
- Cross/complementario: resolucion estructurada de problemas.
- Horario aplicado:
  - 08:30-10:30: teoria POO aplicada al dominio del proyecto.
  - 10:45-12:15: implementar 1 clase inmutable con API limpia.
  - 16:15-17:15: refactor de nombres/contratos y mini-doc de decisiones.
- Producto diario: clase inmutable + tests basicos de constructor/comportamiento.

### Miercoles (12%)
- Tema principal: testing unitario base.
- Cross/complementario: calidad de codigo (naming + legibilidad).
- Horario aplicado:
  - 08:30-10:30: JUnit base y criterios de test limpio.
  - 10:45-12:15: crear suite de pruebas unitarias para clase del martes.
  - 16:15-17:15: limpiar naming, organizar paquetes y cobertura inicial.
- Producto diario: set de tests unitarios ejecutando en verde.

### Jueves (16%)
- Tema principal: AWS IAM (usuario/rol de minimo privilegio).
- Cross/complementario: seguridad de credenciales (fail fast de permisos).
- Horario aplicado:
  - 08:30-10:30: teoria IAM (Users, Roles, Policies, least privilege).
  - 10:45-12:15: crear usuario/rol/policy para caso practico.
  - 16:15-17:15: documentar permisos y validar accesos permitidos/denegados.
- Producto diario: configuracion IAM minima reproducible + evidencia (capturas/comandos).

### Viernes (20%)
- Tema principal: consolidacion semanal.
- Cross/complementario: comunicacion tecnica (resumen defendible).
- Horario aplicado:
  - 08:30-10:30: repaso activo de temas de la semana.
  - 10:45-12:15: cerrar pendientes tecnicos y estabilizar repo.
  - 16:15-17:15: redactar mini-doc de decisiones POO + cierre semanal.
- Producto diario: mini-doc tecnico + commit final semanal.

### Cierre Semana 1
- Producto semanal entregado:
  - repo base operativo
  - clase inmutable con pruebas
  - IAM minimo privilegio validado
- Avance mensual acumulado: `20%` de `core-engine-lab`.

## Semana 2 (meta acumulada 40%)
- Lunes (24%): herencia vs composicion con ejemplo real.
- Martes (28%): polimorfismo + records comparativo.
- Miercoles (32%): Mockito intro en pruebas del ejemplo.
- Jueves (36%): S3 bucket + operaciones basicas.
- Viernes (40%): PR estructurado + checklist code review aplicado.

## Semana 3 (meta acumulada 65%)
- Lunes (45%): Big-O y notas de complejidad.
- Martes (50%): HashMap internals + ejemplo.
- Miercoles (55%): listas (ArrayList/LinkedList) benchmark simple.
- Jueves (60%): AWS CLI perfiles + operaciones S3.
- Viernes (65%): mini-doc HashMap + base de LRU preparada.

## Semana 4 (meta acumulada 100%)
- Lunes (74%): JMM, volatile, synchronized vs lock (demo).
- Martes (83%): ExecutorService, atomics, ConcurrentHashMap.
- Miercoles (90%): deadlock/race conditions reproducibles + notas.
- Jueves (95%): SDK Java S3 CRUD + manejo credenciales.
- Viernes (100%): LRU final + tests >=70% + README defendible.

---

# MES 2 - order-service-monolith

## Semana 5 (meta acumulada 20%)
- Lunes (4%): bootstrap Spring Boot + estructura en capas.
- Martes (8%): controller + service (vertical slice).
- Miercoles (12%): DispatcherServlet/ciclo request documentado.
- Jueves (16%): validacion basica endpoint + codigos HTTP.
- Viernes (20%): API skeleton estable + doc de inicio.

## Semana 6 (meta acumulada 45%)
- Lunes (25%): filtros vs interceptors implementados.
- Martes (30%): @Valid + BindingResult + errores base.
- Miercoles (35%): Dockerfile inicial + run local.
- Jueves (40%): versionado API + GitFlow aplicado.
- Viernes (45%): CRUD base robusto + commit semanal.

## Semana 7 (meta acumulada 70%)
- Lunes (50%): IoC/beans/scopes experimento practico.
- Martes (55%): perfiles dev/prod + env vars seguras.
- Miercoles (60%): Jackson + ResponseEntity avanzado.
- Jueves (65%): Clean/Hexagonal ajustes de estructura.
- Viernes (70%): documento request/response + filtros/interceptors.

## Semana 8 (meta acumulada 100%)
- Lunes (78%): JPA internals + N+1 + lazy/eager.
- Martes (86%): indices + EXPLAIN + locking.
- Miercoles (92%): @ControllerAdvice + transactional correcto.
- Jueves (96%): deploy Beanstalk + logs + rollback.
- Viernes (100%): API completa, dockerizada, CI basico, doc arquitectura.

---

# MES 3 - inventory-reactive-service

## Semana 9 (meta acumulada 20%)
- Lunes (4%): proyecto WebFlux base.
- Martes (8%): Mono/Flux + endpoint reactivo.
- Miercoles (12%): WebClient llamada externa.
- Jueves (16%): DynamoDB tabla + CRUD minimo.
- Viernes (20%): base funcional + notas de thread model.

## Semana 10 (meta acumulada 45%)
- Lunes (25%): error handling reactivo.
- Martes (30%): timeout + retry/backoff.
- Miercoles (35%): SQS productor/consumidor minimo.
- Jueves (40%): idempotencia HTTP + keys.
- Viernes (45%): flujo reactivo robusto + pruebas minimas.

## Semana 11 (meta acumulada 65%)
- Lunes (49%): backpressure + scheduler tuning.
- Martes (53%): cache Caffeine/Redis + TTL.
- Miercoles (57%): invalidacion cache + doc breve.
- Jueves (61%): SNS -> SQS + DLQ basica.
- Viernes (65%): observabilidad base (logs + metricas).

## Semana 12 (meta acumulada 100%)
- Lunes (74%): Testcontainers + integration tests.
- Martes (83%): API Gateway + ECS conexion base.
- Miercoles (90%): operacion SQS/SNS avanzada (FIFO, dedup, redrive).
- Jueves (95%): dashboards + alarmas CloudWatch.
- Viernes (100%): deploy final + comparativo MVC/WebFlux + postmortem.

---

# MES 4 - payment-event-driven-system

## Semana 13 (meta acumulada 25%)
- Lunes (5%): esqueleto event-driven.
- Martes (10%): retry + idempotencia consumidor.
- Miercoles (15%): at-least-once vs exactly-once demo.
- Jueves (20%): logs estructurados.
- Viernes (25%): cola + consumidor base estable.

## Semana 14 (meta acumulada 50%)
- Lunes (30%): outbox simulado.
- Martes (35%): consistencia eventual caso real.
- Miercoles (40%): correlation ID end-to-end.
- Jueves (45%): DLQ monitoring base.
- Viernes (50%): happy path + DLQ funcionando.

## Semana 15 (meta acumulada 70%)
- Lunes (55%): saga minima/compensacion.
- Martes (60%): CQRS trade-offs documentados.
- Miercoles (64%): Micrometer instrumentacion.
- Jueves (67%): alerting basico.
- Viernes (70%): caso de fallo + recuperacion documentada.

## Semana 16 (meta acumulada 100%)
- Lunes (78%): Prometheus/Grafana base.
- Martes (86%): RED metrics + dashboard minimo.
- Miercoles (92%): correlacion logs-metricas-trazas.
- Jueves (96%): simulacion incidente + hallazgos.
- Viernes (100%): sistema final + documento consistencia/fallo.

---

# MES 5 - secure-gateway-service

## Semana 17 (meta acumulada 25%)
- Lunes (5%): skeleton gateway.
- Martes (10%): OAuth2 flujo base.
- Miercoles (15%): JWT emision/validacion.
- Jueves (20%): minimo privilegio + STRIDE inicial.
- Viernes (25%): auth basico estable.

## Semana 18 (meta acumulada 50%)
- Lunes (30%): BCrypt + hardening credenciales.
- Martes (35%): OWASP top 10 aplicado.
- Miercoles (40%): OWASP API top 10 aplicado.
- Jueves (45%): CORS/CSRF + security headers.
- Viernes (50%): rate limiting + doc amenazas/mitigaciones.

## Semana 19 (meta acumulada 75%)
- Lunes (55%): throughput/latency p95/p99.
- Martes (60%): profiling CPU/memory.
- Miercoles (65%): heap/thread dumps + deadlock.
- Jueves (70%): docker resource limits + OOM.
- Viernes (75%): evidencia de performance + recomendaciones.

## Semana 20 (meta acumulada 100%)
- Lunes (82%): GC tuning + JFR.
- Martes (89%): JMC analisis.
- Miercoles (94%): blue/green y canary simulados.
- Jueves (97%): rollback strategy + postmortem.
- Viernes (100%): gateway final + documento seguridad.

---

# MES 6 - high-availability-architecture

## Semana 21 (meta acumulada 25%)
- Lunes (5%): VPC y CIDR inicial.
- Martes (10%): subnetting public/private.
- Miercoles (15%): route tables.
- Jueves (20%): estimacion QPS inicial.
- Viernes (25%): diagrama base + supuestos.

## Semana 22 (meta acumulada 50%)
- Lunes (30%): SG vs NACL escenarios.
- Martes (35%): NAT Gateway y validaciones.
- Miercoles (40%): concurrencia pico + conexiones DB.
- Jueves (45%): throughput vs latency + runbook base.
- Viernes (50%): seccion redes + primeros costos.

## Semana 23 (meta acumulada 75%)
- Lunes (55%): ALB vs NLB + target groups.
- Martes (60%): health checks + fallos tipicos.
- Miercoles (65%): auto scaling policies.
- Jueves (70%): failure modeling (AZ down, target unhealthy).
- Viernes (75%): IOPS + cross-AZ + doc HA/ASG.

## Semana 24 (meta acumulada 100%)
- Lunes (82%): escenarios NAT/DNS y DB lenta.
- Martes (89%): estrategias resiliencia (retry/cb/backpressure).
- Miercoles (94%): cost modeling ALB/EC2/RDS/transfer.
- Jueves (97%): trade-offs + plan rollback.
- Viernes (100%): documento final completo defendible.

---

# MES 7 - distributed-ecommerce-platform

## Semana 25 (meta acumulada 25%)
- Lunes (5%): estrategia multi-region.
- Martes (10%): DR (backup, pilot light, warm standby).
- Miercoles (15%): RTO/RPO definidos.
- Jueves (20%): Well-Architected aplicado.
- Viernes (25%): baseline arquitectura + DR documentado.

## Semana 26 (meta acumulada 50%)
- Lunes (30%): estimaciones QPS/DAU/MAU.
- Martes (35%): storage y crecimiento.
- Miercoles (40%): SLO p95 + bottleneck inicial.
- Jueves (45%): cache distribuido (TTL/invalidation/stampede).
- Viernes (50%): Diseno 1 completo + writing drill.

## Semana 27 (meta acumulada 75%)
- Lunes (55%): rate limiting distribuido.
- Martes (60%): sharding/particionamiento.
- Miercoles (65%): consistencia fuerte vs eventual.
- Jueves (70%): colas + DLQ resiliencia.
- Viernes (75%): Diseno 2 completo + postmortem.

## Semana 28 (meta acumulada 100%)
- Lunes (82%): Diseno 3 pagos (idempotencia/reintentos).
- Martes (89%): reconciliacion basica + trade-offs.
- Miercoles (94%): checklist diseno (seguridad/obs/fallos).
- Jueves (97%): guion defensa oral + diagramas.
- Viernes (100%): proyecto final completo (docs + numeros + DR).

---

## Regla de Control Semanal

Si el viernes no llegas a la meta semanal:
- no agregas temas nuevos el lunes;
- usas lunes/martes para cierre de deuda tecnica;
- luego retomas el plan.
