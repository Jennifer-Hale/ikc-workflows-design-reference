# Workflows Design Reference

Living design reference for the IBM Cloud Pak for Data (CPD) Workflows squad. Built with Carbon Design System styling.

## Structure

Organized like our Box folder system, numbered sections with lettered sub-items:

```
workflows-design-reference/
├── index.html              ← Home: hero, stats, tile navigation
├── onboarding.html         ← 01: What is a workflow, types, users, Flowable, playbacks
├── releases.html           ← 02: Release timeline (5.4 → 3.5)
├── resources.html          ← 03: Figma, Mural, Airtable, recordings, docs
├── competitive.html        ← 04: April 2025 competitive study
├── team.html               ← 05: Roster, meetings, Slack channels
├── css/
│   └── style.css           ← Carbon v11 inspired tokens and components
├── assets/                 ← Add images/screenshots as needed
└── README.md
```

## Design

- Carbon Design System v11 color tokens (Gray 10 / White theme)
- IBM Plex Sans + IBM Plex Mono typography
- Carbon UI shell header, side navigation, tiles, structured lists, tags, notifications
- Responsive: sidebar collapses to horizontal nav on mobile

## Setup

Static site, no build step. Open `index.html` locally or host via GitHub Pages:

1. Push to GitHub
2. **Settings → Pages → Deploy from branch → main / root**
3. Live at `https://<org>.github.io/workflows-design-reference/`

## Updating links

All external links use `href="#"` as placeholders. Search and replace with actual URLs:

```bash
grep -rn 'href="#"' *.html
```

## File naming convention

Following team standard: `YYYY-MM-DD-Name.ext` (e.g., `2023-02-12-ExampleName.doc`)

## Maintained by

Workflows Design Squad — IBM Cloud Pak for Data
