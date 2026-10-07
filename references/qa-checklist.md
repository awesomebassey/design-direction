# UI QA Checklist

Use this before considering interface work complete.

## Data Stress

Test with:

- Empty data
- One item
- Many items
- Very long names
- One-letter names
- Long emails
- Long URLs
- Large currency values
- Negative values
- Zero values
- Missing optional fields
- Slow loading
- Failed loading
- Permission denied

## Layout Stress

Check:

- 320px mobile width
- Common desktop width
- Very wide desktop
- Browser zoom at 125% and 150%
- Long labels in buttons, tabs, cards, and table cells
- Scroll containers
- Sticky elements
- Modals and popovers near viewport edges
- Text overlap
- Layout shift during hover, loading, or state changes

## Interaction States

Every relevant control should have:

- Default
- Hover where applicable
- Focus
- Active or pressed
- Disabled
- Loading
- Success
- Error
- Empty state

## Accessibility

Check:

- Keyboard navigation
- Visible focus
- Semantic buttons and links
- Form labels
- Error announcements where relevant
- Sufficient contrast
- Reduced motion
- No color-only meaning for critical states

## Visual Polish

Look for:

- Inconsistent radius
- Inconsistent spacing
- Unclear hierarchy
- Decorative clutter
- Overuse of accent color
- Mismatched icon weight
- Text that feels too large for its container
- Motion that feels slow or gratuitous

## Completion Standard

If a UI breaks under common real-world content, fix it before shipping. If a rare edge case remains, document it clearly.
