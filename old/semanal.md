# PLAN SENIOR CROSS – JAVA + AWS (28 SEMANAS)
## VERSIÓN DEFINITIVA – SOFTWARE ENGINEER SENIOR (CONSOLIDADO TOTAL + MES 6–7 ENDURECIDOS)

**Objetivo:**  
Convertirse en Software Engineer Senior real: Backend sólido + Arquitectura + Cloud + Operación + Seguridad + Observabilidad + Defensa técnica en entrevistas internacionales.

**Duración:** 7 meses (~28 semanas)

---

# 🔵 MES 1 (Semanas 1–4) — JAVA CORE + JVM + ESTRUCTURAS DE DATOS
## 🧩 Producto mensual: core-engine-lab

## Semana 1
### Bloques de temas
- POO: Encapsulación profunda
- POO: Abstracción aplicada
- POO: Cohesión vs Acoplamiento (intro)
- Testing: Unit testing estructurado (intro)
- Testing: Test de clases inmutables (intro)
- AWS Inicio: IAM básico (intro)
- AWS Inicio: Policies vs Roles (intro)
- CROSS: Git profesional (base)
- CROSS: Conventional commits (base)

### Bloque de prácticas
- AWS (IAM): crear usuario/rol con permisos mínimos (sin "*") + política mínima para un caso real

### Avance Producto Mensual (core-engine-lab)
- Setup repo + estructura + README base
- Implementar 1–2 clases inmutables + tests
- Meta: 20%

---

## Semana 2
### Bloques de temas
- POO: Herencia vs Composición (cuándo usar cada una)
- POO: Polimorfismo dinámico real
- POO: Records vs clases tradicionales
- Testing: Mockito (intro)
- AWS Inicio: S3 básico (concepto + consola)
- CROSS: Pull Request estructurado
- CROSS: Code review checklist

### Bloque de prácticas
- AWS (S3): crear bucket, subir/bajar objetos por consola (con permisos mínimos)

### Avance Producto Mensual (core-engine-lab)
- Documentar decisiones POO (composición vs herencia)
- Agregar ejemplos con tests
- Meta: 40%

---

## Semana 3
### Bloques de temas
- Estructuras: Big-O análisis
- Estructuras: HashMap internals
- Estructuras: List vs ArrayList vs LinkedList
- POO: equals/hashCode contrato
- AWS Inicio: AWS CLI con perfiles seguros (intro)
- CROSS: Validación básica de input
- CROSS: Principio Fail Fast

### Bloque de prácticas
- AWS (CLI): configurar perfiles seguros y operar S3 desde CLI (subir/bajar)

### Avance Producto Mensual (core-engine-lab)
- “HashMap internals notes” (mini doc defendible)
- Preparar estructura para LRU Cache
- Meta: 65%

---

## Semana 4
### Bloques de temas
- JVM/Concurrencia: Heap vs Stack
- JVM/Concurrencia: Java Memory Model (happens-before)
- JVM/Concurrencia: synchronized vs ReentrantLock
- JVM/Concurrencia: volatile
- JVM/Concurrencia: AtomicInteger / AtomicReference
- JVM/Concurrencia: ExecutorService
- JVM/Concurrencia: ConcurrentHashMap
- JVM/Concurrencia: ThreadLocal
- JVM/Concurrencia: Deadlock conceptual
- JVM/Concurrencia: Condiciones de carrera
- Estructuras: Heap / PriorityQueue
- Estructuras: Trees básicos
- Testing: Coverage ≥ 70%
- Testing: Principios de testing limpio
- AWS Inicio: SDK Java S3
- AWS Inicio: Manejo seguro de credenciales

### Bloque de prácticas
- Práctica AWS Inicio (completa):
  - Crear usuarios/roles IAM con mínimo privilegio
  - AWS CLI con perfiles
  - S3 buckets + operaciones
  - CRUD en S3 desde Java (AWS SDK)
  - Rotación/manejo de credenciales sin exponer llaves

### Avance Producto Mensual (core-engine-lab)
- Implementación LRU Cache propia + tests
- Ejemplos de concurrencia controlada + tests
- README técnico defendible
- Commits estructurados
- Meta: 100% (cierre MES 1)

---

# 🔵 MES 2 (Semanas 5–8) — SPRING BOOT MVC + SQL + ARQUITECTURA
## 🧩 Producto mensual: order-service-monolith

