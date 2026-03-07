# PLAN SENIOR CROSS - JAVA + AWS (28 SEMANAS)
## VERSION AJUSTADA - ALINEADA CON PLAN MENSUAL

**Objetivo:**
Convertirse en Software Engineer Senior real: Backend solido + Arquitectura + Cloud + Operacion + Seguridad + Observabilidad + Defensa tecnica en entrevistas internacionales.

**Duracion:** 7 meses (~28 semanas)

---

# RECURSOS POR SEMANA (OFICIAL + LIBRO + UDEMY)

Nota de costos Udemy: rango comun en oferta `$10-$20` USD.
Cuando no hay "pagina", se usa capitulo/seccion/modulo (equivalente a "tema").
Etiquetas:
- `COMPRA REQUERIDA`: curso pago reutilizado en 2 o mas semanas.
- `OPCIONAL`: curso pago puntual (1 semana o reemplazable por documentacion/libro).

## Semana 1
- POO (encapsulacion, abstraccion, cohesion/acoplamiento)
  - Oficial: Java Tutorials OOP Concepts (`javaOO`)
  - Libro: *Head First Java 3rd* - Chapters 1-4
  - Udemy: [COMPRA REQUERIDA] *Java Programming Masterclass* - Secciones OOP basicas (`$10-$20`)
- Testing (unit/inmutables)
  - Oficial: JUnit 5 User Guide (Getting Started)
  - Libro: *Clean Code* - Chapter 9 (Unit Tests)
  - Udemy: [OPCIONAL] *JUnit 5 for Beginners* - Modulos 1-3 (`$10-$20`)
- IAM base
  - Oficial: IAM User Guide (What is IAM?, Users, Roles, Policies)
  - Libro: *AWS Certified Cloud Practitioner CLF-C02* (Stephane Maarek notes) - IAM chapter
  - Udemy: [COMPRA REQUERIDA] *AWS Cloud Practitioner* - Modulo IAM (`$10-$20`)

## Semana 2
- Herencia, composicion, polimorfismo, records
  - Oficial: Java Tutorials (Inheritance/Polymorphism) + JEP 395 (Records)
  - Libro: *Effective Java 3rd* - Items 18, 19, 20
  - Udemy: [COMPRA REQUERIDA] *Java Programming Masterclass* - Modulo OOP intermedio (`$10-$20`)
- Mockito y S3 base
  - Oficial: Mockito docs + S3 User Guide (Buckets/Objects)
  - Libro: *Pragmatic Unit Testing in Java* - Mock objects chapters
  - Udemy: [COMPRA REQUERIDA] *Mockito Crash Course* / *AWS Cloud Practitioner S3 module* (`$10-$20`)

## Semana 3
- Big-O, HashMap, Lists, complejidad
  - Oficial: JDK API (`HashMap`, `ArrayList`, `LinkedList`)
  - Libro: *Grokking Algorithms* - Chapters 1-4
  - Udemy: [OPCIONAL] *Data Structures and Algorithms in Java* - Arrays/Lists/Hashing (`$10-$20`)
- AWS CLI + validacion/fail fast
  - Oficial: AWS CLI User Guide (Configuration and named profiles)
  - Libro: *Clean Code* - Cap. 7 (Error Handling)
  - Udemy: [OPCIONAL] *AWS CLI Quick Start* module (`$10-$20`)

## Semana 4
- JVM y concurrencia
  - Oficial: JLS Chapter 17 + Java Concurrency Tutorial
  - Libro: *Java Concurrency in Practice* - Chapters 1-5
  - Udemy: [OPCIONAL] *Java Multithreading and Concurrency* - Modulos core (`$10-$20`)
- SDK Java S3 + credenciales
  - Oficial: AWS SDK for Java 2.x Developer Guide (S3 examples, credentials chain)
  - Libro: *AWS for Developers* - S3 + IAM sections
  - Udemy: [OPCIONAL] *AWS SDK for Java* - S3 CRUD module (`$10-$20`)

## Semana 5
- Spring MVC base (Servlet, Dispatcher, controllers)
  - Oficial: Spring Framework Reference - Web MVC
  - Libro: *Spring in Action 6th* - Chapters 1-3
  - Udemy: [OPCIONAL] *Spring & Hibernate for Beginners* - MVC intro (`$10-$20`)
- Service Layer y DTO vs Entity
  - Oficial: Spring docs (Controller/Service/Data layers)
  - Libro: *Clean Architecture* - Chapters 20-24
  - Udemy: [COMPRA REQUERIDA] *Software Architecture* - Layering module (`$12-$25`)

## Semana 6
- Filtros, interceptors, validacion, HTTP
  - Oficial: Spring MVC config + Bean Validation docs
  - Libro: *Spring in Action* - Web and validation chapters
  - Udemy: [OPCIONAL] *REST APIs with Spring Boot* - Validation/Error handling (`$10-$20`)
