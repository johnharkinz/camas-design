# DEC-002 — Camas visual direction

## Decision

The Camas design system will use **A2 — Index, with character** as its primary visual and brand direction.

The accepted direction is represented by:

- `explorations/002-refine-index-and-instrument/Direction A2 - Index.dc.html`
- `explorations/003-converge-camas-system/Camas System v1.dc.html`

The design language should keep the **index/reference-work metaphor strongest at the Camas family level** rather than forcing it into every product interaction.

The main characteristics of the accepted direction are:

- Camas presented as a small, well-kept index of useful web tools
- a dictionary-style treatment of the Camas name on the homepage and appropriate brand/about contexts
- the correct origin of the name: Scottish Gaelic `camas`, meaning a bay, as in Camas Geall
- numbered products forming part of a growing collection
- numbered product marks used as the main product identity system
- warm paper and ink colours
- restrained use of vermilion as an attention and problem signal
- Schibsted Grotesk as the primary typeface
- IBM Plex Mono used selectively for machine-derived or machine-facing information such as headers, values, URLs, status codes and technical evidence
- square corners, rules and compact editorial structure
- plain-English explanation before technical implementation detail
- calm, precise and compact product interfaces

The Camassia plant or botanical interpretation of the word Camas is **not** part of the brand direction.

## Product application

The index metaphor should not dominate the individual tools.

Numbers belong primarily to:

- product marks
- product lockups
- the Camas site index
- appropriate family-level navigation or references

They should not be added to rows, findings, headers or controls simply to reinforce the metaphor.

Likewise, reference-book devices such as thumb-index navigation should only be used where they provide genuine value. They should not become a general product-navigation pattern.

Inside Shareable, Noggin and Bonce, usability and the task at hand take precedence over maintaining the metaphor.

The family relationship should instead be carried by:

- typography
- colour
- spacing
- rules
- product marks
- hierarchy
- interaction patterns

## Interaction language

The system adopts one interaction principle developed during the Instrument exploration:

**Depth communicates function.**

Use depth sparingly and consistently:

- **Raised** surfaces are pressable or actionable.
- **Inset** surfaces contain or display values, evidence or editable data.
- **Flat** surfaces are ordinary layout and content.

This principle should not introduce a wider equipment or skeuomorphic aesthetic.

Depth exists to clarify interaction, not to decorate the interface.

## Colour

The base system uses warm paper tones and dark ink.

Vermilion is intentionally scarce.

It is used for:

- the Camas index mark
- problems or information requiring attention
- focus indication

It should not be used as a generic brand fill, active-state colour or decorative accent.

Active and enabled states should normally use ink so that an item being active is not visually confused with an error or problem.

Warning states use a separate ochre treatment.

Status should never rely on colour alone.

## Typography

Schibsted Grotesk is the primary typeface.

IBM Plex Mono is reserved mainly for information produced, consumed or interpreted by machines, including:

- HTTP header names and values
- metadata and tag names
- URLs
- status codes
- dimensions and technical values
- evidence and diagnostic readouts

Mono should not be used as a generic developer-tool aesthetic.

Headings, explanations, buttons and normal interface text should remain in the primary grotesk.

## Product language

Diagnostics and findings should be written in this order:

1. what happened
2. why it matters
3. what the user can do about it, where appropriate
4. technical evidence

For example, prefer:

> The X card image is missing

before exposing:

`twitter:image → /img/og-caching.png → 404`

Technical users should still have access to the underlying evidence, but they should not have to decode it before understanding the result.

## Product family

The launch products remain visually related but should not be forced into identical layouts.

### Shareable

Shareable should prioritise:

- URL entry
- a clear overall verdict
- important findings first
- plain-English explanations
- technical evidence underneath
- realistic preview information
- compressed treatment of successful checks

### Noggin

Noggin should remain a lightweight, compact extension focused on:

- current-site context
- individual HTTP headers
- simple enable/disable state
- adding headers
- global enable/disable state
- settings
- clear local/privacy messaging

### Bonce

Bonce should use the same design language while supporting greater structural density.

Its interface may include:

- named header sets
- site/domain matching
- active sets for the current site
- priority and conflicts
- editing the headers within a set

Bonce should not simply be treated as a larger version of Noggin.

## Rationale

The first exploration deliberately tested several different visual ideas.

The Index direction provided the strongest combination of:

- restraint
- clarity
- product scalability
- compact UI behaviour
- identity for a growing collection of tools

The second exploration developed this into **A2 — Index, with character**, giving the system stronger Camas-specific identity through the name, reference-work
