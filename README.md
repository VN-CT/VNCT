# 🌐 VNCT Base: Technical Knowledge & Standards

**VNCT (Virtual Network & Compute Tech)** is an independent engineering ecosystem focused on low-level system design, security, and developer productivity tools. This document defines our standards, architecture principles, and contribution guidelines.

---

## 🛠 1. Core Engineering Philosophy
*   **Performance & Safety:** We prioritize memory safety and efficient resource utilization.
*   **Security by Design:** All inputs are treated as untrusted. We implement strict validation at all system boundaries.
*   **Versatility:** We support a wide range of interfaces—from CLI utilities to GUI applications and web services. Engineering quality is our top priority.
*   **No "Magic":** We avoid bloated frameworks that obfuscate logic. Code must be explicit, transparent, and readable.

---

## ⚙️ 2. VNCODES: Style & Architecture
*   **Structure:** Standard project layout:
    *   `/src`: Core logic.
    *   `/tests`: Unit and integration tests.
    *   `/docs`: Technical documentation.
*   **Naming:** Use `snake_case` for Python and `camelCase` for Go/Rust functions. Names must be descriptive; avoid ambiguous naming like `func1`.
*   **Error Handling:** Fail fast and fail clean. Every error must be logged with sufficient context.
*   **Dependency Policy:** Minimalism is key. External dependencies are only added when they provide significant, well-maintained value.

---

## ⚖️ 3. Licensing
All public projects under the VNCT brand adhere to these open-source principles:
*   **Primary License:** **[MIT License](https://opensource.org/licenses/MIT)** — we believe in development freedom.
*   **Exceptions:** For critical security modules, **GPLv3** may be used to ensure the openness of future improvements.
*   *Note: Always verify the `LICENSE` file within the specific repository.*

---

## 🚀 4. Tech Stack Preferences
We do not mandate a single language, but we favor stacks that allow for deep system integration:
*   **Languages:** Go, Rust, Python, C++, JavaScript/TypeScript.
*   **OS:** Linux-first (Fedora, Arch).
*   **Tooling:** Git (standardized commit messages), GitHub Actions (CI/CD), and modern build automation.

---

## 🛡 5. Security Protocol & Auditing
Every project undergoes a **mandatory manual audit** before moving from `private` to `public` status. We evaluate:
*   **Vulnerabilities:** Buffer overflows, injection flaws, memory safety issues, and insecure API design.
*   **Data Integrity:** Proper handling of sensitive data (no hardcoded credentials).
*   **Logic:** Architecture cleanliness and logical soundness.
*   **Authorship:** AI-assisted code is permitted only if the author fully understands and refactors the implementation.

---

## 📋 6. Contribution Workflow
1.  **Proposal:** Create an issue in `VNCT-CORE` describing your project idea.
2.  **Challenge:** You will be assigned a non-trivial technical task to verify your skills.
3.  **Incubation:** Development happens in a private repository under your control.
4.  **Audit:** The project maintainer conducts a manual code review.
5.  **Release:** Upon approval, the project is moved to the public VNCT organization.

---

> *"Building tools I wish existed."*

<br>

*VNCT © 2026. All rights reserved.*  
*This documentation is licensed under the [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).*