## Semana 5
### Bloques de temas
- Spring MVC: Arquitectura basada en Servlet
- Spring MVC: DispatcherServlet y ciclo completo de request
- Spring MVC: Thread-per-request model
- Spring MVC: @RestController vs @Controller
- AWS: Elastic Beanstalk (intro)
- CROSS: Diseño profesional de APIs REST (principios)

### Bloque de prácticas
- Skeleton API + 2 endpoints + validación simple

### Avance Producto Mensual (order-service-monolith)
- Repo + estructura + primer vertical slice (controller → service)
- Meta: 20%

---

## Semana 6
### Bloques de temas
- Spring MVC: Filtros vs Interceptors
- Spring MVC: Validación con @Valid y BindingResult
- Spring MVC: HttpMessageConverters
- Spring MVC: Manejo correcto de códigos HTTP
- AWS: CloudWatch Logs (intro)
- DevOps: Docker (intro)
- CROSS: Versionado API (path vs header)
- CROSS: GitFlow formal (intro)

### Bloque de prácticas
- Logging base + manejo de errores inicial (sin @ControllerAdvice aún)
- Dockerfile inicial

### Avance Producto Mensual
- CRUD base + validaciones robustas mínimas
- Meta: 45%

---

## Semana 7
### Bloques de temas
- Spring Internals: IoC container
- Spring Internals: ApplicationContext
- Spring Internals: Bean lifecycle
- Spring Internals: Scopes
- Spring Internals: Proxy dinámico
- Spring Internals: AOP interno
- Spring MVC: Personalización de Jackson
- Spring MVC: ResponseEntity avanzado
- AWS: Variables de entorno seguras (Beanstalk)
- CROSS: OWASP API Top 10 (introducción)

### Bloque de prácticas
- Configuración por perfiles (dev/prod) + env vars seguras

### Avance Producto Mensual
- Documento corto: request/response en MVC + filtros/interceptors
- Meta: 70%

---

## Semana 8
### Bloques de temas
- Persistencia real: JPA/Hibernate internals
- Persistencia real: N+1 problem
- Persistencia real: Lazy vs Eager
- Persistencia real: Isolation levels
- Persistencia real: Transaction boundaries
- Persistencia real: Índices
- Persistencia real: EXPLAIN ANALYZE
- Persistencia real: Locking optimista vs pesimista
- Spring Internals: @Transactional internals
- Spring MVC: @ControllerAdvice aplicado a MVC
- Spring MVC: Upload / Download de archivos
- DevOps: Multi-stage build
- DevOps: CI/CD básico (build + test)
- AWS: Lambda (intro)
- AWS: Elastic Beanstalk + rollback + CloudWatch logs (consolidación)

### Bloque de prácticas
- Práctica AWS Mes 2 (completa):
  - Deploy en Elastic Beanstalk
  - Logs en CloudWatch Logs (errores/latencia)
  - Cambiar env vars sin recompilar
  - Rollback desde consola/CLI
  - Métricas básicas (latencia, error rate)

### Avance Producto Mensual
- API MVC completa + validaciones + errores profesionales
- JPA optimizado
- Dockerizado + CI básico
- Documento arquitectura defendible
- Meta: 100% (cierre MES 2)

---

# 🔵 MES 3 (Semanas 9–12) — WEBFLUX + CACHE + REDES + AWS DEV
## 🧩 Producto mensual: inventory-reactive-service

## Semana 9
### Bloques de temas
- WebFlux: Mono vs Flux
- WebFlux: Thread model
- WebFlux: WebClient (base)
- Networking: HTTP internals (noción)
- Networking: Timeouts (intro)
- Cache: Cache-aside pattern (intro)
- AWS Developer: DynamoDB (intro)
- CROSS: Gestión segura de secrets (intro)

### Bloque de prácticas
- DynamoDB: crear tabla + CRUD desde Java (mínimo)

### Avance Producto Mensual
- Servicio WebFlux base + endpoint + primer call externo
- Meta: 20%

---

## Semana 10
### Bloques de temas
- WebFlux: Error handling reactivo
- WebFlux: Blocking vs Non-blocking
- WebFlux: Cuándo NO usar WebFlux
- WebFlux: Schedulers (intro)
- Networking: Retry + backoff exponencial
- Networking: Idempotencia HTTP
- Cache: Redis básico (intro)
- AWS Developer: SQS (intro: Standard vs FIFO)
- CROSS: Idempotency keys (conceptual)

### Bloque de prácticas
- SQS: publicar/consumir mensajes (mínimo)
- WebClient: timeout + retry con límites

### Avance Producto Mensual
- Flujo reactivo más robusto + pruebas mínimas
- Meta: 45%

---

