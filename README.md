<div align="center">

# Moin, I'm Alexis 👋

### Backend Engineer · Secure-by-design systems · TypeScript & Rust

📍 Cologne &nbsp;·&nbsp; 🟢 **Open to Backend / AppSec roles, Cologne / remote (DE/EU)**

</div>

I build backends with security designed in from the first commit (typed IDs, scoped auth, rate limiting, hardened containers, supply-chain checks), and I prove it with tests: my Rust rewrite of a Spring Boot service passes the same black-box suite as the original. I'm looking for a backend or application-security role where that mindset matters.

**Looking for:** Backend or Application Security Engineer · Cologne or remote (DE/EU)

## 🚀 Featured Projects

- **[Minerva](https://github.com/AlexisRoe/minerva)**: turns reported phishing emails into reviewable analysis cases (TypeScript, NestJS, React, Python workers). Early stage: the TypeScript toolchain, CI and shared job contract are in place, the analysis logic is still being built. Handles untrusted email, so it is where my AppSec work goes.
- **[Ledgerly-Rust](https://github.com/AlexisRoe/Ledgerly-Rust)** ([live demo](https://ledgerly-rust.a-roehrling.workers.dev/)): a Rust backend (axum, sqlx) built as a drop-in replacement for [Ledgerly-Java](https://github.com/AlexisRoe/Ledgerly-Java), as a hands-on way to learn Rust. Both pass the same parity suite, and the 128-lesson *Rust for TypeScript developers* course I wrote along the way is deployed with it.
- **[e-ink-ui-lib](https://github.com/AlexisRoe/e-ink-ui-lib)** ([Storybook](https://e-ink-ui-lib.a-roehrling.workers.dev/)): React component library for e-ink tablets, published on npm and used in a [habit tracker](https://github.com/AlexisRoe/habit-tracker-for-e-ink) and a [project-management PWA](https://github.com/AlexisRoe/project-management-for-e-ink).

## 🔐 Security in practice

- **Secrets:** gitleaks pre-commit hooks and push protection (Ledgerly-Rust)
- **Supply chain:** `cargo-deny`, Renovate and Dependabot for automated dependency updates
- **Hardened runtime:** minimal container images, Caddy for TLS, rate limiting and security headers ([simple-url-shortener](https://github.com/AlexisRoe/simple-url-shortener))
- **Disclosure:** a `SECURITY.md` with private reporting on my main projects

## 🧠 How I work

Model the domain in types · threat-model before building · prove behaviour with black-box tests · automate supply-chain checks in CI.

## 🛠️ Stack

**Languages:** TypeScript, Rust, Java, Python, SQL

**Backend & frontend:** axum, NestJS, Spring Boot, FastAPI, React

**Data & infra:** PostgreSQL, Valkey/Redis, S3, Docker, Caddy, GitHub Actions, Cloudflare Workers

<br>

[LinkedIn](https://www.linkedin.com/in/alexisroehrling/) · [Email](mailto:A.Roehrling+githubprofile@gmail.com)
