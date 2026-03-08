# RECURSOS POR TEMA - PLAN SENIOR CROSS (JAVA + AWS)

Base: `NEW/semanal-ajustada.md`
Moneda: USD
Nota de costo: en Udemy el precio cambia mucho por pais/promocion. Usa estos rangos:
- Oferta comun: `$10-$20`
- Precio sin oferta: `$79.99-$129.99`

## OPTIMIZACION MAXIMA DE COSTO (SIN MERMAR APRENDIZAJE)

Estrategia:
- Comprar solo cursos "tronco" que se reutilizan muchos meses.
- Cubrir temas puntuales con documentacion oficial + libro (sin comprar cursos extra).
- Evitar cursos solapados (ejemplo: varios de Spring o varios de AWS para el mismo objetivo).

Carrito minimo recomendado (4 cursos):
1. Java base/concurrencia:
   - https://www.udemy.com/course/java-the-complete-java-developer-course/
   - Cubre OOP y base Java de Mes 1.
2. AWS Developer Associate (Meses 2-4):
   - https://www.udemy.com/course/aws-certified-developer-associate-dva-c02/
   - Cubre IAM/S3/Lambda/API GW/SQS/SNS/ECS/CloudWatch.
3. AWS Solutions Architect Associate (Meses 6-7):
   - https://www.udemy.com/course/aws-certified-solutions-architect-associate-saa-c03/
   - Cubre VPC, SG/NACL, ALB/NLB, ASG, DR, trade-offs, costos.
4. System Design:
   - https://www.udemy.com/course/grokking-the-system-design-interview/
   - Cubre estimaciones, bottlenecks, escalado, diseños defendibles.

Costo total objetivo en oferta:
- 4 cursos x `$10-$20` = **`$40-$80`** total.

Que NO comprar (usar gratis/oficial/libro):
- Testing (JUnit/Mockito): docs oficiales + practica guiada.
- Observabilidad (Prometheus/Grafana/OpenTelemetry): docs oficiales.
- Seguridad (OWASP, OAuth2/JWT, headers, CORS/CSRF): OWASP + RFCs + Spring Security docs.
- Performance Java (JFR/JMC/GC): docs Oracle + laboratorio propio.

Si quieres reducir aun mas:
- Si ya tienes base Java fuerte, omite curso Java y quedas en 3 cursos:
- **`$30-$60`** total en oferta.

---

## MAS RECURSOS GRATUITOS (FOROS Y COMUNIDAD ESPECIALIZADA)

Para enriquecer aprendizaje sin pagar mas, usa esta capa extra:

### 1) Soporte tecnico serio (preguntas y respuestas)
- AWS re:Post (oficial AWS): https://repost.aws/
- Stack Overflow - Java tag: https://stackoverflow.com/questions/tagged/java
- Stack Overflow - Spring Boot tag: https://stackoverflow.com/questions/tagged/spring-boot
- Stack Overflow - AWS tag: https://stackoverflow.com/questions/tagged/amazon-web-services
- Coderanch (foro Java clasico): https://coderanch.com/forums

### 2) Comunidad oficial/proyecto (mejor para dudas de framework)
- Spring "Getting Help": https://spring.io/projects/spring-boot#learn
- Spring Boot Discussions (GitHub): https://github.com/spring-projects/spring-boot/discussions
- OpenJDK mailing lists (temas JVM/JDK): https://mail.openjdk.org/mailman/listinfo

### 3) Practica gratuita guiada
- AWS Workshops (hands-on oficiales): https://workshops.aws/
- AWS Skill Builder (catalogo free + paid): https://explore.skillbuilder.aws/learn
- Exercism Java track (katas guiadas): https://exercism.org/tracks/java

### 4) Lectura tecnica gratis de alta calidad
- dev.java (portal oficial Java): https://dev.java/
- Baeldung (mucho contenido gratuito): https://www.baeldung.com/
- Foojay (Java weekly/community): https://foojay.io/

### Como usarlos sin perder tiempo
- Regla 80/20:
  - 80% documentacion oficial + practica del plan.
  - 20% foros/comunidad para bloqueos reales.
