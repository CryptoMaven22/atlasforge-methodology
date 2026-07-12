# AtlasForge

AtlasForge is the practical product-development methodology used by Atlas Studios to turn operational ambiguity into validated, buildable products.

This repository contains the public-facing AtlasForge methodology site, including the customer narrative, lifecycle pathway, artifact system, and supporting product-development principles.

## What AtlasForge Does

AtlasForge helps teams move from a real operational problem to a decision-ready product and delivery path by:

- starting with the actual work before selecting technology
- grounding decisions in workflow evidence and representative scenarios
- defining the smallest credible path to prove value
- keeping human judgment, review, and accountability visible
- translating validated learning into requirements, architecture, governance, and delivery planning

## Core Principles

### Start with the work

Understand the workflow, actors, inputs, handoffs, decisions, exceptions, and risks before designing the solution.

### Prove the smallest credible path

Use a focused steel thread, representative scenarios, and clear validation criteria to control scope and avoid premature expansion.

### Keep authority visible

Separate product assistance from human judgment, approval, and final accountability.

## AtlasForge Lifecycle

1. Engagement Intake and Qualification
2. Discovery and Evidence
3. Current-State / Future-State Operating Model
4. Capability and Requirements Definition
5. Prototype and Validation
6. Architecture and Delivery Planning
7. Governance, Decisions, Risks, and Change Control
8. Closeout, Recommendation, and Handoff

## Repository Structure

```text
.
├── index.html
└── README.md
```

The current site is a self-contained static HTML experience and can be deployed directly through GitHub Pages, Vercel, Netlify, or any static hosting provider.

## Run Locally

Open `index.html` directly in a browser, or serve the folder locally:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Deployment

### GitHub Pages

1. Push the repository to GitHub.
2. Open **Settings → Pages**.
3. Choose **Deploy from a branch**.
4. Select the `main` branch and `/root` folder.
5. Save.

### Vercel

1. Import the repository into Vercel.
2. Select **Other** or **Static Site** as the framework preset.
3. Leave the build command empty.
4. Use the repository root as the output directory.
5. Deploy.

## About Atlas Studios

Atlas Studios designs and builds intelligent operating environments.

AtlasForge is how we build. AtlasFlow is what the products run on.

## Status

This repository currently represents the public methodology overview and may evolve as additional examples, artifacts, and interactive content are added.

## License

Copyright © Atlas Studios. All rights reserved.
