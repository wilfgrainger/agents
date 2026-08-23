---
name: motion-system-design
description: Use when a website needs interaction, animation, transition, hover, press, scroll, or reduced-motion rules, especially when motion quality and mobile performance must remain consistent across the experience.
---

# Motion System Design

## Overview

Treat motion as a behavioural system, not decoration. Every animation must communicate hierarchy, feedback, continuity, causality, or brand character. If movement has no job, remove it.

## Inputs

Identify:
- brand personality
- device and browser mix
- page types and interaction density
- important state changes
- performance constraints
- accessibility requirements
- existing animation libraries or framework

## Motion Decision Test

Before adding motion, answer:
1. What does the movement explain?
2. What user action or state caused it?
3. Would the interface be less understandable without it?
4. Does it delay reading or action?
5. Does it remain acceptable on a modest mobile device?

## System

### Entry animations
Use sparingly for hierarchy. Prefer grouped, short reveals over a parade of individually animated elements. The critical headline and CTA must never wait on a theatrical entrance.

### Scroll motion
Use when it clarifies narrative progression or spatial relationships. Avoid scroll-jacking, mandatory scrub sequences, and movement that fights normal reading.

### Hover
Enhance discoverability and confidence without moving layout. Never make hover the only way to reveal essential information.

### Press/tap
Provide immediate tactile feedback. Keep transformations subtle enough that controls remain visually stable.

### State transitions
Animate meaningful changes such as open/closed, selected/unselected, loading/complete, or route continuity. Preserve spatial context.

### Page transitions
Use only when they do not delay navigation. Prefer short continuity cues to cinematic interstitials.

### Baseline: never move
Keep these stable by default:
- body copy while reading
- primary navigation position
- form labels and validation copy
- critical CTAs awaiting input
- dense data
- anything whose movement impairs scanning

## Performance Budget

Design for transform and opacity first. Minimise layout-triggering animation and concurrent effects. Define a reduced-motion state from the beginning, not as a patch.

On mobile:
- prioritise input responsiveness and scroll smoothness
- reduce simultaneous effects
- remove nonessential parallax
- avoid large continuously animated assets
- pause off-screen work

## Output Contract

Return:
1. Motion personality in three adjectives
2. Motion principles
3. Timing/easing scale
4. Entry rules
5. Scroll rules
6. Hover/focus/press rules
7. Component/state transitions
8. Page transition rules
9. Reduced-motion behaviour
10. Mobile performance constraints
11. “Never animate” list

## Quality Bar

Motion should make the interface feel inevitable. It must never tax comprehension in exchange for spectacle.
