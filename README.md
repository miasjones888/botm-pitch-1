# botm-pitch-1

Working repository for the Marginalia pitch to Book of the Month's Creator-in-Residence Program.

Contains the full design system, all sprint artifacts, and source materials for the pitch. The repo serves two purposes — primary upload for Claude Design ingestion, and source-of-truth for the BOTM submission sprint.

---

## What this is

**Marginalia** is a working title for a monthly collage-essay on the interior life of reading — a film + companion printed essay-object + three short cuts per piece. The pitch positions it as Volume-Ø adjacent in publishing register, tied specifically to BOTM's literary fiction lane.

**Sample episode:** *Lost Lambs* by Madeline Cash (BOTM Jan 2026).

**Target submission date:** Thursday, April 23, 2026.

**Application:** [bookofthemonth.applytojob.com/apply/LrtX5jNEpR](https://bookofthemonth.applytojob.com/apply/LrtX5jNEpR/Creator-InResidence-Program)

---

## Repo structure

```
botm-pitch-1/
├── README.md                          ← you are here
├── .gitignore
│
├── design-system/                     ← upload this folder to Claude Design
│   ├── visual-language-foundation.html    primary brand bible
│   ├── botm-design-system.html            code/token reference
│   ├── botm-deck-mockups.html             finished example · digital
│   └── marginalia-zine-brief.html         finished example · print
│
├── project/                           ← project management documents
│   ├── botm-pitch-comprehensive-plan.html source-of-truth, locked decisions
│   ├── botm-pitch-sprint.html             48-hour execution sprint
│   └── claude-design-intake-guide.html    field-by-field intake instructions
│
├── archive/                           ← superseded but kept for reference
│   └── botm-pitch-plan.html              original plan, replaced by comprehensive plan
│
└── source-materials/                  ← original project research and notes
    ├── 01_PROJECT-PLAN.html
    ├── 02_BEATS-AND-LINES.md
    ├── 03_DEEP-ANNOTATION.md
    ├── 03_ANNOTATEDPDF.pdf
    ├── 04_AESTHETIC-AND-ZINE-DIRECTION.md
    ├── 05_OPERATIONS-TOOLKIT.md
    ├── 06_SESSION-LOG-TEMPLATE.md
    └── 07_SOURCESANDLINEAGE.pdf
```

---

## How to use this repo

### For Claude Design ingestion

Open [`project/claude-design-intake-guide.html`](project/claude-design-intake-guide.html) in a browser. It walks through the Claude Design intake form field by field, with copy-paste ready text for the text fields and explicit instructions for the upload fields.

When the intake guide says "drag the folder," upload the `design-system/` folder from this repo. That folder contains the four HTML files Claude Design will extract the visual language from.

### For project continuity

Open [`project/botm-pitch-comprehensive-plan.html`](project/botm-pitch-comprehensive-plan.html) in a browser. It contains:

- Current state of every workstream
- All locked design decisions (do not relitigate)
- Remaining work for Thursday submission
- Handoff protocol for new chat sessions

If picking up the work in a fresh Claude conversation, point the new chat at this file first.

### For sprint execution

Open [`project/botm-pitch-sprint.html`](project/botm-pitch-sprint.html). Block 4 contains pre-drafted budget copy ready to paste into Field 4 of the BOTM application.

---

## What's done, what's pending

### Done — design phase complete

- **Strategic context** locked (BOTM lane, Volume 0 alignment, audience cluster, sample book)
- **Concept** locked (Marginalia, monthly, film + zine + 3 cuts, one piece first)
- **Visual language foundation** built (primary brand bible)
- **Design system v2** documented (typography, color, tokens)
- **Deck mockups v4** locked (5 slides, postcard close on slide 5)
- **Zine design brief** locked (8 spreads — 6 quiet + 2 earned-dense)
- **Comprehensive plan** built (project source-of-truth)

### Pending — writing + production

- **Field 3 pitch text** — the actual writing BOTM will read (~250-400 words). Most important remaining work.
- **Source images** — atmospheric image for deck slide 1, four drift-movement images for slide 3
- **Canva deck build** — translate v4 mockups into editable Canva deck
- **Application fill + submit** — five fields, attach deck PDF

### Deferred — not Thursday-blocking

- **Film sensibility brief** — held until BOTM responds. Building before their input would preempt work that should happen with their feedback.

---

## The visual language at a glance

**Color:** cream ground (#FAF6ED), ink type (#1C1C1A), dusty navy as second voice (#3E4A66), soft lavender as accent used at most once per artifact (#A89DBD). No pure white. No pure black. No forest green as primary.

**Typography:** General Sans (Fontshare, primary), IBM Plex Mono (metadata), Reenie Beanie (handwriting, used exactly once per artifact). No serifs. Ever.

**Composition:** white space is the design. One precious thing per page. Real photography treated to halftone or duotone, placed at modest scale on cream — never collaged with tape, rotation, or overlap. Generous margins. Single-image-per-page chapbook restraint.

**Voice:** intellectually serious, humanly warm. Direct, considered, with breath. Reads as small literary monograph. Not cozy. Not lifestyle. Not Kinfolk. Not flatlay.

For the complete specification, open [`design-system/visual-language-foundation.html`](design-system/visual-language-foundation.html).

---

## Locked decisions — do not relitigate

These are decided. Future iterations should not re-debate them.

- **Concept** — Marginalia as monthly collage-essay. Film + zine + 3 short cuts. Pitch is for one piece first.
- **Sample book** — Lost Lambs by Madeline Cash, BOTM January 2026.
- **Typography** — General Sans + IBM Plex Mono + Reenie Beanie. No serifs. No Caveat.
- **Color** — Cream + ink + navy + lavender accent. No forest green as primary.
- **Deck slide 5** — Postcard close. Not the minimal alternative.
- **Zine register** — Chapbook restraint, not busy collage. White space is the design.
- **Zine hand element** — Used exactly once per publication (colophon signature only).
- **Document chrome** — For new docs: light grey/white. Brand colors confined to inside contained surfaces.
- **Centennial framing** — Dropped as primary. Light context only. One-piece-first pitch.
- **Wordmark** — TBD until project name is finalized. Visual language exists independent of wordmark.

---

## Working with this repo in a new Claude chat

If continuing the work in a fresh conversation, do this:

1. Share the GitHub URL: `https://github.com/miasjones888/botm-pitch-1`
2. Point Claude at `project/botm-pitch-comprehensive-plan.html` first
3. Then `design-system/visual-language-foundation.html` for visual context
4. Then whichever specific file relates to the immediate task

The comprehensive plan contains a "handoff protocol" section that gives a new Claude instance everything it needs to pick up where the work left off — including the full list of locked decisions, voice and tone preferences, and instructions for drafting Field 3.

---

## Notes for future iteration

- The visual language foundation is named after Mia (not after the project) so it can carry forward to other projects beyond BOTM. When new projects launch, they inherit this foundation and add their own wordmark layer on top.
- The "M." monogram appearing in lavender postage stamps is a one-off use specific to current pitch work — not a standalone brand mark. Do not extract or reuse it as a logo.
- When the publication name is finalized, Section VIII of the visual language foundation gets built (logotype, monogram variants, clear-space rules) and the foundation gets re-uploaded to Claude Design via the Remix interface.

---

*Built with Claude. April 2026.*
