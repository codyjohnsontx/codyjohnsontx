# 🏄 🏍️ 🏎️ 🥋 Hello friend, I'm [Cody](https://www.cody-johnson.com/).

I'm a software engineer building full stack apps, AI workflows, analytics, and operational systems.

I like turning vague problems into useful shipped tools, especially when the domain has real world constraints, messy data, and people who need answers fast.

## ⚙️ Tech Stack

TypeScript · JavaScript · React · Next.js · Node.js · Python · FastAPI · C# / .NET · SQL · Postgres · Git · Docker · Vercel · OpenAI · Claude · Claude Code

## 🔧 How I Work

- **Spec first.** Requirements, scope, and acceptance criteria get written down before code starts.
- **Tested.** Automated suites, golden file checks, and round trip verification on anything that leaves the app.
- **Grounded AI.** Evals, guardrails, and answers backed by real data. If a model makes a claim it can't source, it doesn't ship.

## Current Projects

### 🧬 [OncoPath](https://github.com/codyjohnsontx/ocnoPath)
Live app that turns public ClinicalTrials.gov records into plain language explanations for patients. Built around an evaluation harness that caught bugs in both the generator and the automated judge, then got checked against human review before any score was trusted.

### 🚲⚡ [Wattsmith](https://github.com/codyjohnsontx/wattSmith)
Local first cycling workout builder with FTP based power targets and verified `.mrc` / `.erg` export. Exported files are parsed back and diffed against the source automatically, so a bad file never reaches a real training ride. 119 tests and counting.

### 🚲💨 [RideSense](https://github.com/codyjohnsontx/ridesense)
Cycling analytics app that dedupes TrainerRoad, Strava, and uploaded ride data into one canonical training timeline. Content hash deduplication, encrypted OAuth token handling, deterministic analytics, and grounded Q&A without double counted TSS or hand wavy AI coaching.

### 🏍️🏎️ [Track Tuner](https://github.com/codyjohnsontx/trackday_tuner)
Mobile race engineer for riders and drivers. Setup logging, session history, track conditions, and feedback, with RAG based AI setup guidance grounded in the rider's actual history instead of generic advice.

### 🏎️🏁 [Oasis Race Control](https://github.com/codyjohnsontx/oasisRaceControl)
Check-in and live timing for a sim racing venue. Drivers scan a QR code at their rig, a front of store TV shows live "fastest tonight" standings, drivers follow their own laps on their phone, and staff run the floor from one dashboard. A .NET agent on each simulator ships laps through a durable, idempotent outbox, so a network drop or restart never loses a lap, and the database enforces one open assignment per rig instead of trusting the app to.

### 🏍️💬 [CTX Connect](https://github.com/codyjohnsontx/ctxconnect)
Dealership communication workspace for motorcycle teams. Shared customer texting with SMS compliance built in from day one, follow ups, assignments, and manager visibility in one place.

### 🥋🥋 [Diaz on Demand](https://github.com/codyjohnsontx/DiazMartialArts)
Subscription VOD platform for martial arts training. Structured courses, entitlement logic, Stripe billing, Mux video delivery, and admin publishing workflows.
[![GitHub Stats](https://github-stats-extended.vercel.app/api?username=codyjohnsontx&include_all_commits=true&theme=dark)](https://github-stats-extended.vercel.app/api?username=codyjohnsontx&include_all_commits=true&theme=dark)

[![Anurag's GitHub stats](https://github-stats-extended.vercel.app/api?username=codyjohnsontx)](https://github.com/stats-organization/github-stats-extended)
