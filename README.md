# My Sensory Preferences
### ADHD and Her — Women & Adults Edition

A self-exploration questionnaire for understanding sensory preferences and how they shape nervous system regulation, day to day. Includes personalised tools, tips, and a printable worksheet.

Created by **Shelley L'Green**, Occupational Therapist (AHPRA registered).

---

## About this tool

This is a single-file HTML application — no server, no database, no dependencies. Everything runs in the browser. User responses are never collected, stored, or transmitted anywhere. When the browser tab is closed, all answers are gone unless the worksheet has been printed or saved as a PDF.

Built for women and gender diverse adults 18+ who are ADHD diagnosed, exploring a possible diagnosis, or simply curious about how their sensory system and nervous system work together.

---

## How to deploy

### GitHub Pages (recommended)

1. Rename `my-sensory-preferences-updated.html` to `index.html`
2. Upload to this repository
3. Go to **Settings → Pages → Source → Deploy from branch → main / root**
4. Wait ~60 seconds — your live URL will be `https://yourusername.github.io/repo-name`

### Squarespace

Upload the HTML file to your media library or embed the full file contents in a Code Block on a page. Add the page to **Not Linked** pages to keep it off your navigation.

### Any static host

The file is fully self-contained. Upload `index.html` to any static hosting service (Netlify, Vercel, Cloudflare Pages, etc.) and it will work immediately.

---

## Before you publish

### 1. Update the booking link

Search the file for `YOUR_SPLOSE_BOOKING_LINK` and replace it with your actual booking URL. It appears in the closing section on the Shelley session card.

```
YOUR_SPLOSE_BOOKING_LINK
```

### 2. Review the noindex tag

The file contains `<meta name="robots" content="noindex, nofollow">` which prevents Google from indexing it. This is intentional for testing. When you are ready for the tool to be discoverable, remove or update this tag.

### 3. Copyright year

The footer reads `© 2025 ADHD and Her`. Update the year as needed.

---

## File structure

This is a single HTML file. All CSS, JavaScript, and both logo files are embedded inline — nothing external is required except the Google Fonts import (Abel and Inter), which loads from Google's CDN. The tool will still work without an internet connection but will fall back to system fonts.

```
index.html          — the complete application
README.md           — this file
```

---

## What the tool covers

**Questionnaire** — 8 sensory domains, 4 questions each (32 questions total)

| # | Domain |
|---|--------|
| 1 | Tactile |
| 2 | Auditory |
| 3 | Visual |
| 4 | Smell and taste |
| 5 | Vestibular |
| 6 | Proprioception |
| 7 | Interoception |
| 8 | Social and emotional environment |

**Results** — personalised pattern summary (seeking, sensitive, combined, or typical)

**Education** — Window of Capacity framework + Sensory Processing theory, how they connect, and why sensory input matters for nervous system state

**Tools and tips** — personalised strategy cards across 5 tabs: At home, At work, Relationships, Thinking & beliefs, Hormonal cycle

**Worksheet** — printable/saveable personal sensory toolkit

---

## Frameworks and references

This tool draws on:

- Dunn's Model of Sensory Processing (1997, 2007)
- Ayres' Sensory Integration theory (1972)
- Window of Capacity — Linda Thai's adaptation of Siegel's Window of Tolerance
- Craig (2002) — interoception and physiological regulation
- Mahler (2017) — interoception as the eighth sensory system
- Porges (2011) — polyvagal theory (referenced, not used as primary framework)
- Cortese et al. (2025), Bijlenga et al. (2023) — sensory processing in ADHD
- Quinn & Madhoo (2014), Osianlis et al. (2025) — ADHD, hormones, and women

Full references are available in the collapsible references section at the bottom of the tool.

---

## Customisation notes

### Booking link
Find and replace `YOUR_SPLOSE_BOOKING_LINK` with your Splose or other booking platform URL.

### Logo
Both logos are embedded as base64 SVG directly in the HTML. To update:
- Light logo (cover, dark background): replace the base64 string in the cover `<img>` tag
- Dark logo (disclosure page, light background): replace the base64 string in the disclosure `<img>` tag

### Colours
All brand colours are defined as CSS variables at the top of the `<style>` block:
```css
--navy, --navy-mid, --sage, --blush, --blue-pale, etc.
```

---

## Disclaimers

This tool is for educational and self-exploration purposes only. It is not a clinical assessment and does not replace professional diagnosis, therapeutic support, or medical advice.

Created by Shelley L'Green, Occupational Therapist (AHPRA registered). In line with AHPRA advertising guidelines, no claims are made that this tool will diagnose, treat, or cure any condition.

For full terms see adhdandher.com.au.

---

*ADHD and Her — adhdandher.com.au*
