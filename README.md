<div align="center">

![Typing SVG](https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=600&size=28&pause=1000&color=00D9FF&center=true&vCenter=true&width=700&lines=Hey+%F0%9F%91%8B%2C+I'm+Nitesh+Yadav;Senior+Frontend+Engineer;Full+Stack+Engineer+(MERN+%2B+Next.js);Full+Stack+%2B+AI+Engineer;Building+products+that+scale)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nitesh-yadav-aa9229268/)
[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/niteshyadavon)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/de__thor__/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:niteshyadavon@gmail.com)
[![Profile Views](https://komarev.com/ghpvc/?username=niteshyadav7&style=for-the-badge&color=0e75b6)](https://github.com/niteshyadav7)

</div>

---

## 🧑‍💻 About Me

> **Senior Frontend / Full Stack + AI Engineer** — ~3 years turning ideas into production systems. I obsess over clean architecture, performance, and shipping things that actually work.

- 🚀 &nbsp; Shipped **end-to-end products** in production — e-commerce with coupon engines, influencer platforms, AI-powered internal tools
- 🤖 &nbsp; Built a **RAG chatbot from first principles** — no LangChain, no abstraction shortcuts — raw Node.js, vector DBs, async queues
- 🏗️ &nbsp; Core stack: **Next.js 14 · React · TypeScript · Node.js · MongoDB · PostgreSQL · Supabase**
- 🧠 &nbsp; Expanding into **AI/GenAI engineering** — RAG pipelines, LLM APIs (OpenAI, Claude), ChromaDB, pgvector, BullMQ
- ⚙️ &nbsp; Also built: **automation scripts**, internal admin panels, mobile apps (React Native/Expo), Firebase push notifications
- 📍 &nbsp; Based in India — open to **Frontend, Full Stack, or Full Stack + AI** roles at product-first startups
- ✉️ &nbsp; Let's talk: **niteshyadavon@gmail.com**

---

## 🏆 Featured Projects

### 🛒 Sharans.in — Full Stack E-Commerce Platform
> End-to-end production e-commerce application with complete frontend & backend

**Tech Stack:** `Next.js 14` `TypeScript` `Node.js` `PostgreSQL` `Tailwind CSS` `Stripe`

- Built complete product listing, cart, checkout, and order management flows
- Implemented **coupon/discount system** — percentage & flat discounts, expiry, usage limits
- Admin dashboard for inventory management, order tracking, and analytics
- Secure payment integration with webhook-based order confirmation
- Optimized for Core Web Vitals — LCP < 2.5s, CLS < 0.1

[![Live Demo](https://img.shields.io/badge/Live-sharans.in-00D9FF?style=flat-square&logo=vercel)](https://sharans.in)

---

### 🎯 1to7media.in — Influencer Marketing Platform
> Replaced Google Sheets + manual ops with a scalable full-stack portal for an influencer agency

**Tech Stack:** `Next.js 14` `TypeScript` `Supabase` `PostgreSQL` `Tailwind CSS` `React Native/Expo`

- Dynamic influencer application forms driven by a **config table** — zero code changes for new campaigns
- Auto-generated **HY10000-format influencer IDs** with custom PostgreSQL sequences
- Built `DiscoverInfluencers` and `ReviewApplicants` modules with advanced filter/search
- **Admin panel** for internal team: manage influencers, track campaign status, bulk operations
- Mobile app (React Native/Expo) for on-the-go influencer review
- Dark, premium UI aesthetic matching agency brand identity

[![Live Demo](https://img.shields.io/badge/Live-1to7media.in-E4405F?style=flat-square&logo=vercel)](https://1to7media.in)

---

### 🤖 RAG Chatbot — Internal AI Assistant (Built from Scratch)
> Production-grade Retrieval-Augmented Generation chatbot — zero LangChain dependency

**Tech Stack:** `Node.js` `ChromaDB` `pgvector` `BullMQ` `Tesseract.js` `OpenAI API`

- Full pipeline: **PDF ingestion → OCR (scanned pages) → chunking → embedding → vector search → LLM response**
- Implemented multiple chunking strategies: fixed-size, semantic, recursive, structural
- Async processing queue with **BullMQ** — handles large document ingestion without blocking
- Hybrid search with **RRF (Reciprocal Rank Fusion)** for improved retrieval accuracy
- Solved `pdf-parse` v2 API edge cases; added per-page statistics extraction
- Admin panel for document upload, chatbot testing, and retrieval debugging

---

### 📊 FundaX — AI-Powered Stock Analysis Platform (FA + TA)
> Institutional-grade stock research tool for Indian equities — combines deep fundamental analysis with technical setups, powered by LLM

**Tech Stack:** `Next.js` `TypeScript` `Python` `Anthropic API` `PostgreSQL` `TradingView` `Pine Script v5`

#### 🔬 Fundamental Analysis Engine
- Custom LLM prompts scoring NSE/BSE stocks on **Debt/EBITDA, FCF, ROE, ROCE, P/E, EV/EBITDA, Promoter Holding**
- Fixed real data integrity bugs — dividend yield unit mismatch, FCF normalization, Debt/EBITDA scaling errors
- Auto-generates structured **FA score reports** with buy / accumulate / hold / exit thesis
- Tracks **promoter pledging trends**, institutional holding changes (DII/FII), and quarterly result momentum
- Filterable stock screener across sectors — FMCG, Banking, IT, Pharma, Auto, Infra

#### 📈 Technical Analysis Module
- **Supply & Demand Zone detection** using GTF (Gann, Trend, Flow) methodology — marks institutional entry/exit levels
- **Option Chain analysis** — PCR tracking, max pain calculation, IV percentile, OI buildup for Nifty 50 & BankNifty
- **Pine Script v5 indicators** — custom GTF zone plotter with trade scoring, auto-invalidation on zone breach
- **Swing trade setups** — identifies high-probability pullback entries using trend + momentum + volume confluence
- **Chartink screener formula** — combines liquidity filters, trend strength, RSI momentum, and demand zone proximity → produces ~20 actionable swing candidates daily
- Nifty/BankNifty expiry analysis — weekly options strategy support (CE/PE selection based on OI data)

#### ⚙️ Platform Features
- Unified dashboard — FA score + TA chart setup side by side for any stock
- Watchlist management with alert triggers on zone retests
- Export reports as PDF for offline review

---

## ⚙️ Tech Stack

### Frontend
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

### Backend & Database
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=flat-square&logo=mongodb&logoColor=white)
![Mongoose](https://img.shields.io/badge/Mongoose-880000?style=flat-square&logo=mongodb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

### AI / GenAI Engineering
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Anthropic](https://img.shields.io/badge/Anthropic_Claude-CC785C?style=flat-square&logo=anthropic&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B35?style=flat-square)
![pgvector](https://img.shields.io/badge/pgvector-316192?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB Atlas](https://img.shields.io/badge/MongoDB_Atlas_Vector-4EA94B?style=flat-square&logo=mongodb&logoColor=white)
![BullMQ](https://img.shields.io/badge/BullMQ-FF0000?style=flat-square&logo=redis&logoColor=white)

### Tools & DevOps
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-0078D4?style=flat-square&logo=visual%20studio%20code&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

### 📉 Trading & Market Analysis
![TradingView](https://img.shields.io/badge/TradingView-131722?style=flat-square&logo=tradingview&logoColor=white)
![Pine Script](https://img.shields.io/badge/Pine_Script_v5-131722?style=flat-square&logo=tradingview&logoColor=00D9FF)
![NSE](https://img.shields.io/badge/NSE%2FBSE-India-FF6B35?style=flat-square)
![Option Chain](https://img.shields.io/badge/Option_Chain_Analysis-4EA94B?style=flat-square)
![Chartink](https://img.shields.io/badge/Chartink_Screener-1DA1F2?style=flat-square)
> I leverage AI-assisted development workflows to ship faster without compromising code quality.

![Cursor](https://img.shields.io/badge/Cursor_AI-000000?style=flat-square&logo=cursor&logoColor=white)
![GitHub Copilot](https://img.shields.io/badge/GitHub_Copilot-000000?style=flat-square&logo=github&logoColor=white)
![OpenAI Codex](https://img.shields.io/badge/OpenAI_Codex-412991?style=flat-square&logo=openai&logoColor=white)
![Anysphere](https://img.shields.io/badge/Antigravity_AI-FF6B35?style=flat-square&logoColor=white)
![Claude](https://img.shields.io/badge/Claude_(Anthropic)-CC785C?style=flat-square&logo=anthropic&logoColor=white)

- 🖱️ &nbsp; **Cursor** — AI-native editor for context-aware code generation, refactoring, and multi-file edits
- 🤖 &nbsp; **GitHub Copilot** — inline completions and chat for rapid boilerplate and pattern-based coding
- ⚡ &nbsp; **OpenAI Codex** — automated code generation and task execution via CLI/API
- 🪐 &nbsp; **Antigravity** — agentic coding workflows for complex, multi-step feature development
- 🧠 &nbsp; **Claude (Anthropic)** — architecture reviews, debugging sessions, and system design reasoning

---

## 📈 GitHub Stats

<div align="center">

![Nitesh's GitHub Stats](https://github-readme-stats.vercel.app/api?username=niteshyadav7&show_icons=true&theme=tokyonight&hide_border=true&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=niteshyadav7&layout=compact&theme=tokyonight&hide_border=true)

[![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=niteshyadav7&theme=tokyonight&hide_border=true)](https://github.com/niteshyadav7)

</div>

---

## 🤝 Open to Opportunities

I'm actively looking for roles in any of these tracks at **product-first startups** (Razorpay, CRED, Groww, Zepto, PhonePe and similar):

| Role | What I bring |
|------|-------------|
| 🎨 **Senior Frontend Engineer** | React internals, Next.js 14, performance optimization, system design |
| 🔧 **Full Stack Engineer** | MERN stack, REST APIs, auth systems, DB design (MongoDB + PostgreSQL) |
| 🤖 **Full Stack + AI Engineer** | RAG pipelines, LLM integration, vector search, async AI workflows |

> I've shipped real production systems — not just side projects. If you're building something that matters, let's connect.

[![LinkedIn](https://img.shields.io/badge/Let's_Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nitesh-yadav-aa9229268/)
[![Email](https://img.shields.io/badge/Send_Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:niteshyadavon@gmail.com)

---

<div align="center">

*Built with focus. Shipped with care.*

![Footer](https://raw.githubusercontent.com/bornmay/bornmay/Update/svg/Bottom.svg)

</div>