- Para cada duda tecnica:
  - 1) Busca primero en documentacion oficial.
  - 2) Si no resuelve, busca en Stack Overflow o re:Post.
  - 3) Si sigue ambiguo, publica pregunta con contexto minimo reproducible.
- Criterio de calidad de respuesta en foros:
  - Prioriza respuestas con version de framework, codigo reproducible y explicacion de trade-off.

---

## MES 1 - JAVA CORE + JVM + ESTRUCTURAS

### POO y fundamentos
- Encapsulacion profunda
  - Oficial: https://docs.oracle.com/javase/tutorial/java/javaOO/
  - Udemy: https://www.udemy.com/course/java-the-complete-java-developer-course/
  - Costo: `$10-$20` oferta
- Abstraccion aplicada
  - Oficial: https://docs.oracle.com/javase/tutorial/java/IandI/abstract.html
  - Udemy: https://www.udemy.com/course/java-programming-tutorial-for-beginners/
  - Costo: `$10-$20` oferta
- Inmutabilidad bien aplicada
  - Oficial: https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/Record.html
  - Udemy: https://www.udemy.com/course/java-multithreading-concurrency-performance-optimization/
  - Tema/video a ver en Udemy: seccion de `Immutability and Thread Safety` (keywords: immutable objects, final fields, safe publication)
  - Costo: `$10-$20` oferta
- Cohesion vs acoplamiento
  - Oficial: https://docs.oracle.com/javase/tutorial/java/concepts/
  - Udemy: https://www.udemy.com/course/software-architecture-design-of-modern-large-scale-systems/
  - Costo: `$12-$25` oferta
- Herencia vs composicion
  - Oficial: https://docs.oracle.com/javase/tutorial/java/IandI/subclasses.html
  - Udemy: https://www.udemy.com/course/java-the-complete-java-developer-course/
  - Costo: `$10-$20` oferta
- Polimorfismo dinamico
  - Oficial: https://docs.oracle.com/javase/tutorial/java/IandI/polymorphism.html
  - Udemy: https://www.udemy.com/course/java-programming-tutorial-for-beginners/
  - Costo: `$10-$20` oferta
- Records vs clases tradicionales
  - Oficial: https://openjdk.org/jeps/395
  - Udemy: https://www.udemy.com/course/java-the-complete-java-developer-course/
  - Costo: `$10-$20` oferta
- equals/hashCode contrato
  - Oficial: https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/Object.html
  - Udemy: https://www.udemy.com/course/java-the-complete-java-developer-course/
  - Costo: `$10-$20` oferta

### Estructuras y complejidad
- Big-O
  - Oficial: https://www.geeksforgeeks.org/analysis-algorithms-big-o-analysis/ 
  - Udemy: https://www.udemy.com/course/master-the-coding-interview-data-structures-algorithms/
  - Costo: `$10-$20` oferta
- HashMap internals
  - Oficial: https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/HashMap.html
  - Udemy: https://www.udemy.com/course/data-structures-and-algorithms-deep-dive-using-java/
  - Costo: `$10-$20` oferta
- List vs ArrayList vs LinkedList
  - Oficial: https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/List.html
  - Udemy: https://www.udemy.com/course/data-structures-and-algorithms-deep-dive-using-java/
  - Costo: `$10-$20` oferta
- Complejidad temporal vs espacial
  - Oficial: https://docs.oracle.com/javase/tutorial/collections/
  - Udemy: https://www.udemy.com/course/master-the-coding-interview-data-structures-algorithms/
  - Costo: `$10-$20` oferta
- Heap / PriorityQueue
  - Oficial: https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/PriorityQueue.html
  - Udemy: https://www.udemy.com/course/data-structures-and-algorithms-deep-dive-using-java/
  - Costo: `$10-$20` oferta
- Trees basicos
  - Oficial: https://docs.oracle.com/javase/tutorial/collections/interfaces/
  - Udemy: https://www.udemy.com/course/data-structures-and-algorithms-deep-dive-using-java/
  - Costo: `$10-$20` oferta
