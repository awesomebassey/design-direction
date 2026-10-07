# Motion Principles

Motion should explain, orient, respond, or add carefully chosen delight. If it only draws attention to itself, remove it.

## Decide Purpose First

Use motion for:

- State changes
- Spatial continuity
- Feedback after input
- Revealing hierarchy
- Drawing attention to important changes
- Making direct manipulation feel physical

Avoid motion for:

- Repeated workflows where it slows people down
- Dense data surfaces where clarity matters more
- Critical alerts that should be immediate
- Interfaces without reduced-motion support

## Choose Properties Carefully

Prefer animating:

- `transform`
- `opacity`
- `filter` only with restraint
- canvas/WebGL values when using 3D or shaders

Avoid animating:

- layout dimensions in large trees
- expensive shadows or blurs
- properties that trigger jank

## Curves And Duration

- Entering elements usually ease out.
- Exiting elements can be faster and slightly ease in.
- Direct manipulation often benefits from spring motion.
- Small UI feedback usually belongs under 200ms.
- Larger spatial transitions can sit around 250-500ms.
- Complex cinematic scenes may go longer, but should still feel interruptible.

## Interaction Details

- Motion should be interruptible.
- Hover and press states should settle quickly.
- Gesture handoffs should preserve velocity when possible.
- Reduced-motion mode should keep meaning while removing unnecessary movement.
- Do not animate everything at once; stagger only when it improves comprehension.

## Implementation Guidance

- Use Motion for most React UI transitions.
- Use GSAP for complex timelines, scroll choreography, or cross-element sequencing.
- Use Three.js or React Three Fiber for real 3D scenes, not decorative fake depth.
- Use shaders when the effect is central to the experience and can be verified visually.
- Use Remotion for video or generated motion graphics.

## Motion Review Checklist

- Does it have a purpose?
- Is it fast enough for repeated use?
- Is it interruptible?
- Does it preserve layout stability?
- Does reduced motion work?
- Does it still feel good on a mid-range device?
