# PLAN SENIOR CROSS - JAVA + AWS (28 SEMANAS)
## VERSION DEFINITIVA - SOFTWARE ENGINEER SENIOR

**Objetivo:**
Convertirse en Software Engineer Senior real:
Backend solido + Arquitectura + Cloud + Operacion + Seguridad + Observabilidad + Defensa tecnica.

**Duracion:** 7 meses (~28 semanas)

---

# MES 1 - JAVA CORE + JVM + ESTRUCTURAS DE DATOS

## POO Formal
- Encapsulacion profunda
- Abstraccion aplicada
- Herencia vs Composicion
- Polimorfismo dinamico real
- Inmutabilidad bien aplicada
- Equals / hashCode contrato
- Records vs clases tradicionales
- Cohesion vs Acoplamiento

## JVM + Concurrencia
- Heap vs Stack
- Java Memory Model (happens-before)
- synchronized vs ReentrantLock
- volatile
- AtomicInteger / AtomicReference
- ExecutorService
- ConcurrentHashMap
- ThreadLocal
- Deadlock conceptual
- Condiciones de carrera

## Estructuras de Datos
- Big-O analisis
- HashMap internals
- List vs ArrayList vs LinkedList
- Heap / PriorityQueue
- Trees basicos
- Implementacion LRU Cache propia
- Complejidad temporal vs espacial

## Testing
- Unit testing estructurado
- Mockito
- Test de clases inmutables
- Coverage >= 70%
- Principios de testing limpio

## AWS Inicio
- IAM basico
- Policies vs Roles
- S3 basico
- SDK Java S3
- Manejo seguro de credenciales

### Practica AWS Inicio
- Crear usuarios y roles IAM con minimo privilegio.
- Configurar AWS CLI con perfiles seguros.
- Crear buckets S3 y operar por consola y CLI.
- Programar CRUD sobre S3 desde Java con AWS SDK.
- Rotar y manejar credenciales sin exponer llaves.

## Cross Profesional
- Resolucion estructurada de problemas
- Pensamiento computacional
- Git profesional
- Conventional commits
- Pull Request estructurado
- Code review checklist
- Validacion basica de input
- Principio Fail Fast

## Producto Mes 1
**Repositorio:** core-engine-lab
- Implementacion LRU Cache propia
- Ejemplos de concurrencia controlada
- Tests >= 70%
- README tecnico defendible
- Commits estructurados

---

# MES 2 - SPRING BOOT MVC + SQL + ARQUITECTURA

## Spring Boot MVC
- Arquitectura basada en Servlet
- DispatcherServlet y ciclo completo de request
- Thread-per-request model
- Filtros vs Interceptors
- @RestController vs @Controller
- Validacion con @Valid y BindingResult
- HttpMessageConverters
- Personalizacion de Jackson
- @ControllerAdvice aplicado a MVC
- ResponseEntity avanzado
- Manejo correcto de codigos HTTP
- Upload / Download de archivos
- Integracion correcta de @Transactional en capa service

## Spring Internals
- IoC container
- ApplicationContext
- Bean lifecycle
- Scopes
- Proxy dinamico
- AOP interno
- @Transactional internals
- Lazy initialization
- Profiles por entorno

## Persistencia real
- JPA/Hibernate internals
- N+1 problem
- Lazy vs Eager
- Isolation levels
- Indices
- EXPLAIN ANALYZE
- Locking optimista vs pesimista
- Transaction boundaries

## Arquitectura
- SOLID profundo
- Clean Architecture
- Hexagonal
- Service Layer
- DTO vs Entity
- Mapper pattern

## AWS
- Lambda
- CloudWatch logs
- Elastic Beanstalk
- Variables de entorno seguras

### Practica AWS Mes 2
- Desplegar `order-service-monolith` en Elastic Beanstalk.
- Revisar logs en CloudWatch Logs (errores, latencia).
- Cambiar variables de entorno sin recompilar.
- Hacer rollback desde consola o CLI.
- Integrar metricas basicas (latencia, error rate).

## DevOps
- Docker
- Multi-stage build
- CI/CD basico (build + test pipeline)

## Cross Profesional
- Diseno profesional de APIs REST
- Versionado API (path vs header)
- OWASP API Top 10 (introduccion)
- GitFlow formal
- Versionado semantico
- Rebase interactivo
- Gestion profesional de branches

## Producto Mes 2
**Repositorio:** order-service-monolith
- API REST MVC completa
- Validaciones robustas
- Manejo profesional de errores
- JPA optimizado
- Dockerizado
- Documento de arquitectura defendible