## Semana 11
### Bloques de temas
- WebFlux: Backpressure (profundo)
- Cache: Caffeine
- Cache: TTL strategies
- Cache: Cache invalidation (conceptos y problemas)
- AWS Developer: SNS (intro) + suscripciones
- Operación SQS/SNS: visibility timeout (intro)
- Operación SQS/SNS: redrive policy (intro)
- Testing: Tests reactivos (intro)
- CROSS: Observabilidad básica (logs/métricas base)

### Bloque de prácticas
- SNS → SQS (flujo) + DLQ configurada (mínimo)

### Avance Producto Mensual
- Cache implementado (redis/caffeine según aplique) + doc breve TTL/invalidation
- Meta: 65%

---

## Semana 12
### Bloques de temas
- Testing: Integration testing
- Testing: Testcontainers
- Testing: Tests reactivos (consolidación)
- AWS Developer: API Gateway
- AWS Developer: ECS
- AWS Developer: DLQ básica
- Operación real SQS/SNS:
  - FIFO vs Standard
  - MessageGroupId
  - Deduplication ID
  - Visibility timeout
  - Redrive policy
  - Idempotencia real en consumidores
- Observabilidad: CloudWatch Monitoring
- Observabilidad: Dashboards + alarmas
- Networking: TLS básico + DNS noción
- CROSS: DevOps thinking + configuración por entornos

### Bloque de prácticas
- Práctica AWS Developer (completa):
  - DynamoDB (CRUD)
  - SQS (Standard/FIFO) publicar/consumir
  - SNS suscripciones
  - API GW → Lambda/ECS → SQS → Consumer
  - Consumer resiliente con visibility timeout + redrive policy + DLQ
  - Pruebas end-to-end

### Avance Producto Mensual
- Servicio completo + deploy AWS
- Documento comparativo MVC vs WebFlux
- Métricas/logs en CloudWatch + dashboards + alarmas
- Análisis de fallo documentado
- Meta: 100% (cierre MES 3)

---

# 🔵 MES 4 (Semanas 13–16) — DISTRIBUIDOS + OBSERVABILIDAD + CONSISTENCIA
## 🧩 Producto mensual: payment-event-driven-system

## Semana 13
### Bloques de temas
- Patrones distribuidos: Circuit Breaker
- Patrones distribuidos: Retry
- Patrones distribuidos: Idempotencia
- Patrones distribuidos: At-least-once vs exactly-once
- Observabilidad: Logs estructurados (base)
- CROSS: Métricas vs logs vs traces (base)

### Bloque de prácticas
- Simular reintentos controlados + idempotencia en consumidor

### Avance Producto Mensual
- Esqueleto event-driven + cola + consumidor base
- Meta: 25%

---

## Semana 14
### Bloques de temas
- Patrones distribuidos: Outbox
- Consistencia eventual práctica
- Observabilidad: Correlation ID
- Observabilidad: DLQ monitoring (base)
- CROSS: Runbook básico (intro)

### Bloque de prácticas
- Outbox “simulado” + idempotencia en consumo

### Avance Producto Mensual
- Flujo principal “happy path” + DLQ funcionando
- Meta: 50%

---

## Semana 15
### Bloques de temas
- Patrones distribuidos: Saga
- Patrones distribuidos: CQRS (trade-offs)
- Observabilidad: Micrometer (intro)
- Observabilidad: Alerting básico
- CROSS: Estrategia uniforme de logging

### Bloque de prácticas
- Simular saga mínima (o compensación) + documentar decisiones

### Avance Producto Mensual
- Caso de fallo + recuperación documentada
- Meta: 70%

---

## Semana 16
### Bloques de temas
- Observabilidad pro: Prometheus (noción)
- Observabilidad pro: Grafana (noción)
- Observabilidad pro: RED metrics
- Observabilidad operativa: Dashboard mínimo (latencia p95, error rate, throughput)
- Observabilidad operativa: Correlación logs–métricas–trazas
- Observabilidad operativa: Triage de latencia + detección temprana de degradación
- Simulador: Examen AWS Developer
- CROSS: Simulación incidente técnico + postmortem básico

### Bloque de prácticas
- Dashboard mínimo + alarmas + simulación de incidente (con hallazgos)

### Avance Producto Mensual
- Sistema listo + DLQ correcta + métricas + dashboard
- Documento consistencia eventual + simulación fallo documentada
- Meta: 100% (cierre MES 4)

---

# 🟢 MES 5 (Semanas 17–20) — PERFORMANCE + SEGURIDAD AVANZADA
## 🧩 Producto mensual: secure-gateway-service

