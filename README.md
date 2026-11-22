# Nada Ismail — AI Engineering Portfolio

Premium portfolio website for **Nada Ismail**, AI Engineer specializing in **Agentic AI, Multi-Agent Systems, LLM Applications, and AI Automation**.

> Building Intelligent Systems. Solving Real-World Problems.
>
> Open to remote roles and freelance work.

## Live Sections

- **Hero** — Introduction, availability, and an interactive multi-agent workflow diagram
- **About** — Focus on agentic AI, multi-agent systems, LLM applications, and automation
- **Technical Skills** — AI Engineering, Development, and Tools & Infrastructure
- **Featured Projects** — Expandable case studies with architecture flows:
  - AI Operations Manager
  - Multi-Agent RFP Automation System
  - AI Financial Analyst and Forecasting System
  - Enterprise Customer Support Agent
  - Haven & Home AI Strategic Decision System
- **Engineering Approach** — Problem Understanding → Research → Architecture → Development → Integration → Testing → Evaluation
- **Contact** — "Have a Problem Worth Solving?"

## Connect

- LinkedIn: https://www.linkedin.com/in/nadaismail1

## Tech

This is a dependency-free static website: a single self-contained `index.html` with inline CSS and JavaScript. No build step is required, which keeps it fast, easy to maintain, and simple to deploy anywhere.

- Semantic, accessible HTML
- Responsive design (desktop and mobile)
- SEO metadata and Open Graph social sharing tags
- Smooth scrolling, subtle entrance animations, interactive project cards, expandable case studies, and interactive workflow diagrams

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
