# MEMORY.md — Octo Long-Term Memory

> **Bootstrap file — keep lean.** One atomic fact per line. Deep context lives in `memory/areas/` and `memory/resources/` — retrieved on demand via `memory_search`.
> Before acting on anything involving prior context: run `memory_search` first.

---

## 👤 Faris

- Name: Faris. Pronouns: he/him. Timezone: America/Chicago.
- School: UIUC sophomore (senior credits). Major: Brain & Cognitive Sciences. Minor: CS.
- Muslim. Ramadan 2026 (Spring semester) affected rhythm and energy.
- First conversation with Octo: April 11, 2026. Primary channel: Discord (switched May 19, 2026). Telegram still active but Discord is preferred.
- Discord channel structure: Three categories — **OCTO** (#alerts, #daily-brief, #recruiting, #content), **WITHOCTO** (#octo-business main convo, #site for withocto.co website only), **PROJECTS** (#builds general dev work default, #saas-farm, #neurobeats, #mbsa-site). Each guild channel = isolated session. Rule: dev/deploy work → #builds; withocto.co site specifically → #site; never mix dev convos into #octo-business.
- Deeply interested in brain-tech: Neuralink, Room Labs, BCIs, neurotech startups.
- Career interests: SWE, AI engineering, platform engineering, anything brain+tech.
- Recruiting hadn't gone well going into Spring 2026; refocused and motivated.
- Communication style: processes out loud; wants direct opinions, not hedging.
- Responds poorly to wishy-washy answers; wants evidence and conviction.

---

## 🎓 School — Fall 2026

- Confirmed courses: BCOG 458, CS 440, CS 411, Elementary Standard Arabic.
- Already taken: CS 361, PSYC 408.
- 4th BCOG elective: undecided. Top candidate: PSYC 421 (Psychophysiology, Prof. Dolcos).
- PSYC 421 conflict: forces Arabic to 11am — Faris struggles with early mornings.
- Ruled out: PSYC 453 (conflicts CS 440), PSYC 403 (conflicts BCOG 458).
- Full details → `memory/areas/school.md`

---

## 🌍 Study Abroad — Spring 2027

- Deadline: early June 2026 (~1 week left as of May 25). **URGENT.**
- Options: Morocco (CIEE Rabat) / Jordan (Amman) vs Singapore (NUS/NTU).
- Status: leaning Morocco. Tension: cultural/spiritual depth vs. academic rigor.
- Octo framing that resonated: "Ask which you'd regret NOT doing at 35."
- Full details → `memory/areas/school.md`

---

## 💼 Active Projects

- **PRIMARY:** withocto.co — AI automation business. Lead Response Agents for solo real estate agents. $1,200 setup + $300/mo. Relay product spec v1.1 complete (May 22), interactive demo + simulation server built. Next: n8n integration, landing page polish.
- **withocto site:** Next.js 14 + Tailwind, lives at `/workspace/projects/withocto-site/`. Deploy via **`git push origin main`** (Vercel GitHub integration auto-deploys). Never use `vercel --prod` directly — auth issues with commit author email. DNS on Porkbun (A → 76.76.21.21, CNAME www → cname.vercel-dns.com). Full deploy notes: `projects/withocto-site/DEPLOY_NOTES.md`.
- **Freelancing (AAAS):** Full collateral built (May 19): service agreement, outreach tracker with researched targets, pricing, templates, ICPs. Blocked on outreach email from Faris.
- **SaaS Idea Generator v1 (IdeaForge):** ✅ Built May 25. Next.js 14 + Tailwind, GPT-4o-mini, JSON store, dark editorial theme. Ready to run (needs OPENAI_API_KEY in .env.local). Lives at `projects/saas-idea-generator/`. Discord: #ideaforge (1508593095686750278).
- **Neurobeats:** Next.js project scaffolded May 20. `/workspace/projects/neurobeats/`.
- **MBSA Site:** Next.js project scaffolded May 24. `/workspace/projects/mbsa-site/`.
- **SIDE:** X personal brand (AI job hunting / builder niche). Account not yet live.
- **SIDE:** Instagram journey ("I gave $1K to AI to build a startup"). Day 1 script drafted, not yet filmed.
- **QUEUED IDEAS:** Agent Dashboard, Idea Marketplace (v3).
- Full plans: `/workspace/projects/`

---

## 🛠️ Dev Rules (Permanent)

- **Always use Claude Code for all development work.** No exceptions — writing/editing code, building features, refactoring, etc. goes through Claude Code, not inline exec.
- **Responsive design: use explicit Tailwind breakpoints (text-[size] sm:text-[size] lg:text-[size]), never rely on clamp()/vw alone.** Test at 390px (mobile), 768px (tablet), 1280px+ (desktop). Every page must be mobile-first.
- **Never use generic AI aesthetics:** no dark grids, no purple/violet radial glows, no gradient text on headings, no purple borders on logos. Purple/indigo is fine as a solid button accent color only.
- Claude Code: installed + authenticated (May 19, 2026).
- Frontend design: use the frontend design MCP plugin when available.

---

## 🔧 OpenClaw & Tools Config

- Config file: `~/.openclaw/openclaw.json`
- Exec: ✅ Fixed (May 19). `security:"full"`, `ask:"on-miss"`. Basic commands run free; dangerous ops still prompt.
- Discord: ✅ Configured and live (May 19, 2026). Bot is set up and active.
- Claude Code: installed + authenticated (May 19, 2026).

---

## 📄 Resume

- Key experience: HOPPR AI (LangChain, SageMaker), Click for Syria (1st place hackathon), CASPER Lab, MTC co-founder.
- Resume project sidelined (May 20, 2026). Blocked on Faris providing .tex file location.
- Full details → `memory/resources/resume.md` if resumed later.

## 🚧 Persistent Blockers (Needs Faris)

These have been open 5+ days as of May 25. Each blocks a significant workstream:
1. **Study abroad decision** — Deadline early June (~1 week). Morocco vs. Singapore.
2. **Outreach email** — Set up faris.builds@gmail.com (or similar). Unblocks: cold outreach, freelancing pipeline.
3. **Resume .tex file** — Confirm location. Unblocks: job application tailoring.


---

## ⚙️ Autonomy Rules (Permanent)

- **Act freely on:** research, writing, drafts, building files/tools, planning docs, code, internal reorganization.
- **Require Faris:** sending external messages, spending money, creating accounts, identity verification, being on camera.
- **Bottleneck protocol:** surface blocker → immediately document how to eliminate it permanently.
- "Don't ask, just do" applies to all safe + reversible actions. Report after, not before.
- **Primary driver rule (May 19, 2026):** Octo is the primary driver, not Faris. Keep building until a real bottleneck is hit. Maximize automation. Never stop and wait when forward progress is possible.
- **After-task rule (May 19, 2026):** After finishing every task, identify what else can be done to further the goals, do it, and only ping Faris if there's a hard bottleneck.

---

## 📐 Quality Standard (set May 22, 2026)

- **Evidence-first always.** Every significant deliverable — specs, plans, decisions, recommendations — must be research-backed. Search before writing. Cite sources. No hand-waving.
- This was explicitly set as the bar after the Relay product spec. Faris said: "this kind of evidence based depth and attention to detail should be the standard."
- Pattern: research → synthesize → decide with justification → write → deliver.

---

## 🧠 Patterns

- Faris processes out loud — reflect back, don't race to conclusions.
- "Wasted time" feelings spike during/after Ramadan — note as context, not fact.
- Plans to drop classes if overloaded — building flexibility in intentionally.
- Easily context-switches between big ideas — capture them all, prioritize ruthlessly.

---

## 📁 Memory Navigation

| Where | What |
|---|---|
| `MEMORY.md` (this file) | Lean atomic facts. Always in context. |
| `memory/areas/content.md` | Content strategy, X/Instagram plans |
| `memory/areas/recruiting.md` | Job search, applications, targets |
| `memory/areas/school.md` | Courses, study abroad, academic context |
| `memory/areas/freelancing.md` | AAAS clients, pipeline, pricing |
| `memory/resources/resume.md` | Resume details, feedback, LaTeX template |
| `memory/resources/tools.md` | Tools, access, credentials summary |
| `memory/YYYY-MM-DD.md` | Daily raw logs |
| `/workspace/projects/` | Full project specs |
