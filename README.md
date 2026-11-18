### Moin, I'm Alexis 👋

I'm a **Backend Engineer from Cologne moving into application security**. I build backends with security designed in from the start: typed IDs, scoped auth, rate limiting, hardened containers and supply-chain checks. Right now I'm building **Minerva**, a phishing and email analysis platform, and learning **Rust** by rewriting a production-style backend.

- 🔭 **Currently working on:** [Minerva](https://github.com/AlexisRoe/minerva), a tool for reporting and analysing suspicious emails to improve an organisation's security posture
- 🌱 **Currently learning:** Rust (axum, sqlx, tokio), email security (headers, SPF/DKIM/DMARC, phishing indicators) and secure-by-design architecture
- 📫 **Reach me:** [LinkedIn](https://www.linkedin.com/in/alexisroehrling/) | [Email](mailto:A.Roehrling+githubprofile@gmail.com)

---

### 🚀 Featured Projects

1. **[Minerva](https://github.com/AlexisRoe/minerva)**: report suspicious emails and turn them into structured, reviewable analysis cases.
   - **Tech:** TypeScript, NestJS, React, Python workers, PostgreSQL, Valkey, S3 (Garage), Caddy, Docker
   - **Highlight:** A pnpm monorepo with a shared typed job contract between services, so a payload change breaks the build instead of production. An isolated image proxy for rendering email content safely is planned. Parsing and analysis experiments live in a separate [Python lab](https://github.com/AlexisRoe/minerva-experimental-email-parser-and-analyser).

2. **[Ledgerly-Rust](https://github.com/AlexisRoe/Ledgerly-Rust)**: an expense-approval REST backend, rewritten from [Java/Spring Boot](https://github.com/AlexisRoe/Ledgerly-Java) as a drop-in Rust replacement. ([Live demo](https://ledgerly-rust.a-roehrling.workers.dev/))
   - **Tech:** Rust, axum, sqlx, tokio, PostgreSQL, Docker
   - **Highlight:** Security by design (typed IDs, secrets that can't be logged, team-scoped queries, an SSRF architecture test, malware scanning of uploads, no `unwrap`/`panic!` outside tests). Both versions pass the same black-box parity test suite. Comes with a 128-lesson *Rust for TypeScript developers* course.

3. **[e-ink-ui-lib](https://github.com/AlexisRoe/e-ink-ui-lib)**: a React component library for e-ink tablets, published on [npm](https://www.npmjs.com/package/e-ink-ui-lib). ([Storybook](https://e-ink-ui-lib.a-roehrling.workers.dev/?path=/docs/about--docs))
   - **Tech:** TypeScript, React, CSS, Storybook, GitHub Actions
   - **Highlight:** 75+ components designed for slow-refresh greyscale screens (no hover, no animations). It powers my local-first PWAs: [PaperFlow](https://github.com/AlexisRoe/project-management-for-e-ink), [HabitTracker](https://github.com/AlexisRoe/habit-tracker-for-e-ink) and the [Spacecraft Mock Interface](https://github.com/AlexisRoe/spacecraft-mock-interface).

---

### 🛠️ Tech Stack

- **Core:** TypeScript, JavaScript, Python, SQL
- **Frameworks & Libraries:** Node.js, NestJS, React, Vite, FastAPI, Storybook
- **Data & Infra:** PostgreSQL, Redis/Valkey, S3-compatible storage, Docker, Caddy, Cloudflare Workers, GitHub Actions, Linux
- **Currently learning:** Rust (axum, sqlx), Java & Spring Boot, application security and email threat analysis
