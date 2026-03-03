# Sprint Bot Project
This project lives at https://github.com/emagarotto/Sprint-Bot (code is private).

# SprintBot — AI-Powered UX Agents

A platform offering 24 production-ready AI agents that automate the entire UX/UCD process from discovery through validation. Users choose from plug-and-play Claude Skills, Gemini Gems, or ChatGPTs.

**Phases 1-7 Complete | 24 Agents | Production Ready**

## Tech Stack

- **React 18** + **TypeScript** + **Vite**
- **Tailwind CSS** + **shadcn/ui**
- **Framer Motion** for animations
- **React Router** for client-side routing

## Getting Started

```bash
# Install dependencies
npm install

# Start dev server
npm run dev
```

## Pages

| Route | Description |
|---|---|
| `/` | Landing page with hero, stats, how-it-works, categories, testimonials, pricing preview |
| `/agents` | Full agent directory with search, phase filters, and pricing plans |
| `/agents/:id` | Individual agent detail with prompts for ChatGPT, Claude, and Gemini |
| `/pricing` | Pricing page |
| `/how-it-works` | Process overview |
| `/about` | About page |

## 📦 Complete Agent Library (24 Agents)

### Phase 1: Discovery (3 agents)
1. **Stakeholder Interview Agent** — AI-powered stakeholder interviews with goal extraction
2. **Competitive Analysis Agent** — Market landscape and competitive feature analysis
3. **Research Planning Agent** — Research methodology selection and plan generation

### Phase 2: Research Execution (4 agents)
4. **User Interview Conductor** — Simulated user interviews with theme extraction
5. **Usability Testing Agent** — Task-based testing with SUS scores
6. **Survey Agent** — Survey deployment and statistical analysis
7. **Field Study Agent** — Contextual inquiry and environmental analysis

### Phase 3: Analysis & Synthesis (4 agents)
8. **Qualitative Analyzer Agent** — Thematic analysis and affinity mapping
9. **Quantitative Data Processor** — Statistical analysis and metrics
10. **Persona Generator** — User segmentation and persona creation
11. **Journey Mapper** — Customer journey mapping

### Phase 4: Definition (4 agents)
12. **Problem Framing Agent** — Problem statement generation
13. **Information Architecture Agent** — Site structure and navigation design
14. **Requirements Documentation Agent** — Functional and technical requirements
15. **Feature Prioritization Agent** — RICE/MoSCoW scoring and roadmaps

### Phase 5: Ideation (2 agents)
16. **Concept Development Agent** — Ideation facilitation and concept generation
17. **Concept Evaluation Agent** — Concept scoring and feasibility assessment

### Phase 6: Design Production (5 agents)
18. **Wireframing Agent** — Low-fidelity wireframe generation
19. **Prototyping Agent** — Interactive prototype specifications
20. **Visual Design Agent** — High-fidelity mockup creation
21. **Design System Agent** — Component libraries and style guides
22. **Content Strategy Agent** — Content hierarchy and messaging

### Phase 7: Validation (2 agents)
23. **Usability Testing Planner** — Test plan and scenario development
24. **Design Refinement Agent** — Issue prioritization and iteration planning

## 💰 Pricing Tiers

| Plan | Agents | Price |
|---|---|---|
| **Free** | 5 essential agents | $0 forever |
| **Pro** | 15 agents (5 free + 10 more) | $195 one-time |
| **Enterprise** | All 24 agents + priority support | $899 one-time |

## Agent Data

All 24 agents are defined in `src/data/agents.ts` with prompts for three AI platforms (ChatGPT, Claude, Gemini). A script at `scripts/export-prompts.ts` can export all prompts to text files.

## Project Structure

```
src/
├── components/       # Navbar, Footer, AgentCard, UI components
├── data/             # Agent definitions and metadata
├── pages/            # Route-level page components
├── hooks/            # Custom React hooks
├── lib/              # Utilities
└── index.css         # Design system tokens and global styles
```

## 🎯 Key Highlights

- **99.99% cost reduction** — $0 vs $50,000+ traditional UX process
- **2000x faster** — Minutes instead of months
- **3 AI platforms** — ChatGPT, Claude, and Gemini prompts included
- **Complete UX coverage** — All 7 phases of user-centered design

## License

MIT
