# Claude Design brief: gregjudelman.com landing page

*v1 launch · prepared in Claude Cowork*

## The assignment

Design the v1 landing page for Greg Judelman, a senior strategic advisor. One page, eight sections, top to bottom. The page introduces Greg's practice and routes readers to one of three actions: take the AI Transition Diagnostic, see the AI Transformation Canvas, or book a 30-minute call.

Apply the **Greg Judelman Consulting design system** you have access to for typography, color, layout patterns, and visual register. The constraints below are the page-specific decisions that matter most.

## The reader

Senior buyers in regulated and high-stakes environments — federal and provincial government, health systems, universities, foundations, regulated enterprise. CIOs, ADMs, VPs, program leads navigating AI adoption under pressure. Skeptical of hype. Have seen transformation efforts stall. The page should feel like something a senior practitioner wrote and considered carefully, not something a marketing firm produced.

## Emotional register

Calm, intelligent, grounded, editorial. Closer to a well-designed research publication than a SaaS product or consulting template.

## How to use this brief

The constraints below are the design decisions already made. Within them, the specifics — hero composition, typographic scale, spacing rhythm, Canvas diagram rendering, responsive behavior — are yours. Exercise design judgment grounded in the Greg Judelman Consulting design system. Where the system and this brief don't specify, default to the system's defaults.

## Documents to reference

**Copy — use exactly as written, do not rewrite:**

- `landing-page-deck.md` — final copy for all eight sections, with visual treatment hints attached to each element (typeface, weight, size cues, position notes).

**Visual brand — primary system:**

- The Greg Judelman Consulting design system you have access to.

**Strategic context — optional, for understanding intent:**

- `website-v1-outline.md`, Section 1 (what the site is for) and Section 4 (section-by-section structure and rationale).

Do not reference the rest of the outline. The strategic and copy decisions are settled.

## Visual direction

These are the constraints that matter most for this page. Within them, the specifics are yours.

**Surface and palette.** Paper (`#F6F2EC`) is the default surface for the page. Ink (`#041F28`) is reserved for the hero and at most one other moment of visual emphasis. Sage (`#7DA7A7`) appears only as 1px horizontal rules between sections and as text-link accent — never as filled blocks. The palette avoids reds, oranges, and saturated blues.

**Typography.** Source Serif 4 for headings and the primary hero invitation. Helvetica Neue Light for body. Sentence case throughout. The page does not use eyebrows from the broader brand pattern — section headlines do the wayfinding on their own. Sage 1px horizontal rules between sections carry the sage accent that eyebrows would have provided.

**Layout.** Asymmetric, top-aligned columns. Generous whitespace. Square corners (`radius: 0`) everywhere — no rounded SaaS-style cards. Hairline horizontal rules only — no left or right rules on cards or sections.

**The hero (Section 4.1).** Typographic. No image. The wordmark, hero line, supporting line, and two CTAs carry the section. Composition is yours.

**The Canvas preview (Section 4.4).** This section needs a real diagram, not a placeholder. Render the 8-block AI Transformation Canvas structure in three horizontal bands: Strategic Focus (top), Adaptation (middle), Enablement (bottom). Eight blocks distributed across the bands. Quiet line-and-label treatment on paper surface. Treat it like a diagram in a research publication, not a marketing infographic. The exact composition and label rendering is yours; reference the canvas structure described in the outline for block identity.

**The Diagnostic preview (Section 4.5).** Use a visual element: a small abstract grid representing 8 dimensions of the AI Transformation Canvas × 4 maturity tiers. If included, paper surface, quiet line treatment, consistent in language with the Canvas preview.

**Section 4.6 (How to work together).** Three top-aligned columns of equal width. Each card has a hairline rule top and bottom, no left or right rules. The cards should be scannable side by side: a reader comparing *60–90 minutes · leadership team* with *Half-day or full-day · leadership team or extended group* with *Multi-week or multi-month* should be able to do it in a glance.

**Section 4.7 (Where I've worked).** Include a small portrait at the right edge of the section, paper surface, restrained treatment. 

**Section 4.8 (Closing / contact).** No heading on this section. The serif invitation acts as the closing line of the page — like the last paragraph of an essay rather than a contained section. The channel partner line below sits in quieter visual treatment (smaller, lower contrast, more spacing above it).

## No-go list

- No gradients, textures, noise, or drop shadows.
- No emoji in any context.
- No rounded SaaS-style card shapes.
- No decorative icons. If icons are required for any functional purpose, Lucide stroke 1.5, 16–20px.
- No warm sun-drenched stock imagery, no AI-generated composites, no stock photography in general.
- No hero photograph or hero illustration. The hero is typographic.
- No question marks or exclamation points anywhere on the page.

## What to produce

A complete v1 landing page design covering all eight sections, designed primarily for desktop and large tablet. Responsive behavior handled but not the primary register.

Acceptable output formats, in order of preference for handoff:

1. **HTML/CSS mockup** rendered to spec.
2. **High-fidelity static designs** (PNG or PDF, one per section, with a separate spec for the Canvas diagram).

The downstream build is likely to be in Claude Cowork and/or Claude Code, depending on what Greg decides after seeing the designs.

## A note on what success looks like

The page should feel like something a senior advisor would put their name on. Restraint is the design move. The reader should finish the page with a clear sense of who Greg is, what kind of work he does, and what action to take next — and should not feel as though they've been sold to.