---

# MES 3 - WEBFLUX + CACHE + REDES + AWS DEV

## WebFlux profundo
- Mono vs Flux
- Backpressure
- Schedulers
- WebClient
- Error handling reactivo
- Thread model
- Blocking vs Non-blocking
- Cuando NO usar WebFlux

## Cache
- Cache aside pattern
- Redis basico
- Caffeine
- Cache invalidation
- TTL strategies

## Networking
- HTTP internals
- Idempotencia HTTP
- Timeouts
- Retry + backoff exponencial
- TLS basico
- DNS nocion

## AWS Developer
- DynamoDB
- SQS
- SNS
- API Gateway
- ECS
- DLQ basica

### Practica AWS Developer
- CRUD en DynamoDB desde Java.
- SQS Standard/FIFO publicar y consumir.
- SNS con suscripciones.
- Endpoint en API Gateway conectado a WebFlux/Lambda.
- Consumer resiliente con visibility timeout y redrive policy.
- Flujo E2E: API Gateway -> Lambda/ECS -> SQS -> Consumer.

### Operacion SQS/SNS
- FIFO vs Standard queues
- MessageGroupId
- Deduplication ID
- Visibility timeout
- Redrive policy
- Idempotencia real en consumidores

## Testing
- Integration testing
- Testcontainers
- Tests reactivos

## Cross Profesional
- DevOps thinking
- Configuracion por entornos
- Gestion segura de secrets
- Idempotency keys
- Rate limiting conceptual
- Observabilidad basica

## Producto Mes 3
**Repositorio:** inventory-reactive-service
- Servicio WebFlux
- Cache implementado
- Integracion con SQS/SNS
- Deploy AWS
- Documento comparativo MVC vs WebFlux
- Metricas y logs en CloudWatch
- Dashboards y alarmas
- Analisis de fallo documentado

---

# MES 4 - DISTRIBUIDOS + OBSERVABILIDAD + CONSISTENCIA

## Patrones Distribuidos
- Circuit Breaker
- Retry
- Outbox
- Saga
- CQRS
- Idempotencia
- At-least-once vs exactly-once
- Consistencia eventual practica

## Observabilidad profesional
- Logs estructurados
- Correlation ID
- Micrometer
- Prometheus
- Grafana
- Alerting basico
- RED metrics
- DLQ monitoring
- Distributed tracing conceptual
- APM nocion (Dynatrace / Datadog / New Relic)

### Observabilidad operativa avanzada
- Dashboard minimo (latencia p95, error rate, throughput)
- Correlacion logs-metricas-trazas
- Triage de latencia
- Deteccion temprana de degradacion

## Cross Profesional
- Metricas vs logs vs traces
- Runbook basico
- Simulacion de incidente tecnico
- Estrategia uniforme de logging

## Producto Mes 4
**Repositorio:** payment-event-driven-system
- Arquitectura basada en eventos
- DLQ configurada correctamente
- Metricas expuestas
- Dashboard minimo
- Documento de consistencia eventual
- Simulacion de fallo documentada

---

# MES 5 - PERFORMANCE + SEGURIDAD AVANZADA

## Performance
- GC tuning
- Heap dump analisis
- Profiling CPU/memory
- Thread dumps
- Deadlock detection
- Java Flight Recorder (JFR)
- Java Mission Control (JMC)
- Load testing basico (k6/JMeter)
- Throughput vs Latency
- p95 vs p99 analisis

## Contenedores
- Docker multi-stage
- Resource limits
- OOMKilled analisis
- GC vs container memory

## Seguridad backend real
- OAuth2 profundo
- JWT lifecycle
- Password hashing (BCrypt)
- Principio minimo privilegio
- Seguridad interna microservicios
- OWASP Top 10
- OWASP API Top 10 profundo
- Rate limiting avanzado
- CORS / CSRF
- Security headers (HSTS, CSP)
- Replay attack basico

## DevOps avanzado
- Blue/Green
- Canary deployment
- Rollback strategy
- Feature flags nocion

## Cross Profesional
- Threat modeling (STRIDE)
- Dependency scanning
- Gestion de vulnerabilidades
- Postmortem tecnico profesional
- Gestion de incidentes reales

## Producto Mes 5
**Repositorio:** secure-gateway-service
- OAuth2 + JWT implementado
- Rate limiting real
- Analisis de heap dump documentado
- Documento de seguridad

---

# MES 6 - AWS ARCHITECT I (TECNICO ENDURECIDO)

