# AGENTS.md

## Purpose

This repository is the design source of truth for:

- camas.dev
- Shareable
- Noggin
- Bonce

It contains briefs, references, design explorations, assets, design decisions and, later, a small runnable reference site.

It is not initially a shared production component library.

## Working principles

- Treat `docs/project-brief.md` as the primary project brief.
- Treat accepted files in `docs/decisions/` as established design decisions.
- Do not assume the existing Camas logo, colours, typography or UI are fixed.
- Prefer coherent design proposals over asking for arbitrary choices such as individual spacing values, colours or typefaces.
- Explore genuinely different visual directions before converging.
- Avoid generic SaaS, default framework or developer-tool aesthetics unless they are a deliberate design choice.
- Evaluate design work across all three contexts:
  - marketing site
  - web application
  - compact browser extension
- Keep usability, accessibility and clarity ahead of decoration.

## Decisions

Design decisions live in:

`docs/decisions/`

Use one file per decision.

Naming convention:

`DEC-###-short-description.md`

Do not silently rewrite an established decision if the direction changes. Create a new decision and mark the previous one as superseded where appropriate.

## Explorations

Experimental or competing design work belongs in:

`explorations/`

Explorations are not accepted design decisions.

Do not treat an exploration as canonical until it has been reviewed and recorded in `docs/decisions/`.

## References

Design references belong in:

`references/`

References should capture why something is useful, not simply collect screenshots or links.

## Implementation

The design repository describes and demonstrates the agreed design system.

Do not introduce shared production packages or cross-product component architecture unless that has been explicitly agreed.

When producing implementation guidance, derive it from the accepted design decisions rather than redefining the design during implementation.

## Workflow

For significant design work:

1. Read the project brief.
2. Read relevant accepted decisions.
3. Review relevant references and previous explorations.
4. Produce or revise the design exploration.
5. Review the result against the project brief.
6. Record any accepted choices as design decisions.
7. Only then turn those choices into implementation guidance.