# 3DVIZ — SketchUp & Rhino to Twinmotion 2026

A complete bilingual (EN/FR) production manual for architectural visualisation, written for design studio students in years 2 and 3.

### 📖 **[Read it online → urbandronedesign.github.io/3DVIZ](https://urbandronedesign.github.io/3DVIZ/)**

That is the link to give students — no download, no install, works on a phone.

### ⌨️ **[Commands & shortcuts →](https://urbandronedesign.github.io/3DVIZ/commands.html)**

A companion reference page: every key and command the course uses in SketchUp, Rhino 3D and Twinmotion, taken from the official documentation and linked back to it. Also arranged by task, so you can look up "check face orientation" rather than hunting for a key.

To use it offline instead, download **[`twinmotion_2026_manual-v6.html`](twinmotion_2026_manual-v6.html)** and open it in any browser. One self-contained file, ~430 KB, no build step and no dependencies. It works from a USB key with no internet connection.

---

## What's in it

14 chapters following the actual order of production — set up, model, export, import, light, render — plus a reference section.

| Part | Chapters |
|---|---|
| **I — Foundations** | The pipeline end to end · **The project folder** · SketchUp model hygiene · Rhino NURBS, SubD & meshing |
| **II — Getting in** | Exporting `.skp` and `.glb` · Import options decoded · Materials & PBR |
| **III — Light** | Choosing a render engine · Exterior lighting & HDRI · Interior lighting & light leaks |
| **IV — Output** | Cameras & composition · Stills & the Path Tracer · Video & animation · Panoramas, VR & delivery |
| **Reference** | 95-entry student FAQ · 41-symptom troubleshooting index · 56-term bilingual glossary |

Roughly 66,000 words across both languages.

Chapter 1 opens with a full-page schema of the whole pipeline — seven stages, the decisions belonging to each, and the return path showing that a fault noticed downstream was made upstream. The project folder is drawn as the container around all of it, because a project that is not portable is not really a project.

## Features

- **Bilingual** — EN/FR toggle, remembered between visits
- **Client-side search** across chapters, FAQ and the troubleshooting index
- **Y2 / Y3 level filter** so second-years can hide the advanced material
- **Symptom → fix index** organised by what you see on screen, not by chapter
- **Print stylesheet** — prints or exports to PDF cleanly, with sensible page breaks
- **Responsive** — works on a phone at 1 a.m. the night before a crit

## The course structure

The manual runs on **one project**, carried through 13 stages. Students submit three things:

| | Deliverable |
|---|---|
| **A** | The 3D model — saved natively from SketchUp (`.skp`) and Rhino 3D (`.3dm`) |
| **B** | Five rendered still images, composed as one argument |
| **C** | A 60–90 second video sharing the stills' lighting and cameras |

Because the native model is submitted, the modelling-hygiene chapters are directly assessed rather than being preparation for something else.

## Figures

Eight figures are **drawn diagrams** — inline SVG in both languages, needing nothing from you. They cover the things a screenshot explains badly: why light rounds a zero-thickness wall, what tessellation costs in triangles, what `Collapse all` does to the scene graph, why parallelism matters.

Eleven more are **photographs** that cannot be drawn — six interface captures and five comparisons from a real project. See **[CAPTURE-GUIDE.md](CAPTURE-GUIDE.md)** for click-by-click instructions.

Until a file exists, that figure is **hidden from readers**, so the manual never looks unfinished. To see what is still missing, add `?figures` to the URL:

```
https://urbandronedesign.github.io/3DVIZ/twinmotion_2026_manual-v6.html?figures
```

## A note on the writing

The manual is written **for students, not about them.** It is addressed to the reader in the second person throughout and contains no instructions to a tutor, no assessment-setting advice, and no marking commentary — students have access to this document, so anything that would only make sense to whoever is teaching lives outside it, in [CAPTURE-GUIDE.md](CAPTURE-GUIDE.md).

Two conventions carry the difference between fact and opinion:

- **Documented** — verified against official Epic Games, Trimble or McNeel documentation
- **Studio practice** — craft and judgement, which a student is invited to argue with

## Accuracy

Technical claims are marked in the text:

- **Documented** — verified against official Epic Games, Trimble or McNeel documentation
- **Studio practice** — craft and judgement, not specification

Several widely-repeated claims about this pipeline turn out not to be documented anywhere — minimum wall thicknesses quoted as engine requirements, hard limits on group nesting, a "Dev Tools" menu that does not exist. Where the manual contradicts common advice it says so, and says what the documentation actually supports.

Twinmotion changes yearly. Where the manual and your copy of the software disagree about a menu path, trust the software and check the current documentation.

## Licence

No licence has been chosen yet. Until one is added, default copyright applies — the material is readable here but not licensed for reuse.
