### Hi, I'm Mark.

Software developer based in Düsseldorf. Backend with Python/FastAPI and
TypeScript/Next.js, infrastructure as code on AWS and Azure, plus C++ for the
low-level side.

**Stack**

`Python` `FastAPI` `TypeScript` `Next.js` `Terraform` `Docker` `Kubernetes` `AWS Lambda` `DynamoDB` `PostgreSQL` `Supabase` `GitHub Actions` `C++17` `Astro`

**What I'm working on**

| Project | What it is | Stack |
|---------|-----------|-------|
| [lead-triage](https://github.com/Mark1Anthony/lead-triage) | Lead intake and classification. **Three storage backends behind one interface** — SQLite, Postgres, DynamoDB — and the same code runs on all three. Deployed twice: [on AWS Lambda](https://642dvsi6k1.execute-api.eu-central-1.amazonaws.com) behind an HTTP API Gateway, and [on Render](https://lead-triage-31jo.onrender.com) with Postgres. Both free tiers, so give the first request a moment. | FastAPI, Terraform, AWS, Docker |
| [lead-triage-platform](https://github.com/Mark1Anthony/lead-triage-platform) | The platform underneath: Helm charts, Terraform, and a pipeline that builds a real three-node Kubernetes cluster on every push, deploys into it, proves it serves traffic, and tears it down. Five architecture decision records, including the one arguing against Kubernetes for a workload this size. | Kubernetes, Helm, Terraform, Azure |
| [dealflow-crm](https://github.com/Mark1Anthony/dealflow-crm) | CRM with a deal pipeline, Kanban drag & drop and Row Level Security on every table — access control in the database, not in the application. [Live demo](https://dealflow-crm-tau.vercel.app) — guest access, no sign-up | Next.js 16, Supabase, TypeScript |
| [client-showcase](https://github.com/Mark1Anthony/client-showcase) | Seven demo industry sites plus a multi-step sales funnel with dynamic pricing and an availability calendar, ~450 lines of vanilla JS | HTML, Tailwind, JavaScript |
| [Shell](https://github.com/Mark1Anthony/Shell) | A small Windows command interpreter — four built-ins and process launching straight through the Win32 API. Written to learn `CreateProcessA`, and deliberately not `system()` | C++17, CMake |

Every company, price and reference in the showcase is invented — those are demo
sites, not clients.

**[Portfolio](https://mark1anthony.github.io/mark-portfolio/)** · **[Email](mailto:markamaechi.dev@gmail.com)**
