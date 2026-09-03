<h1 style="color:#4CAF50; text-align:center">AgroSelect</h1>

A decision-support website for smallholder farmers: what to plant, and what it's actually worth.

Pod project addressing the problem of **smallholder crop and input choice**. Farmers routinely commit land and money to a crop for the season with little more than habit and guesswork to go on. AgroSelect compares crop and input options against a farmer's own plot, budget, and target market, turning "what should I plant" into a cost-vs-expected-return comparison instead of a gut call.

## Problem

- Crop choice depends on soil, climate, input cost, and market price at harvest which is more variables than most households can track from memory or informal advice.
- Agricultural extension services can't scale to meet the need: a single officer may support thousands of farmers, far past what personal visits can cover.
- Existing digital tools tend to specialize in *either* agronomic advice (what/how to grow) *or* market and financial access; not the combined "what will this cost me, and what will it be worth" comparison a farmer needs before committing to a season.

Full background and supporting research: see `res/Selector_Pod_Master_Research_Document.docx`.

## What's in this repo

| File | What it is |
|---|---|
| `res/Selector_Pod_Master_Research_Document.docx` | Research submission: problem statement, background, existing-solutions landscape, proposed direction, objectives, scope, references |
| `index.html` | Landing page containing the intro segment, problem framing, how-it-works, sample crop comparison table, signup CTA |
| `agroselect-logo.svg` | Logo icon alone, scalable |
| `agroselect-logo-lockup-light.svg` | Icon + wordmark, for light backgrounds |
| `agroselect-logo-lockup-dark.svg` | Icon + wordmark, for Deep Green / dark backgrounds |
| `agroselect-brand-identity.html` | Brand reference sheet: logo usage & clear space, color palette, type system, do/don't guidance |

## Brand at a glance

**Name:** AgroSelect
**logo:** four diagonal color bands running through the full palette. inspired by rows of a ploughed field

**Color**
| Color | Hex | Role |
|---|---|---|
| Deep Green | `#1B5E20` | Headings, nav, primary text |
| Mid Green | `#4CAF50` | Buttons, links, active states |
| Lime | `#AEEA00` | "Best value" highlight only |
| Yellow | `#FFEB3B` | Small accents, used sparingly |
| Paper | `#FAFAFA` | Base background |

**Type:** Space Grotesk for headings and data, Inter for body text. Full scale and usage rules are in `agroselect-brand-identity.html`.

## Viewing the files

- Open the `.html` files directly in a browser.
- The `.svg` logo files can be opened in a browser, placed in an `<img>` tag, or dropped into design tools (Figma, Illustrator) directly.
- The wordmark lockups reference Space Grotesk as a web font; if you need them to render with zero font dependency (e.g. for print), the text should be converted to outlined paths first.

