# Jason Beaver

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=25&pause=1000&color=AE8EF7&width=435&lines=Full-Stack+Engineer;Mobile-first+Product+Builder;Software+Architect;Data+Analyst)](https://git.io/typing-svg)
---

I build fast, human-friendly apps and the infrastructure to support them. My work spans mobile (Flutter), web (React/SvelteKit), and backends (.NET/Firebase/Node), with a bias toward clear architecture, performance, and maintainability.

## Highlights
- Cross-platform mobile: Flutter (Riverpod, GoRouter, codegen) with production patterns
- Data & real-time: Firebase Auth/Firestore/Storage, Cloud Functions, offline caching, media processing
- Web & backend: React/SvelteKit, ASP.NET Core, Node/Express, REST APIs
- Engineering habits: typed models, generative tooling, testable design, readable repos

## Skills
**Frontend**: Flutter (Dart), React, SvelteKit, TailwindCSS  
**Backend & APIs**: ASP.NET Core, Node.js/Express, Firebase, Supabase, Spring  
**Data**: Firestore, PostgreSQL, MongoDB, SQL Server  
**Infra & Tools**: Docker, Git, Build Runner, Firebase Emulators, CI/CD basics

---

## Featured Projects

### HERD — Cross-platform social app (Flutter + Firebase)
A modern social platform with three feeds (Alt/anonymous, Herds/sub-communities, Public/real-identity), rich media posts, a time-decay “hot” ranking, and **Babble**, a real-time chat overlay with rubber-band drag and haptics.  
**Security**: 1:1 chat E2EE using X25519 (key exchange), HKDF (derivation), and ChaCha20-Poly1305 (AEAD).  
**Backend**: Cloud Functions for post triggers, notifications, ranking jobs, and user lifecycle.

Repo: https://github.com/LeaveItToBeaver/Herd  
License: Proprietary (closed beta)

**Tech**: Flutter (Dart), Riverpod 2.x, GoRouter, Freezed, JsonSerializable, Firebase Auth/Firestore/Storage, Cloud Functions

**What to look at**
- `functions/` — triggers, notifications, score recalcs, callable endpoints
- `functions/utils.js` — time-decay ranking
- `lib/features/social/chat_messaging/…` — crypto + messaging repo + widgets

---

### amlang — Algorithmic Mathematics (Rust)
An experimental mathematical programming language meant to be **writable on paper** and **executable by machine**. The repo includes notation docs and a Rust codebase for the implementation.

Repo: https://github.com/LeaveItToBeaver/algorithmic-mathematics  
License: MIT

**Tech**: Rust  
**Docs**: `NOTATION.md` / `NOTATION.pdf`

---

### Selected smaller projects
- **Wedding Website** — React-based site with clean, responsive UI  
  https://github.com/LeaveItToBeaver/wedding_website
- **Blogging Website** — SvelteKit + Supabase CMS-style blog  
  https://github.com/LeaveItToBeaver/BloggingWebsite
- **HERD (Archived)** — earlier iteration of HERD preserved for reference  
  https://github.com/LeaveItToBeaver/HERD_old

---

## Contact
- LinkedIn: https://www.linkedin.com/in/jason-beaver-dev  
- Email: jasonbeaverw99@gmail.com

---