- LRU Cache propia
  - Oficial: https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/LinkedHashMap.html
  - Udemy: https://www.udemy.com/course/data-structures-and-algorithms-deep-dive-using-java/
  - Costo: `$10-$20` oferta

### JVM, concurrencia y testing
- Heap vs stack / JMM / volatile / locks / atomics / race conditions
  - Oficial: https://docs.oracle.com/javase/specs/jls/se17/html/jls-17.html
  - Oficial: https://docs.oracle.com/javase/tutorial/essential/concurrency/
  - Udemy: https://www.udemy.com/course/java-multithreading-concurrency-performance-optimization/
  - Tema/video a ver en Udemy:
    - `Java Memory Model (JMM) and Happens-Before`
    - `Data Races and Race Conditions`
    - `Volatile Keyword`
    - `Locks and Synchronization` (intrinsic lock vs `ReentrantLock`)
    - `Atomic Operations` (`AtomicInteger`, `AtomicReference`)
  - Costo: `$10-$20` oferta
- ExecutorService / ConcurrentHashMap / ThreadLocal / deadlock
  - Oficial: https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/concurrent/package-summary.html
  - Udemy: https://www.udemy.com/course/java-multithreading-concurrency-performance-optimization/
  - Tema/video a ver en Udemy:
    - `Thread Creation and Lifecycle`
    - `Executor Framework / Thread Pools`
    - `Concurrent Collections` (`ConcurrentHashMap`)
    - `ThreadLocal`
    - `Deadlocks, Livelocks and Starvation`
  - Costo: `$10-$20` oferta
- Unit testing / Mockito / cobertura
  - Oficial: https://junit.org/junit5/docs/current/user-guide/
  - Oficial: https://site.mockito.org/
  - Udemy: https://www.udemy.com/course/junit5-for-beginners/
  - Costo: `$10-$20` oferta

### AWS y cross profesional
- IAM / Policies vs Roles
  - Oficial: https://docs.aws.amazon.com/IAM/latest/UserGuide/introduction.html
  - Udemy: https://www.udemy.com/course/aws-certified-cloud-practitioner-new/
  - Costo: `$10-$20` oferta
- S3 / AWS CLI / SDK Java / credenciales
  - Oficial: https://docs.aws.amazon.com/s3/
  - Oficial: https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-welcome.html
  - Oficial: https://docs.aws.amazon.com/sdk-for-java/latest/developer-guide/home.html
  - Udemy: https://www.udemy.com/course/aws-sdk-for-java/
  - Costo: `$10-$20` oferta
- Git profesional / PR / code review / fail fast
  - Oficial: https://git-scm.com/doc
  - Udemy: https://www.udemy.com/course/git-and-github-bootcamp/
  - Costo: `$10-$20` oferta

---

## MES 2 - SPRING MVC + SQL + ARQUITECTURA

### Spring MVC e internals
- Servlet, DispatcherServlet, thread-per-request, controllers
  - Oficial: https://docs.spring.io/spring-framework/reference/web/webmvc.html
  - Udemy: https://www.udemy.com/course/spring-hibernate-tutorial/
  - Costo: `$10-$20` oferta
- Filtros, interceptors, validacion, converters, codigos HTTP
  - Oficial: https://docs.spring.io/spring-framework/reference/web/webmvc/mvc-config.html
  - Oficial: https://docs.spring.io/spring-framework/reference/core/validation/beanvalidation.html
  - Udemy: https://www.udemy.com/course/spring-boot-restful-web-services-and-microservices/
  - Costo: `$10-$20` oferta
- Jackson, ResponseEntity, ControllerAdvice, upload/download
  - Oficial: https://docs.spring.io/spring-framework/reference/web/webmvc/mvc-controller/ann-methods/responseentity.html
  - Udemy: https://www.udemy.com/course/spring-boot-restful-web-services-and-microservices/
  - Costo: `$10-$20` oferta
- IoC, ApplicationContext, lifecycle, scopes, AOP, profiles, lazy
  - Oficial: https://docs.spring.io/spring-framework/reference/core/beans.html
  - Udemy: https://www.udemy.com/course/spring-framework-5-beginner-to-guru/
  - Costo: `$10-$20` oferta
