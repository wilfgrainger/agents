# Super Web Dev

A master agent-skill pack for designing, building, verifying, improving, and launching distinctive high-quality websites.

This replaces the original seven-skill Luxury Website bundle with one orchestration skill plus eight focused specialists. The goal is not a house style. The goal is a repeatable way to produce websites that fit the brand, convert honestly, feel deliberate, perform well, and do not collapse into the same AI-generated skeleton.

## Master skill

`super-web-dev` is the entry point whenever a website request spans more than one discipline or the correct specialist is unclear.

## Specialists

1. `web-creative-direction` — brand, audience, competitive position, visual system, page structure, experience grammar
2. `conversion-design` — first-ten-seconds clarity, hero, proof, CTA hierarchy
3. `scroll-experience-design` — emotional arc, scroll narrative, interaction grammar, signature move, timeline verification
4. `motion-system-design` — motion language, component states, transitions, reduced motion, performance
5. `conversion-copywriting` — awareness, objections, evidence, section copy, microcopy
6. `frontend-build-planning` — component architecture, responsive rules, loading, accessibility, implementation sequence
7. `conversion-audit` — journey friction, trust, measurement, prioritised experiments
8. `website-launch-optimization` — launch readiness, first-30-day learning loop, feedback, stopping rules

## Default routes

```text
NEW / REDESIGN
super-web-dev
  → web-creative-direction
  → conversion-design
  → scroll-experience-design   (only when the journey earns it)
  → motion-system-design
  → conversion-copywriting
  → frontend-build-planning
  → conversion-audit
  → website-launch-optimization

EXISTING SITE
super-web-dev
  → conversion-audit
  → only specialists implicated by evidence
  → frontend-build-planning
  → verify again

SCROLL / EXPERIENTIAL
super-web-dev
  → web-creative-direction
  → scroll-experience-design
  → conversion-design
  → motion-system-design
  → frontend-build-planning
  → rendered timeline verification
```

The route is conditional, not ceremonial. Do not load every specialist for a one-section task.

## Shared laws

- **Brand over house style.** Do not make “our kind of website.”
- **Journey over section inventory.** Every section must change what the visitor knows, feels, believes, or can do.
- **Evidence over invention.** Never fabricate testimonials, customers, statistics, awards, scarcity, dashboards, or research.
- **Feeling before device.** Choose interaction because it serves the emotional/narrative job.
- **One engineered peak.** Constant spectacle produces no memorable moment.
- **Conversion without coercion.** No dark patterns, fake urgency, or deceptive defaults.
- **Mobile is a composition, not a shrink.**
- **Reduced motion preserves meaning.**
- **Accessibility and performance are design constraints.**
- **Rendered behaviour is the truth.** Verify actual states, scroll positions, focus states, responsive layouts, loading states, and changing media.
- **Distinctiveness is structural.** New colours and imagery on the same skeleton are a reskin.

## Anti-template gate

Before approving a direction, compare it with recent work across experience grammar, navigation model, hero behaviour, beat sequence, ending/CTA pattern, and signature interaction. If the new design differs only in palette, imagery, copy, or reordered middle sections, redesign the structure.

## External influence

The scroll-experience methodology is informed in part by Nate Herk's MIT-licensed `scroll-craft` project. We intentionally do not vendor its engine, scripts, or asset-generation pipeline. See `ATTRIBUTION.md`.

## Repo structure

```text
AGENTS.md
README.md
ATTRIBUTION.md
VALIDATION.md
skills/
  super-web-dev/
  web-creative-direction/
  conversion-design/
  scroll-experience-design/
  motion-system-design/
  conversion-copywriting/
  frontend-build-planning/
  conversion-audit/
  website-launch-optimization/
docs/superpowers/
  specs/
  plans/
```
