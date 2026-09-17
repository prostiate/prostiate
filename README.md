# Muhammad Irfan Kurniawan

Senior Full Stack & Systems Engineer based in Jakarta, Indonesia.  
Writing about systems, web performance, and architecture at [**irfankurniawan.com**](https://irfankurniawan.com).

---

## Focus & Experience

Senior engineer with 8+ years of experience designing, shipping, and operating high-concurrency retail systems, internal platforms, and distributed web applications. Currently driving application architecture and infrastructure at **Amazone Indonesia**.

- **Production Ownership & Scale:** Sole frontend and application infrastructure owner across 6 live production systems (Head Office Backoffice, Nationwide Cashier/POS, Multi-tenant Inventory, HSE, Payout, and Auth Admin).
- **Pragmatic Systems Engineering:** Evidence-driven decision making—designed and load-tested a K3s GitOps cluster, then retired it after disk-I/O benchmarking exposed baremetal hardware bottlenecks (10–15 MB/s), rebuilding zero-downtime health-gated rolling releases on Docker Compose instead.
- **Enterprise Identity & Security:** Designed and built an in-house Go/GraphQL authentication service replacing Firebase Auth across 11 applications, implementing revocable server sessions, rotating refresh tokens, and auditable RBAC with zero cutover downtime.
- **Constrained Hardware Performance:** Engineered for real-world field constraints—audited and optimized POS frontends for legacy in-store machines (Chrome 109 / Windows 7), eliminating memory and render freezes via server-paginated flows instead of forcing costly hardware refreshes.
- **Frontend Architecture:** Consolidated 3 fragmented Nuxt applications into a unified Bun + Turborepo monorepo with a shared `@amazone/base` layer (27 components, unified auth), halving CI/CD build times.

---

## Highlighted Projects

Curated case studies from [**irfankurniawan.com/projects**](https://irfankurniawan.com/projects):

- **[Amazone Retail & POS Monorepo](https://irfankurniawan.com/projects/fe-amazone-monorepo)**  
  Consolidated three independent Nuxt frontends and a desktop cashier shell into a Bun + Turborepo monorepo. Solved severe in-store form freezes on legacy hardware and cut staging/production pipeline build times in half.  
  *Stack: Vue 3 · Nuxt · Bun · Turborepo · Element Plus*

- **[In-House Authentication Service](https://irfankurniawan.com/projects/amazone-auth-service)**  
  Engineered a centralized Go and GraphQL session service replacing Firebase Auth across 5 backends and 6 frontends. Features opaque revocable sessions, HMAC-peppered bcrypt hashing, and server-driven RBAC permissions.  
  *Stack: Go · GraphQL (gqlgen) · PostgreSQL · Redis · Docker*

- **[Baremetal Platform Modernization](https://irfankurniawan.com/projects/k8s-docker-migration)**  
  Load-tested a K3s GitOps cluster, identified a shared SAS HDD bottleneck under concurrent image pulls, and transitioned to health-gated, multi-node Docker Compose rolling deploys with per-node rollback guarantees and zero production downtime.  
  *Stack: Docker Compose · Jenkins · Nginx · Linux (VMs) · Observability*

- **[Ono Toolkit](https://onotoolkit.irfankurniawan.com)**  
  Client-side web utility suite that executes file processing, media compositing, and ONNX Runtime model inference locally in the browser with zero server upload payload.  
  *Stack: Nuxt 4 · WebAssembly · ONNX Runtime Web · Web Workers*

*Explore all case studies and architecture write-ups at [**irfankurniawan.com/projects**](https://irfankurniawan.com/projects).*

---

## Selected Writing

- [23 MB I Never Load: What Shipping Ghostscript and ONNX to Cloudflare Costs](https://irfankurniawan.com/blog/23-mb-i-never-load-cloudflare-wasm-payload)
- [The Kubernetes Deployment That Taught Me to Measure the Disk](https://irfankurniawan.com/blog/kubernetes-storage-postmortem-multi-vm-blue-green-automation)
- [Self-Hosting the Delivery Loop on a Tight Resource Budget](https://irfankurniawan.com/blog/privacy-first-self-hosted-infrastructure-cicd-observability)
- [From Copy-Pasted Frontends to One Shared Nuxt Layer](https://irfankurniawan.com/blog/micro-frontend-evolution-cashier-backoffice-v2-nuxt-monorepo)

---

## Contact

- **Website:** [irfankurniawan.com](https://irfankurniawan.com)
- **Email:** [mail@irfankurniawan.com](mailto:mail@irfankurniawan.com)
- **LinkedIn:** [muhammad-irfan-kurniawan](https://www.linkedin.com/in/muhammad-irfan-kurniawan/)
- **Location:** Jakarta, Indonesia