- Transactional (internals y service layer)
  - Oficial: https://docs.spring.io/spring-framework/reference/data-access/transaction.html
  - Udemy: https://www.udemy.com/course/spring-hibernate-tutorial/
  - Costo: `$10-$20` oferta

### Persistencia y arquitectura
- JPA/Hibernate, N+1, Lazy/Eager, isolation, locking, indices, EXPLAIN
  - Oficial: https://docs.jboss.org/hibernate/orm/current/userguide/html_single/
  - Oficial: https://docs.spring.io/spring-data/jpa/reference/
  - Udemy: https://www.udemy.com/course/hibernate-and-spring-data-jpa-beginner-to-guru/
  - Costo: `$10-$20` oferta
- SOLID / Clean / Hexagonal / DTO-Entity / Mapper / Service Layer
  - Oficial: https://12factor.net/
  - Udemy: https://www.udemy.com/course/software-architecture-design-of-modern-large-scale-systems/
  - Costo: `$12-$25` oferta

### AWS, DevOps y cross
- Elastic Beanstalk, CloudWatch logs, Lambda, env vars
  - Oficial: https://docs.aws.amazon.com/elasticbeanstalk/
  - Oficial: https://docs.aws.amazon.com/AmazonCloudWatch/latest/logs/WhatIsCloudWatchLogs.html
  - Oficial: https://docs.aws.amazon.com/lambda/
  - Udemy: https://www.udemy.com/course/aws-certified-developer-associate-dva-c02/
  - Costo: `$10-$20` oferta
- Docker / multi-stage / CI-CD basico
  - Oficial: https://docs.docker.com/
  - Oficial: https://docs.github.com/en/actions
  - Udemy: https://www.udemy.com/course/docker-kubernetes-the-practical-guide/
  - Costo: `$10-$20` oferta
- API design, GitFlow, semver, rebase
  - Oficial: https://semver.org/
  - Oficial: https://git-scm.com/docs/git-rebase
  - Udemy: https://www.udemy.com/course/git-and-github-bootcamp/
  - Costo: `$10-$20` oferta

---

## MES 3 - WEBFLUX + CACHE + REDES + AWS DEV

- Mono/Flux, schedulers, backpressure, WebClient, errores
  - Oficial: https://docs.spring.io/spring-framework/reference/web/webflux.html
  - Udemy: https://www.udemy.com/course/reactive-programming-with-spring-framework-5/
  - Costo: `$10-$20` oferta
- Cache-aside, Redis, Caffeine, TTL, invalidation
  - Oficial: https://redis.io/docs/
  - Oficial: https://github.com/ben-manes/caffeine/wiki
  - Udemy: https://www.udemy.com/course/redis-the-complete-developers-guide-p/
  - Costo: `$10-$20` oferta
- HTTP internals, idempotencia, timeout, retry/backoff, TLS, DNS
  - Oficial: https://developer.mozilla.org/en-US/docs/Web/HTTP
  - Oficial: https://datatracker.ietf.org/doc/html/rfc9110
  - Udemy: https://www.udemy.com/course/computer-networking/
  - Costo: `$10-$20` oferta
- DynamoDB, SQS, SNS, API Gateway, ECS, DLQ
  - Oficial: https://docs.aws.amazon.com/amazondynamodb/
  - Oficial: https://docs.aws.amazon.com/AWSSimpleQueueService/
  - Oficial: https://docs.aws.amazon.com/sns/
  - Oficial: https://docs.aws.amazon.com/apigateway/
  - Oficial: https://docs.aws.amazon.com/ecs/
  - Udemy: https://www.udemy.com/course/aws-certified-developer-associate-dva-c02/
  - Costo: `$10-$20` oferta
- Testcontainers, integration tests, tests reactivos
  - Oficial: https://java.testcontainers.org/
  - Udemy: https://www.udemy.com/course/testing-spring-boot-beginner-to-guru/
  - Costo: `$10-$20` oferta
- CloudWatch monitoring, dashboards, alarmas
  - Oficial: https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/
  - Udemy: https://www.udemy.com/course/aws-certified-cloud-practitioner-new/
  - Costo: `$10-$20` oferta