- SOLID y mapper
  - Oficial: Martin Fowler catalog (patterns)
  - Libro: *Clean Architecture* - SOLID chapters
  - Udemy: [OPCIONAL] *SOLID Principles* course module (`$10-$20`)

## Semana 7
- IoC, context, lifecycle, scopes, AOP, profiles
  - Oficial: Spring Core Container docs
  - Libro: *Spring in Action* - Bean wiring / AOP chapters
  - Udemy: [OPCIONAL] *Spring Framework 5 Beginner to Guru* - IoC/AOP (`$10-$20`)
- Clean/Hexagonal
  - Oficial: Ports & Adapters references (Hexagonal essays)
  - Libro: *Get Your Hands Dirty on Clean Architecture* - Chapters 1-6
  - Udemy: [COMPRA REQUERIDA] *Software Architecture* - Clean/Hexagonal module (`$12-$25`)

## Semana 8
- JPA/Hibernate profundo
  - Oficial: Hibernate User Guide + Spring Data JPA docs
  - Libro: *High-Performance Java Persistence* - Chapters 1-5
  - Udemy: [OPCIONAL] *Hibernate and Spring Data JPA* (`$10-$20`)
- Transacciones y @ControllerAdvice
  - Oficial: Spring Transaction Management + Exception Handling docs
  - Libro: *Spring in Action* - Transactions chapter
  - Udemy: [OPCIONAL] *Spring Boot REST* - Error handling module (`$10-$20`)

## Semana 9
- WebFlux base (Mono/Flux, thread model, WebClient)
  - Oficial: Spring WebFlux Reference
  - Libro: *Reactive Spring* - Chapters 1-3
  - Udemy: [OPCIONAL] *Reactive Programming with Spring* - Intro modules (`$10-$20`)
- DynamoDB base
  - Oficial: DynamoDB Developer Guide
  - Libro: *DynamoDB Book* (Alex DeBrie) - modeling basics
  - Udemy: [COMPRA REQUERIDA] *AWS Developer Associate* - DynamoDB module (`$10-$20`)

## Semana 10
- Error handling reactivo, schedulers, retries
  - Oficial: Project Reactor docs (Schedulers, Error Handling, Retry)
  - Libro: *Reactive Spring* - Error and resilience chapters
  - Udemy: [OPCIONAL] *Reactive Spring* - Intermediate module (`$10-$20`)
- SQS intro + idempotency
  - Oficial: SQS Developer Guide (Standard vs FIFO)
  - Libro: *Designing Data-Intensive Applications* - Messaging basics
  - Udemy: [COMPRA REQUERIDA] *AWS Developer Associate* - SQS module (`$10-$20`)

## Semana 11
- Backpressure, cache (Redis/Caffeine/TTL)
  - Oficial: Reactor Backpressure + Redis docs + Caffeine wiki
  - Libro: *Designing Data-Intensive Applications* - Caching chapter
  - Udemy: [COMPRA REQUERIDA] *Redis - Complete Developer Guide* (`$10-$20`)
- SNS + DLQ base
  - Oficial: SNS docs + SQS DLQ docs
  - Libro: *Enterprise Integration Patterns* - Pub/Sub concepts
  - Udemy: [COMPRA REQUERIDA] *AWS Developer Associate* - SNS module (`$10-$20`)

## Semana 12
- Integration testing + Testcontainers
  - Oficial: Testcontainers docs + JUnit 5 guide
  - Libro: *Growing Object-Oriented Software* - integration tests chapters
  - Udemy: [OPCIONAL] *Testing Spring Boot Beginner to Guru* (`$10-$20`)
- API Gateway/ECS y observabilidad CloudWatch
  - Oficial: API Gateway docs + ECS docs + CloudWatch monitoring docs
  - Libro: *Amazon ECS in Action* - service deployment chapters
  - Udemy: [COMPRA REQUERIDA] *AWS Developer Associate* - API GW/ECS/Monitoring (`$10-$20`)

## Semana 13
- Circuit breaker, retry, idempotencia, delivery semantics
  - Oficial: Resilience4j docs + microservices.io patterns
  - Libro: *Building Microservices 2nd* - Resilience chapter
  - Udemy: [OPCIONAL] *Microservices with Spring Cloud* (`$10-$20`)
- Logs estructurados y metrica/log/trace
  - Oficial: OpenTelemetry docs (signals)
  - Libro: *Distributed Systems Observability* - Chapters 1-3
  - Udemy: [COMPRA REQUERIDA] *OpenTelemetry for Developers* (`$10-$20`)

## Semana 14
- Outbox, consistencia eventual, correlation ID
  - Oficial: microservices.io (Transactional Outbox)
  - Libro: *Microservices Patterns* - Saga/Outbox chapters
  - Udemy: [OPCIONAL] *Event-Driven Microservices* (`$10-$20`)
