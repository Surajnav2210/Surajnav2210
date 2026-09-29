# Hi, I'm Suraj 👋

I'm a software engineer who enjoys building **full-stack products**: scalable backends, cloud infrastructure, AI-powered features, and clean web and mobile apps that real people use.

I recently graduated from **UW–Madison** with a B.S. in Computer Science and Data Science. Along the way I've shipped production software at a startup, built internal tools for a public media organization, done ML research and consulting, and worked on products from mobile apps to payment flows. I like owning a problem end to end, from the data model and APIs to the deploy and what users actually experience.

- 🔭 **Interested in:** backend systems, cloud infrastructure, full-stack product development, and applied AI/ML
- 🌱 **Currently:** building production-style projects end to end, from system design to deploy
- 📍 **Location:** Madison, WI (open to relocation)
- 💼 **Looking for:** new-grad Software Engineering and AI Engineering roles

---

## 🚀 Selected Projects

### [StructNote](https://github.com/Surajnav2210/StructNote) · Voice memo to structured document SaaS

`Next.js` `TypeScript` `AWS S3/SQS/Lambda` `Supabase` `pgvector`

🔗 **[Live demo](https://struct-note-suraj-naveens-projects.vercel.app/)**

Record a meeting wrap-up or site walk and get back a finished note (summary, decisions, action items) in under 40 seconds. Built and deployed solo in one week.

- Event-driven pipeline: presigned S3 uploads → SQS (with DLQ) → idempotent Lambda workers
- Whisper transcription + Gemini structuring into schema-validated JSON, with automatic retry
- RAG search over past notes on pgvector, returning answers with cited sources
- Multi-tenant security with Supabase Auth JWT, Postgres Row Level Security, and least-privilege IAM

### [Gatepass](https://github.com/Surajnav2210/Juspay-OA-) · Ticketing checkout on Juspay Hyperswitch

`Next.js` `TypeScript` `Payments` `Webhooks`

- Seat holds with a TTL and US all-in pricing (face value + service fee shown before paying)
- Authorize-then-capture: the card is charged only if the seat hold is still alive, otherwise the payment is voided
- Soft declines keep the hold and issue a fresh payment intent (up to 3 retries) instead of releasing the seat

### [Bedtime Story Agents](https://github.com/Surajnav2210/OA-Hippocratic-) · Multi-agent LLM pipeline with an independent judge

`Python` `OpenAI API` `LLM evaluation`

- Four agents: router → planner → writer → judge
- The judge sees only the finished story and returns four rubric scores plus targeted edits
- Safety revisions are enforced in code, and the best-scoring draft is returned so a bad revision can never win

### [RiskChain](https://github.com/Surajnav2210/RiskChain) · Insurance fraud-ring detection (MadHacks 2025)

`FastAPI` `NetworkX` `Next.js` `SQLite`

- Builds a connection graph across 350+ claims (shared doctors, lawyers, IPs) to surface organized fraud rings
- Real-time 0–100 risk score, an employee dashboard, and a claimant submission portal

### [SPONTA](https://github.com/Surajnav2210/SPONTA) · Gamified spontaneity app for college students

`React Native` `Expo` `Firebase` `Node.js`

- Team-built iOS app with challenges, events, and real-time sync, launched to 40+ users
- I worked on the frontend

### [Cloud Data Ingestion & Analytics](https://github.com/Surajnav2210/Cloud-data-ingestion-analytics-) · Dataset upload and analytics service

`Flask` `Pandas` `PostgreSQL` `AWS Lambda/S3/SES`

- Upload CSV/Excel datasets that are automatically cleaned and preprocessed
- REST endpoints for summary stats, missing values, and distributions, plus weekly emailed reports

<details>
<summary><b>More ML and data projects</b></summary>

<br>

- **[DCGAN Patcher](https://github.com/Surajnav2210/DCGANPatcher):** reconstructs images from fragments using a modified GAN loss, L1 regularization, and a U-Net generator (hackathon, team project)
- **[PCA + t-SNE Facial Clustering](https://github.com/Surajnav2210/PCA-tSNE-Facial-Clustering):** 80% dimensionality reduction on YaleB faces while keeping 90% of the variance
- **[FashionMNIST Classifier](https://github.com/Surajnav2210/FashionMNIST-Classifier):** PyTorch neural network with 84.7% test accuracy
- **[Student Performance Explorer](https://github.com/Surajnav2210/Student-Performance-Explorer-):** interactive R Shiny app ([live](https://suraj2210.shinyapps.io/StudentPerformanceFactors/))
- **[Soccer Striker Analysis](https://github.com/Surajnav2210/Soccer-Striker-Analysis):** statistical study of age vs. striker performance in R

</details>

---

## 💼 Experience

**Software Engineer** · PBS Wisconsin · *Jan 2026 – May 2026*

- Built a Slack RAG assistant (FastAPI + ChromaDB) that lets staff query 500+ records in natural language
- Owned embedding model selection, chunking strategy, and the Airtable ingestion pipeline

**Full Stack Software Engineer** · Dealcycle AI · *May 2025 – Aug 2025*

- Shipped two production SaaS apps end to end (Next.js, PostgreSQL, Python and Node.js APIs)
- Owned CI/CD on AWS with Docker, and redesigned onboarding using PostHog funnel data

**ML Consultant** · Wearable Technologies Inc. · *Jan 2026 – May 2026*

- Audited a production fall-detection classifier with a 19-threshold precision-recall sweep
- Recommended a new alert cutoff that the ML lead adopted

**Undergraduate Research Assistant** · MAGIC Lab, UW–Madison · *Jan 2025 – Nov 2025*

- Built Pandas data pipelines across 10 studies and cut experiment setup from 45 minutes to one command

**Software Engineer Intern** · Evenforce Technologies · *Jun 2023 – Jul 2023*

- Improved reliability and SQL performance for a garage-management SaaS used by 200+ dealerships

---

## 🛠️ Skills

- **Languages:** Python, TypeScript, JavaScript, Java, C, C++, SQL, R
- **Frontend & Mobile:** React, Next.js, React Native (Expo), Tailwind CSS
- **Backend & APIs:** Node.js, Express, FastAPI, Flask, REST APIs, webhooks, microservices, event-driven pipelines
- **Cloud & DevOps:** AWS (S3, SQS, Lambda, IAM, SES), Docker, Vercel, CI/CD, Linux, Git
- **Databases:** PostgreSQL, pgvector, Supabase, Firebase, SQLite, ChromaDB
- **AI / ML:** PyTorch, TensorFlow/Keras, scikit-learn, LLM applications, RAG, multi-agent systems, model evaluation
- **Data & Analytics:** Pandas, NumPy, Matplotlib, Tableau, R Shiny, PostHog
- **Practices:** Agile/Scrum, code reviews, system design, OOP, testing (pytest)

---

## 📫 Contact

- 🌐 **Portfolio:** [surajnaveen.dev](https://surajnaveen.dev)
- 💼 **LinkedIn:** [linkedin.com/in/suraj-naveen](https://www.linkedin.com/in/suraj-naveen)
- ✉️ **Email:** [snaveen@wisc.edu](mailto:snaveen@wisc.edu)

Always happy to chat about software, side projects, new ideas, or opportunities. Feel free to reach out!
