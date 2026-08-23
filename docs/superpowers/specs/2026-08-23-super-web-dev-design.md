# Super Web Dev Pack Design

## Goal

Replace the original seven independent website skills with a coherent master capability that routes narrow tasks efficiently and coordinates end-to-end website work without imposing a house style.

## Architecture

Use a flat Agent Skills namespace with one orchestrator (`super-web-dev`) and eight independently discoverable specialists. The orchestrator owns routing, shared laws, phase ordering, and completion criteria. Specialists own judgement-heavy domains and remain useful alone.

## Decisions

1. Replace `luxury-creative-direction` with `web-creative-direction` so the pack supports premium, editorial, brutalist, playful, dense, product-led, and conventional directions.
2. Add `scroll-experience-design` rather than bloating general motion guidance.
3. Keep conversion, copy, build planning, CRO, and launch separate.
4. Integrate Scroll Craft concepts at methodology level only; do not vendor its runtime, scripts, templates, or generation pipeline.
5. Make anti-template evaluation structural: grammar, navigation, hero, sequence, ending, signature interaction.
6. Require rendered verification for stateful/scroll experiences.
7. Keep routing conditional so narrow requests do not trigger the full pipeline.

## Shared quality model

Optimise for brand specificity, narrative clarity, honest persuasion, structural distinctiveness, accessible interaction, mobile composition, performance, resilient implementation, and observable conversion outcomes.

## Scroll methodology

Scroll-driven work adds an explicit experience grammar with prohibitions, beat-by-beat emotional curve, one engineered peak, brand-specific signature interaction, deliberate pacing, device choice per beat, state-by-state browser verification, and reduced-motion/mobile equivalents.

## Out of scope

No proprietary frontend framework, mandatory scrollytelling, universal design system, generated-assets default, fabricated conversion evidence, or vendored Scroll Craft runtime.
