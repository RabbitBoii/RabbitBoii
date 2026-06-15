<div align="center">
  <h1>Hey, I'm Chetan 👋</h1>
  <p>I build AI-powered fullstack apps — RAG pipelines, LLM integrations, and the interfaces around them.</p>
  <p>IIT Roorkee '26 · M.Sc. Mathematics & Computing · Based in India</p>
  <br/>
  <a href="https://www.linkedin.com/in/chetan-atram/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:chetanatram11284@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
</div>

---

## 🛠️ What I'm building

Right now I'm focused on the intersection of LLMs and real products — not just calling APIs, but building the retrieval layers, streaming pipelines, and UIs that make AI actually usable.

- 🔍 RAG pipelines with semantic search (Pinecone, ChromaDB, vector embeddings)
- ⚡ Real-time LLM streaming with SSE and FastAPI
- 🧩 VS Code extensions, fullstack Next.js apps, and AI-native tooling

---

## 🚀 Featured Projects

### [CoverCraft](https://coverizer.vercel.app/) — AI Cover Letter Generator
> React · FastAPI · Pinecone · Groq · SSE Streaming

Built an AI-powered cover letter generator that does semantic search over your past applications to generate contextually relevant letters. Real-time streaming via SSE, dual-storage architecture with SQLite + Pinecone vector DB, deployed on Render + Vercel.

**The interesting part:** migrated from local ChromaDB + Ollama to cloud-native Pinecone + HuggingFace embeddings — learned a lot about embedding model tradeoffs in production.

---

### [Codebase Chat](https://github.com/RabbitBoii/codebase-chat) — Chat with your codebase in VS Code
> VS Code Extension · Ollama · Groq · Llama 3

A VS Code extension that lets you query your entire local codebase in natural language. Built a RAG pipeline with local embedding generation (nomic-embed-text) and pure JS cosine similarity — no native dependencies, works completely offline for full code privacy.

**The interesting part:** replaced HNSWLib with a custom cosine-similarity engine to eliminate native build issues. Sometimes the simple solution is the right one.

---

### [Habit AI](https://habit-tracker-rabbitboii-42.vercel.app/) — AI Project Management
> Next.js 14 · tRPC · TypeScript · Groq · Llama 3.3

Fullstack project management platform where you describe a goal and Llama 3.3 generates a structured project plan with tasks. Kanban board with optimistic UI updates, progress visualizations, end-to-end typesafe with tRPC.

---

## 🧰 Tech Stack

**Frontend:** Next.js · React · TypeScript · Tailwind CSS · Shadcn UI

**Backend:** FastAPI · Node.js · Express · tRPC · Prisma

**AI / LLM:** LangChain · Embeddings · Groq · Ollama · Pinecone · ChromaDB · RAG Pipelines 

**Databases:** PostgreSQL · SQLite · MongoDB · Firebase 

**Tools:** Git · Vercel · Render

---

## 📌 A bit about me

I'm a Math & Computing grad from IIT Roorkee who got deep into fullstack and then deeper into AI engineering. I like building things that are actually useful — tools I'd use myself, with architecture decisions I can explain.

Currently targeting **AI engineer / fullstack roles** at startups. If you're building something interesting, [let's talk](mailto:chetanatram11284@gmail.com).

---

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=RabbitBoii&show_icons=true&theme=tokyonight&hide_border=true" height="150"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=RabbitBoii&layout=compact&theme=tokyonight&hide_border=true" height="150"/>
</div>