- Runbook basico
  - Oficial: Google SRE Workbook
  - Libro: *The Site Reliability Workbook* - incident response
  - Udemy: [OPCIONAL] *Site Reliability Engineering* (`$12-$25`)

## Semana 15
- Saga, CQRS, Micrometer, alertas
  - Oficial: Micrometer docs + CQRS reference patterns
  - Libro: *Microservices Patterns* - CQRS and Saga chapters
  - Udemy: [OPCIONAL] *Microservices Patterns* modules (`$10-$20`)
- Tracing distribuido y APM
  - Oficial: OpenTelemetry traces docs
  - Libro: *Distributed Systems Observability* - tracing chapters
  - Udemy: [COMPRA REQUERIDA] *OpenTelemetry for Developers* (`$10-$20`)

## Semana 16
- Prometheus, Grafana, RED, dashboards, triage
  - Oficial: Prometheus docs + Grafana docs
  - Libro: *Site Reliability Engineering* - Monitoring distributed systems
  - Udemy: [OPCIONAL] *Prometheus and Grafana* (`$10-$20`)
- Simulacion de incidente
  - Oficial: SRE postmortem practices
  - Libro: *The DevOps Handbook* - incident management chapters
  - Udemy: [OPCIONAL] *Incident Response* module (`$10-$20`)

## Semana 17
- OAuth2/JWT/minimo privilegio/seguridad interna
  - Oficial: Spring Security docs + OAuth2 specs + JWT RFC 7519
  - Libro: *Spring Security in Action* - Chapters 1-6
  - Udemy: [OPCIONAL] *Spring Security 6 Zero to Master* (`$10-$20`)
- STRIDE
  - Oficial: Microsoft Threat Modeling docs
  - Libro: *Threat Modeling* (Adam Shostack) - Chapters 1-3
  - Udemy: [OPCIONAL] *Threat Modeling for Developers* (`$10-$20`)

## Semana 18
- BCrypt, OWASP, CORS/CSRF, headers, rate limiting
  - Oficial: OWASP Cheat Sheets + OWASP Top 10 + API Top 10 + MDN headers
  - Libro: *Web Application Security* - practical defenses
  - Udemy: [OPCIONAL] *REST API Security* (`$10-$20`)
- Dependency scanning
  - Oficial: OWASP Dependency-Check docs
  - Libro: *Securing DevOps* - dependency risk chapters
  - Udemy: [OPCIONAL] *DevSecOps Fundamentals* (`$10-$20`)

## Semana 19
- Throughput/latency p95/p99 + profiling/dumps
  - Oficial: Oracle performance tuning docs + JDK tools docs
  - Libro: *Java Performance* (Scott Oaks) - Chapters 2-6
  - Udemy: [COMPRA REQUERIDA] *Java Performance Tuning* (`$10-$20`)
- Docker resource limits/OOM
  - Oficial: Docker docs (resource constraints)
  - Libro: *Docker Deep Dive* - runtime limits chapter
  - Udemy: [OPCIONAL] *Docker and Kubernetes Practical Guide* (`$10-$20`)

## Semana 20
- GC tuning, JFR, JMC
  - Oficial: Oracle JFR/JMC guides
  - Libro: *Optimizing Java* - GC and profiling chapters
  - Udemy: [COMPRA REQUERIDA] *Java Performance Tuning* advanced module (`$10-$20`)
- Blue/Green, Canary, rollback, postmortem
  - Oficial: AWS deployment strategies docs
  - Libro: *Accelerate* - deployment and reliability metrics
  - Udemy: [OPCIONAL] *DevOps Deployment Strategies* (`$10-$20`)

## Semana 21
- VPC, CIDR, subnetting, route tables
  - Oficial: AWS VPC User Guide
  - Libro: *AWS Certified Solutions Architect Study Guide* - networking chapters
  - Udemy: [COMPRA REQUERIDA] *SAA-C03 course* - VPC module (`$10-$20`)
- QPS base y checklist release
  - Oficial: AWS Well-Architected Framework
  - Libro: *System Design Interview* - estimation intro
  - Udemy: [COMPRA REQUERIDA] *Grokking System Design* (`$12-$25`)

## Semana 22
- SG vs NACL, NAT, concurrencia DB, throughput/latency
  - Oficial: AWS VPC security + NAT docs
  - Libro: *Designing Data-Intensive Applications* - bottlenecks chapter
  - Udemy: [COMPRA REQUERIDA] *SAA-C03 networking deep dive* (`$10-$20`)
- Runbook operativo
  - Oficial: SRE Workbook runbook guidance
  - Libro: *The Site Reliability Workbook*
  - Udemy: [OPCIONAL] *SRE Fundamentals* (`$10-$20`)

## Semana 23
- ALB vs NLB, target groups, health checks, auto scaling
  - Oficial: Elastic Load Balancing + Auto Scaling docs
  - Libro: *AWS Study Guide* - load balancing chapters
  - Udemy: [COMPRA REQUERIDA] *SAA-C03* - ELB/ASG module (`$10-$20`)
