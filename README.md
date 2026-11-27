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

## Using the page

- **Drag** to turn, **scroll or pinch** to zoom, **select a pin** to read it.
- **Earlier / Later** step through the definitions in order; a hot‑pink pointer marks the one being read.
- **Build from 1902** replays the century; the slider shows the terrain up to any year.
- The **school chips** hide or show ridges.
- **Scan ← →** (bottom left) zooms in a step and glides along the timeline; **Center** returns to the home view.

## The data

[`data/jog_definition_passages.csv`](data/jog_definition_passages.csv) — 1,549 passages found by scanning the Journal for sentences that define geography, with year, authors, title, volume, issue, pages, DOI, the matched pattern, and the surrounding text. It includes the passages that were read and not pinned.

[`data/jog_definition_passages_coded.csv`](data/jog_definition_passages_coded.csv) — the 359 passages that state a definition outright, each with a coded rhetorical function (`move`, `stance`, `audience`, `family`) and a `school` code added on 27 November 2026. The school code reads the passage as a whole; where one passage holds several definitions (Dryer 1905, for instance) its pins may sit on different ridges.

Each passage was read and sorted by hand. Rules applied: only passages that state, quote or argue a definition of geography were pinned; a rejected definition sits on the ridge of the idea it rejects; duplicates across issues were merged; survey articles (Dryer 1905, Parkins 1934, Griffin 1953, Floyd 1963, Weiss 1981) got one pin per distinct named source. Sorting into schools is an interpretation; a passage fitting two schools went with the idea it leans on hardest. The CSV sometimes lists a passage under the article adjacent to the one it came from, so check the DOI before citing.

## Built with

A single `index.html`: [Three.js r128](https://threejs.org/) from cdnjs for the terrain, HTML overlays for the type. No build step; open the file or serve the folder.

## Credits

Compiled by Paul Strootman, Head of Social Sciences, American School of Dubai. Passages © their authors and the National Council for Geographic Education / Taylor & Francis; quoted here for study, with a link to each source.
