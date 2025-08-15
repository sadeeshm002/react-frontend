#Spring boot

- Spring Boot is a Java-based framework that makes it much easier and faster to build 
- Spring applications — especially web apps, REST APIs, and microservices — without all the heavy setup and boilerplate of traditional Spring.

| Feature                    | What it means                                                                                                                                   |
| -------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| **Auto-configuration**     | Spring Boot guesses and sets up most configurations for you (e.g., if it sees MySQL in dependencies, it configures a DataSource automatically). |
| **Embedded server**        | No need to deploy to Tomcat manually — Spring Boot includes **Tomcat**, **Jetty**, or **Undertow** in the app itself.                           |
| **Starter dependencies**   | Use `spring-boot-starter-*` dependencies to easily add features (like web, JPA, security).                                                      |
| **Production-ready tools** | Built-in health checks, metrics, and monitoring (`spring-boot-actuator`).                                                                       |
| **No XML required**        | Configuration is done in Java classes or `application.properties` / `application.yml`.                                                          |