- Failure modeling (AZ down, unhealthy targets)
  - Oficial: AWS resiliency whitepapers
  - Libro: *Release It!* - stability patterns
  - Udemy: [OPCIONAL] *AWS Architecture* scenario labs (`$10-$20`)

## Semana 24
- Failure scenarios + mitigaciones + cost modeling
  - Oficial: AWS Cost Management + AWS Pricing Calculator + Well-Architected Cost Pillar
  - Libro: *Cloud FinOps* - cost trade-off chapters
  - Udemy: [OPCIONAL] *AWS Cost Optimization* (`$10-$20`)
- Blue/Green formal
  - Oficial: AWS deployment docs
  - Libro: *The DevOps Handbook* - deployment chapter
  - Udemy: [OPCIONAL] *DevOps deployment patterns* (`$10-$20`)

## Semana 25
- Multi-region + DR + RTO/RPO + Well-Architected
  - Oficial: AWS Disaster Recovery whitepaper + Reliability Pillar
  - Libro: *AWS for Solutions Architects* - DR chapter
  - Udemy: [COMPRA REQUERIDA] *SAA-C03* - DR and multi-region (`$10-$20`)
- Cost optimization
  - Oficial: AWS Cost Explorer docs
  - Libro: *Cloud FinOps* - optimization chapters
  - Udemy: [OPCIONAL] *AWS FinOps Basics* (`$10-$20`)

## Semana 26
- Estimaciones numericas de system design
  - Oficial: Google SRE SLO chapters
  - Libro: *System Design Interview Vol. 1* - Chapter 1 (estimation framework)
  - Udemy: [COMPRA REQUERIDA] *Grokking System Design* - Capacity estimation module (`$12-$25`)
- Caching distribuido
  - Oficial: Redis docs (caching patterns)
  - Libro: *Designing Data-Intensive Applications* - caching sections
  - Udemy: [COMPRA REQUERIDA] *Redis Complete Guide* (`$10-$20`)

## Semana 27
- Rate limiting, sharding, consistencia, colas + DLQ
  - Oficial: AWS SQS DLQ docs + architecture patterns
  - Libro: *Designing Data-Intensive Applications* - partitioning/consistency
  - Udemy: [COMPRA REQUERIDA] *Software Architecture* - distributed patterns (`$12-$25`)
- Diseno de notificaciones
  - Oficial: AWS SNS/SQS architecture examples
  - Libro: *System Design Interview Vol. 2* - notification system
  - Udemy: [OPCIONAL] *System Design* notification case (`$10-$20`)

## Semana 28
- Diseno de pagos, idempotencia, retries, reconciliacion
  - Oficial: Stripe docs (idempotency concepts) + AWS retry guidance
  - Libro: *Payments Systems in the U.S.* - core concepts (capitulos intro)
  - Udemy: [OPCIONAL] *Payment Gateway Integration* (`$10-$20`)
- Defensa escrita/oral, checklist, postmortem
  - Oficial: AWS Well-Architected review process
  - Libro: *The Pyramid Principle* - Chapters 1-3 (argumentacion)
  - Udemy: [OPCIONAL] *Communication Skills for Engineers* (`$10-$20`)

---

# MES 1 (Semanas 1-4) - JAVA CORE + JVM + ESTRUCTURAS DE DATOS
## Producto mensual: core-engine-lab

## Semana 1
### Bloques de temas
- POO: Encapsulacion profunda
- POO: Abstraccion aplicada
- POO: Inmutabilidad bien aplicada
- POO: Cohesion vs Acoplamiento (intro)
- Testing: Unit testing estructurado (intro)
- Testing: Test de clases inmutables (intro)
- AWS Inicio: IAM basico (intro)
- AWS Inicio: Policies vs Roles (intro)
- CROSS: Git profesional (base)
- CROSS: Conventional commits (base)
- CROSS: Resolucion estructurada de problemas
- CROSS: Pensamiento computacional

### Bloque de practicas
- AWS (IAM): crear usuario/rol con permisos minimos (sin "*") + politica minima para un caso real

### Avance Producto Mensual (core-engine-lab)
- Setup repo + estructura + README base
- Implementar 1-2 clases inmutables + tests
- Meta: 20%

---

## Semana 2
### Bloques de temas
- POO: Herencia vs Composicion (cuando usar cada una)
- POO: Polimorfismo dinamico real
- POO: Records vs clases tradicionales
- Testing: Mockito (intro)
- AWS Inicio: S3 basico (concepto + consola)
- CROSS: Pull Request estructurado
- CROSS: Code review checklist

### Bloque de practicas
- AWS (S3): crear bucket, subir/bajar objetos por consola (con permisos minimos)

### Avance Producto Mensual (core-engine-lab)
- Documentar decisiones POO (composicion vs herencia)
- Agregar ejemplos con tests
- Meta: 40%

---

