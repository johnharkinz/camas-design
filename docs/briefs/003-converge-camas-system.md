Please read the project context and current explorations before starting:

- `AGENTS.md`
- `docs/project-brief.md`
- `docs/decisions/`
- `docs/briefs/001-visual-direction-exploration.md`
- the existing explorations, especially:
  - Direction A — Index
  - Direction A2 — Index, with character
  - Direction D2 — Instrument, in the hand

We are now converging rather than exploring.

## Decision

Use **A2 — Index, with character** as the primary Camas visual and brand direction.

Keep its strongest ideas:

- Camas as a well-kept index/reference work
- the dictionary-style treatment of the Camas name
- the correct naming origin: Scottish Gaelic `camas`, meaning bay, as in Camas Geall
- numbered products as part of a growing collection
- warm paper / ink palette
- restrained vermilion index mark
- Schibsted Grotesk with selective mono usage
- strong editorial hierarchy
- square corners and rules
- plain-English explanation before technical detail
- calm, precise, compact UI

Do **not** use the Camassia plant or botanical meaning as part of the brand.

## Refine the metaphor

A2 currently pushes the reference-book/index metaphor too far inside the tools.

Keep the metaphor strongest at the **Camas and product-family level**.

Inside Shareable, Noggin and Bonce, allow the interface to become more task-focused and conventional where that improves usability.

In particular:

- do not number every header or row simply because the index system exists
- do not force thumb-index tabs onto every screen
- do not make every product interaction feel like a reference-book convention
- retain the visual family through typography, colour, hierarchy, rules, spacing and product identity instead

## Adopt one interaction principle from D2

Bring across this principle from Direction D2:

**Depth should communicate function.**

Use it sparingly:

- raised surfaces = pressable/actionable
- inset surfaces = fields, values, readouts or data
- ordinary layout = flat

Do not import the wider “instrument” or equipment aesthetic.

Do not make the interface skeuomorphic.

The depth should be subtle enough that A2 still clearly feels like A2.

## Product language

Continue the plain-English-first approach.

For diagnostics and findings:

1. explain the issue in normal language
2. explain why it matters
3. show the technical evidence underneath

For example:

“The X card image is missing”

before:

`twitter:image → /img/og-caching.png → 404`

The product should respect technical users without forcing them to decode implementation details before understanding the result.

## Produce the next system pass

Create a coherent refinement showing all of the following:

### 1. Camas identity

Refine:

- wordmark
- dictionary/name treatment
- product numbering system
- product marks/icons at realistic sizes
- relationship between Camas and individual product names

Do not assume every surface needs the full dictionary treatment.

### 2. camas.dev

Create a realistic homepage for launch.

It should:

- introduce Camas clearly
- present Shareable, Noggin and Bonce
- show enough product UI to make the tools understandable
- include the person behind the tools without turning the site into a personal portfolio
- feel distinctive without becoming over-designed
- leave room for future Camas tools

### 3. Shareable

Create a realistic product screen.

Prioritise:

- URL entry
- overall verdict
- important problems first
- plain-English explanation
- technical evidence underneath
- preview of how the URL will appear on relevant platforms
- calm handling of passing checks

Reduce any unnecessary index/reference-book decoration.

### 4. Noggin

Create a realistic **360 × 540 browser-extension popup**.

This should reflect the actual simplicity of Noggin:

- current-site context
- list of headers
- per-header on/off state
- global on/off state
- add-header interaction
- settings access
- clear local/privacy message

Keep it extremely clear and compact.

Do not invent complexity that belongs in Bonce.

### 5. Bonce

For the first time in this process, design Bonce separately rather than treating it as a larger Noggin.

Show a realistic browser-extension interface for:

- named header sets
- domains/site matching
- which set is active for the current site
- enabling/disabling sets
- viewing/editing the headers within a set
- enough complexity to distinguish Bonce from Noggin without making it heavy

Use the same Camas design language but allow Bonce to be denser and more structured.

### 6. Core design language

Show the emerging system for:

- typography
- colour
- spacing
- rules/borders
- buttons
- inputs/readouts
- toggles
- status treatments
- focus states
- product marks/icons
- use of mono type
- use of the vermilion accent
- use of depth

## Important

This is not yet a final production design system.

The goal is to turn A2 into a coherent, realistic system that can be judged across the actual launch products.

Do not produce multiple new directions.

Do not merge A2 and D2 aesthetically.

Do not add visual ideas simply for variety.

Make strong design decisions and show the result.