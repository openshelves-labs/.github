<div align="center">

<img src="assets/banner.svg" alt="OpenShelves: your university library, as easy to search as the web. Early morning light slants through tall bookshelves, with dust drifting in the beams. The light finds every shelf." width="100%">

<br><br>

*The early light through window glass*<br>
*lies pale along the patient rows;*<br>
*the dust drifts slow as hours pass,*<br>
*and every answer, waiting, glows.*

<br>

[![Explore the project](https://img.shields.io/badge/Explore_the_project-→-2F5D45?style=for-the-badge)](https://github.com/openshelves-labs/openshelves)
&nbsp;
[![See the prototype](https://img.shields.io/badge/See_the_prototype-→-1E3F2E?style=for-the-badge)](https://github.com/openshelves-labs/openshelves-demo-site)
&nbsp;
[![Contribute](https://img.shields.io/badge/Contribute-→-5C6460?style=for-the-badge)](https://github.com/openshelves-labs/openshelves/blob/main/CONTRIBUTING.md)

</div>

<br>

## 💡 Prologue · Why OpenShelves

Somewhere in every university, the answer to someone's question already sits on a shelf. Too often it is never found: buried under clunky filters, cryptic call numbers and pages that haven't changed in twenty years.

**OpenShelves gives every academic library a modern front door**: as easy to search as the web, as dependable as the archive behind it.

<br>

## ✨ The Shelves · What it does

<p align="center">
  <img src="assets/shelves.svg" alt="What OpenShelves does. Discover: catalog, journals and digital resources, in one search. Borrow: loans, renewals, holds and fines, without the desk. Research: reading lists, history and citations, kept together. Keep: a calm workspace for librarians to catalog." width="100%">
</p>

<br>

## 🧭 The Ledger · Where we are

> *Every great library began as a single shelf.*

| Chapter | Status | |
|---|---|---|
| **Design** | ✅ Written | API design for every feature, design system, architecture |
| **Sign-in** | 🚧 Being built | Password login and sessions in the API; campus SSO (SAML / OIDC) next |
| **Catalog** | 🚧 Being built | Data model and metadata-provider integrations; search API next |
| **Web app** | 🚧 Being built | Next.js app with the design system; screens shaped from the prototype |
| **Borrowing** | 📋 Planned | Loans, renewals, holds, fines |
| **Research tools** | 📋 Planned | Reading lists, history, notifications |

<br>

## 🏗️ The Blueprint · How it fits together

<img src="https://github.com/openshelves-labs/openshelves/blob/main/docs/assets/architecture.svg?raw=true" alt="OpenShelves architecture: patrons and librarians use the Next.js frontend, which calls the Spring Boot backend API with a bearer token. The backend stores data in PostgreSQL, looks up book metadata from external providers, and will later integrate with campus SSO, payments, email and a library proxy." width="100%">

<br>

## 🚀 The Collection · Our projects

<p align="center">
  <a href="https://github.com/openshelves-labs/openshelves"><img src="assets/project-openshelves.svg" alt="OpenShelves, the platform: backend API, web app and infrastructure, in one repository. Start here." width="47%"></a>
  &nbsp;&nbsp;&nbsp;
  <a href="https://github.com/openshelves-labs/openshelves-demo-site"><img src="assets/project-demo.svg" alt="Demo Site, the prototype: an early sketch on sample data, showing where the experience is headed." width="47%"></a>
</p>

### 📚 Reading guides

| Guide | What's inside |
|---|---|
| 📐 **[API design](https://github.com/openshelves-labs/openshelves/blob/main/docs/api-design/README.md)** | Every endpoint, grouped by feature: auth, catalog, loans and more |
| 🎨 **[Design system](https://github.com/openshelves-labs/openshelves/blob/main/docs/Design%20System.md)** | Colours, type and components behind the web app |
| 🖥️ **[Frontend architecture](https://github.com/openshelves-labs/openshelves/blob/main/docs/Frontend%20Architecture.md)** | How the Next.js app is structured and talks to the API |

<br>

## 🛠️ The Craft · Built with

<div align="center">

![Java 25](https://img.shields.io/badge/Java_25-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot 4](https://img.shields.io/badge/Spring_Boot_4-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Next.js 16](https://img.shields.io/badge/Next.js_16-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React 19](https://img.shields.io/badge/React_19-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Tailwind CSS 4](https://img.shields.io/badge/Tailwind_CSS_4-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

</div>

<br>

## 🌱 An Open Invitation

The first pages are still being written, which makes now the best time to add yours.

Whether you write code, shape interfaces, keep a library, or simply love the idea, there is a place for you on these shelves.

**→ Begin with the [Contributing Guide](https://github.com/openshelves-labs/openshelves/blob/main/CONTRIBUTING.md).**

<br>

---

<div align="center">

<sub>
<a href="https://github.com/openshelves-labs/openshelves/blob/main/CODE_OF_CONDUCT.md">Code of Conduct</a> ·
<a href="https://github.com/openshelves-labs/openshelves/blob/main/GOVERNANCE.md">Governance</a> ·
<a href="https://github.com/openshelves-labs/openshelves/blob/main/SECURITY.md">Security</a> ·
<a href="https://github.com/openshelves-labs/openshelves/blob/main/ANTI-IMPERSONATION.md">Anti-Impersonation</a> ·
<a href="https://github.com/openshelves-labs/openshelves/blob/main/LICENSE">License (BUSL 1.1)</a>
</sub>

<br><br>

**© 2026 OpenShelves Labs** · Built with care for the academic community

</div>
