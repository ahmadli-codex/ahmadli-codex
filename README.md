# Ibrahim Ahmadli

Incoming MS in Computer Science at Columbia. I build products end to end — mostly AI systems, full-stack web, and mobile.

Previously CS + Economics at UW–Madison. Currently in New York.

---

## What I'm building

**[CareerLab](https://www.thecareerlab.live)** — AI career exploration platform, 300+ users
Students test careers through hands-on job simulations instead of reading descriptions. I own the architecture end to end. Retrieval-grounded generation over a curated career corpus rather than raw LLM output — Pinecone vector store, OpenAI embeddings, LangChain plumbing — chosen for output grounding and predictable inference cost. Also built the Clara AI companion (shared session and retrieval layer across embedded widget and sidebar surfaces), the partner analytics dashboard, and the admin tooling. Monorepo with Zod schemas and Drizzle tables shared between client and server, and a Vitest suite covering unit, integration, and security paths against a real Postgres, gated in CI.

`React` `TypeScript` `Vite` `Express` `PostgreSQL` `Drizzle` `Pinecone` `OpenAI` `Tailwind`

**[Revio](https://explorerevio.com)** — social restaurant discovery, mobile
Group-first restaurant discovery: location-weighted hangout ranking, real-time 1:1 and group chat, and swipe/bracket polls for deciding where to eat. Built with a co-developer. Most of the interesting work has been on correctness under real conditions — offline handling, backend scale audits, and a production-behavior testing practice that caught rounding bugs synthetic test data missed twice.
`React Native` `Expo` `Supabase` `TypeScript`

**[HEYBE Atelier](https://heybeatelier.com)** — premium leather goods, custom storefront
Built the storefront from scratch rather than using Shopify — catalog, cart, checkout, and admin. Interesting constraint: Stripe doesn't support AZN, so payments run through a local provider, and the store currently uses a feature-flagged reserve-to-order flow instead of live checkout.
`Next.js` `Prisma` `Supabase` `Vercel`

---

## Research

**Clinical RAG system** — Molecular Imaging & MR Lab, UW–Madison
Retrieval-augmented guidance system over 160+ clinical papers, reaching 92%+ source-citation accuracy with 44% lower response latency through IVF-FLAT indexing and a retrieve-then-rerank pipeline. Co-designed the validation study benchmarking six LLMs against 177 physician-verified queries. Accepted for long oral presentation at the American College of Surgeons Clinical Congress.

---

## Note on repositories

Most of what I build is in private repos — CareerLab and Revio have real users, so the code stays closed. The pinned repos here are coursework and research code I can share openly, plus write-ups of the architecture behind the private projects.

---

## Stack

**Languages** Python · TypeScript · Java · SQL · R · C
**Frontend** React · React Native · Next.js
**Backend** Node · Express · FastAPI · PostgreSQL · Supabase · Firebase
**AI/ML** LangChain · LangGraph · PyTorch · Pinecone · Milvus · RAG architectures
**Infra** Docker · Vercel · Git · Linux

---

📫 [ia2629@columbia.edu](mailto:ia2629@columbia.edu) · [LinkedIn](https://www.linkedin.com/in/iahmadli/)

<!--
**ahmadli-codex/ahmadli-codex** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
