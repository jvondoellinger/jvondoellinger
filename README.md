<h1 align="center">Jorge Von Doellinger</h1>
<p align="center">
  Backend &amp; Arquitetura de Software — Java · Spring · .NET · AWS<br>
  <em>Sistemas distribuídos, CQRS, testes de verdade e entrega contínua Git-first.</em>
</p>

<p align="center">
  <img alt="Java" src="https://img.shields.io/badge/Java-17-ED8B00?logo=openjdk&logoColor=white">
  <img alt="Spring Boot" src="https://img.shields.io/badge/Spring%20Boot-4-6DB33F?logo=springboot&logoColor=white">
  <img alt=".NET" src="https://img.shields.io/badge/.NET-512BD4?logo=dotnet&logoColor=white">
  <img alt="Angular" src="https://img.shields.io/badge/Angular-21-DD0031?logo=angular&logoColor=white">
  <img alt="AWS" src="https://img.shields.io/badge/AWS-Cloud%20Practitioner-FF9900?logo=amazonaws&logoColor=white">
  <img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white">
</p>

---

## Sobre

Desenvolvedor backend com foco em **arquitetura, sistemas distribuídos e qualidade de software**.

Trabalho em ambientes de **documentação viva e deploy contínuo Git-first**: commit no repositório-fonte → geração automatizada → quality gates → publicação, com rollback previsível. Nos projetos pessoais aplico o mesmo rigor: domínio isolado de framework, testes de integração com banco real e decisões arquiteturais registradas.

- Estudante de **Engenharia de Software**
- **AWS Certified Cloud Practitioner**; em preparação para **Solutions Architect Associate**
- Linguagens de trabalho: **Java**, **C#/.NET**, **TypeScript/Node.js**

---

## Como eu construo software

- **Vertical Slice / feature-oriented** — cada caso de uso reúne endpoint, command/query, handler e serviço
- **Ports & Adapters** — domínio sem dependência de framework, persistência como adaptador
- **CQRS** — separação explícita entre escrita (`Command`) e leitura (`Query` + cache)
- **State Machine no agregado** — transições inválidas rejeitadas no domínio
- **Railway-Oriented Programming** — resultado monádico (`ResultB<T>`) em vez de exceção como fluxo de negócio
- **Testes em camadas** — unitários (JUnit 5 + Mockito) e integração com **Testcontainers** (banco real)
- **Observabilidade desde o início** — Actuator + Micrometer → Prometheus → Grafana

---

## Stack

| Domínio | Tecnologias |
| --- | --- |
| Backend | Java 17 · Spring Boot 4 · WebFlux · Spring Data JPA · Spring Security · C#/.NET · Node.js |
| Frontend | Angular 21 (SSR) · TypeScript · .NET MAUI |
| Dados | MySQL · PostgreSQL · MongoDB Atlas · Redis · DynamoDB |
| Cloud & DevOps | AWS (S3, SQS, DynamoDB, CloudWatch, LocalStack) · GCP · Cloudflare Pages/Workers · Docker Compose · GitHub Actions |
| Integrações | Spring Cloud Gateway · Stripe · Mercado Pago · JWT/JWE · APIs REST |
| Qualidade | JUnit 5 · Mockito · Testcontainers · Prometheus · Grafana |

---

## Projetos em destaque

### Rising HelpDesk — [`Rising-HelpDesk`](https://github.com/jvondoellinger/Rising-HelpDesk)

Sistema de chamados de ponta a ponta: API Spring Boot 4, Gateway, MySQL, Redis, observabilidade e SPA Angular com SSR.

- **CQRS** com handlers tipados por feature
- **State Machine** de tickets com transições validadas no domínio
- **Cache-Aside** em Redis com serializer próprio e TTL de 30 min
- **Testcontainers** subindo MySQL real nos testes de integração
- Métricas em `/actuator/prometheus`, dashboards no Grafana e stack completa via `docker compose`

### Marketplace de itens virtuais — [`Marketplace`](https://github.com/jvondoellinger/Marketplace)

API reativa com **Spring WebFlux**, integrações de pagamento **Stripe** e **Mercado Pago**, Redis, MongoDB Atlas e AWS S3, com pipeline CI/CD no GitHub Actions e testes em sandbox.

### OmniSphere — [`OmniSphere---no-branch`](https://github.com/jvondoellinger/OmniSphere---no-branch)

Ecossistema de microsserviços de vendas em .NET, com foco em escalabilidade e limites de serviço bem definidos.

### Product — [`Product`](https://github.com/jvondoellinger/Product)

Laboratório de AWS com **LocalStack**: mensageria com **SQS** e persistência em **DynamoDB**, praticando desacoplamento entre serviços.

### Design Patterns — [`DesingPattern`](https://github.com/jvondoellinger/DesingPattern)

Implementações comentadas de padrões GoF em Java, base das decisões usadas nos projetos maiores.

---

## Estudando agora

- AWS Solutions Architect Associate
- Arquitetura orientada a eventos e resiliência (retry, idempotência, circuit breaker)
- Observabilidade ponta a ponta: logs estruturados, métricas e tracing
- Pipelines de build reproduzível e quality gates bloqueantes

---

## Estatísticas

<p align="center">
  <img height="165" alt="GitHub stats" src="https://github-readme-stats.vercel.app/api?username=jvondoellinger&show_icons=true&theme=github_dark&hide_border=true&count_private=true">
  <img height="165" alt="Top languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=jvondoellinger&layout=compact&theme=github_dark&hide_border=true">
</p>

---

## Contato

- LinkedIn: https://www.linkedin.com/in/jorge-von-doellinger/
- E-mail: jvondoellinger.career@outlook.com.br
