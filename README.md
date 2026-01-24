# 👋 Hi, I’m Barış Saylı

**Hands-on Software Architect**  
**Java 21 · Spring Boot 3.x · Backend & Platform Engineering**

I design and evolve **production backend systems** where architecture, API contracts, and operational reliability must remain stable **well beyond day one**.

My work spans both **greenfield foundations** (designing microservice ecosystems, defining bounded contexts, building shared platform libraries) and **brownfield evolution** (monolith-to-microservices migration, refactoring under load, and resolving production bottlenecks without disrupting delivery).

The common thread is simple:  
**systems that can change safely while staying understandable months and years later.**

---

## 📂 Selected Repositories

### 🧠 Spring Boot OpenAPI Generics Clients

**Contract-driven, generics-aware OpenAPI client generation**

A reference implementation showing how **server and client can share a single canonical response contract** (`ServiceResponse<T>`, `ServiceResponse<Page<T>>`) without duplicated envelopes or erased generics.

This repository focuses on:
- End-to-end type safety across API boundaries
- Deterministic OpenAPI 3.1 schemas
- RFC 9457-compliant error handling
- Minimal, generator-safe Mustache customizations

👉 https://github.com/bsayli/spring-boot-openapi-generics-clients

---

### ⚙️ Codegen Blueprint

**Architecture-first project generation with build-time guardrails**

A CLI-driven generator that turns **architectural intent into executable build-time rules** using generated ArchUnit tests evaluated during `mvn verify`.

The emphasis is not scaffolding speed, but:
- Explicit, verifiable architectural boundaries
- Standard or Hexagonal layouts by construction
- Drift detection while context is still fresh
- Deterministic, CI-visible feedback

👉 https://github.com/blueprint-platform/codegen-blueprint

---

### 🔐 Licensing Project

**End-to-end licensing framework for Spring Boot applications**

A complete license issue / validate lifecycle built on **Spring Boot, Keycloak, Redis, and EdDSA-signed JWTs**, including SDK and CLI consumption patterns with a reproducible Docker setup.

The project demonstrates:
- Secure license issuance and validation
- Detached signatures and token-based verification
- Clear separation between service, SDK, and CLI concerns

👉 https://github.com/bsayli/licensing

---

## 📌 Focus Signals

- **Type-safe API contracts** shared across server and client
- **Architecture that stays visible** as systems evolve
- **Incremental change under production constraints**
- **Enterprise concerns**: security, identity, and platform consistency

These repositories are built as **reference implementations** — not tutorials or demos.
Design decisions, trade-offs, and constraints are documented where they matter most: **in code and in builds**.

For professional background and contact details, see the links in my GitHub profile sidebar.
