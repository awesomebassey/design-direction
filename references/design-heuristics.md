# Design Heuristics

## Product Fit

Design is contextual. A CRM dashboard, an AI coding tool, a mobile meditation app, a restaurant page, and a game should not share the same visual language.

Before choosing a style, decide:

- Who uses it
- How often they use it
- Whether they are browsing, comparing, deciding, creating, monitoring, or recovering from an error
- Whether speed, confidence, delight, trust, or expression matters most

## Layout

- Put the primary workflow where the eye lands first.
- Use grids to organize, not to decorate.
- Make repeated items scan as a set.
- Avoid section cards that simply frame content already separated by spacing.
- Use whitespace to group and separate, not to create emptiness.
- Keep controls close to the thing they affect.
- Prefer progressive disclosure for rare or advanced controls.

## Typography

- Use fewer sizes with clearer roles.
- Keep body text readable and compact enough for the surface.
- Avoid hero-sized type in dashboards, settings, tables, sidebars, or dense tools.
- Never use negative letter spacing as a default style.
- Avoid viewport-scaled font sizes; use responsive layout, not fluid type tricks.

## Color

- Start with semantic roles: background, surface, border, text, muted text, accent, success, warning, danger.
- Avoid one-note palettes where every element is the same hue family.
- Ensure important states are visible without relying on color alone.
- Use accent color sparingly so it still means something.

## Interaction

- Every interactive element needs clear affordance.
- Hover should reinforce clickability, not become the only signal.
- Focus states must be visible.
- Disabled states should explain themselves when ambiguity matters.
- Loading should preserve layout and communicate progress when the wait is meaningful.
- Empty states should help the user take the next useful action.

## Common Agent Mistakes

- Making a marketing page when the user asked for a tool.
- Adding decorative cards around every section.
- Using giant typography in compact product surfaces.
- Creating elaborate gradients instead of better hierarchy.
- Forgetting mobile input zoom, sticky hover, and safe areas.
- Designing only the happy path.
- Adding motion that slows down repeated work.
- Using a component library without adapting it to the product's tone.
- Treating screenshots as code.
