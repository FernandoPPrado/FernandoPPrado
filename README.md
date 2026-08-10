# Fernando Prado

**Desenvolvedor Java Backend** · Santa Catarina, Brasil

Foco em APIs REST, mensageria e arquitetura orientada a eventos.
Estudante de Engenharia de Controle e Automação no IFC — São Bento do Sul.

---

## Stack principal

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=spring-boot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat&logo=spring&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat&logo=rabbitmq&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat&logo=JSON%20web%20tokens&logoColor=white)
![JUnit5](https://img.shields.io/badge/JUnit5-25A162?style=flat&logo=junit5&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=flat&logo=apache-maven&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

---

## Projetos

### 🛡️ [Nexus Identity Provider](https://github.com/FernandoPPrado/nexus-identity-provider) ![Produção](https://img.shields.io/badge/Status-Em_Produ%C3%A7%C3%A3o-25A162?style=flat)
**Microsserviço em produção** desenvolvido para gerenciar autenticação e segurança descentralizada. Implementa criptografia assimétrica (JWT RSA) com endpoint JWK, arquitetura multi-tenant, controle de abusos via Rate Limiting (Bucket4j/Caffeine) e processamento assíncrono de fluxos por e-mail.

`Java 21` `Spring Boot 3` `Spring Security` `JWT (RSA)` `RabbitMQ` `PostgreSQL` `Docker` `Oracle Cloud`

---

### 🔧 [LHMJavaMonitor](https://github.com/FernandoPPrado/LHMJavaMonitor)
Agente standalone que coleta métricas de CPU, GPU e memória em tempo real e publica em fila RabbitMQ (CloudAMQP) a cada segundo. Arquitetura orientada a eventos com Java Flow API, integração com LibreHardwareMonitor via Feign Client e interface system tray no Windows.

`Java 23` `RabbitMQ` `Java Flow API` `OpenFeign` `Jackson` `Virtual Threads`

---

### 🍕 [PizzariaAPI](https://github.com/FernandoPPrado/PizzariaAPI)
Backend completo para sistema de pedidos com pagamentos reais via Mercado Pago. Inclui webhooks idempotentes, controle de estoque automático pós-pagamento, upload de imagens, autenticação JWT e logs estruturados.

`Java 21` `Spring Boot` `Spring Security` `JWT` `MercadoPago SDK` `JPA/Hibernate` `MySQL`

---

### 🔐 [SecurityModule](https://github.com/FernandoPPrado/SecurityModule)
Módulo de segurança reutilizável pensado para ser plugado em qualquer API REST sem reescrita. Suporta autenticação local (email/senha) e social (Google OAuth2 + OIDC), geração e validação de JWT com controle de roles e arquitetura em camadas documentada no README.

`Java 17` `Spring Boot 3` `Spring Security 6` `OAuth2` `OIDC` `JWT`

---

### 🛒 [EcommerceProject](https://github.com/FernandoPPrado/EcommerceProject)
API REST de e-commerce com autenticação JWT, integração com Mercado Pago, controle de produtos e compras por roles, timer de tentativas de login com backoff exponencial e deploy automático no Railway via Docker.

`Java 17` `Spring Boot` `Spring Security` `JWT` `MercadoPago SDK` `Docker` `Railway`

---

### 📰 [API---sistema-de-artigos](https://github.com/FernandoPPrado/API---sistema-de-artigos)
Aplicação que consome a NewsAPI, armazena uma notícia por dia no banco de dados e exibe os artigos em uma interface web com calendário — o usuário seleciona a data e vê a notícia daquele dia.

`Java 17` `Spring Boot` `Thymeleaf` `JPA` `MySQL` `NewsAPI`

---

## Atualmente estudando

- Deploy em AWS e GCP (ECS, RDS, Cloud Run, GKE)
- Testes automatizados com JUnit e Mockito
- CI/CD com GitHub Actions
- Containerização avançada com Docker Compose

---

## Contato

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/fernando-prado21)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/FernandoPPrado)
