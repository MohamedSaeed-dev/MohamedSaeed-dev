## Mohamed Saeed bin Omar

**Backend Engineer — .NET & Node.js** · Riyadh, Saudi Arabia

I build backend systems that other people depend on. Most of my work lives in
two ecosystems: **ASP.NET Core** for line-of-business systems that need to be
correct and stay running, and **NestJS/TypeScript** for services where I want
fast iteration and a strong type system.

Lately I spend most of my thinking on three things: designing data access that
does not fall apart at scale, keeping business logic out of controllers, and
building applications on top of LLMs that behave predictably instead of
impressively.

---

### What I'm working on

- **[Jaberah](https://github.com/MohamedSaeed-dev/Jaberah-ASP)** — a management
  system for a Quran school (students, groups, teachers, attendance, exams,
  salaries, reports). ASP.NET Core 9 API in production, deployed on every push
  to `master`, with a [Flutter client](https://github.com/MohamedSaeed-dev/Jaberah-Flutter).
  Real users, real data, real bug reports.
- **[Mawaiid](https://github.com/MohamedSaeed-dev/Mawaiid)** — a backend
  reference application where I implement the topics I want to understand
  properly: authentication, background jobs, caching, transactions, observability.
- Reading about distributed systems and applied LLM engineering — retrieval,
  evaluation, and cost control rather than prompt tricks.

---

### How I approach engineering

- **Controllers stay thin.** Transport concerns belong in the controller;
  business rules belong in a service that can be tested without HTTP.
- **The database is a design decision, not a detail.** Indexes, soft deletes,
  query filters, and projection over `SELECT *` — I'd rather shape the query
  than cache a bad one.
- **Boring, explicit code wins.** I optimise for the person reading this in six
  months, usually me.
- **Ship it, then watch it.** A feature isn't done when it compiles. Logging,
  error handling, and a deployment pipeline are part of the feature.

---

### Selected projects

| Project | What it is | Stack |
|---|---|---|
| [Jaberah API](https://github.com/MohamedSaeed-dev/Jaberah-ASP) | Production school-management API — 13 modules, soft deletes, in-memory caching, CI/CD to production | ASP.NET Core 9, EF Core, SQL Server, GitHub Actions |
| [Gitify](https://github.com/MohamedSaeed-dev/Gitify) | GitHub PR dashboard that groups pull requests by base branch and auto-detects stacked PRs | Next.js 14, TypeScript, TanStack Query, GitHub App OAuth |
| [Arabic LinkedIn Content Generator](https://github.com/MohamedSaeed-dev/Generate-Linkedin-content) | LLM service that drafts Arabic technical posts on a schedule | NestJS, Gemini, LangChain, Prisma |
| [NestJS + Fastify + Prisma starter](https://github.com/MohamedSaeed-dev/nestjs-fastify-prisma-starter) | Opinionated backend template — layered modules, Zod-validated config, Docker for dev and prod | NestJS, Fastify, Prisma, Docker |

---

### Tools I reach for

**Languages** C# · TypeScript · JavaScript · Python · Dart
**Backend** ASP.NET Core · NestJS · Express · FastAPI
**Data** SQL Server · PostgreSQL · MongoDB · Redis · EF Core · Prisma
**Infrastructure** Docker · GitHub Actions · Nginx
**AI/LLM** LangChain · Gemini API · retrieval & prompt evaluation

---

### Contact

[Email](mailto:mohamedsas966@gmail.com) ·
[LinkedIn](https://linkedin.com/in/mohamed-saeed-bin-omar) ·
[Stack Overflow](https://stackoverflow.com/users/24899979/mohamed-saeed-bin-omar)

Happy to talk about backend architecture, .NET, or anything LLM-adjacent.