---

## MES 4 - DISTRIBUIDOS + OBSERVABILIDAD

- Circuit breaker, retry, outbox, saga, CQRS, consistencia eventual
  - Oficial: https://microservices.io/patterns/
  - Udemy: https://www.udemy.com/course/software-architecture-design-of-modern-large-scale-systems/
  - Costo: `$12-$25` oferta
- At-least-once vs exactly-once, idempotencia
  - Oficial: https://kafka.apache.org/documentation/
  - Udemy: https://www.udemy.com/course/apache-kafka/
  - Costo: `$10-$20` oferta
- Logs estructurados, correlation id, metricas, alertas, RED
  - Oficial: https://opentelemetry.io/docs/
  - Oficial: https://prometheus.io/docs/introduction/overview/
  - Oficial: https://grafana.com/docs/
  - Udemy: https://www.udemy.com/course/observability-with-prometheus/
  - Costo: `$10-$20` oferta
- Tracing distribuido y APM
  - Oficial: https://opentelemetry.io/docs/concepts/signals/traces/
  - Udemy: https://www.udemy.com/course/opentelemetry-for-developers/
  - Costo: `$10-$20` oferta
- Runbook y simulacion de incidentes
  - Oficial: https://sre.google/sre-book/table-of-contents/
  - Udemy: https://www.udemy.com/course/site-reliability-engineering/
  - Costo: `$12-$25` oferta

---

## MES 5 - PERFORMANCE + SEGURIDAD AVANZADA

- OAuth2, JWT, seguridad entre microservicios
  - Oficial: https://oauth.net/2/
  - Oficial: https://datatracker.ietf.org/doc/html/rfc7519
  - Oficial: https://docs.spring.io/spring-security/reference/
  - Udemy: https://www.udemy.com/course/spring-security-6-zero-to-master/
  - Costo: `$10-$20` oferta
- BCrypt, CORS, CSRF, headers (HSTS, CSP), replay attacks
  - Oficial: https://cheatsheetseries.owasp.org/
  - Oficial: https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers
  - Udemy: https://www.udemy.com/course/spring-security-6-zero-to-master/
  - Costo: `$10-$20` oferta
- OWASP Top 10 y OWASP API Top 10
  - Oficial: https://owasp.org/www-project-top-ten/
  - Oficial: https://owasp.org/www-project-api-security/
  - Udemy: https://www.udemy.com/course/api-and-web-service-introduction/
  - Costo: `$10-$20` oferta
- Rate limiting avanzado
  - Oficial: https://konghq.com/blog/engineering/how-to-design-a-scalable-rate-limiting-algorithm
  - Udemy: https://www.udemy.com/course/software-architecture-design-of-modern-large-scale-systems/
  - Costo: `$12-$25` oferta
- Performance Java: profiling, heap dump, thread dump, deadlock, GC, JFR/JMC
  - Oficial: https://docs.oracle.com/en/java/javase/17/
  - Oficial: https://docs.oracle.com/javacomponents/jmc-5-5/jfr-runtime-guide/about.htm
  - Udemy: https://www.udemy.com/course/java-performance-tuning/
  - Costo: `$10-$20` oferta
- k6/JMeter, throughput vs latency, p95 vs p99
  - Oficial: https://grafana.com/docs/k6/latest/
  - Oficial: https://jmeter.apache.org/usermanual/index.html
  - Udemy: https://www.udemy.com/course/performance-testing-jmeter/
  - Costo: `$10-$20` oferta
- Blue/Green, Canary, rollback, feature flags
  - Oficial: https://martinfowler.com/bliki/CanaryRelease.html
  - Oficial: https://launchdarkly.com/docs/home/releases/
  - Udemy: https://www.udemy.com/course/devops-projects/
  - Costo: `$10-$20` oferta

---

## MES 6 - AWS ARCHITECT I

- VPC, CIDR, subnetting, route tables, SG vs NACL, NAT
  - Oficial: https://docs.aws.amazon.com/vpc/
  - Udemy: https://www.udemy.com/course/aws-certified-solutions-architect-associate-saa-c03/
  - Costo: `$10-$20` oferta
