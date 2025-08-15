**Microservices:**

Microservices are an architectural approach to developing software application as a collection of small, independent services that communicate with each other over a network.

Advatanges:
- Loosly coupled
- Easily deployable
- different technologies can be used in each service
- Microservices can be updated independentlyreducing risks during chnages and enhancing system.

| **Aspect**               | **Monolithic Architecture**                                                | **Microservices Architecture**                                                              |
| ------------------------ | -------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------- |
| **Definition**           | A single, unified codebase where all features are part of one application. | An application split into many small, independent services that communicate over a network. |
| **Deployment**           | Deployed as **one unit** — changes require redeploying the whole app.      | Each service can be deployed **independently** without affecting others.                    |
| **Scalability**          | Scales **vertically** (add more CPU/RAM to the same server).               | Scales **horizontally** (scale only the services that need it).                             |
| **Technology Stack**     | Usually one tech stack for the whole app.                                  | Each service can use a **different** tech stack, database, or language.                     |
| **Team Structure**       | One large team working on the entire codebase.                             | Multiple small teams, each owning a service.                                                |
| **Codebase Size**        | Single, large codebase — can become hard to manage as it grows.            | Smaller codebases — easier to maintain but more services to manage.                         |
| **Communication**        | Internal function/method calls.                                            | Services talk via APIs (HTTP/REST, gRPC, messaging).                                        |
| **Fault Isolation**      | A failure in one module can crash the whole app.                           | A failure in one service usually does not crash the entire system.                          |
| **Speed of Development** | Fast in the early stages but slows as app grows.                           | Requires more initial setup but allows faster independent development later.                |
| **Testing**              | Easier to set up end-to-end tests initially.                               | More complex testing (integration between services needed).                                 |
| **DevOps Complexity**    | Simple to deploy and monitor.                                              | Requires advanced DevOps for deployment, monitoring, service discovery, etc.                |
| **Examples**             | Early versions of Instagram, Twitter, LinkedIn.                            | Netflix, Amazon, Uber.                                                                      |
