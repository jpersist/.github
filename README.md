# 🔌 JPersist Organization: Zero-Boilerplate JPA Build Automation

Welcome to the official home of **JPersist**. We engineer modern, high-performance, and **Gradle Configuration Cache-compliant** development tools that completely automate the tedious boilerplate configuration of enterprise **Jakarta Persistence API (JPA)** environments.

Our suite provides zero-configuration support for Hibernate, EclipseLink, and Apache OpenJPA multi-module builds — enforcing compile-time safety and streamlining enterprise Java/Jakarta application pipelines.

---

## 🗺️ Ecosystem Repositories

| Repository | Release Version | Scope | Core Capabilities |
| :--- | :--- | :--- | :--- |
| [**persistence**](https://github.com/jpersist/persistence) | ![Gradle Plugin Portal](https://img.shields.io/gradle-plugin-portal/v/io.github.jpersist.jpa) | Main Mono-Repo | Descriptor Generation, Bytecode Enhancement, Schema Validation, Query Linting, GraalVM AOT Metadata. |
| [**.github**](https://github.com/jpersist/.github) | _Internal_ | Global Governance | Centralized community profile, global fallback documentation templates, and unified issue intake forms. |

---

## ⚡ Key Architectural Advantages

* **🛠️ Zero-Boilerplate:** ASM-powered bytecode scanning handles entity tracking automatically without manual XML metadata edits.
* **🛡️ Compile-Time Safety:** Catch JPQL/HQL query typos and database schema mismatches *before* your code is ever deployed.
* **🚀 Native Performance:** Heavy bytecode manipulation tasks run completely isolated from the main Gradle daemon classpath using the Worker API.
* **🔒 Enterprise Governance:** Full compliance with strict SemVer, Gradle Configuration Cache mechanics, and automated CI/CD release pipelines.

---

## 📚 Centralized Documentation

* 📘 **User Guide:** [jpersist.github.io/persistence/plugins/guide/latest](https://jpersist.github.io/persistence/plugins/guide/latest/)
* 📖 **Plugins API Reference (Groovydoc):** [jpersist.github.io/persistence/plugins/api/latest](https://jpersist.github.io/persistence/plugins/api/latest/)
* 📖 **Libraries API Reference (Javadoc):** [jpersist.github.io/persistence/libraries/api/latest](https://jpersist.github.io/persistence/libraries/api/latest/)

---

## 🤝 Community & Governance

This repository houses the global configuration profiles and fallbacks for the entire `jpersist` organization. We are committed to a healthy, safe, and welcoming community for all contributors.

* 📋 **Contribution Pipeline:** Please read our global [Contributing Guide](CONTRIBUTING.md) before opening Pull Requests.
* 📜 **Behavior Standards:** All community interactions are governed by our [Code of Conduct](CODE_OF_CONDUCT.md).
* 🛡️ **Security Advisories:** If you discover a vulnerability, please review our [Security Policy](SECURITY.md) to report it privately.
* 💖 **Back the Project:** If JPersist is saving your engineering team debugging hours, consider becoming a [GitHub Sponsor](https://github.com/sponsors/jpersist).

---
_Maintained with 💚 by the JPersist Core Team._
