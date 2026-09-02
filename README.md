# Ibrahim Ahmadli

Incoming MS in Computer Science at Columbia. I build products end to end — mostly AI systems, full-stack web, and mobile.

Previously CS + Economics at UW–Madison. Currently in New York.

---

## What I'm building

### [CareerLab](https://www.thecareerlab.live) — AI career exploration platform, 300+ users

Students test careers through hands-on job simulations instead of reading descriptions. I own the architecture end to end. Retrieval-grounded generation over a curated career corpus rather than raw LLM output — Pinecone vector store, OpenAI embeddings, LangChain plumbing — chosen for output grounding and predictable inference cost. Also built the Clara AI companion (shared session and retrieval layer across embedded widget and sidebar surfaces), the partner analytics dashboard, and the admin tooling. Monorepo with Zod schemas and Drizzle tables shared between client and server, and a Vitest suite covering unit, integration, and security paths against a real Postgres, gated in CI.

`React` `TypeScript` `Vite` `Express` `PostgreSQL` `Drizzle` `Pinecone` `OpenAI` `Tailwind`

<p align="center">
  <img src="assets/careerlab-1.png" width="49%">
  <img src="assets/careerlab-2.png" width="49%">
</p>
<p align="center">
  <img src="assets/careerlab-3.png" width="49%">
  <img src="assets/careerlab-4.png" width="49%">
</p>

---

### [Revio](https://explorerevio.com) — social restaurant discovery, mobile

Group-first restaurant discovery: location-weighted hangout ranking, real-time 1:1 and group chat, and swipe/bracket polls for deciding where to eat. Built with a co-developer. Most of the interesting work has been on correctness under real conditions — offline handling, backend scale audits, and a production-behavior testing practice that caught rounding bugs synthetic test data missed twice.

`React Native` `Expo` `Supabase` `TypeScript`

<p align="center">
  <img src="assets/revio-1.png" width="32%">
  <img src="assets/revio-2.png" width="32%">
  <img src="assets/revio-3.png" width="32%">
</p>

---

### [HEYBE Atelier](https://heybeatelier.com) — premium leather goods, custom storefront

Built the storefront from scratch rather than using Shopify — catalog, cart, checkout, and admin. Interesting constraint: Stripe doesn't support AZN, so payments run through a local provider, and the store currently uses a feature-flagged reserve-to-order flow instead of live checkout.

`Next.js` `Prisma` `Supabase` `Vercel`

<p align="center">
  <img src="assets/heybe-1.png" width="70%">
</p>

### BestTrans — interactive 3D site

Frontend build for a logistics business, structured around interactive 3D dioramas
rather than a conventional page layout. Mostly an exercise in scene composition,
asset weight, and keeping the thing smooth on mid-range devices.

`Three.js` `React`

<p align="center">
  <img src="assets/besttrans-1.png" width="70%">
</p>

---

## Research & analysis

### Clinical RAG system — Molecular Imaging & MR Lab, UW–Madison

Retrieval-augmented guidance system over 160+ clinical papers, reaching 92%+ source-citation accuracy with 44% lower response latency through IVF-FLAT indexing and a retrieve-then-rerank pipeline. Co-designed the validation study benchmarking six LLMs against 177 physician-verified queries. Accepted for long oral presentation at the American College of Surgeons Clinical Congress.

### Predicting violent crime hotspots in Chicago — ECON 695, group project

Built a 789-tract panel from 8.5M Chicago crime incidents and 311 service requests spanning 2018–2025. Pooled OLS explained 79% of cross-sectional variation, but adding tract-level fixed effects collapsed six of eight disorder indicators — graffiti, infrastructure, abandonment, and sanitation all lost significance once each neighborhood was compared only to itself. Only property/street crime and vice/public disorder survived, and both held under a one-year lag. Replicated on 1,212 Los Angeles tracts as an external validity check.

The maps below show homicide counts and vacant building complaints by tract; the overlap on the south and west sides is the visual version of the regression result.

<p align="center">
  <img src="assets/chicago-homicide-map.png" width="42%">
  <img src="assets/chicago-vacant-map.png" width="42%">
</p>
<p align="center">
  <img src="assets/chicago-fixed-effects.png" width="49%">
  <img src="assets/chicago-lagged.png" width="49%">
</p>

---

## Note on repositories

Most of what I build is in private repos — CareerLab and Revio have real users, so the code stays closed. The pinned repos here are coursework and research code I can share openly, plus write-ups of the architecture behind the private projects.

---

## Stack

**Languages** Python · TypeScript · Java · SQL · R · C
**Frontend** React · React Native · Next.js · Tailwind
**Backend** Node · Express · FastAPI · PostgreSQL · Supabase · Drizzle · Firebase
**AI/ML** LangChain · LangGraph · PyTorch · Pinecone · Milvus · RAG architectures
**Infra** Docker · Vercel · Render · Git · Linux

---

📫 [ia2629@columbia.edu](mailto:ia2629@columbia.edu) · [LinkedIn](https://www.linkedin.com/in/iahmadli/)