## Semana 3
### Bloques de temas
- Estructuras: Big-O analisis
- Estructuras: HashMap internals
- Estructuras: List vs ArrayList vs LinkedList
- Estructuras: Complejidad temporal vs espacial
- POO: equals/hashCode contrato
- AWS Inicio: AWS CLI con perfiles seguros (intro)
- CROSS: Validacion basica de input
- CROSS: Principio Fail Fast

### Bloque de practicas
- AWS (CLI): configurar perfiles seguros y operar S3 desde CLI (subir/bajar)

### Avance Producto Mensual (core-engine-lab)
- "HashMap internals notes" (mini doc defendible)
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
- Estructuras: Trees basicos
- Testing: Coverage >= 70%
- Testing: Principios de testing limpio
- AWS Inicio: SDK Java S3
- AWS Inicio: Manejo seguro de credenciales

### Bloque de practicas
- Practica AWS Inicio (completa):
  - Crear usuarios/roles IAM con minimo privilegio
  - AWS CLI con perfiles
  - S3 buckets + operaciones
  - CRUD en S3 desde Java (AWS SDK)
  - Rotacion/manejo de credenciales sin exponer llaves

### Avance Producto Mensual (core-engine-lab)
- Implementacion LRU Cache propia + tests
- Ejemplos de concurrencia controlada + tests
- README tecnico defendible
- Commits estructurados
- Meta: 100% (cierre MES 1)

---

# MES 2 (Semanas 5-8) - SPRING BOOT MVC + SQL + ARQUITECTURA
## Producto mensual: order-service-monolith

## Semana 5
### Bloques de temas
- Spring MVC: Arquitectura basada en Servlet
- Spring MVC: DispatcherServlet y ciclo completo de request
- Spring MVC: Thread-per-request model
- Spring MVC: @RestController vs @Controller
- Arquitectura: Service Layer
- Arquitectura: DTO vs Entity
- AWS: Elastic Beanstalk (intro)
- CROSS: Diseno profesional de APIs REST (principios)

### Bloque de practicas
- Skeleton API + 2 endpoints + validacion simple

### Avance Producto Mensual (order-service-monolith)
- Repo + estructura + primer vertical slice (controller -> service)
- Meta: 20%

---

## Semana 6
### Bloques de temas
- Spring MVC: Filtros vs Interceptors
- Spring MVC: Validacion con @Valid y BindingResult
- Spring MVC: HttpMessageConverters
- Spring MVC: Manejo correcto de codigos HTTP
- Arquitectura: SOLID profundo
- Arquitectura: Mapper pattern
- AWS: CloudWatch Logs (intro)
- DevOps: Docker (intro)
- CROSS: Versionado API (path vs header)
- CROSS: GitFlow formal (intro)
- CROSS: Versionado semantico

### Bloque de practicas
- Logging base + manejo de errores inicial (sin @ControllerAdvice aun)
- Dockerfile inicial

### Avance Producto Mensual
- CRUD base + validaciones robustas minimas
- Meta: 45%

---

## Semana 7
### Bloques de temas
- Spring Internals: IoC container
- Spring Internals: ApplicationContext
- Spring Internals: Bean lifecycle
- Spring Internals: Scopes
- Spring Internals: Proxy dinamico
- Spring Internals: AOP interno
- Spring Internals: Lazy initialization
- Spring Internals: Profiles por entorno
- Spring MVC: Personalizacion de Jackson
- Spring MVC: ResponseEntity avanzado
- Arquitectura: Clean Architecture
- Arquitectura: Hexagonal
- AWS: Variables de entorno seguras (Beanstalk)
- CROSS: OWASP API Top 10 (introduccion)
- CROSS: Gestion profesional de branches

### Bloque de practicas
- Configuracion por perfiles (dev/prod) + env vars seguras
- Reorganizar estructura hacia capas defendibles

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
- Persistencia real: Indices
- Persistencia real: EXPLAIN ANALYZE
- Persistencia real: Locking optimista vs pesimista
- Spring Internals: @Transactional internals
- Spring MVC: @ControllerAdvice aplicado a MVC
- Spring MVC: Upload / Download de archivos
- Spring MVC: Integracion correcta de @Transactional en capa service
- DevOps: Multi-stage build
- DevOps: CI/CD basico (build + test)
- AWS: Lambda (intro)
- AWS: Elastic Beanstalk + rollback + CloudWatch logs (consolidacion)
- CROSS: Rebase interactivo

### Bloque de practicas
- Practica AWS Mes 2 (completa):
  - Deploy en Elastic Beanstalk
  - Logs en CloudWatch Logs (errores/latencia)
  - Cambiar env vars sin recompilar
  - Rollback desde consola/CLI
  - Metricas basicas (latencia, error rate)

### Avance Producto Mensual
- API MVC completa + validaciones + errores profesionales
- JPA optimizado
- Dockerizado + CI basico
- Documento arquitectura defendible
- Meta: 100% (cierre MES 2)

