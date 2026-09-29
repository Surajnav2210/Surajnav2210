Hi, I'm Suraj 👋
I build full-stack products with AI in the loop: event-driven backends on AWS, RAG systems that answer with sources, and web apps people actually ship to.

I recently graduated from UW–Madison with a B.S. in Computer Science and Data Science. Along the way I shipped two production SaaS apps at Dealcycle AI, built a Slack RAG assistant for staff at PBS Wisconsin, and ran an ML consulting engagement whose recommended alert threshold was adopted by a wearables company's ML lead.

🔭 Interested in: backend and cloud infrastructure, LLM/RAG applications, applied ML
🌱 Currently: building production-style side projects end to end, from system design to deploy
📍 Madison, WI, open to relocation and looking for new-grad SWE / AI engineering roles


🚀 Selected Projects
StructNote: voice memo → structured document SaaS
Live demo · Next.js · TypeScript · AWS (S3, SQS, Lambda) · Supabase · pgvector

Record a meeting wrap-up or site walk and get back a finished note (summary, decisions, action items) in under 40 seconds. I built and deployed it solo in a week.

Event-driven pipeline: presigned S3 uploads → SQS (with DLQ) → idempotent Lambda workers
Whisper transcription + Gemini structuring into schema-validated JSON, with automatic retry
RAG search over past notes on pgvector, returning answers with cited sources
Multi-tenant security via Supabase Auth JWT, Postgres Row Level Security, and least-privilege IAM
Gatepass: ticketing checkout on Juspay Hyperswitch
Next.js · TypeScript · Payments

Seat holds, all-in US pricing, and authorize-then-capture payments. A card is only charged if the seat hold is still alive; otherwise the payment is voided. Soft declines keep the hold and issue a fresh payment intent (up to 3 retries) instead of releasing the seat. Webhook and client triggers share one idempotent finalize path.
Bedtime Story Agents: multi-agent LLM pipeline with an independent judge
Python · OpenAI API · LLM evaluation

Router → planner → writer → judge agents. The judge only sees the finished story and returns four rubric scores plus targeted edits. Safety revisions are enforced in code, not just the prompt, and the best-scoring draft wins, so a bad revision can't. The judge is calibrated with deliberately broken test stories.
RiskChain: insurance fraud-ring detection (MadHacks 2025)
FastAPI · NetworkX · Next.js · SQLite

Builds a connection graph across 350+ claims (shared doctors, lawyers, IPs) to surface organized fraud rings and a real-time 0–100 risk score, with an employee dashboard and a claimant submission portal.
SPONTA: gamified spontaneity app for college students
React Native (Expo) · Firebase · Node.js/Express

A team-built iOS app with challenges, events, and real-time sync, launched to 40+ users. I worked on the frontend.
Cloud Data Ingestion & Analytics
Flask · Pandas · PostgreSQL · AWS (Lambda, S3, SES)

Upload CSV/Excel datasets and they're automatically cleaned. You get summary, missing-value, and distribution analytics over a REST API, plus weekly emailed reports.

More ML & data work DCGAN Patcher: reconstructs images from fragments. Fixed vanishing generator gradients with a modified loss + L1 regularization and a U-Net generator (hackathon, team project)
PCA + t-SNE Facial Clustering: 80% dimensionality reduction on YaleB faces while keeping 90% variance (PSNR 20.01 dB, SSIM 0.76)
FashionMNIST Classifier: PyTorch MLP, 84.7% test accuracy
Student Performance Explorer: interactive R Shiny app (live)
Soccer Striker Analysis: statistical study of age vs. striker performance in R


💼 Experience
Role
What I did
Software Engineer, PBS Wisconsin · 2026
Slack RAG assistant (FastAPI + ChromaDB) that lets staff query 500+ records in natural language. I owned embedding and chunking evaluation and the Airtable ingestion pipeline.
Full Stack Engineer, Dealcycle AI · 2025
Shipped 2 production SaaS apps (Next.js, Postgres, Python/Node APIs), owned CI/CD on AWS + Docker, and redesigned onboarding based on PostHog funnel data.
ML Consultant, Wearable Technologies Inc. · 2026
Audited a production fall classifier and ran a 19-threshold precision-recall sweep. My recommended cutoff was adopted by the ML lead.
Research Assistant, MAGIC Lab, UW–Madison · 2025
Built Pandas data pipelines across 10 studies and cut experiment setup from 45 minutes to a single command.
SWE Intern, Evenforce Technologies · 2023
Improved reliability and SQL latency for a garage-management SaaS used by 200+ dealerships.



🛠️ Skills
Languages: Python, TypeScript, Java, C, C++, SQL, R Web & backend: React, Next.js, Node.js, FastAPI, Flask, REST APIs, microservices Cloud & data: AWS (S3, SQS, Lambda, IAM), Docker, PostgreSQL, pgvector, Supabase, Firebase, CI/CD AI/ML: RAG, LLM pipelines and evaluation, PyTorch, TensorFlow, scikit-learn, Pandas


📫 Contact
Portfolio: surajnaveen.dev · LinkedIn: suraj-naveen · Email: snaveen@wisc.edu

Always happy to talk about backend systems, RAG, or new-grad roles.
