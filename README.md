# CirqHub — a four-day hackathon delivery

**A project-management case study.** CirqHub is an AI-driven circular-economy platform for physical market vendors: what to do with unsold surplus (donate, barter, reuse), recipe ideas for it, and capacity forecasting for staffing and layout.

**[Live demo](https://cirqhub.base44.app)** · **[Full case study](https://arielzin33-creator.github.io/#project-1)** · Built on Base44, so the application code lives on that platform; this repository documents how the project was run.

![CirqHub](https://arielzin33-creator.github.io/assets/projects/project-1.jpg)

## The problem

Vendors need a fast, safe decision about surplus before it goes to waste, and a view of the day ahead. The constraint: **four days, a team, and a working demo at the end.**

## Scope & plan

- Specification before implementation: **MRD, PRD, system architecture, database schema and REST API design**.
- The four days planned **day by day** against a fixed deliverable list of **eight-plus artifacts**, from market research to pitch deck, so the team always knew what "done today" meant.

## My role

Team member owning planning and the spec: co-designed the architecture and the two AI decision engines, directed the AI-assisted implementation against the spec, and ran QA and code review before sign-off.

## Key decision & risk

An AI recommending what to do with food is a safety risk, so the controls were written **into the specification** rather than left to the build:

- deterministic calculations kept separate from LLM-generated text
- a database-enforced allow-list of **12 external data sources**
- hard-coded food-safety rules

QA then checked each control against the spec before sign-off.

## Outcome

Delivered **on schedule**: all eight-plus artifacts and a working end-to-end demo, with vendor decisions, the operator capacity view and offline/online sync functioning together.

---

Ariel Zinger · Technical Project Manager · AI · [Portfolio](https://arielzin33-creator.github.io) · [LinkedIn](https://www.linkedin.com/in/ariel-zinger-1067936b/)
