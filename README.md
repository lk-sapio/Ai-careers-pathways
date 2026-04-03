# AI Careers Pathways

An interactive online experience for teenagers exploring how AI is affecting careers, jobs, qualifications, training routes, and future opportunities.

This project was designed for 15–16 year old pupils and is intended to take about 15 minutes to complete. It is structured, classroom-friendly, and grounded in recent evidence from reputable international and UK sources.

## Purpose

The experience helps pupils:
- understand that AI changes tasks inside jobs, not only whole occupations
- compare which sectors are more or less exposed to AI
- see where growth is happening in the wider economy
- recognise that opportunity is not only in software or "tech jobs"
- explore different routes in, including apprenticeships, FE, and degree pathways
- think more carefully and realistically about future careers without either hype or panic

## Audience

- UK secondary pupils aged 15–16
- teachers, careers leaders, school leaders, and education consultants

## Core design principles

- academically credible
- no login
- no user data collection
- no analytics
- no chatbot or open text input
- structured interaction only
- scaffolded in stages
- suitable for classroom use
- built to encourage judgement, comparison, and reflection

## Format

This is a static single-page web app.

Main file:
- `index.html`

There is no backend and no build process required.

## Stage structure

The experience currently includes:

- Stage 1: Then, Now, Next
  - generational change in qualifications, digital life, and labour-market context
- Stage 2: What does AI actually do to jobs?
  - matching tasks, myth/fact/uncertain judgements
- Stage 3: Exposure, Risk & Opportunity
  - sector judgement with slider placement and evidence feedback
- Stage 4: Where Is Opportunity Growing?
  - interests + priorities combined into one pathway exploration activity
- Stage 5: New Jobs, Changed Jobs
  - job classification, role guessing, and transferable-vs-specialist skills
- Stage 6: Reality Check
  - provocations with prediction and evidence reveal

## Sources

The content is grounded in evidence from sources including:

- World Economic Forum, Future of Jobs Report 2025
- International Labour Organization, Working Paper 96 on generative AI and jobs
- International Monetary Fund, labour-market exposure to AI and complementarity
- OECD reports on AI skill demand and changing labour-market skills
- UK Government Assessment of Priority Skills to 2030
- UK Government Occupations in Demand 2025
- UK Government AI Skills for Life and Work reports
- ONS education and internet-use statistics
- LinkedIn Jobs on the Rise 2025 UK

## Educational approach

The experience uses:
- prediction before reveal
- matching and sorting
- comparative judgement
- multiple choice reasoning
- evidence reveal with feedback
- metacognitive reflection

The intention is not simply to inform pupils, but to make them think.

## Privacy and safeguarding

This project:
- stores no personal data
- uses no cookies or analytics
- has no account creation
- has no free text box
- has no open-ended AI interaction

All interaction is local to the page session.

## Running locally

Because this is a static site, you can open `index.html` directly in a browser.

If you want to run it through a simple local server, for example:

```bash
python3 -m http.server 4173
```

Then visit:

```text
http://localhost:4173
```

## Repository contents

- `index.html` — complete interactive experience
- `README.md` — project overview and usage notes

## Notes for adaptation

If you want to adapt this project for another audience or school context, likely places to edit are:
- stage wording and instructional text
- sector and job examples
- evidence summaries and source set
- stage ordering or timing
- visual design tokens in the CSS section

## Suggested next steps

Possible future improvements:
- add GitHub Pages deployment
- add teacher notes or facilitation guide
- create a printable worksheet companion
- produce a school-branded version
- add a lightweight citations panel per stage
- refine language further for a specific school or region

## Licence

This project is licensed under:
- CC BY-NC-ND 4.0

That means others may copy and share the work with attribution, but they may not use it commercially and may not distribute adapted versions.

The copyright holder may still use the work commercially, including as part of a paid course or consultancy offering.

Full licence text is included in the `LICENSE` file.
