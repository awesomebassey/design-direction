# Mobile-Native Web Polish

Use this when building or reviewing web apps on phones, tablets, or touch devices.

## Touch Behavior

- Avoid sticky hover states on touch devices.
- Make tap targets at least 44px when space allows.
- Remove accidental text selection on controls that behave like native buttons.
- Use `touch-action` intentionally for gestures.
- Avoid hover-only affordances.

## Inputs

- Use at least 16px font size on mobile inputs to avoid browser zoom.
- Match input type to content: `email`, `tel`, `number`, `search`, `url`, etc.
- Keep labels visible or recoverable.
- Make validation messages close to the input.
- Ensure keyboard opening does not hide the active field or primary action.

## Viewport And Safe Areas

- Treat `100vh` carefully on mobile browsers.
- Use dynamic viewport units such as `100dvh` where supported.
- Respect safe-area insets for bottom bars, floating actions, and full-screen surfaces.
- Test sticky headers and footers with browser chrome visible and hidden.

## Scrolling

- Avoid nested scroll containers unless they are necessary.
- Keep scroll position stable when filters, tabs, or async data update.
- Preserve momentum and avoid scroll hijacking.
- Make pull-to-refresh conflicts explicit in gesture-heavy apps.

## Responsive Density

- Mobile is not just desktop stacked vertically.
- Keep the primary action reachable.
- Collapse secondary controls into menus only when discoverability remains acceptable.
- Tables need alternate layouts, horizontal scroll with affordance, or summary cards.
- Avoid truncating critical labels without a way to inspect the full value.

## Mobile QA

Test:

- 320px wide viewport
- 375px wide viewport
- Large phone width
- Landscape phone
- Touch-only interaction
- Long text and localized text
- Keyboard open state
- Reduced motion
- Dark mode if supported
