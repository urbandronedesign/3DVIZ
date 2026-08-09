# 3DVIZ — SketchUp & Rhino to Twinmotion 2026

A complete bilingual (EN/FR) production manual for architectural visualisation, written for design studio students in years 2 and 3.

### 📖 **[Read it online → urbandronedesign.github.io/3DVIZ](https://urbandronedesign.github.io/3DVIZ/)**

That is the link to give students — no download, no install, works on a phone.

To use it offline instead, download **[`twinmotion_2026_manual-v6.html`](twinmotion_2026_manual-v6.html)** and open it in any browser. One self-contained file, ~430 KB, no build step and no dependencies. It works from a USB key with no internet connection.

---

## What's in it

13 chapters following the actual order of production — model, export, import, light, render — plus a reference section.

| Part | Chapters |
|---|---|
| **I — Foundations** | The pipeline end to end · SketchUp model hygiene · Rhino NURBS, SubD & meshing |
| **II — Getting in** | Exporting `.skp` and `.glb` · Import options decoded · Materials & PBR |
| **III — Light** | Choosing a render engine · Exterior lighting & HDRI · Interior lighting & light leaks |
| **IV — Output** | Cameras & composition · Stills & the Path Tracer · Video & animation · Panoramas, VR & delivery |
| **Reference** | 95-entry student FAQ · 41-symptom troubleshooting index · 56-term bilingual glossary |

Roughly 58,000 words across both languages.

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

Eight of the manual's figures are **drawn diagrams** — inline SVG, in both languages, needing nothing from you. They cover the things a screenshot explains badly: why light rounds a zero-thickness wall, what tessellation costs in triangles, what `Collapse all` does to the scene graph, why parallelism matters.

The remaining **11 are photographs** that cannot be drawn — six interface captures and five comparisons from a real project. The manual's *Screenshot capture guide* gives click-by-click instructions for each.

To fill one, save it into `images/` using **exactly** the filename from the guide. The page detects it and swaps the placeholder automatically — no code editing. Anything not yet captured stays as a labelled dashed box, so the manual is usable at every stage of completion.

```
images/
  05-01-import-dialog.png          ← do this one first
  09-01-lumen-surface-view.png     ← and this one second
  ...
```

Recommended: PNG, 1600 px wide minimum, application window only, interface language matching the edition you are illustrating.

> **Take them yourself.** Screenshots of software you are licensed to run are fine for teaching. Frames pulled from someone else's tutorial video, or images lifted from a blog, are their copyright — and this repo is public.

## Accuracy

Technical claims are marked in the text:

- **Documented** — verified against official Epic Games, Trimble or McNeel documentation
- **Studio practice** — craft and judgement, not specification

A [corrections page](twinmotion_2026_manual-v6.html) in the front matter records five claims from the previous version of this material that did not match the official documentation, including a collapse-mode recommendation that was causing the exact interior light-leaking problem a later chapter tried to solve.

Twinmotion changes yearly. Where the manual and your copy of the software disagree about a menu path, trust the software and check the current documentation.

## Licence

No licence has been chosen yet. Until one is added, default copyright applies — the material is readable here but not licensed for reuse.
