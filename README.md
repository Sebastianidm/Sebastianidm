# ¡Hola! Soy Sebastián Díaz Miranda 👋

### Desarrollador Backend 

Soy un apasionado del desarrollo. Actualmente curso Ingeniería en Informática en DUOC UC (Vespertino) y dedico mi tiempo libre a profundizar en patrones de diseño, comunicación eficiente entre servicios y automatización.

Mi meta técnica es clara: diseñar y desplegar soluciones backend eficientes, desacopladas y listas para producción. Aunque tengo bases en Frontend (React), mi lugar en el ecosistema está del lado del servidor y los datos.

---

## 🚀 Proyectos Destacados

### 🎬 [Blockbuster Microservices](https://github.com/Sebastianidm/blockbuster-microservices)

Un monorepo que simula una plataforma transaccional de arriendo de películas implementada con una arquitectura de microservicios reales sobre Spring Boot.

*   **Arquitectura:** 6 microservicios independientes que se comunican mediante OpenFeign, coordinados con Spring Cloud API Gateway y Eureka Server.
*   **Persistencia Políglota:** Uso de PostgreSQL para flujos transaccionales rígidos y MongoDB para el manejo de logs/notificaciones ágiles, controlado con Flyway.
*   **Seguridad:** Mecanismos complementarios mediante JWT Bearer para clientes externos y API Keys para la confianza entre microservicios internos.
*   **Calidad:** Cobertura de pruebas unitarias y de integración del 95% verificadas con JaCoCo.
*   **Infraestructura:** Orquestación y despliegue local simplificado mediante contenedores con Docker Compose.

### 🏥 [MediTurno](https://github.com/Sebastianidm/mediturno) 

Sistema backend RESTful diseñado para mitigar la ineficiencia en la asignación de citas médicas, resolviendo problemas críticos de solapamiento de horarios, cancelaciones tardías y falta de trazabilidad mediante un sistema de roles estructurado (Paciente, Médico, Admin).

*   **Consistencia Estricta (ACID):** Uso estratégico de persistencia relacional con PostgreSQL para garantizar integridad referencial y bloqueos consistentes, evitando por completo problemas de doble reserva simultánea.
*   **Notificaciones Asíncronas (`@Async`):** Optimización del rendimiento de la API mediante la delegación del envío de correos HTML (JavaMailSender/SMTP) a un pool de hilos en segundo plano, reduciendo la latencia de respuesta al usuario.
*   **Rendimiento y Escalabilidad:** Implementación obligatoria de paginación (`Pageable`) en endpoints críticos de alta concurrencia para mitigar riesgos de desbordamiento de memoria (OOM) y optimizar el consumo de ancho de banda.
*   **Seguridad y Acceso:** Autenticación stateless implementada con Spring Security y JSON Web Tokens (JWT) para control de acceso basado en roles.
*   **Calidad y Resiliencia:** Cobertura de pruebas unitarias y de integración utilizando JUnit 5 y Mockito 5, con base de datos H2 en memoria para entornos de prueba.
*   **Infraestructura y Migración:** Control de versiones de base de datos automatizado con Flyway y contenedorización del entorno local y productivo mediante Docker y Docker Compose.

---

## 🛠️ Mi Caja de Herramientas

| Categoría | Tecnologías |
|---|---|
| **Lenguajes & Frameworks** | Java 17/21 (Spring Boot 3.x, Spring Cloud, Spring Security, Hibernate/JPA) |
| **Nube & Infraestructura** | AWS *(Certified Cloud Practitioner)*: EC2, S3, RDS, IAM — Docker, Docker Compose |
| **Bases de Datos** | PostgreSQL 16, MongoDB, SQL, H2 Database |
| **Calidad & Documentación** | OpenAPI/Swagger, Postman, Flyway, JaCoCo, Maven, JUnit 5, Mockito 5 |
| **Metodologías** | Scrum / Agile |

---

## 🤝 Conectemos

Si estás buscando un desarrollador backend **Junior o Trainee** con bases sólidas y con un fuerte interés en la cultura DevOps, hablemos:

*   💼 **LinkedIn:** [linkedin.com/in/sebastián-díaz-miranda](https://linkedin.com/in/sebastián-díaz-miranda)
*   📧 **Correo:** sebastiandiazmiranda@gmail.com
*   📍 **Ubicación:** Villa Alemana, Valparaíso, Chile 🇨🇱
