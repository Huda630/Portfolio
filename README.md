# Nada Ismail — AI Engineering Portfolio

Premium portfolio website for **Nada Ismail**, AI Engineer specializing in **Agentic AI, Multi-Agent Systems, LLM Applications, and AI Automation**.

> Building Intelligent Systems. Solving Real-World Problems.
>
> Open to remote roles and freelance work.

## Sections

- **Home** — Introduction and availability, with a single Connect on LinkedIn call to action
- **About** — A concise first-person introduction to her focus and engineering approach
- **Technical Skills** — AI Engineering, Development, and Tools & Infrastructure, presented as badges
- **Portfolio — "Systems in action."** — A featured project with two more revealed on demand, each with a dedicated case study page:
  - **Nova — Enterprise Customer Support & Operations Resolver** (featured) — Python · LangGraph · LangChain · FastAPI · SQLite
  - **AI Operations Manager** — LangChain · LangGraph · OpenRouter · Gmail API · Google Calendar API · Python
  - **AI-Powered RFP Automation** — Pinecone · Embeddings · RAG · Semantic Search
- **Blog — "Thoughts & Insights"** — Editorial-style articles on AI engineering, each with its own page:
  - Why Multi-Agent Systems Beat One Big Prompt
  - RAG, Done Right: Retrieval Is a Gate, Not a Search Box
  - The LLM Should Never Do the Math
  - Designing Agents That Know When to Escalate
  - From Problem to Working System: A 7-Step Engineering Approach
- **Contact** — "Have a Problem Worth Solving?" with a single Connect on LinkedIn button

## Connect

- LinkedIn: https://www.linkedin.com/in/nadaismail1

## Tech

This is a dependency-free static website: a single self-contained `index.html` with inline CSS and JavaScript. No build step is required, which keeps it fast, easy to maintain, and simple to deploy anywhere.

- Semantic, accessible HTML
- Responsive design (desktop, tablet, and mobile)
- SEO metadata, Open Graph tags, and structured data for the blog
- Hash-based routing for blog articles (`#blog/<article>`) and case studies (`#case/<project>`), so every article and case study has its own URL
- Smooth scrolling, subtle entrance animations, and an emerald-on-charcoal premium design system

## Run Locally

Open `index.html` in a browser, or serve the folder:

```bash
npx serve .
# or
python3 -m http.server 8000
```

Then visit http://localhost:8000 (or the port shown).

## Deploy on Vercel

1. Go to https://vercel.com and sign in with GitHub.
2. Click **Add New → Project** and import `Huda630/Portfolio`.
3. Framework Preset: **Other**. Leave Build Command and Output Directory empty — this is a static site with `index.html` at the root. `vercel.json` in this repo already declares this.
4. Click **Deploy**. Vercel will publish the site and give you a public `*.vercel.app` URL.
5. Every future push to the `main` branch redeploys automatically.

## Updating

Edit `index.html` (structure, styles, and scripts are clearly sectioned with comments), commit, and push to `main`. Vercel redeploys automatically.