---

# MES 3 (Semanas 9-12) - WEBFLUX + CACHE + REDES + AWS DEV
## Producto mensual: inventory-reactive-service

## Semana 9
### Bloques de temas
- WebFlux: Mono vs Flux
- WebFlux: Thread model
- WebFlux: WebClient (base)
- Networking: HTTP internals (nocion)
- Networking: Timeouts (intro)
- Cache: Cache-aside pattern (intro)
- AWS Developer: DynamoDB (intro)
- CROSS: Gestion segura de secrets (intro)

### Bloque de practicas
- DynamoDB: crear tabla + CRUD desde Java (minimo)

### Avance Producto Mensual
- Servicio WebFlux base + endpoint + primer call externo
- Meta: 20%

---

## Semana 10
### Bloques de temas
- WebFlux: Error handling reactivo
- WebFlux: Blocking vs Non-blocking
- WebFlux: Cuando NO usar WebFlux
- WebFlux: Schedulers (intro)
- Networking: Retry + backoff exponencial
- Networking: Idempotencia HTTP
- Cache: Redis basico (intro)
- AWS Developer: SQS (intro: Standard vs FIFO)
- CROSS: Idempotency keys (conceptual)
- CROSS: Rate limiting conceptual

### Bloque de practicas
- SQS: publicar/consumir mensajes (minimo)
- WebClient: timeout + retry con limites

### Avance Producto Mensual
- Flujo reactivo mas robusto + pruebas minimas
- Meta: 45%

---

## Semana 11
### Bloques de temas
- WebFlux: Backpressure (profundo)
- Cache: Caffeine
- Cache: TTL strategies
- Cache: Cache invalidation (conceptos y problemas)
- AWS Developer: SNS (intro) + suscripciones
- Operacion SQS/SNS: visibility timeout (intro)
- Operacion SQS/SNS: redrive policy (intro)
- Testing: Tests reactivos (intro)
- CROSS: Observabilidad basica (logs/metricas base)

### Bloque de practicas
- SNS -> SQS (flujo) + DLQ configurada (minimo)

### Avance Producto Mensual
- Cache implementado (redis/caffeine segun aplique) + doc breve TTL/invalidation
- Meta: 65%

---

## Semana 12
### Bloques de temas
- Testing: Integration testing
- Testing: Testcontainers
- Testing: Tests reactivos (consolidacion)
- AWS Developer: API Gateway
- AWS Developer: ECS
- AWS Developer: DLQ basica
- Operacion real SQS/SNS:
  - FIFO vs Standard
  - MessageGroupId
  - Deduplication ID
  - Visibility timeout
  - Redrive policy
  - Idempotencia real en consumidores
- Observabilidad: CloudWatch Monitoring
- Observabilidad: Dashboards + alarmas
- Networking: TLS basico + DNS nocion
- CROSS: DevOps thinking
- CROSS: Configuracion por entornos

### Bloque de practicas
- Practica AWS Developer (completa):
  - DynamoDB (CRUD)
  - SQS (Standard/FIFO) publicar/consumir
  - SNS suscripciones
  - API GW -> Lambda/ECS -> SQS -> Consumer
  - Consumer resiliente con visibility timeout + redrive policy + DLQ
  - Pruebas end-to-end

### Avance Producto Mensual
- Servicio completo + deploy AWS
- Documento comparativo MVC vs WebFlux
- Metricas/logs en CloudWatch + dashboards + alarmas
- Analisis de fallo documentado
- Meta: 100% (cierre MES 3)

---

# MES 4 (Semanas 13-16) - DISTRIBUIDOS + OBSERVABILIDAD + CONSISTENCIA
## Producto mensual: payment-event-driven-system

## Semana 13
### Bloques de temas
- Patrones distribuidos: Circuit Breaker
- Patrones distribuidos: Retry
- Patrones distribuidos: Idempotencia
- Patrones distribuidos: At-least-once vs exactly-once
- Observabilidad: Logs estructurados (base)
- CROSS: Metricas vs logs vs traces (base)

### Bloque de practicas
- Simular reintentos controlados + idempotencia en consumidor

### Avance Producto Mensual
- Esqueleto event-driven + cola + consumidor base
- Meta: 25%

---

## Semana 14
### Bloques de temas
- Patrones distribuidos: Outbox
- Consistencia eventual practica
- Observabilidad: Correlation ID
- Observabilidad: DLQ monitoring (base)
- CROSS: Runbook basico (intro)

### Bloque de practicas
- Outbox "simulado" + idempotencia en consumo

### Avance Producto Mensual
- Flujo principal "happy path" + DLQ funcionando
- Meta: 50%

---

## Semana 15
### Bloques de temas
- Patrones distribuidos: Saga
- Patrones distribuidos: CQRS (trade-offs)
- Observabilidad: Micrometer (intro)
- Observabilidad: Alerting basico
- Observabilidad: Distributed tracing conceptual
- Observabilidad: APM nocion (Dynatrace / Datadog / New Relic)
- CROSS: Estrategia uniforme de logging

