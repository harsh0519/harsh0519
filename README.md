<h1 align="center">Harsh Kumar Mehta</h1>
<h3 align="center">Full Stack Developer — Frontend-Focused, System-Minded</h3>

<p align="center">
  <a href="https://harshbuilds.vercel.app">Portfolio</a> ·
  <a href="https://linkedin.com/in/harsh-kumar-mehta">LinkedIn</a> ·
  <a href="https://twitter.com/harsh__mehta">Twitter</a> ·
  <a href="mailto:harshmhta0519@gmail.com">harshmhta0519@gmail.com</a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=harsh0519&label=Profile%20views&color=0e75b6&style=flat" alt="profile views" />
</p>

---

### About

Full stack developer who builds and ships production systems end to end, with a
frontend specialism and a working command of the backend, data layer, and
release process. Most of my work is on admin-heavy and transactional products —
dashboards, marketplaces, and vendor/partner platforms — where correctness,
clear data modelling, and a trustworthy UI matter more than demos.

I am comfortable owning a feature from schema and API through to the screen an
operator actually uses, and I think in terms of invariants, lifecycle states,
and failure modes rather than happy paths.

---

### What I Work On

- **Admin and operations platforms** — dashboards, audit logs, role-separated
  consoles, and the aggregation/reporting behind them.
- **Transactional systems** — payment capture and reconciliation (Razorpay,
  bank/IMPS transfers), prepaid wallet and licence ledgers, idempotent money
  operations, and off-platform settlement with a full audit trail.
- **Marketplace and auction flows** — listing lifecycles (draft → live → sold),
  bidding, buy-now, order and fulfilment state, and the payment linkage between
  them.
- **Multi-tenant / partner APIs** — API-key authentication, per-tenant balances,
  usage metering, and self-serve partner portals.

---

### How I Approach System Design

- Model the domain around explicit **states and invariants** (an order, a
  payment, and an auction are separate records with enforced transitions).
- Keep money and ownership changes **idempotent and reversible-by-design** —
  guarded writes, atomic claims, rollback on partial failure, dry-run first on
  anything that touches production data.
- Make the backend the **source of truth** and keep the UI a faithful
  projection of it — exact figures, not sampled estimates.
- Treat **data visibility and auditability** as a feature: every manual or
  automated change leaves a reference an operator can trace.
- Maintain clean **module boundaries and release hygiene** — isolated feature
  areas, careful branch integration and conflict resolution, secrets kept out
  of version control.

---

### Tech Stack

#### Frontend
<p align="left">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg" width="40" alt="React"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nextjs/nextjs-original.svg" width="40" alt="Next.js"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/angular/angular-original.svg" width="40" alt="Angular"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" width="40" alt="TypeScript"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" width="40" alt="JavaScript"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg" width="40" alt="HTML5"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg" width="40" alt="CSS3"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/tailwindcss/tailwindcss-original.svg" width="40" alt="Tailwind CSS"/>
</p>

#### Animation and Interaction
<p align="left">
  <img src="https://cdn.simpleicons.org/greensock/88CE02" width="40" alt="GSAP"/>
  <img src="https://cdn.simpleicons.org/framer/0055FF" width="40" alt="Framer Motion"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/threejs/threejs-original.svg" width="40" alt="Three.js"/>
</p>

#### Backend and Data
<p align="left">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original.svg" width="40" alt="Node.js"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original.svg" width="40" alt="Express"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original.svg" width="40" alt="MongoDB"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original.svg" width="40" alt="PostgreSQL"/>
</p>

#### CMS, Auth, and Cloud
<p align="left">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/sanity/sanity-original.svg" width="40" alt="Sanity"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/firebase/firebase-original.svg" width="40" alt="Firebase"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/supabase/supabase-original.svg" width="40" alt="Supabase"/>
</p>

#### Payments and Integrations
<p align="left">
  <img src="https://cdn.simpleicons.org/razorpay/0C2451" width="40" alt="Razorpay"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" width="40" alt="AWS"/>
</p>

#### Tooling and Delivery
<p align="left">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/git/git-original.svg" width="40" alt="Git"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg" width="40" alt="Docker"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" width="40" alt="Linux"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/vercel/vercel-original.svg" width="40" alt="Vercel"/>
</p>

---

### Principles

- Production-ready over proof-of-concept — code that holds up under real data and real users.
- Performance and UX as first-class concerns, not afterthoughts.
- Clear, scalable architecture with boundaries that survive growth.
- Measurable correctness: verify against the source of truth before shipping.

---

<p align="center"><i>I turn complex, data-heavy interfaces into clean, dependable products.</i></p>
