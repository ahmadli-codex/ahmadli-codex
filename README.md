# Ibrahim Ahmadli

MS in Computer Science at Columbia, ML track. Previously CS + Economics at UW–Madison — a long way of saying I like building things and I like knowing whether they worked.

Lately that's meant an AI career platform with 300+ users, a restaurant discovery app, a leather goods storefront, and a retrieval system for thyroid cancer patients that's headed to the American College of Surgeons Clinical Congress. Recurring theme: I ship it, then spend twice as long finding out where it breaks — which is how I found out one of my own products was confidently making things up, and how a semester of regression work ended with six of eight predictors falling apart under scrutiny.

Before all that: audit at EY, and a summer keeping the systems running at Azerbaijan's national space agency.

New York now. Four languages, one very over-automated apartment, and an ongoing project to eat at every restaurant in the city.

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)

**Frontend**

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![React Native](https://img.shields.io/badge/React_Native-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-20232A?style=flat-square&logo=nextdotjs&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-20232A?style=flat-square&logo=threedotjs&logoColor=white)

**Backend & data**

![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-20232A?style=flat-square&logo=express&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=black)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)

**AI / ML**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=flat-square&logo=pinecone&logoColor=white)

**Infra**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-20232A?style=flat-square&logo=vercel&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

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

---

### [BestTrans](https://besttranslogistic.com) — interactive 3D site

Frontend build for a logistics business, structured around interactive 3D dioramas
rather than a conventional page layout. Mostly an exercise in scene composition,
asset weight, and keeping the thing smooth on mid-range devices.

`Three.js` `React`

<p align="center">
  <img src="assets/besttrans-1.png" width="70%">
</p>

---

## Research & analysis

### Thyroaid, Clinical RAG system — Molecular Imaging & MR Lab, UW–Madison

Retrieval-augmented guidance system over 160+ clinical papers, reaching 92%+ source-citation accuracy with 44% lower response latency through IVF-FLAT indexing and a retrieve-then-rerank pipeline. Co-designed the validation study benchmarking six LLMs against 177 physician-verified queries. Accepted for long oral presentation at the American College of Surgeons Clinical Congress.

On aggregate score the RAG system landed level with the strongest standalone model. The gain shows up in the dimensions that matter clinically: completeness 9.5 vs 6.8 and safety 9.6 vs 8.9 against the non-RAG average — retrieval mostly stops the model from leaving things out.

📄 [ACS Clinical Congress abstract (PDF)](papers/thyroaid-acs-abstract.pdf) · [Presentation slides (PDF)](papers/thyroaid-symposium.pdf)

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

📄 [Full paper (PDF)](papers/chicago-violent-crime.pdf) — ECON 695 coursework, included in full so the methods and results are inspectable.

### Predicting restaurant revenue

Compared OLS, ridge, LASSO, random forest, and gradient boosting on 137 restaurants
across 43 variables, with a 70/30 split and 10-fold cross-validated penalty tuning in R.

The interesting part is where OLS fails. On raw revenue it produced a *negative*
out-of-sample R² — worse than just predicting the mean — because 37 heavily
correlated predictors on 137 observations is a recipe for overfitting. Regularization
fixed most of it; tree-based models did best. Restaurant age was the only predictor
LASSO kept at the optimal penalty.

`R` `glmnet` `randomForest` `gbm` `ggplot2`

<p align="center">
  <img src="assets/restaurant-correlation.png" width="49%">
  <img src="assets/restaurant-importance.png" width="49%">
</p>

📄 [Full paper (PDF)](papers/restaurant-revenue-prediction.pdf) — ECON 695 coursework. Predictors are anonymized as P1–P37 in the source data, so this is a model-comparison exercise rather than an economic interpretation.

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