### Bloque de practicas
- Simular saga minima (o compensacion) + documentar decisiones

### Avance Producto Mensual
- Caso de fallo + recuperacion documentada
- Meta: 70%

---

## Semana 16
### Bloques de temas
- Observabilidad pro: Prometheus (nocion)
- Observabilidad pro: Grafana (nocion)
- Observabilidad pro: RED metrics
- Observabilidad operativa: Dashboard minimo (latencia p95, error rate, throughput)
- Observabilidad operativa: Correlacion logs-metricas-trazas
- Observabilidad operativa: Triage de latencia
- Observabilidad operativa: Deteccion temprana de degradacion
- Simulador: Examen AWS Developer
- CROSS: Simulacion incidente tecnico

### Bloque de practicas
- Dashboard minimo + alarmas + simulacion de incidente (con hallazgos)

### Avance Producto Mensual
- Sistema listo + DLQ correcta + metricas + dashboard
- Documento consistencia eventual + simulacion fallo documentada
- Meta: 100% (cierre MES 4)

---

# MES 5 (Semanas 17-20) - PERFORMANCE + SEGURIDAD AVANZADA
## Producto mensual: secure-gateway-service

## Semana 17
### Bloques de temas
- Seguridad: OAuth2 profundo
- Seguridad: JWT lifecycle
- Seguridad: Principio minimo privilegio (conceptual)
- Seguridad: Seguridad interna microservicios
- DevOps avanzado: Feature flags (nocion)
- CROSS: Threat modeling (STRIDE) (intro)

### Bloque de practicas
- Auth flow minimo + emision/validacion JWT (seguro)

### Avance Producto Mensual
- Skeleton gateway + auth basico
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

### Bloque de practicas
- Rate limiting real + headers + validaciones + checklist OWASP aplicado

### Avance Producto Mensual
- Seguridad solida en endpoints + doc amenazas/mitigaciones
- Meta: 50%

---

## Semana 19
### Bloques de temas
- Performance: Throughput vs Latency
- Performance: p95 vs p99 analisis
- Performance: Profiling CPU/memory
- Performance: Heap dump analisis
- Performance: Thread dumps
- Performance: Deadlock detection
- Contenedores: Docker multi-stage
- Contenedores: Resource limits
- Contenedores: OOMKilled analisis
- Contenedores: GC vs container memory

### Bloque de practicas
- Load testing basico (k6/JMeter)
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
- Seguridad: Replay attack basico
- CROSS: Gestion vulnerabilidades
- CROSS: Postmortem tecnico profesional
- CROSS: Gestion de incidentes reales

### Bloque de practicas
- Documento de seguridad + simulacion despliegue/rollback

### Avance Producto Mensual
- Gateway terminado (OAuth2/JWT) + rate limiting real
- Analisis heap dump documentado
- Documento seguridad (OWASP + mitigaciones)
- Meta: 100% (cierre MES 5)

---

# MES 6 (Semanas 21-24) - AWS ARCHITECT I (TECNICO ENDURECIDO)
## Producto mensual: high-availability-architecture (documento tecnico)

## Semana 21
### Bloques de temas
- AWS Networking: VPC
- AWS Networking: CIDR planning (calculo de rangos, crecimiento, segmentacion)
- AWS Networking: Subnetting (public/private, AZ distribution)
- AWS Networking: Route tables (flujo real de trafico)
- Modelado tecnico: estimacion de QPS (intro)
- CROSS: Checklist antes de release (infra + app) (intro)

### Bloque de practicas
- Construir VPC con subnets publicas/privadas funcionales

### Avance Producto Mensual (high-availability-architecture)
- Diagrama base + supuestos iniciales
- Meta: 25%

---

## Semana 22
### Bloques de temas
- AWS Networking: Security Groups vs NACL (stateful vs stateless + casos reales)
- AWS Networking: NAT Gateway (impacto tecnico y economico)
- Modelado tecnico: concurrencia pico
- Modelado tecnico: conexiones simultaneas a DB
- Modelado tecnico: Throughput vs Latency (cuando escala y cuando no)
- Cost modeling: NAT vs endpoints (nocion)
- CROSS: Runbook operacion minima (intro)

### Bloque de practicas
- Validar que solo subnets correctas salen a Internet (NAT + reglas)

### Avance Producto Mensual
- Seccion redes lista + primeros costos
- Meta: 50%

---

## Semana 23
### Bloques de temas
- AWS Networking: ALB vs NLB (casos por protocolo y performance)
- AWS Networking: Target Groups + Health checks (fallos tipicos y tuning)
- Auto Scaling:
  - Policies por CPU
  - Policies por RequestCount/TargetResponseTime
  - Cooldowns, warmup, flapping
