# The Terrain of a Definition: *what is geography?*

An interactive 3D block diagram of **370 definitions of geography** printed in the *Journal of Geography*, 1902–2026.

Time runs left to right. Each ridge is one school of thought — one way of answering the question — and it stands tall where that answer was given often. Every pin is one definition you can read, with its author, citation and a DOI link to the article.

**Live page:** enable GitHub Pages on this repository (Settings → Pages → Deploy from branch `main`, folder `/ (root)`) and it will be served at `https://<user>.github.io/<repo>/`.

## The ten schools

| Ridge | Pins |
|---|---|
| Distribution, place, region | 86 |
| Mutual relations | 86 |
| The Earth described | 43 |
| Declining to define | 39 |
| People adjust to the land | 25 |
| The Earth as the home of man | 25 |
| The Earth as a living whole | 23 |
| A way of thinking | 19 |
| Many geographies | 13 |
| The land shapes its people | 11 |

The last two ridges were added on 27 November 2026, after a second reading of the passages found definitions that name a method or a plurality rather than a subject matter: geography as a way of thinking (a point of view, "what is where, why there, and why care"), and geography defined by enumeration (traditions, themes, many geographies, "what geographers do"). The 32 pins that moved to them are ringed in white on the page.

Each school also carries the name its tradition goes by in the academic literature (anti-essentialism, chorography, cosmography, environmental determinism, chorology and the spatial tradition, human ecology/possibilism, the Ritterian formula, the man–land tradition, spatial thinking, disciplinary pluralism), shown in the reading panel, the pin tooltip and on hover over the school chips.

## What each definition is doing

On 27 November 2026 every defining passage in the coded sheet was read a second way, following Wittgenstein's advice to ask what a word is used for rather than what it means (*Philosophical Investigations* §§11, 43, 65–67, 421). Each passage was assigned one of eight functional moves — boundary work, curricular gatekeeping, legitimation, chartering a subfield, licensing a method, signaling reform, deflating or refusing, codifying the canon — with a short reading of what the definition is doing and a note on the moment it was written in. On the page:

- **Pins coloured by → What the definition does** recolours the pins by move, with chips to isolate a move.
- Each pin's panel shows its move, the reading, and (folded) the moment.
- **Shocks to the field** draws amber walls at 1904 (AAG), 1915 (NCGT), 1948 (Harvard closes geography), 1957 (Sputnik), 1961 (HSGP), 1983 (*A Nation at Risk*), 1984 (Five Themes) and 1994 (National Standards).
- A move × decade grid in the panel counts all 772 coded passages; selecting a cell isolates that move and jumps to its first pin in that decade.

234 of the 370 pins have a reading; the rest come from passages added on 23–24 November 2026 that the coded sheet does not hold. The readings were made by Claude Science (Anthropic) and are interpretations.

## Using the page

- **Drag** to turn, **scroll or pinch** to zoom, **select a pin** to read it.
- **Earlier / Later** step through the definitions in order; a hot‑pink pointer marks the one being read.
- **Build from 1902** replays the century; the slider shows the terrain up to any year.
- The **school chips** hide or show ridges.
- **Scan ← →** (bottom left) zooms in a step and glides along the timeline; **Center** returns to the home view.

## The data

[`data/jog_definition_passages.csv`](data/jog_definition_passages.csv) — 1,549 passages found by scanning the Journal for sentences that define geography, with year, authors, title, volume, issue, pages, DOI, the matched pattern, and the surrounding text. It includes the passages that were read and not pinned.

[`data/jog_definition_passages_coded.csv`](data/jog_definition_passages_coded.csv) — the 359 passages that state a definition outright, each with a coded rhetorical function (`move`, `stance`, `audience`, `family`) and a `school` code added on 27 November 2026. The school code reads the passage as a whole; where one passage holds several definitions (Dryer 1905, for instance) its pins may sit on different ridges. The functional readings shown on the page come from the Expanded edition's sheet, [`terrain-of-a-definition-expanded/data/jog_definition_passages.csv`](https://github.com/edgeoinnovations-resources/terrain-of-a-definition-expanded/blob/main/data/jog_definition_passages.csv).

Each passage was read and sorted by hand. Rules applied: only passages that state, quote or argue a definition of geography were pinned; a rejected definition sits on the ridge of the idea it rejects; duplicates across issues were merged; survey articles (Dryer 1905, Parkins 1934, Griffin 1953, Floyd 1963, Weiss 1981) got one pin per distinct named source. Sorting into schools is an interpretation; a passage fitting two schools went with the idea it leans on hardest. The CSV sometimes lists a passage under the article adjacent to the one it came from, so check the DOI before citing.

## Built with

A single `index.html`: [Three.js r128](https://threejs.org/) from cdnjs for the terrain, HTML overlays for the type. No build step; open the file or serve the folder.

## Credits

Compiled by Paul Strootman, Head of Social Sciences, American School of Dubai. Passages © their authors and the National Council for Geographic Education / Taylor & Francis; quoted here for study, with a link to each source.
