# 👋 Hi, I’m Barış Saylı

**Software Architect · Platform & Backend Engineering**
**Java · Spring Boot · Distributed Systems · API Contracts**

I design and evolve backend systems where **architecture is explicit, contracts are stable, and change is safe** — not just at day one, but under real production pressure months and years later.

My work focuses on making systems:

* **predictable** (deterministic behavior across environments)
* **understandable** (clear boundaries and contracts)
* **evolvable** (safe change without hidden coupling)

I operate across both:

* **Greenfield systems** — designing service boundaries, contracts, and platform foundations
* **Brownfield systems** — refactoring live systems, reducing risk, and restoring architectural clarity

---

## 📂 Selected Work

### 🧠 OpenAPI Generics

**Contract-first API system with generics-aware client generation**

A platform-oriented implementation showing how **API contracts remain the single source of truth**, while OpenAPI acts as a **deterministic projection layer** — not a model generator.

Core ideas:

* Preserve `ServiceResponse<T>` semantics across server and client
* Eliminate DTO duplication and schema drift
* Treat OpenAPI as a projection, not authority
* Ensure safe regeneration of clients

👉 [https://github.com/blueprint-platform/openapi-generics](https://github.com/blueprint-platform/openapi-generics)

---

### ⚙️ Codegen Blueprint

**Executable architecture with build-time enforcement**

A generator that turns architectural intent into **verifiable, build-time rules** using ArchUnit.

Instead of relying on conventions or reviews:

* architecture is **generated**
* violations are **detected at build time**
* feedback is **deterministic and immediate**

Focus:

* Architecture as a build-enforced contract
* Hexagonal / layered structures by construction
* Drift detection during development, not after

👉 [https://github.com/blueprint-platform/codegen-blueprint](https://github.com/blueprint-platform/codegen-blueprint)

---

### 🔐 Licensing Project

**Security-focused licensing platform (JWT + cryptography)**

An end-to-end system for issuing and validating licenses using:

* EdDSA-signed JWTs
* Detached signature verification
* Redis-backed validation
* SDK and CLI separation

Focus:

* Clear trust boundaries
* Deterministic validation
* Production-grade security design

👉 [https://github.com/bsayli/licensing](https://github.com/bsayli/licensing)

---

## 🧭 Architectural Focus

My work consistently centers on a few non-negotiable principles:

* **Contract as authority (SSOT)**
  Runtime models define truth — tools must not redefine them

* **Determinism over convenience**
  Same input → same output, across build and runtime

* **Explicit boundaries**
  Architecture must be visible in structure, not implied in conventions

* **Build-time guarantees**
  Violations should fail early — not leak into production

* **Separation of concerns**
  Contract / projection / generation / consumption are distinct layers

---

## 📌 What You’ll Find Here

These repositories are not tutorials.

They are **reference implementations** that demonstrate:

* real architectural trade-offs
* constrained design decisions
* production-oriented thinking

The goal is not to show *how to start fast*, but how to:

> **build systems that remain correct as they evolve**

---

## 🔗 Connect

For background, writing, and contact:
* LinkedIn → [https://www.linkedin.com/in/bsayli](https://www.linkedin.com/in/bsayli)
* Medium → [https://medium.com/@baris.sayli](https://medium.com/@baris.sayli)

---

> Architecture should not rely on discipline.
> It should be **observable, enforceable, and evolvable**.