## Semana 17
### Bloques de temas
- Seguridad: OAuth2 profundo
- Seguridad: JWT lifecycle
- Seguridad: Principio mínimo privilegio (conceptual)
- DevOps avanzado: Feature flags (noción)
- CROSS: Threat modeling (STRIDE) (intro)

### Bloque de prácticas
- Auth flow mínimo + emisión/validación JWT (seguro)

### Avance Producto Mensual
- Skeleton gateway + auth básico
- Meta: 25%

---

## Semana 18
### Bloques de temas
- Seguridad: Password hashing (BCrypt)
- Seguridad: OWASP Top 10
- Seguridad: OWASP API Top 10 (profundo)
- Seguridad: CORS / CSRF
- Seguridad: Security headers (HSTS, CSP)
- Seguridad: Rate limiting avanzado
- CROSS: Dependency scanning (intro)

### Bloque de prácticas
- Rate limiting real + headers + validaciones + checklist OWASP aplicado

### Avance Producto Mensual
- Seguridad sólida en endpoints + doc amenazas/mitigaciones
- Meta: 50%

---

## Semana 19
### Bloques de temas
- Performance: Throughput vs Latency
- Performance: p95 vs p99 análisis
- Performance: Profiling CPU/memory
- Performance: Heap dump análisis
- Performance: Thread dumps
- Performance: Deadlock detection
- Contenedores: Resource limits
- Contenedores: OOMKilled análisis
- Contenedores: GC vs container memory

### Bloque de prácticas
- Load testing básico (k6/JMeter)
- Capturar evidencia (profiling + dumps) y sacar conclusiones

### Avance Producto Mensual
- Evidencia performance + recomendaciones
- Meta: 75%

---

## Semana 20
### Bloques de temas
- Performance: GC tuning
- Performance: Java Flight Recorder (JFR)
- Performance: Java Mission Control (JMC)
- DevOps avanzado: Blue/Green
- DevOps avanzado: Canary deployment
- DevOps avanzado: Rollback strategy
- Seguridad: Replay attack básico
- CROSS: Gestión vulnerabilidades
- CROSS: Postmortem técnico profesional
- CROSS: Gestión de incidentes reales

### Bloque de prácticas
- Documento de seguridad + simulación despliegue/rollback

### Avance Producto Mensual
- Gateway terminado (OAuth2/JWT) + rate limiting real
- Análisis heap dump documentado
- Documento seguridad (OWASP + mitigaciones)
- Meta: 100% (cierre MES 5)

---

# 🟢 MES 6 (Semanas 21–24) — AWS ARCHITECT I (TÉCNICO ENDURECIDO)
## 🧩 Producto mensual: high-availability-architecture (documento técnico)

## Semana 21
### Bloques de temas
- AWS Networking: VPC
- AWS Networking: CIDR planning (cálculo de rangos, crecimiento, segmentación)
- AWS Networking: Subnetting (public/private, AZ distribution)
- AWS Networking: Route tables (flujo real de tráfico)
- Modelado técnico: estimación de QPS (intro)
- CROSS: Checklist antes de release (infra + app) (intro)

### Bloque de prácticas
- Construir VPC con subnets públicas/privadas funcionales

### Avance Producto Mensual (high-availability-architecture)
- Diagrama base + supuestos iniciales
- Meta: 25%

---

## Semana 22
### Bloques de temas
- AWS Networking: Security Groups vs NACL (stateful vs stateless + casos reales)
- AWS Networking: NAT Gateway (impacto técnico y económico)
- Modelado técnico: concurrencia pico
- Modelado técnico: conexiones simultáneas a DB
- Cost modeling: NAT vs endpoints (noción)
- CROSS: Runbook operación mínima (intro)

### Bloque de prácticas
- Validar que solo subnets correctas salen a Internet (NAT + reglas)

### Avance Producto Mensual
- Sección redes lista + primeros costos
- Meta: 50%

---

## Semana 23
### Bloques de temas
- AWS Networking: ALB vs NLB (casos por protocolo y performance)
- AWS Networking: Target Groups + Health checks (fallos típicos y tuning)
- Auto Scaling:
  - Policies por CPU
  - Policies por RequestCount/TargetResponseTime
  - Cooldowns, warmup, flapping
- Failure modeling:
  - cae 1 AZ
  - ALB con target unhealthy
- Modelado técnico:
  - IOPS (lecturas/escrituras)
  - impacto cross-AZ (latencia + costo data transfer)

### Bloque de prácticas
- Desplegar ALB + target groups + simular health checks y fallos

