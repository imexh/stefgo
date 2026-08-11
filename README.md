# STEFGO — LUMINARK

`stefgo-luminark.html` is the complete site: one self-contained file, no build step, no
framework. Open it in a browser and it runs.

## Adding your images

Put your six files next to the HTML in a folder called `assets`, named exactly:

```
assets/luminark-01.jpg   ← gold vinyl corset + vermilion drape
assets/luminark-02.jpg   ← bronze mirror corset dress, projected disc
assets/luminark-03.jpg   ← seated profile, sculpted collar   (this is the hero)
assets/luminark-04.jpg   ← circle-print cape + mirrored column skirt
assets/luminark-05.jpg   ← one-shoulder circle-dyed gown
assets/stefgo-logo.png   ← the brand mark
```

Nothing is cropped destructively — the originals stay 1068 × 1600 and the layout is
built around that ratio. Save WebP or AVIF copies alongside the JPGs if you want the
extra 30–40% on load; swap the `src` values and the rest still works.

If the folder isn't there yet, the page tells you and offers **Attach images** in the
bottom-left corner. Pick all six at once and they load straight into the layout for
review. That control disappears once `assets` is populated.

### The logo

Supply it as-is; the page does not redraw or restyle it. On load it's keyed onto the
dark ground so a white-background file works as well as a transparent one — the letter-
forms are untouched either way. If the logo can't be read (opening the file directly
from disk rather than a server, which blocks the read), the page falls back to the
wordmark set in Bodoni Moda.

## What's here

Intro sequence with a point of light opening into the atmosphere, skippable and stored
per session. Editorial collection intro. The world of 55 Cancri e with the three
concepts. A canvas planet — a *projected disc*, the same instrument that lit the
campaign — with four hotspots. Asymmetric editorial collection grid. Material section
with the metallic marquee and detail crops. Horizontal-scroll lookbook. Philosophy.
Journal index. About. Footer.

Motion respects `prefers-reduced-motion` throughout, the custom cursor is desktop-only,
and mobile gets its own art direction rather than a squeezed desktop — the lookbook
becomes vertical, the editorial grid re-stacks with offsets intact.
