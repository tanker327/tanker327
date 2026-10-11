# Eric Wu

📧 eric.wuge@gmail.com | 🔗 [linkedin.com/in/eric-wu-tl](https://linkedin.com/in/eric-wu-tl) | 💻 [github.com/tanker327](https://github.com/tanker327)

---

## About Me

I've been shipping software for 15+ years: consulting, then ad tech, then life insurance, and now finance at JPMorgan Chase, where I lead a frontend team. Outside of work I build AI agent systems and run them on a homelab that's more serious than it needs to be.

I think AI is the biggest shift I'll see in my career, and the best way I know to get ready for it is to build with it. I write code for people first and machines second, and these days I use AI for both.

I keep reinventing the wheel. It gets a little rounder every time.

---

## Skills

- **Programming languages:** TypeScript/JavaScript, Python, Go, Swift, SQL, shell
- **AI:** Claude Agent SDK, Pi Agent SDK, LangChain, RAG, multi-agent pipelines, local inference (vLLM, llama.cpp), Qdrant, LanceDB
- **Frontend:** React, TanStack, shadcn/ui, Tailwind CSS, single-spa, ag-grid, Zedux, Playwright
- **Backend:** Node.js, Bun, Hono, Express, GraphQL, Flask, BullMQ, pg-boss, hey-api
- **Infrastructure:** Docker, Kubernetes, AWS, Google Cloud, Proxmox, GitHub Actions
- **Databases:** PostgreSQL, MySQL, MongoDB, Turso/libSQL
- **Human languages:** English, Chinese

---

## Work Experience

### JPMorgan Chase, Jersey City, NJ
**Vice President, Lead Software Engineer** | Nov 2024 – Present

Tech lead and architect for Portfolio Intelligence 2.0, the rebuild of our corporate portfolio asset management platform.

- Lead the frontend team and own the architecture: a multi-window app stitched together from single-spa micro-frontends, with real-time updates over SSE and ag-grid for the big tables.
- Leading the team's AI adoption, starting with an agentic workflow that takes a Jira ticket and turns it into code, so engineers start from a draft instead of a blank file.

**Stack:** TypeScript, React, TanStack, Tailwind CSS, single-spa, ag-grid, Salt DS (JPMorgan's design system), Zedux, Playwright

### Loopdoop LLC
**Master Builder** | Jan 2024 – Present

My own company, which is how I got to pick the title. A lot of the work here goes after one problem: there's far more worth reading and listening to than anyone has time for.

- **Juicer** and Keeper pull in content from several platforms, back it up to S3-compatible storage, and run every item through seven LLM stages (taxonomy, signals, summary, key takeaways, claims, mindmap, fact-check). BullMQ and Postgres underneath, React and TanStack on top.
- **ai-hub** is the OpenAI-compatible gateway (Bun, Hono, Postgres) my other projects use to talk to models. It tracks cost per service, keeps a semantic cache, and runs long jobs async with webhook callbacks.
- Built two multi-agent systems on the Pi Agent SDK: a review panel where a judge agent weighs what several panelists say, and an AI Research Lab where planner, researcher, analyst, evaluator, and synthesizer agents work through a question together.
- **Podcasts Station** turns the podcasts, newsletters, and YouTube channels I follow into bilingual English/Chinese documents. It worked a little too well: I now have more to read than time to read it. So I'm building **Brewer**, which boils long transcripts and articles down to short, verified briefs.
- RIG is my semantic search layer (LanceDB + nomic-embed).
- Most of it runs at home on a Proxmox cluster with an RTX PRO 6000 (96GB) and an RTX 4090. I benchmark and serve open-source models there, mostly Qwen through vLLM and llama.cpp.
- Side quests: ModelPK.com, DevsBestFriend.com, and a few open-source libraries and MCP servers (prompts-mcp-server, xtract-js, WebRobber). Currently building skl (useskl.com), one place to manage agent skills across Claude Code, Codex, Cursor, Copilot, Gemini, and Grok.

### Haven Technologies, New York, NY
**Senior Engineer & Tech Liaison** | Apr 2018 – Dec 2023

Built and scaled HT Underwriting, an ML-powered platform for life insurance decisions. Risk evaluation used to take weeks; we got it down to under a minute.

- Built the multi-stage decisioning workflow for term and whole life policies, plus HUP Admin to manage the whole flow.
- Wired in the third-party data that underwriting depends on: MIB, Milliman IntelliScript, LexisNexis, ExamOne, and APS.
- Created Metron, a company-wide configuration management system that keeps the full history of every change.

**Stack:** Node.js/TypeScript, Python, Angular, React, RabbitMQ, Postgres, Orca, AWS

### Yieldmo, New York, NY
**Senior Developer & Tech Lead** | Dec 2014 – Mar 2018

An ad platform connecting advertisers and publishers through privacy-compliant, ML-driven contextual targeting.

- Built core ad products: responsive ad formats, the Ads SDK, and the [Ad-Builder site](https://formats.yieldmo.com).
- Plus the internal tools: the admin system, an A/B testing tool (YMTP), and the product feed system.
- Co-inventor on two US patents for video ads that react to scrolling. (You've probably scrolled past one.)

**Stack:** Java, Spring MVC, TypeScript, Angular, Express

### Kforce Inc.
**Consultant** | Jan 2010 – Dec 2014

Built web platforms and internal tools for clients including Verizon, Audible, Pearson, and Barclays Capital.

---

## Education

**M.S. in Computer Science**, Syracuse University, Dec 2009

---

## Patents

- [US9966109B2](https://patents.google.com/patent/US9966109B2/en): *Methods for serving interactive content to a user*, granted May 2018
- [US10306336B2](https://patents.google.com/patent/US10306336B2/en): *Methods for serving a video advertisement to a user*, granted May 2019
