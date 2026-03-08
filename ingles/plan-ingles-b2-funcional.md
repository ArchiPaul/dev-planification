# Plan Ingles Tecnico Poderoso B1 -> B2 (28 semanas)

## Objetivo oficial
Al finalizar 28 semanas:
- [ ] B1 solido operativo en entrevistas tecnicas
- [ ] B2 funcional en speaking tecnico (arquitectura, trade-offs, decisiones)
- [ ] Respuestas de 2 minutos con estructura y control

## Alineacion con tu plan integral
Este plan esta sincronizado con `Complete/main/semanal-ajustada.md`.
Se ejecuta en tu bloque fijo de ingles tecnico: L-V 15:15-16:00 (45 min).

## Protocolo diario fijo (45 min)
1. Activacion (5 min): 6 terminos + 2 conectores (sin mirar)
2. Input (10 min): 4 terminos nuevos del tema tecnico del dia
3. Speaking (20 min): 2 respuestas (tiempo segun semana)
4. Cierre (10 min): reformulacion + 1 frase modelo + score

## Regla incremental dura (anti-estancamiento)
- Semanas 1-4: 45-60s por respuesta
- Semanas 5-8: 60-75s
- Semanas 9-12: 75-90s
- Semanas 13-16: 90-105s
- Semanas 17-20: 105-120s
- Semanas 21-24: 120s estables
- Semanas 25-28: 120s bajo presion y repregunta

## Estructura obligatoria de respuesta
Context -> Decision -> Trade-off -> Result

## Sistema de puntuacion semanal (0-5)
- Fluidez
- Claridad
- Conectores
- Defensa tecnica
- Control del tiempo
Meta minima: promedio >= 3.5 (B1 alto)
Meta alta: promedio >= 4.2 (B2 funcional)

---

## Plan semanal incremental (alineado a semanal-ajustada)

### Semana 1 - Setup, POO base, IAM
- Objetivo speaking: describir rol y tareas sin bloqueo (45s)
- Conectores: first, then, because, so
- Salida: explicar una responsabilidad tecnica y una decision simple

### Semana 2 - Herencia/composicion, polimorfismo, records, Mockito, S3
- Objetivo speaking: comparar 2 conceptos (50s)
- Conectores: however, for example, as a result
- Salida: defender composicion vs herencia

### Semana 3 - Big-O, HashMap, listas, AWS CLI
- Objetivo speaking: explicar causa-efecto tecnico (55s)
- Conectores: therefore, thats why, in addition
- Salida: explicar por que elegiste una estructura de datos

### Semana 4 - JVM, concurrencia, heap/stack, locks, ExecutorService
- Objetivo speaking: explicar problema + mitigacion (60s)
- Conectores: although, while, as a result
- Salida: incidente corto de concurrencia

### Semana 5 - Spring MVC, Servlet, controller/service, DTO vs entity
- Objetivo speaking: explicar flujo request-response (65s)
- Conectores: first, after that, finally
- Salida: arquitectura en capas basica defendible

### Semana 6 - filtros/interceptors, validacion, HTTP, SOLID, mapper, Docker
- Objetivo speaking: justificar decisiones de capa (70s)
- Conectores: due to, therefore, moreover
- Salida: defender filter vs interceptor

### Semana 7 - IoC, lifecycle, AOP, profiles, Clean/Hexagonal
- Objetivo speaking: comparar arquitecturas (75s)
- Conectores: on the other hand, whereas, however
- Salida: defender layered vs hexagonal

### Semana 8 - JPA/Hibernate, N+1, lazy/eager, transactions, locking
- Objetivo speaking: explicar costo de decisiones de persistencia (75s)
- Conectores: even though, nevertheless, as a result
- Salida: defender limites transaccionales

### Semana 9 - WebFlux, Mono/Flux, thread model, WebClient, DynamoDB
- Objetivo speaking: explicar cuando usar/no usar enfoque (80s)
- Conectores: from my perspective, while, however
- Salida: decision reactivo vs bloqueante

### Semana 10 - retries, backoff, SQS, idempotency, rate limiting
- Objetivo speaking: resiliencia con trade-offs (85s)
- Conectores: the main risk is, to mitigate this, therefore
- Salida: defender politica de reintentos

### Semana 11 - backpressure, cache, TTL, invalidation, SNS, DLQ
- Objetivo speaking: explicar trade-off performance-consistencia (90s)
- Conectores: one limitation is, in addition, on the other hand
- Salida: defender estrategia de cache

### Semana 12 - Testcontainers, API Gateway, ECS, CloudWatch
- Objetivo speaking: explicar flujo end-to-end (90s)
- Conectores: the key point is, as a result, furthermore
- Salida: diagrama verbal de arquitectura