- Failure modeling:
  - cae 1 AZ
  - ALB con target unhealthy
- Modelado tecnico:
  - IOPS (lecturas/escrituras)
  - impacto cross-AZ (latencia + costo data transfer)

### Bloque de practicas
- Desplegar ALB + target groups + simular health checks y fallos

### Avance Producto Mensual
- Seccion HA/ASG + fallos tipicos documentados
- Meta: 75%

---

## Semana 24
### Bloques de temas
- Failure modeling:
  - NAT saturado / error DNS
  - DB lenta (conexiones agotadas)
- Estrategias:
  - degradacion controlada
  - timeouts + retries con limites
  - circuit breaker en borde
  - backpressure / shedding (nocion)
- Cost modeling:
  - costo mensual ALB (base + LCU aproximado)
  - EC2/ECS (instancias y escalado)
  - RDS (single vs multi-AZ)
  - data transfer (cross-AZ/cross-region nocion)
- Trade-offs:
  - Multi-AZ vs Single-AZ
  - ALB vs NLB
  - NAT vs endpoints
- CROSS: Estrategia formal Blue/Green (pasos, riesgos, rollback)

### Bloque de practicas
- Practica AWS Architect I (consolidacion):
  - estimar costos mensuales aproximados
  - simular fallo de AZ (al menos diseno + validacion)
  - ajustar policies de Auto Scaling y medir impacto
  - comparar NACL vs SG en escenarios

### Avance Producto Mensual
- Documento final completo:
  - diagrama end-to-end
  - QPS/concurrencia (con supuestos)
  - diseno subnets/route tables (resumen)
  - plan resiliencia (fallos y respuesta)
  - estimacion costos
  - plan rollback
- Meta: 100% (cierre MES 6)

---

# MES 7 (Semanas 25-28) - AWS ARCHITECT II + SYSTEM DESIGN (CON NUMEROS)
## Producto mensual: distributed-ecommerce-platform

## Semana 25
### Bloques de temas
- Multi-region patterns (active-passive / active-active) (nocion)
- Disaster Recovery strategies:
  - Backup & Restore
  - Pilot Light
  - Warm Standby
  - Multi-site (nocion)
- RTO / RPO (definicion, implicacion en costo)
- Well-Architected Framework (pilares aplicados a decisiones)
- Cost optimization (rightsizing, savings, data transfer awareness)

### Bloque de practicas
- Definir DR del proyecto (RTO/RPO) y justificar costo
- Simular arquitectura multi-region y degradacion controlada ante caida regional

### Avance Producto Mensual (distributed-ecommerce-platform)
- Estructura de docs + baseline arquitectura + DR planteado
- Meta: 25%

---

## Semana 26
### Bloques de temas
- System Design (con numeros):
  - estimar QPS desde DAU/MAU
  - tamano request/response
  - almacenamiento diario/mensual/anual
  - crecimiento mensual/anual
  - latencia objetivo (SLO p95)
  - identificar primer bottleneck (CPU/IO/DB/red/locks)
- Componentes:
  - caching distribuido (Redis cluster nocion)
  - TTLs
  - invalidacion
  - cache stampede (nocion)
- Diseno 1: E-commerce (catalogo + carrito + checkout simplificado)

### Bloque de practicas
- Writing drill: 1 pagina defendiendo Diseno 1 (trade-offs)

### Avance Producto Mensual
- Diseno 1 completo + numeros + diagrama (flujo/datos)
- Meta: 50%

---

## Semana 27
### Bloques de temas
- Componentes:
  - rate limiting distribuido (token bucket / leaky bucket) (nocion)
  - llaves por usuario/cliente/IP
  - sharding/particionamiento (por usuario / por region) (nocion practica)
  - consistencia fuerte vs eventual (casos de negocio)
  - mensajeria: colas + DLQ como resiliencia
- Diseno 2: Notificaciones (email/SMS/push con colas + DLQ)

### Bloque de practicas
- Writing drill: 1 pagina defendiendo Diseno 2 + checklist (seguridad/obs/fallos)

### Avance Producto Mensual
- Diseno 2 completo + numeros + postmortem simulado (incidente)
- Meta: 75%

---

## Semana 28
### Bloques de temas
- Diseno 3: Pagos simplificados
  - idempotencia + reintentos + reconciliacion basica
- Writing drills: 1 pagina por diseno (trade-offs)
- Checklist revision de diseno (seguridad, observabilidad, fallos)
- Postmortem simulado (un incidente por diseno)
- Simulacion defensa oral (guion 10-15 min)

### Bloque de practicas
- Guion de defensa oral + 3 diagramas minimos:
  - flujo
  - datos
  - fallos

### Avance Producto Mensual
- Proyecto global completo:
  - docs + diagramas + numeros
  - resiliencia (fallos y respuesta)
  - DR (RTO/RPO)
  - documento estilo entrevista senior
- Meta: 100% (cierre MES 7)

---