### Avance Producto Mensual
- Sección HA/ASG + fallos típicos documentados
- Meta: 75%

---

## Semana 24
### Bloques de temas
- Failure modeling:
  - NAT saturado / error DNS
  - DB lenta (conexiones agotadas)
- Estrategias:
  - degradación controlada
  - timeouts + retries con límites
  - circuit breaker en borde
  - backpressure / shedding (noción)
- Cost modeling:
  - costo mensual ALB (base + LCU aproximado)
  - EC2/ECS (instancias y escalado)
  - RDS (single vs multi-AZ)
  - data transfer (cross-AZ/cross-region noción)
- Trade-offs:
  - Multi-AZ vs Single-AZ
  - ALB vs NLB
  - NAT vs endpoints
- CROSS:
  - Estrategia formal Blue/Green (pasos, riesgos, rollback)

### Bloque de prácticas
- Práctica AWS Architect I (consolidación):
  - estimar costos mensuales aproximados
  - simular fallo de AZ (al menos diseño + validación)
  - ajustar policies de Auto Scaling y medir impacto
  - comparar NACL vs SG en escenarios

### Avance Producto Mensual
- Documento final completo:
  - diagrama end-to-end
  - QPS/concurrencia (con supuestos)
  - diseño subnets/route tables (resumen)
  - plan resiliencia (fallos y respuesta)
  - estimación costos
  - plan rollback
- Meta: 100% (cierre MES 6)

---

# 🟢 MES 7 (Semanas 25–28) — AWS ARCHITECT II + SYSTEM DESIGN (CON NÚMEROS)
## 🧩 Producto mensual: distributed-ecommerce-platform

## Semana 25
### Bloques de temas
- Multi-region patterns (active-passive / active-active) (noción)
- Disaster Recovery strategies:
  - Backup & Restore
  - Pilot Light
  - Warm Standby
  - Multi-site (noción)
- RTO / RPO (definición, implicación en costo)
- Well-Architected Framework (pilares aplicados a decisiones)
- Cost optimization (rightsizing, savings, data transfer awareness)

### Bloque de prácticas
- Definir DR del proyecto (RTO/RPO) y justificar costo

### Avance Producto Mensual (distributed-ecommerce-platform)
- Estructura de docs + baseline arquitectura + DR planteado
- Meta: 25%

---

## Semana 26
### Bloques de temas
- System Design (con números):
  - estimar QPS desde DAU/MAU
  - tamaño request/response
  - almacenamiento diario/mensual/anual
  - crecimiento mensual/anual
  - latencia objetivo (SLO p95)
  - identificar primer bottleneck (CPU/IO/DB/red/locks)
- Componentes:
  - caching distribuido (Redis cluster noción)
  - TTLs, invalidación, cache stampede (noción)
- Diseño 1: E-commerce (catálogo + carrito + checkout simplificado)

### Bloque de prácticas
- Writing drill: 1 página defendiendo Diseño 1 (trade-offs)

### Avance Producto Mensual
- Diseño 1 completo + números + diagrama (flujo/datos)
- Meta: 50%

---

## Semana 27
### Bloques de temas
- Componentes:
  - rate limiting distribuido (token bucket / leaky bucket) (noción)
  - llaves por usuario/cliente/IP
  - sharding/particionamiento (por usuario / por región) (noción práctica)
  - consistencia fuerte vs eventual (casos de negocio)
  - mensajería: colas + DLQ como resiliencia
- Diseño 2: Notificaciones (email/SMS/push con colas + DLQ)

### Bloque de prácticas
- Writing drill: 1 página defendiendo Diseño 2 + checklist (seguridad/obs/fallos)

### Avance Producto Mensual
- Diseño 2 completo + números + postmortem simulado (incidente)
- Meta: 75%

---

## Semana 28
### Bloques de temas
- Diseño 3: Pagos simplificados
  - idempotencia + reintentos + reconciliación básica
- Writing drills: 1 página por diseño (trade-offs)
- Checklist revisión de diseño (seguridad, observabilidad, fallos)
- Postmortem simulado (un incidente por diseño)
- Simulación defensa oral (guion 10–15 min)

### Bloque de prácticas
- Guion de defensa oral + 3 diagramas mínimos:
  - flujo
  - datos
  - fallos

### Avance Producto Mensual
- Proyecto global completo:
  - docs + diagramas + números
  - resiliencia (fallos y respuesta)
  - DR (RTO/RPO)
  - documento estilo entrevista senior
- Meta: 100% (cierre MES 7)

---