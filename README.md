# AI Sprint Studio

**Ship a working AI feature in two weeks.**

AI Sprint Studio helps funded startups scope and build one focused AI capability — for their product or internal workflows — then hand it off working. No hiring cycle, no consulting retainer, no six-month roadmap.

Live site: [AI Sprint Studio](https://srikathyayani-s.github.io/ai-sprint-studio-demand/)

---

## What It Is

A single-page marketing and demand-generation site for AI Sprint Studio, a service that delivers rapid AI feature sprints to founder-led teams.

The page covers:

- **What We Do** — focused AI capability delivery in 1–2 weeks
- **Sprint Types** — Website Rebranding, Media Extraction Pipelines, AI Feature Prototypes
- **Sprint Deliverables** — working prototype + technical handoff + founder decision
- **Why Us** — fast execution, low-risk adoption, senior technical expertise
- **How It Works** — Discovery Call → Sprint Definition → Rapid Implementation → Handoff
- **About Us** — team background (Intel, AMD, Microsoft, and others)
- **Contact / Book a Call** — interest form + Calendly booking link

---

## Tech Stack

- Pure HTML/CSS/JavaScript — no build step, no framework
- Google Fonts: Newsreader, Manrope, JetBrains Mono
- Light/dark theme toggle (persisted via `localStorage`)
- Contact form opens the user's mail client (`mailto:`)
- Deployed via GitHub Pages

---

## Local Development

No build step required. Open `index.html` directly in a browser:

```bash
open index.html        # macOS
start index.html       # Windows
xdg-open index.html    # Linux
```

Or serve it locally:

```bash
npx serve .
# then visit http://localhost:3000
```

---

## Deployment

The site deploys automatically to GitHub Pages from the `main` branch. Push to `main` to publish.

---

## Contact

Interested in a sprint? [Book a free discovery call](https://calendly.com/srikathyayani-srikanteswara/30min).
