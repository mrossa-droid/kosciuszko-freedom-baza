# FREEDOM — Production Base

Production database of **"Freedom"** — the story of Thaddeus Kosciuszko and his fight for
American independence. A fully AI-crafted short film, runtime **17 min 30 s**.

**Live site:** https://freedom-base.creait.me

## Pages

| Page | What's inside |
|---|---|
| [`index.html`](index.html) | Landing page — film overview and entry points |
| [`Kosciuszko_Graph_EN.html`](Kosciuszko_Graph_EN.html) | **Interactive dependency graph** — character map (portraits + labelled relationships) and the full production graph: 120 nodes / 221 edges with filters and search; nodes stay where you drop them |
| [`Kosciuszko_Timeline_EN.html`](Kosciuszko_Timeline_EN.html) | **Vertical timeline with a narrative map** — character lanes, 16 scene cards in 3 acts, history 1746–1817, themes, music cue sheet M1–M10, AI reference statuses |
| [`credits.html`](credits.html) | **Credits** — full cast & crew of the film |

All pages are self-contained (the graph library and face thumbnails are embedded) — they also
work offline, straight from disk.

The Polish working files (`Kosciuszko_Baza_Zaleznosci.html`, `Kosciuszko_Graf_Zaleznosci.html`)
are kept in the repo but are not linked from the site.

## Contents of the base

- **12 characters** — recasting canon with NOT sections and key lines
- **16 scenes** per the "Freedom" screenplay (scene timecodes follow the 10-minute structural plan; final cut runs 17:30)
- **40 Seedance sequences** (SEQ ↔ scene mapping)
- **8 themes** (the Declaration, conscience/slavery, the will as a frame, engineer not warrior, the value of life, the flame, humility, the ocean)
- **music cue sheet M1–M10** ("The Flame" concept, D minor → D major)
- **Higgsfield references** — media/job IDs with production statuses

## Updating the data

Data lives in JavaScript constants at the top of each page's `<script>` section:
timeline → `POSTACIE / SCENY / WATKI / MUZYKA / REFERENCJE / HISTORIA / TORY / KOLOR_POSTACI`;
graph → `NODES / EDGES / SEQS / RELACJE / PORTRETY`.

---

A James Drake Media & Creait.Me Production · © 2026