- ALB vs NLB, target groups, health checks
  - Oficial: https://docs.aws.amazon.com/elasticloadbalancing/
  - Udemy: https://www.udemy.com/course/aws-certified-solutions-architect-associate-saa-c03/
  - Costo: `$10-$20` oferta
- Auto Scaling policies, cooldown, warmup
  - Oficial: https://docs.aws.amazon.com/autoscaling/
  - Udemy: https://www.udemy.com/course/aws-certified-solutions-architect-associate-saa-c03/
  - Costo: `$10-$20` oferta
- Modelado: QPS, concurrencia, conexiones DB, IOPS, throughput/latency
  - Oficial: https://docs.aws.amazon.com/wellarchitected/latest/framework/welcome.html
  - Udemy: https://www.udemy.com/course/grokking-the-system-design-interview/
  - Costo: `$12-$25` oferta
- Failure modeling (AZ down, targets unhealthy, NAT/DNS, DB lenta)
  - Oficial: https://docs.aws.amazon.com/whitepapers/latest/availability-and-beyond-improving-resilience/
  - Udemy: https://www.udemy.com/course/aws-certified-solutions-architect-associate-saa-c03/
  - Costo: `$10-$20` oferta
- Cost modeling (ALB, EC2/ECS, RDS, transferencias)
  - Oficial: https://docs.aws.amazon.com/cost-management/
  - Oficial: https://calculator.aws/
  - Udemy: https://www.udemy.com/course/aws-certified-solutions-architect-associate-saa-c03/
  - Costo: `$10-$20` oferta

---

## MES 7 - AWS ARCHITECT II + SYSTEM DESIGN

- Multi-region, DR strategies, RTO/RPO, Well-Architected, cost optimization
  - Oficial: https://docs.aws.amazon.com/wellarchitected/latest/reliability-pillar/welcome.html
  - Oficial: https://docs.aws.amazon.com/whitepapers/latest/disaster-recovery-workloads-on-aws/disaster-recovery-workloads-on-aws.html
  - Udemy: https://www.udemy.com/course/aws-certified-solutions-architect-associate-saa-c03/
  - Costo: `$10-$20` oferta
- Estimaciones con numeros (QPS, storage, crecimiento, p95, bottlenecks)
  - Oficial: https://sre.google/sre-book/service-level-objectives/
  - Udemy: https://www.udemy.com/course/grokking-the-system-design-interview/
  - Costo: `$12-$25` oferta
- Caching distribuido, stampede, rate limiting, sharding, consistencia
  - Oficial: https://redis.io/docs/
  - Oficial: https://martinfowler.com/articles/patterns-of-distributed-systems/
  - Udemy: https://www.udemy.com/course/software-architecture-design-of-modern-large-scale-systems/
  - Costo: `$12-$25` oferta
- Mensajeria y DLQ para resiliencia
  - Oficial: https://docs.aws.amazon.com/AWSSimpleQueueService/latest/SQSDeveloperGuide/sqs-dead-letter-queues.html
  - Udemy: https://www.udemy.com/course/aws-certified-developer-associate-dva-c02/
  - Costo: `$10-$20` oferta
- Writing drills, checklist de diseno, postmortem, defensa oral
  - Oficial: https://aws.amazon.com/architecture/well-architected/
  - Oficial: https://sre.google/workbook/postmortem-culture/
  - Udemy: https://www.udemy.com/course/communication-skills-for-engineers/
  - Costo: `$10-$20` oferta

---

## RESUMEN DE COSTO RECOMENDADO (SI COMPRAS SOLO LO NECESARIO)

- Ruta minima (1-2 cursos por mes): `$80-$180` total en oferta.
- Ruta completa (muchos cursos): `$180-$400` total en oferta.
- Ruta optimizada troncal (recomendada): `$40-$80` total en oferta.

Recomendacion practica:
1. Prioriza documentacion oficial para cada tema.
2. Compra primero solo los 4 cursos troncales.
3. Agrega cursos opcionales solo si detectas brecha real despues de practicar.
4. Espera ofertas para mantener cada compra en `$10-$20`.
