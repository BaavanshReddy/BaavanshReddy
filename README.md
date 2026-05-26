<h1 align="center">Hey, I'm Baavansh 👋</h1>

<p align="center">
  <b>Backend &amp; AI/ML Engineer</b> &nbsp;•&nbsp; CS @ Rutgers University &nbsp;•&nbsp; Graduating May 2026
</p>

<p align="center">
  <a href="https://baavansh-portfolio.vercel.app">
    <img src="https://img.shields.io/badge/🌐%20Portfolio-baavansh--portfolio.vercel.app-6C63FF?style=for-the-badge" alt="Portfolio"/>
  </a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/baavansh"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white"/></a>
  &nbsp;
  <a href="https://github.com/BaavanshReddy"><img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white"/></a>
  &nbsp;
  <a href="mailto:baavanshreddy@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white"/></a>
</p>

---

I'm wrapping up my Computer Science degree at Rutgers, and most of it has gone into chasing one stubborn question: *what's actually happening underneath?* That curiosity is how I ended up writing a RISC-V CPU in C, building a compiler from the lexer up, and lately, a memory engine that lets AI agents actually remember things between conversations.

What I care about is software that's solid all the way down. Code that holds up when the input is messy, when the network drops, when the happy path isn't the one you get. I'm graduating in **May 2026** (Magna Cum Laude, 3.76 GPA), and I'm looking for **backend or AI/ML engineering roles**. If you're hiring for that, I'd love to talk.

---

### 🧠 What I'm most excited about right now — AgentMemry

Most agent-memory frameworks ask you to stand up Postgres or pay for a cloud vector DB before your agent can remember a single thing. **[AgentMemry](https://github.com/BaavanshReddy/agentmemry) doesn't.** It's a Python library that gives any AI agent persistent, searchable memory using nothing but **SQLite and local embeddings**. No server. No API key. No setup. The entire memory store is a single portable `.db` file you can copy anywhere.

```python
from agentmemry import Memory

mem = Memory()
mem.add("User prefers concise, bullet-point answers")
mem.search("how should I respond?")   # semantic recall, fully local
```

It does semantic search, MMR diversity search, and per-agent isolation out of the box. → **[See AgentMemry on GitHub](https://github.com/BaavanshReddy/agentmemry)**

---

### 🛠 Things I've built

| Project | What it is |
|---|---|
| 🧠 **[agentmemry](https://github.com/BaavanshReddy/agentmemry)** | Local-first memory library for AI agents. SQLite + local embeddings, semantic & MMR search, zero cloud |
| 🌐 **[baavansh-portfolio](https://github.com/BaavanshReddy/baavansh-portfolio)** | My portfolio site with a built-in RAG agent recruiters can *ask questions* of. [Live ↗](https://baavansh-portfolio.vercel.app) |
| 🖥 **[risc-v-simulator](https://github.com/BaavanshReddy/risc-v-simulator)** | Single-cycle RISC-V RV32I CPU in C with a 1 KiB direct-mapped cache and full memory hierarchy |
| ⚙️ **[tinyl-compiler](https://github.com/BaavanshReddy/tinyl-compiler)** | A complete compiler pipeline: lexer, recursive-descent parser, AST, stack-based bytecode generation |
| 🗂 **[linux-filesystem](https://github.com/BaavanshReddy/linux-filesystem)** | Unix-style virtual filesystem in C with inodes, permissions, persistence, and an interactive shell |
| 🔢 **[neural-net-from-scratch](https://github.com/BaavanshReddy/neural-net-from-scratch)** | 3-layer neural net with backprop written by hand — no frameworks, 89% face-recognition accuracy |
| 🔬 **[LLM_factcheck](https://github.com/BaavanshReddy/LLM_factcheck)** | LLM factual-QA evaluation framework. BM25 vs RAG, 11-class error taxonomy, research paper |
| 🕸 **[campus-event-scraper](https://github.com/BaavanshReddy/campus-event-scraper)** | Resilient Python scraper with retry/backoff, data normalization, SQLite, graceful offline fallback |
| 🍕 **[RUPizza](https://github.com/BaavanshReddy/RUPizza)** | Java + JavaFX ordering app built around the Factory pattern and clean OOP design |

---

### ⚙️ Tools I reach for

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=mysql&logoColor=white)

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white)

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=BaavanshReddy&show_icons=true&hide_border=true&theme=transparent" height="150"/>
  &nbsp;
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=BaavanshReddy&layout=compact&hide_border=true&theme=transparent" height="150"/>
</p>

<p align="center">
  <sub>Open to backend &amp; AI/ML roles starting summer 2026. The fastest way to reach me is <a href="mailto:baavanshreddy@gmail.com">email</a>.</sub>
</p>
