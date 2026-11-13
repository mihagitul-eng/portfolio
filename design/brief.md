# Design brief

Source: the interview, without Stitch
Mood: friendly, cold, neon. Technical precision with a cold neon glow: code-editor metadata and dot-grid structure paired with clean, spacious layout.

## Style

- Style: Technical, with a Modern touch: generous whitespace and borderless list structure.
- Feel: friendly, cold, neon.
- Personal detail: a subtle mountain ridge divider between sections, inspired by mountain hiking in Almaty.
- Motion: crisp and functional: state changes, subtle glowing hover shifts. When the visitor prefers reduced motion, nothing moves.

## Colours

| Token | Light | Dark | Used for |
|---|---|---|---|
| background | #f6f7f9 | #0d1117 | page background: cool white, with a faint dot grid |
| surface | #f1f3f6 | #161b22 | cards |
| text | #161b22 | #e6edf3 | headings and body text |
| muted | #57606a | #9198a1 | dates, labels, file names, borders |
| accent | #0066cc | #38bdf8 | links, focus ring: neon blue |
| on-accent | #ffffff | #0d1117 | text on an accent-coloured button |

## Type

| Role | Font | Size | Weight |
|---|---|---|---|
| headings | "JetBrains Mono", ui-monospace, Menlo, Consolas, monospace | name 2rem, section 1.125rem, card 1rem | 600 |
| body | "IBM Plex Sans", system-ui, sans-serif | 1rem, line height 1.6 | 400 |
| details | "JetBrains Mono", ui-monospace, Menlo, Consolas, monospace | dates and labels 0.875rem | 400 |

## Shapes

- Corner radius: none: square corners.
- Borders: 1px in the muted colour thinned out, around cards and tags.
- Shadows: none.

## Layout

- One column, at most 46rem, centred, with 1.25rem space at the sides on phones; a faint dot grid behind the page.
- 3rem between sections, 1rem between items in a list.
- Experience & timeline: clean vertical timeline with monospace dates.

## Components

- Links: accent colour, underlined; keyboard focus shows a 2px neon accent ring.
- Cards: surface background, 1px border, 1.25rem inner space, the title in the heading font.
- Skills: a monospace list written like an array: [ "PHP", "GoLang", "PostgreSQL" ].
- Section headings: in the heading font, with "// " before them as decoration.

## Signature

- Move: Other cards step back on hover and focus
- Guide: guides/css/child-state-based-styling.md
- Where: the cards: while one is pointed at or focused, the others step back.

## Sections

1. `bio`: the name, the headline, pitch, availability, and the bio.
2. `links`: LinkedIn and email links for recruiters to reach out.
3. `cv`: experience timeline and technical skills list.
4. `events`: workshops and conferences attended.
