# 🔌 Welcome to JPersist Organization

**JPersist** is a community-driven suite of modern, high-performance, and Gradle Configuration Cache-compliant development tools designed to automate enterprise **Jakarta Persistence API (JPA)** build environments.

Our mission is to eliminate JPA boilerplate configurations (`persistence.xml`), enforce compile-time query safety, and provide bulletproof build automation tools for enterprise Java/Jakarta applications.

---

### 📊 Repository Ecosystem Status

| Project | Release Version | Scope | Core Capabilities |
| :--- | :--- | :--- | :--- |
| [**persistence**](https://github.com/jpersist/persistence) | ![Gradle Plugin Portal](https://img.shields.io/gradle-plugin-portal/v/io.github.jpersist.jpa) | Mono-Repo (Plugins & Libraries) | Descriptor Generation, Bytecode Enhancement, Schema Validation, Query Linting, GraalVM AOT Metadata. |

---

### ⚡ Key Architectural Principles

* **🛠️ Zero-Boilerplate:** ASM-powered bytecode scanning handles entity tracking automatically without manual XML edits.
* **🛡️ Compile-Time Safety:** Catch JPQL/HQL query typos and database schema mismatches *before* your code is deployed.
* **🚀 Native Isolation:** Non-cached bytecode manipulation tasks run completely isolated from the main Gradle daemon classpath.
* **🔒 Corporate Governance:** Full compliance with strict SemVer, Gradle Configuration Cache, and automated CI/CD release pipelines.

---

### 🤝 Join the Community & Contribute

We love open-source collaboration! Whether you want to report a bug, request a feature, or add a new persistence provider module, you are welcome here.

* 📘 **Read our Governance Docs:** [Code of Conduct](https://github.com/jpersist/persistence/blob/main/.github/CODE_OF_CONDUCT.md) | [Contributing Guide](https://github.com/jpersist/persistence/blob/main/.github/CONTRIBUTING.md)
* 🛡️ **Security Inquiries:** Please review our [Security Policy](https://github.com/jpersist/persistence/blob/main/.github/SECURITY.md) to report vulnerabilities privately.
* 💖 **Support Us:** Help sustain the project by becoming a [GitHub Sponsor](https://github.com/sponsors/jpersist).

---
_Maintained with 💚 by the JPersist Core Team._
