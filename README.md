## Hi there, I'm Vivid 👋

AI Product & Venture Lead · Startup Founder · Sydney, Australia 🇦🇺

I play at the intersection of frontier AI, product strategy, and human-centred design. My background spans HCI and design, two startup exits, and 12 countries — now focused on building AI systems that actually work for people.

---

## 🧠 What I Do

- **AI Product Strategy** — Defining product vision and roadmap for AI-native systems; from concept to deployment
- **Human-AI Interaction** — Designing experiences where AI augments human decision-making (built on Stanford HCI principles)
- **Agentic AI Systems** — Exploring multi-agent architectures, LLM orchestration, and AI-driven gameplay
- **Data Science & ML** — Bridging product thinking with model evaluation, feature engineering, and AI pipeline design
- **Startup Building** — Two successful exits in video games (Shanghai & Berlin); currently building with AI agents as co-founders

---

## ✨ Featured Works

### [vivid-clean](https://github.com/vnsavitri/vivid-clean) — local document hygiene for AI-assisted work
*open source · privacy*

A local-first tool for removing deterministic provenance markers and common AI-writing tells from documents, images and text. Built for people who use AI as an accessibility or writing aid and want control over the metadata attached to their work.

- Processes files locally and creates a cleaned copy rather than overwriting the original
- Supports Word, PowerPoint, PDF, plain text, Markdown and common image formats
- Checks for Unicode markers, document properties, C2PA data and EXIF/XMP metadata

`Bash` · `Python` · `local-first` · `document hygiene`

---

A curated slice of what I'm building. Full case studies and writing at **[vnsavitri.github.io](https://vnsavitri.github.io)**.

### [vai_sante_os](https://github.com/vnsavitri/vai_sante_os) — privacy-first multimodal memory
*active · research*

A framework for provenance-aware multimodal memory and orchestration in high-stakes AI workflows (health, legal, policy, safety).

- Provenance-aware retrieval returns content **and** chain of custody
- Human-in-the-loop review gates for sensitive decisions
- Treats time and evidence quality as first-class, not metadata

`Python` · `Mermaid` · `evaluation harness`

---

### [dam-butler-mcp](https://github.com/vnsavitri/dam-butler-mcp) — Breville's first MCP tool, in daily production use
*production · enterprise*

GTM teams across APAC, North America, and EMEA needed daily access to 235K+ brand assets in Brandfolder — but retrieving the right file meant knowing the exact folder taxonomy, which most non-technical users didn't. Built Breville's first MCP-based internal tool: a custom GPT connected to the Brandfolder API via an intent parser and clarification loop.

- Natural language query → intent parser → structured Brandfolder API call
- Clarification loop resolves ambiguous inputs before the API fires
- Prototyped Sep 2025; shipped to production, in daily workflows across APAC, North America, and EMEA — [demo video](https://www.youtube.com/watch?v=UOeHNyh5A7Y)

`MCP` · `Brandfolder API` · `ChatGPT Enterprise` · `Vercel`

---

### [vivid-alpaca](https://github.com/vnsavitri/vivid-alpaca) — multi-agent trading with execution guardrails
*active · safety*

Paper-first multi-agent AI trading lab built on the AlpacaTradingAgent lineage. Execution-layer guardrails sit between agent recommendations and broker order submission.

- Configurable agent mindsets (capital preservation → paper-aggressive training)
- Goal-aware workflows with target return, time horizon, max drawdown
- Live trading gated behind manual approval, journaling, cooldown, replay

`Python` · `Dash` · `Alpaca API` · `multi-agent`

---

### [espresso-horoscope-mcp](https://github.com/vnsavitri/espresso-horoscope-mcp) — local-first MCP, OpenAI hackathon
*shipped · hackathon · ⭐ 3*

Local MCP project that turns espresso shot metrics into a personalized cosmic reading via GPT-OSS through LM Studio. Built for the OpenAI Open Model Hackathon (Best Local Agent category).

- 100% offline — no cloud inference
- Structured sensor data → strict tool/prompt boundary → user artifact
- Six-week deadline, [3-min demo video](https://youtu.be/hHNMkw1NXDE) shipped

`Python` · `Next.js 15` · `LM Studio` · `MCP`

---

### [sourdough-intelligence](https://github.com/vnsavitri/sourdough-intelligence) — pre-LLM data science, live product
*live · [vividcrumb.netlify.app](https://vividcrumb.netlify.app)*

Started in 2018 — before LLMs. Built a two-stage model to find the sourdough recipe with the highest first-time success rate: multiple linear regression across recipe variables + IBM Watson NLP sentiment analysis on 207 recipes and their YouTube comment threads.

- Top-3 shortlist generated → picked one → worked first try
- Now a live scheduling app: bake-time wizard, baker's percentage formula gen, temperature-aware bulk fermentation, printable plans

`R` · `IBM Watson NLP` · `regression`

---

### [Almost](https://github.com/vnsavitri/Almost) — the life you didn't quite live
*shipped · product*

Upload a LinkedIn PDF. Almost finds 3–5 real fork points in your career history. You pick one. It renders the alternate you as a LinkedIn Ghost, Wiki Stub, Museum Plaque, or Tarot Card.

- Built on Anthropic Claude API (`claude-sonnet-4`)
- Claude native document support — no PDF library plumbing
- Four hand-tuned output formats, RevenueCat-gated Pro tier

`Next.js 14` · `Anthropic API` · `Fraunces`

---

## 👷🏽‍♀️ How I build

I use AI where it makes sense, part of the fun is figuring out whether AI would be helpful or slowing me down; especially if it produces slop. Ain't nobody got time to babysit dumb AI agents!

- **Open-source and local AI** — My preference is to always try to use open and local models, choosing for privacy, cost, capability and the job at hand... if possible. Whereas at work, I kinda stuck with closed models from OpenAI or Anthropic (unfortunately). 

- **Agent loops and graph engineering** - I build the harness around agent workflows, with clear state, scoped delegation, useful hand-offs and memory that does not turn into a junk drawer.

- **Human-AI product design** — I try to turn messy real-world work into AI products people can understand, trust and use.

- **Evaluation, evidence and safety** — I test what a system does, keep provenance where it matters, and put review gates around decisions with real consequences.

- **Product direction and delivery** — Moves from problem framing and prototype to a working product, with enough technical depth to make good calls along the way.

---
## 🔭 Currently Building

- AI-guided financial literacy app for next-gen Indonesians *(early beta)*
- AI-native video game development with agentic workflows and multi-agent collaboration
  - Prototyping with Hermes Agent and isolated sub-agents for parallel task execution
  - Running hybrid model workflows across local models and OpenRouter-hosted models, including Qwen 3.x variants
  - Building AI evaluation frameworks for product decision-making
- Learning deeper Python for AI/ML, LLM fine-tuning, and agent orchestration patterns
---

## 🌏 Background

- 🎓 AI Product Management — Duke University (Pratt School of Engineering)
- 🎓 MBA — Steinbeis Hochschule, Berlin *(Thesis: AI-Driven Application for Experience Design)*
- 👩🏻‍🎓 B.A. in Science, Technology, and Society, Stanford University, School of Humanities & Sciences (HCI focus)
- 🌐 Lived and worked in 12 countries across 4 continents
- 🗣️ English · French · Mandarin

---

## 🤝 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vividsavitri/)
[![Discord](https://img.shields.io/badge/Discord-5865F2?style=flat-square&logo=discord&logoColor=white)](https://discord.com/users/VividSydney)