## Networking + Diseno (AWS)
- VPC
- CIDR planning (rangos, crecimiento, segmentacion)
- Subnetting (public/private, AZ distribution)
- Route tables (flujo real de trafico)
- Security Groups vs NACL
- NAT Gateway (impacto tecnico y economico)
- ALB vs NLB
- Target Groups + Health checks
- Auto Scaling:
  - Policies por CPU
  - Policies por RequestCount/TargetResponseTime
  - Cooldowns, warmup, flapping

## Modelado tecnico (obligatorio)
- Estimacion de QPS (requests/seg)
- Estimacion de concurrencia pico
- Estimacion de conexiones a DB
- Throughput vs Latency
- Estimacion basica de IOPS
- Impacto cross-AZ (latencia + costo)

## Failure Modeling (obligatorio)
- Escenario: cae 1 AZ
- Escenario: ALB con target unhealthy
- Escenario: NAT saturado / error DNS
- Escenario: DB lenta (conexiones agotadas)
- Estrategias:
  - Degradacion controlada
  - Timeouts + retries con limites
  - Circuit breaker en borde
  - Backpressure / shedding

## Cost Modeling (obligatorio)
- Costo mensual estimado:
  - ALB (base + LCU aproximado)
  - EC2/ECS (instancias y escalado)
  - RDS (single vs multi-AZ)
  - Data transfer (cross-AZ/cross-region)
- Comparacion por trade-offs:
  - Multi-AZ vs Single-AZ
  - ALB vs NLB
  - NAT vs endpoints

### Practica AWS Networking and Design
- Construir VPC con subnets publicas y privadas funcionales.
- Configurar SG y NACL para acceso legitimo y bloqueo.
- Crear NAT Gateway y validar salida correcta.
- Desplegar ALB con target groups.
- Simular health checks y fallos.
- Configurar Auto Scaling bajo carga variable.

### Practica AWS Architect I
- Estimar costos mensuales aproximados.
- Simular fallo de una AZ y validar failover.
- Ajustar Auto Scaling y medir impacto.
- Probar NACL vs Security Group en escenarios.

## Cross Profesional
- Runbook de operacion minima
- Checklist antes de release (infra + app)
- Estrategia formal Blue/Green

## Producto Mes 6
**Documento tecnico:** high-availability-architecture
- Diagrama AWS end-to-end
- Calculo QPS + concurrencia pico
- Diseno subnets + route tables
- Plan de resiliencia
- Estimacion de costos
- Plan de rollback

---

# MES 7 - AWS ARCHITECT II + SYSTEM DESIGN

## Arquitectura Cloud (AWS)
- Multi-region patterns (active-passive / active-active)
- Disaster Recovery strategies:
  - Backup and Restore
  - Pilot Light
  - Warm Standby
  - Multi-site
- RTO / RPO
- Well-Architected Framework aplicado
- Cost optimization (rightsizing, savings, transfer awareness)

## System Design (obligatorio, con numeros)
**Regla:** ningun diseno vale sin numeros.

### 1) Estimacion y modelado
- Estimar QPS desde DAU/MAU
- Estimar tamano request/response
- Estimar almacenamiento (diario/mensual/anual)
- Estimar crecimiento (mensual/anual)
- Estimar latencia objetivo (SLO p95)
- Identificar primer bottleneck (CPU, IO, DB, red, locks)

### 2) Componentes tecnicos
- Caching distribuido (Redis cluster):
  - TTLs
  - invalidacion
  - cache stampede
- Rate limiting distribuido:
  - token bucket / leaky bucket
  - llave por usuario/cliente/IP
- Sharding/particionamiento:
  - por usuario
  - por region
- Consistencia: fuerte vs eventual
- Mensajeria: colas + DLQ para resiliencia

### 3) Disenos a realizar
- Diseno 1: E-commerce
- Diseno 2: Notificaciones
- Diseno 3: Pagos simplificados

## Cross Profesional
- Writing drills: 1 pagina por diseno (trade-offs)
- Checklist de revision de diseno
- Postmortem simulado por diseno

### Practica AWS Cloud Architecture
- Definir DR con RTO/RPO.
- Disenar y simular arquitectura multi-region.
- Probar degradacion controlada ante falla regional.
- Evaluar trade-offs de costo por region/servicio.

## Producto Final
**Proyecto:** distributed-ecommerce-platform
- Diseno completo documentado
- Diagramas (flujo, datos, fallos)
- Estimaciones numericas (QPS, storage, crecimiento)
- Estrategia de resiliencia
- Plan DR (RTO/RPO)
- Documento estilo entrevista senior
- Guion de defensa oral (10-15 min)
