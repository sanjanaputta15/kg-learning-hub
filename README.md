# Knowledge Graph Learning Hub

A self-contained learning site covering **RDF, Ontology, and OWL** through a hospital drug-safety use case — from beginner concepts to a demo-ready skill set.

## What's inside

### Tab 1 — Medical use case
- The problem (why connected data matters)
- RDF triples with colour-coded examples
- Ontology class hierarchy
- OWL rules and reasoning
- Live SPARQL queries with results
- Interactive 6-step prescription demo
- Three-level explanation guide (exec / technical / architect)

### Tab 2 — Learning checklist
- **Beginner** (Week 1–2): KG fundamentals, RDF triples, ontology vocabulary, OWL basics
- **Intermediate** (Week 3–5): Turtle syntax, OWL design, SPARQL queries, Protégé + Jena + GraphDB
- **Advanced** (Week 6–10): Design patterns, data integration, industrial IoT mapping, demo preparation
- Progress persists in localStorage — tick topics as you complete them
- Each topic expands to show exactly what to learn

## How to host on GitHub Pages

1. Create a new GitHub repository (e.g. `kg-learning-hub`)
2. Upload `index.html` to the root
3. Go to **Settings → Pages → Source → Deploy from branch → main → / (root)**
4. Your site is live at `https://your-username.github.io/kg-learning-hub`

## Local preview

Just open `index.html` in any browser — no server needed.

```bash
open index.html        # macOS
start index.html       # Windows
xdg-open index.html    # Linux
```

## Tech stack

- Pure HTML, CSS, JavaScript — zero dependencies, zero build step
- Progress saved in `localStorage` (browser, per device)
- Works offline

## Use case context

Built to support a knowledge graph demo for oil & gas / manufacturing IoT — the hospital scenario teaches the exact same patterns (RDF triples, ontology hierarchy, OWL inference rules, SPARQL queries) that apply to industrial sensor data, equipment monitoring, and predictive maintenance.

---

*Start at Beginner → tick each topic → reach the Advanced demo checklist → present.*
