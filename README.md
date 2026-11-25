# Computer Science — Grade 10 Notes (Units 1–6)

Condensed, exam-focused notes for the **NBF (National Book Foundation) Grade 10 Computer Science** textbook, written as a single self-contained HTML page.

No build step, no dependencies, no internet connection required — open the file and read.

**→ [`Computer-Science-Grade10-Notes.html`](Computer-Science-Grade10-Notes.html)**

---

## What's inside

| Unit | Title | What the notes cover |
| :--: | --- | --- |
| 01 | **Computer Systems** | Bits and data types, the four number bases and conversions, binary arithmetic, overflow and underflow, 1's and 2's complement, ASCII vs Unicode, OS functions and types, process states, file systems, software types, IDE and compiler, hosting |
| 02 | **Computational Thinking** | Problem types, counting principles, permutations and combinations, pigeonhole and inclusion–exclusion, algorithm properties, Boolean logic, sorting and searching, decomposition, pattern recognition, abstraction, generalisation, dry runs and trace tables, error types |
| 03 | **Programming Fundamentals** | Front-end vs back-end, client–server, HTML forms and tables, CSS animation, arrays and methods, DOM updates, arrays vs lists, linear search, unit tests, breakpoints and watchpoints |
| 04 | **Data and Analysis** | Data science vs AI vs machine learning, supervised / unsupervised / reinforcement learning, churn and segmentation, choosing charts, the visualisation lifecycle, KPIs, an inventory case study |
| 05 | **Applications of Computing** | IoT components and uses, blockchain, cloud computing, speech vs voice recognition, NLP, robotics, AI bias, responsibilities of designers |
| 06 | **Impacts of Computing** | Digital addiction, internet benefits and harms, spam / spyware / cookies, public and private cloud, security controls, cybercrime law and reporting, cyberbullying, environmental and cultural effects, the digital divide |

**38 topics · 30 tables · 11 hand-drawn SVG diagrams · 18 quick-check questions.** Three diagrams are interactive, and there is a live decimal → binary converter plus a closing revision table of twelve facts worth memorising.

## Features

- **A logo and favicon** — an inline SVG mark, so the tab and the page share one identity without a single image request.
- **Bookmarked header** — jump to any unit (or the revision page) from the sticky header. The current unit and a reading-progress bar update as you scroll, and the active tab scrolls itself into view on narrow screens.
- **Phone-first layout** — a two-row mobile header with a scrollable unit rail, 40px+ tap targets, 16px body text, tables and diagrams that scroll sideways rather than shrinking into unreadable smudges, and safe-area aware floating controls.
- **Diagrams, not decoration** — eleven inline SVGs (OS layers, the counting tree, client–server, the data lifecycle, the IoT loop, a blockchain chain, the digital divide, and more) that each replace a paragraph of text.
- **Diagrams you can touch** — tap a layer of the computer stack or a stage of the data life cycle to hear what it does, and step through a live binary search that greys out the half it just discarded.
- **Collapsible quick checks** — 18 "check yourself" questions with answers hidden behind a tap, so the page stays skimmable.
- **Light and dark** — follows your choice, remembered in `localStorage`.
- **Prints cleanly** — header and controls disappear, answers open, page breaks avoid splitting figures and tables.
- **Zero network requests** — system fonts, inline CSS and JavaScript, no fonts, images, trackers or CDNs. It works offline and from a USB stick.

## Using it

```bash
# just open it
start Computer-Science-Grade10-Notes.html     # Windows
open  Computer-Science-Grade10-Notes.html     # macOS
xdg-open Computer-Science-Grade10-Notes.html  # Linux
```

To host it, enable GitHub Pages for this repository and point it at the branch root — the file is already named for direct serving. Rename it to `index.html` if you want the bare repo URL to serve the notes.

## How it was made

The source PDF is a 262-page **scanned** book with no text layer, so every page used here was rendered and run through OCR (PyMuPDF + Tesseract), then rewritten by hand. Nothing is copied verbatim: each section was reduced to the definition, one worked example, and a plain-language analogy.

Scope is deliberately **Units 1–6 only** (pages 8–194), stopping before the book's annexures.

## Notes on the content

- One example per concept, and one analogy per hard idea — repetition and filler were cut.
- Section numbers are merged where the book repeats itself (e.g. *2.2–2.3 Counting principles*, *6.10–6.11 Digital divide*), so the numbering marks groups of ideas rather than mirroring every sub-heading.
- Diagrams are schematic, not to scale; they exist to show relationships.

## Repository contents

```
Computer-Science-Grade10-Notes.html   the notes
README.md                             this file
.gitignore                            ignores everything else in the folder
```

Everything else — the PDFs, OCR output, and local tooling — is intentionally untracked.

## Status

Checked in headless Edge at 390px (phone) and 1280px (laptop): no horizontal page overflow, the mobile header rail works, and the interactive diagrams respond to taps and to scripted clicks. Structurally: balanced HTML, valid inline SVG, no duplicate IDs, no broken internal anchors, balanced CSS, and parsing inline JavaScript. Firefox and Safari were not tested, but the page uses only widely supported CSS and JavaScript.

---

*Study notes for personal revision. The textbook content belongs to the National Book Foundation; this is an independent summary.*
