# Three Visual Languages — prototype 01

A dependency-free prototype of a digital editorial-design library. Open `index.html` directly, or serve this folder with any static server.

## Structure

- `index.html` — minimal application entry point.
- `styles.css` — the quiet shared library shell and the expressive Book I system.
- `app.js` — views, sample Book I content, navigation, search index, popovers, and browser-local reading state.

The shell contains three books, but only Book I is implemented. Book II is titled **International Typographic Style**. Book III remains provisionally titled **Modern Japanese Editorial / Book Design**.

## What works

- Collection view and entry/resume route.
- Persistent in-book contents sidebar with click-to-jump and active-section tracking.
- Collection-search prototype (`Ctrl/Cmd + K`) backed by a simple index designed to be replaced by generated content metadata.
- Browser-local saved-book and continue-reading state; no account or server.
- Internal reference jump with return-to-previous-section behavior.
- Definition, citation, and methodology popovers.
- Figure/caption pattern with creator, title, year, medium, dimensions, printer, archive, object number, and external link.
- Responsive reading layout and collapsible contents on small screens.
- Demonstration-only analytical grid overlay.

## Evidence status

Sourced content is deliberately limited. The typography-history statement links to the Bauhaus-Archiv. The Joost Schmidt object metadata links to MoMA. The poster-like graphic shown in the case study is **an explicit placeholder, not a reproduction**. All geometric diagrams and page miniatures are original demonstrations or analytical prompts, labeled as such.

No unlicensed historical imagery is bundled. The finished book needs image-rights review, licensed reproductions, page-level citations, and a proper bibliography before publication.

## Refine next

1. Establish a research and image-rights inventory for every proposed historical figure.
2. Replace placeholder prose with researched chapters and attach citations at claim level.
3. Expand the figure schema into structured content data (JSON or a CMS), including rights and uncertainty fields.
4. Test the Book I editorial system against several licensed works before treating its palette, geometry, type, or spatial behaviors as historically substantiated.
5. Add full keyboard/focus testing, reduced-motion handling, and screen-reader announcements.
6. Choose a framework only after the content model is stable; this prototype intentionally keeps architecture legible and portable.

