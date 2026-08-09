# Screenshot capture guide

**For whoever maintains the manual — not for students.** This lives outside the manual on purpose: it is production instructions for the document, and students reading it would just be confused by it.

Eight of the manual's figures are drawn diagrams and need nothing. The eleven below cannot be drawn — they are either an interface that has to be photographed, or a comparison that only means something coming from a real project.

## How the image system works

Save each capture into `images/` using **exactly** the filename below. The manual detects it and displays it automatically — no code editing.

Until a file exists, that figure is **hidden from readers**, so the manual never looks unfinished. To see what is still missing, open the manual with `?figures` on the end of the URL:

```
https://urbandronedesign.github.io/3DVIZ/twinmotion_2026_manual-v6.html?figures
```

That reveals every empty slot as a labelled placeholder telling you what to capture. Remove the parameter and they vanish again.

## Take them yourself

Screenshots of software you are licensed to run are fine for teaching. Frames pulled from someone else's tutorial video, or images lifted from a blog, are that person's copyright — and this repo is public. Every capture must be your own.

## Settings for all captures

PNG · at least 1600 px wide · application window only, not the whole desktop · interface language matching the edition you are illustrating. If you produce both an English and a French interface version, add `-fr` to the French filename.

---

## Group 1 — Interface captures

Six dialogs and panels. Roughly forty minutes in total, and they can all be done in one sitting with any model open.

| Filename | How to get there | Frame it so that |
|---|---|---|
| `05-01-import-dialog.png`<br>**do this one first** | Twinmotion → **Import > Geometry**, choose any `.skp`, let the options panel open. Expand every collapsed section. | Collapse mode, Enable Nanite, Unit conversion and Up axis are all readable in one frame. Most-referenced image in the book. |
| `09-01-lumen-surface-view.png`<br>**and this one second** | With Lumen active, click the **viewport mode icon in the upper-right corner of the viewport**. Leave the dropdown open with **Lumen surface** highlighted. | The dropdown position is unmistakable. Students hunt for a "Dev Tools" menu that does not exist — this image is what stops that. |
| `11-01-pathtracer-settings.png` | **Properties > Ambience > Render**, switch to Path tracer, expand its settings. | Quality, Samples per pixel, Max bounces, Emissive materials, Denoiser and Fireflies all visible with their values. |
| `02-02-purge-dialog.png` | SketchUp → **Window > Model Info > Statistics**. | Face and edge counts and the *Purge Unused* button in the same frame. Use a heavy model so the numbers are alarming. |
| `02-03-outliner-naming.png` | SketchUp Outliner panel, on a properly organised model. | The naming scheme is legible and clearly systematic. This is the picture of what Stage 2 asks for. |
| `04-01-rhino-glb-export.png` | Rhino → **File > Export Selected**, choose glTF Binary, let the options dialog open. | Material, texture and mesh options readable. McNeel changes these labels between versions — capture the version your cohort actually runs. |

## Group 2 — Comparisons from a real project

These five come out of a teaching model. Every one is something the stages already ask students to produce, so running the course through once yourself generates them as a by-product.

| Filename | What to render | Comes from |
|---|---|---|
| `11-02-sample-comparison.png` | One interior at 64, 256 and 2048 samples. Crop all three to the **same dark shadow region** at 100% zoom and label the render times. The crop is the point — full-frame images at these settings look nearly identical. | Stage 11 |
| `07-01-engine-comparison.png` | The identical view in Standard, Lumen and Path Tracer, camera and lights untouched, render time under each. | Stage 7 |
| `08-02-four-hours.png` | One façade at four times across two seasons, correct north offset set. Best if the low winter sun visibly models the depth that midsummer flattens. | Stage 8 |
| `09-03-light-leak-real.png` | A real interior with a visible floor–wall glow, and the same camera after re-importing with Keep hierarchy and adding thickness. The diagram explains the mechanism; this proves it happens. | Stage 9 |
| `10-02-focal-lengths.png` | The same interior at 16, 28 and 50 mm from an identical point, so the space appears to change size while the room does not. | Stage 10 |

---

## A note on sourcing Group 2

If you have a demonstration model you teach from, build all five from it once and they will serve for years.

If you do not, a strong student project works — with their written permission and a credit line. That has a useful side effect: it shows the next cohort what the standard actually looks like, which is worth more than any amount of describing it.

## Where each figure appears

| Shot | Chapter | Section |
|---|---|---|
| `02-02`, `02-03` | 2 | Model hygiene |
| `04-01` | 4 | Exporting |
| `05-01` | 5 | Import options |
| `07-01` | 7 | Choosing an engine |
| `08-02` | 8 | Exterior lighting |
| `09-01`, `09-03` | 9 | Interior lighting |
| `10-02` | 10 | Cameras |
| `11-01`, `11-02` | 11 | Stills and the Path Tracer |

Each has a slot in both the English and the French edition; one file fills both.
