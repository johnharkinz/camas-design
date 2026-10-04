# Camas — Project & Design Brief

## Purpose

Camas is a home for small, practical web-development tools.

The immediate project is to design and launch:

- **camas.dev** — the main Camas website
- **Shareable** — a web application
- **Noggin** — a browser extension
- **Bonce** — a browser extension

Noggin and Bonce must also be ready for submission to the Chrome Web Store.

This project covers the visual identity, product design and design system needed to make those four experiences feel coherent and ready to launch.

## Current position

There are existing implementations and some existing visual ideas, but none of the visual design should be considered fixed.

This includes:

- logo and icon
- colour
- typography
- spacing
- layout
- visual hierarchy
- illustration or graphic style
- product UI
- website structure and presentation

Existing work can be retained where it proves useful, but it should not constrain the exploration.

## Product idea

Camas should feel like a collection of useful tools made by someone who cares about how the web works.

The tools should be:

- focused
- understandable
- quick to use
- trustworthy
- pleasantly designed
- free from unnecessary product complexity

They are developer tools, but they do not need to look like generic developer tooling.

Camas should have enough character to be recognisable without allowing the brand to get in the way of the tools themselves.

## Launch products

### camas.dev

The main site introduces Camas, explains what it is, provides a home for the tools and gives some sense of the person behind them.

The marketing site can have more personality and visual expression than the individual tools.

### Shareable

A web tool for checking how a URL is likely to behave when shared, including social metadata, images and related page information.

The experience should make potentially technical information easy to understand and quickly communicate whether something looks healthy or needs attention.

### Noggin

A simple browser extension for applying HTTP headers while working with websites.

It should feel lightweight, immediate and local.

Its interface will operate within the constrained dimensions of a browser-extension popup, so clarity and economy matter more than visual flourish.

### Bonce

A more capable browser extension for managing sets of HTTP headers and applying them to appropriate sites or domains.

It is related to Noggin but is a separate product rather than simply a larger version of it.

Its UI must accommodate greater complexity without becoming visually heavy.

## Audience

The primary audience is people who build, test, maintain or work with websites.

That includes developers but can also include QA engineers, technical marketers, SEO specialists, analytics specialists and other technically minded web professionals.

The products should respect an experienced technical user without assuming that every user understands the underlying implementation details.

## Desired qualities

The overall experience should feel:

- simple
- clear
- modern
- considered
- useful
- calm
- trustworthy
- precise
- pleasant to use

It should have personality, but not at the expense of usability.

It should feel designed rather than merely styled.

## Things to avoid

Avoid defaulting to familiar visual shorthand simply because these are developer tools.

In particular, question directions that feel:

- like a generic SaaS landing page
- like a default Tailwind/shadcn application
- excessively monochrome and austere
- covered in gradients, glowing effects or decorative blobs
- dependent on terminal/code aesthetics for personality
- over-branded inside the actual tools
- cute or whimsical enough to undermine trust
- polished but anonymous

Likewise, simplicity should not become blandness.

## Relationship between brand and products

Camas needs a recognisable family identity, but the four surfaces have different jobs.

### Marketing

camas.dev can be the most expressive manifestation of the identity.

It needs to make the collection memorable and give the tools context.

### Web tools

Tools such as Shareable should be quieter.

Brand should provide coherence, typography, structure and character without competing with the user's task.

### Browser extensions

Noggin and Bonce need the most compact expression of the system.

Space is constrained and interaction density is higher, so hierarchy, typography and spacing must work particularly well at small sizes.

The same design language should survive across all three contexts rather than requiring three unrelated designs.

## Responsive and constrained UI

The design system must work at normal website widths and at realistic browser-extension popup dimensions.

Design exploration should therefore include constrained interfaces early rather than designing a spacious website first and attempting to shrink the system afterwards.

Noggin and Bonce should eventually be evaluated at their real intended popup dimensions.

## Accessibility

Accessibility should be treated as a design constraint rather than a later compliance exercise.

The system should support:

- strong text contrast
- clearly distinguishable interactive states
- comfortable type sizes
- keyboard interaction
- visible focus states
- layouts that do not rely on colour alone to communicate meaning

## Design-system approach

`camas-design` is the source of truth for the design project.

Initially it will contain:

- this brief
- design references
- explorations
- assets
- recorded design decisions

Once a direction has been established, it should become a small runnable reference site.

That reference should demonstrate things such as:

- typography
- colour
- spacing
- hierarchy
- controls
- basic components
- layout patterns
- states and feedback
- camas.dev examples
- Shareable examples
- realistic Noggin examples
- realistic Bonce examples

The repository should describe and demonstrate the system.

It should **not initially become a production component package shared by the four applications**. Production applications remain responsible for their own implementations.

## Role of AI in the design process

The project should use AI as a design collaborator rather than requiring the project owner to prescribe design-system values.

Design exploration should make informed proposals for typography, spacing, colour, hierarchy and composition and explain why those decisions work together.

Questions should focus on meaningful design choices and trade-offs rather than repeatedly asking the project owner to select arbitrary values.

Several genuinely different directions should be explored before one is chosen.

Changing a font or accent colour does not constitute a different design direction.

## Evaluation

A proposed design direction should be judged against questions such as:

**Identity**  
Does this feel recognisably like Camas rather than a generic software template?

**Clarity**  
Can users quickly understand the page, interface and available actions?

**Hierarchy**  
Does the design naturally guide attention without excessive decoration?

**Character**  
Does it have enough personality to be memorable?

**Restraint**  
Does the design stay out of the way when someone is using a tool?

**Range**  
Can the same system support an expressive marketing page, a web application and a compact browser extension?

**Craft**  
Do typography, spacing, alignment and interaction details feel intentional?

**Longevity**  
Does this feel like a system that can support additional Camas tools rather than a one-off design for the launch products?

## Initial design task

The first visual-design phase should explore several genuinely different ways Camas could look and feel.

These should be coherent design directions, not small variants of the same interface.

Each direction should demonstrate enough of the system to judge it properly, including at least:

- Camas identity/wordmark treatment
- camas.dev homepage or substantial homepage section
- a representative Shareable screen
- a compact browser-extension interface
- typography
- colour approach
- basic controls and interface treatment

The aim of this phase is not to produce final screens.

It is to discover the visual language that is worth developing further.

## Launch definition

The initial design project is successful when:

- camas.dev presents Camas and the three launch products convincingly
- Shareable feels complete and deliberately designed
- Noggin feels complete at real extension dimensions
- Bonce handles its additional complexity cleanly
- all four clearly belong to the same family
- Noggin and Bonce have the assets necessary for Chrome Web Store submission
- the design system is documented well enough that future Camas tools can build on it
- implementation has been reviewed against the agreed design rather than merely approximating it