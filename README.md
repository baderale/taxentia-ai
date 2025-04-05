
<div align="center">

# 🧾 Taxentia.ai  
### _Smarter Tax Intelligence for Professionals_

**Built for CPAs, Tax Attorneys, and Tax Experts**  
Logic-first. Citation-powered. Audit-trail ready.

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Powered by OpenAI](https://img.shields.io/badge/Powered%20by-OpenAI-ff69b4.svg)](https://openai.com)
[![Status](https://img.shields.io/badge/status-building-brightgreen.svg)]()

</div>

---

## 📌 What is Taxentia?

**Taxentia.ai** is a professional-grade SaaS platform designed to help CPAs and tax professionals answer complex IRS code questions with confidence, speed, and citation-backed clarity.

Unlike generic AI chatbots, Taxentia:

✅ Interprets IRS Code, Treasury Regs, IRS Pubs, Rev. Ruls., and case law  
✅ Builds chain-of-reasoning logic for every response  
✅ Cites exact code sections and references (e.g., IRC §195, Pub. 535)  
✅ Displays confidence scores + fallback logic when guidance is unclear  
✅ Supports client-level query tracking, memo generation, and more

---

## 🧠 Key Features

| Feature                          | Description |
|----------------------------------|-------------|
| 🔍 **Tax AI Copilot**            | Ask IRS-related tax law questions and receive cited, step-by-step answers |
| 📚 **Real IRS Sources**          | Ingests IRC Title 26, IRS Pubs, Rev. Ruls., court cases |
| 📈 **Confidence Scoring**        | Every answer includes a visual + numeric confidence rating |
| 📄 **PDF Memo Generator**        | Generate legal-style tax memos (280A, §195, Reasonable Comp) *(Pro/Team)* |
| 🗂️ **Client Folders**           | Save queries by client, case, or scenario *(Team tier)* |
| 🔁 **Auto Updates**              | Regular re-embedding of source materials for compliance |
| 🔐 **User Privacy First**        | No data is sold; built for CPA-grade confidentiality |

---

## 🚧 Roadmap Milestones

- ✅ Ingestion pipeline for IRS content → Pinecone
- ✅ Prompt engine for logic + citations + fallback
- ⏳ n8n search → GPT pipeline (in progress)
- ⏳ Retool UI + Slack/WhatsApp integrations
- ⏳ Stripe billing for Free / Pro / Team tiers
- 🔜 Product Hunt launch

---

## 💼 Who is This For?

> "I don't want a summary. I want the law."

**If you're a:**
- CPA
- Tax Attorney
- EA or Tax Strategist  
👉 Taxentia will streamline your research, improve audit defensibility, and save you hours.

---

## 📂 Repo Structure

```bash
TAXENTIA-AI/
├── taxentia-core/         # Embedding, LLM pipelines, n8n logic
├── taxentia-embeddings/   # Chunking + preprocessing utils
├── taxentia-prompts/      # System + fallback prompt templates
├── taxentia-ui/           # Retool/WeWeb UI components
├── taxentia-docs/         # Roadmap, PRD, onboarding
├── Project Docs/          # Research inputs (IRS, screenshots, etc.)
└── README.md
```

---

## 🧰 Tech Stack

- **OpenAI** – GPT-4 Turbo + Embedding API
- **Pinecone** – Vector DB for tax logic search
- **n8n** – Automation workflows (query → GPT → format)
- **Supabase** – Auth + storage
- **Retool / WeWeb** – Frontend UI
- **PDFMonkey / Placid** – Memo generation
- **Apify** – IRS web scraping & change detection

---

## 👨‍💻 Getting Started

_Coming soon: local setup guide, environment variables, and test scripts._

Stay tuned or watch the repo for updates.

---

## 🧠 License

This project is MIT-licensed. See [LICENSE](LICENSE) for more details.

---

<div align="center">

_"Taxentia is the logic layer between the IRS and the professionals who interpret it."_  
💼 Built for serious practitioners. Designed for clarity. Powered by AI.

</div>