### Semana 13 - circuit breaker, retry, idempotencia, observabilidad base
- Objetivo speaking: storytelling tecnico STAR (95s)
- Conectores: when this happened, so we decided, as a result
- Salida: caso real de fallo y recuperacion

### Semana 14 - outbox, consistencia eventual, correlation ID, runbook
- Objetivo speaking: defender consistencia eventual (100s)
- Conectores: although, one advantage is, one drawback is
- Salida: justificar outbox pattern

### Semana 15 - saga, CQRS, Micrometer, tracing, alerting
- Objetivo speaking: defensa tecnica senior inicial (105s)
- Conectores: the main trade-off is, from my experience
- Salida: defender CQRS o no CQRS

### Semana 16 - Prometheus, Grafana, RED metrics, incident simulation
- Objetivo speaking: explicar investigacion de incidente (105s)
- Conectores: first we noticed, then we validated, finally we fixed
- Salida: postmortem oral corto

### Semana 17 - OAuth2, JWT, least privilege, STRIDE
- Objetivo speaking: seguridad aplicada a arquitectura (110s)
- Conectores: due to this risk, to reduce exposure, therefore
- Salida: defender decision de autenticacion/autorizacion

### Semana 18 - BCrypt, OWASP, CORS/CSRF, headers, rate limiting
- Objetivo speaking: riesgos y mitigaciones (110s)
- Conectores: the threat was, we mitigated it by, however
- Salida: justificar controles de API security

### Semana 19 - throughput/latency, p95/p99, profiling, dumps, OOM
- Objetivo speaking: performance bajo presion (115s)
- Conectores: the bottleneck was, this improved, one limitation remained
- Salida: explicar plan de optimizacion

### Semana 20 - GC tuning, JFR/JMC, blue-green, canary, rollback
- Objetivo speaking: defensa de despliegue seguro (120s)
- Conectores: we considered, we chose, to mitigate rollback risk
- Salida: defender estrategia de release

### Semana 21 - VPC, CIDR, subnetting, route tables, QPS
- Objetivo speaking: arquitectura de red basica (120s)
- Conectores: to begin with, then, as a result
- Salida: explicar diseno de VPC

### Semana 22 - SG vs NACL, NAT, concurrencia, throughput/latency
- Objetivo speaking: comparaciones de red defendibles (120s)
- Conectores: whereas, on the other hand, therefore
- Salida: defender SG vs NACL en escenario real

### Semana 23 - ALB vs NLB, Auto Scaling, failure modeling
- Objetivo speaking: decisiones de escalado (120s)
- Conectores: the main reason is, one trade-off is, to mitigate this
- Salida: defender arquitectura multi-AZ

### Semana 24 - failure modeling, retries, circuit breaker, cost modeling
- Objetivo speaking: costo vs resiliencia (120s)
- Conectores: while this improves reliability, it also increases cost
- Salida: defender decision costo-tecnica

### Semana 25 - DR, RTO/RPO, Well-Architected, cost optimization
- Objetivo speaking: argumentacion ejecutiva tecnica (120s)
- Conectores: in business terms, technically, as a result
- Salida: justificar estrategia DR

### Semana 26 - system design con numeros, caching distribuido
- Objetivo speaking: diseno con estimaciones (120s)
- Conectores: based on these assumptions, therefore, however
- Salida: mini defensa de system design

### Semana 27 - rate limiting, sharding, consistencia, colas y DLQ
- Objetivo speaking: defender decisiones distribuidas complejas (120s)
- Conectores: the main bottleneck is, one option is, the trade-off is
- Salida: arquitectura de notificaciones defendible

### Semana 28 - pagos, idempotencia, retries, reconciliacion, defensa final
- Objetivo speaking: entrevista final nivel B1 alto/B2 funcional (120s + repreguntas)
- Conectores: to summarize, the key decision was, if I had to improve it
- Salida: mock final completo (HR + tecnica + arquitectura)

---

## Plantillas de alto impacto (usar desde semana 5)

### Plantilla arquitectura
- The architecture is based on...
- We chose this because...
- The main trade-off is...
- To mitigate that, we...
- As a result, we achieved...

### Plantilla decision tecnica
- We considered two options...
- Option A gave us...
- Option B reduced...
- We chose... because...
- One limitation is...

### Plantilla incidente
- The incident started when...
- The root cause was...
- The immediate fix was...
- The long-term fix was...
- The measurable impact was...

## Regla de control (cada viernes)
- [ ] 2 respuestas en tiempo objetivo de la semana
- [ ] 1 defensa con trade-off explicito
- [ ] 1 arquitectura explicada de punta a punta
- [ ] Score semanal >= 3.5/5

## Resultado esperado realista
- Semanas 1-8: B1 operativo
- Semanas 9-20: B1 alto tecnico
- Semanas 21-28: B2 funcional en speaking tecnico
