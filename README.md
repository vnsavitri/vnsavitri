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

## ✨ Featured Work

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

## 🚀 Tech Stack

### Foundation Models & Routing
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Anthropic Claude](https://img.shields.io/badge/Anthropic%20Claude-D97706?style=flat-square&logo=anthropic&logoColor=white)
![OpenRouter](https://img.shields.io/badge/OpenRouter-000000?style=flat-square&logo=openrouter&logoColor=white)
![Hugging Face](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)

### Agentic Systems & Orchestration
![Paperclip](https://img.shields.io/badge/Paperclip-111111?style=flat-square&logo=github&logoColor=white)
![Hermes Agent](https://img.shields.io/badge/Hermes%20Agent-6B21A8?style=flat-square&logo=github&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Multi-Agent Systems](https://img.shields.io/badge/Multi--Agent%20Systems-0F172A?style=flat-square&logo=github&logoColor=white)

### AI Coding Agents & Prototyping
![Cursor](https://img.shields.io/badge/Cursor-000000?style=flat-square&logo=cursor&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude%20Code-D97706?style=flat-square&logo=anthropic&logoColor=white)
![OpenCode](https://img.shields.io/badge/OpenCode-181717?style=flat-square&logo=github&logoColor=white)
![OpenAI Codex](https://img.shields.io/badge/OpenAI%20Codex-412991?style=flat-square&logo=openai&logoColor=white)

### Applied ML, Data & Evaluation
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

### Product, Design & Delivery
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white)
![Notion](https://img.shields.io/badge/Notion-000000?style=flat-square&logo=notion&logoColor=white)
![Miro](https://img.shields.io/badge/Miro-FFD02F?style=flat-square&logo=miro&logoColor=black)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google%20Cloud-4285F4?style=flat-square&logo=google-cloud&logoColor=white)

---
## 🔭 Currently Building

- AI-native video game development with agentic workflows and multi-agent collaboration
  - Prototyping with Hermes Agent and isolated sub-agents for parallel task execution
  - Running hybrid model workflows across local models and OpenRouter-hosted models, including Qwen 3.x variants
  - Building AI evaluation frameworks for product decision-making
- Learning deeper Python for AI/ML, LLM fine-tuning, and agent orchestration patterns
---

## 🌏 Background

- 🎓 HCI & Design — Stanford University
- 🎓 AI Product Management — Duke University (Pratt School of Engineering)
- 🎓 MBA — Steinbeis Hochschule, Berlin *(Thesis: AI-Driven Application for Experience Design)*
- 🌐 Lived and worked in 12 countries across 4 continents
- 🗣️ English · French · Mandarin

---

## 🤝 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vividsavitri/)
[![Discord](https://img.shields.io/badge/Discord-5865F2?style=flat-square&logo=discord&logoColor=white)](https://discord.com/users/VividSydney)
