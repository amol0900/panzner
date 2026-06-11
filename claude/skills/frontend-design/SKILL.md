---
name: frontend-design
description: Create distinctive, production-grade frontend interfaces with high design quality. Use this skill when the user asks to build web components, pages, artifacts, posters, or applications (examples include websites, landing pages, dashboards, React components, HTML/CSS layouts, or when styling/beautifying any web UI). Generates creative, polished code and UI design that avoids generic AI aesthetics.
license: Complete terms in LICENSE.txt
---

This skill guides creation of distinctive, production-grade frontend interfaces that avoid generic "AI slop" aesthetics. Implement real working code with exceptional attention to aesthetic details and creative choices.

The user provides frontend requirements: a component, page, application, or interface to build. They may include context about the purpose, audience, or technical constraints.

## Design Thinking

Before coding, understand the context and commit to a BOLD aesthetic direction:
- **Purpose**: What problem does this interface solve? Who uses it?
- **Tone**: Commit to a distinct direction: brutally minimal, maximalist chaos, luxury/refined, lo-fi/zine, dark/moody, soft/pastel, editorial/magazine, brutalist/raw, retro-futuristic, handcrafted/artisanal, organic/natural, art deco/geometric, playful/whimsical, industrial/utilitarian, etc. There are infinite varieties to start from and surpass. Use these as inspiration, but the final design should feel singular, with every detail working in service of one cohesive direction.
- **Constraints**: Technical requirements (framework, performance, accessibility).
- **Differentiation**: What makes this UNFORGETTABLE? What's the one thing someone will remember?

**CRITICAL**: Choose a clear conceptual direction and execute it vigorously. Bold maximalism and refined minimalism both work - the key is intentionality, not intensity.

Then implement working code (HTML/CSS/JS, React, Vue, etc.) that is:
- Production-grade, functional, and responsive
- Visually striking and memorable
- Cohesive with a clear aesthetic point-of-view
- Meticulously refined in every detail
- Fully accessible to all users, meeting WCAG 2.1 AA as a baseline standard

## Frontend Aesthetics Guidelines

Focus on:
- **Typography**: Typography carries the design's singular voice. Choose fonts with interesting personality. Default fonts signal default thinking: skip Arial, Inter, Roboto, system stacks. Font choices should be inseparable from the aesthetic direction. Display type should be expressive, even risky. Body text should be legible, refined. Pair them like actors in a scene. Work the full typographic range: size, weight, case, spacing to establish hierarchy. Body text must be a minimum 16px; never sacrifice legibility for aesthetics.
- **Color & Theme**: Commit to a cohesive aesthetic. Palettes should take a clear position: bold and saturated, moody and restrained, or high-contrast and minimal. Lead with a dominant color, punctuate with sharp accents. Avoid timid, non-committal distributions. Use CSS variables for consistency. **All text must meet WCAG 2.1 AA contrast ratios: 4.5:1 for normal text, 3:1 for large text (18px+ bold or 24px+) and UI components.** Verify contrast for every text/background pairing, including text over gradients, images, or translucent layers — sample the worst-case region. Never rely on color alone to convey meaning: pair color with text labels, icons, patterns, or shapes so information is accessible to users with color vision deficiencies.
- **Motion**: Use animations for effects and micro-interactions. Prioritize CSS-only solutions for HTML. Use Motion library for React when available. Focus on high-impact moments: one well-orchestrated page load with staggered reveals (animation-delay) creates more delight than scattered micro-interactions. Use scroll-triggering and hover states that surprise. **Always wrap motion in `prefers-reduced-motion` media queries** — provide a static fallback so animations never cause harm for users with vestibular disorders.
- **Spatial Composition**: Unexpected layouts. Asymmetry. Overlap and z-depth. Diagonal flow. Grid-breaking elements. Dramatic scale jumps. Full-bleed moments. Generous negative space OR controlled density.
- **Backgrounds & Visual Details**: Create atmosphere and depth rather than defaulting to solid colors. Add contextual effects and textures that match the overall aesthetic. Apply creative forms like gradient meshes, noise and grain overlays, geometric patterns, layered transparencies and glassmorphism, dramatic or soft shadows and glows, parallax depth, decorative borders and clip-path shapes, print-inspired textures (halftone, duotone, stipple), knockout typography, and custom cursors. When text sits over atmospheric backgrounds, ensure contrast is maintained — darken, blur, or add a scrim layer as needed.
- **Accessibility & Interaction**: Semantic HTML is non-negotiable: use `<nav>`, `<main>`, `<header>`, `<footer>`, `<section>`, `<article>`, `<button>`, and heading hierarchy (`h1`–`h6`) correctly. Every interactive element must be keyboard-reachable and operable. Focus indicators must be clearly visible — design them as a feature, not an afterthought; a bold outline or branded ring can be beautiful and functional. Add ARIA labels, roles, and `aria-describedby` where native semantics are insufficient (custom controls, icon-only buttons, modals, carousels). Images need descriptive `alt` text; decorative images use `alt=""`. Form inputs require associated `<label>` elements.

NEVER use generic AI-generated aesthetics like overused font families (Inter, Roboto, Arial, Space Grotesk, system fonts), cliched color schemes (particularly purple gradients on white backgrounds), predictable layouts and component patterns, and cookie-cutter designs that lack context-specific character.
NEVER produce inaccessible code: no missing focus styles, no color-only cues, no non-semantic `<div>` soup, no animation without `prefers-reduced-motion` guards, no contrast failures.
INSTEAD: distinctive fonts. Bold, committed palettes that still pass contrast. Layouts that surprise. Bespoke details. Every choice rooted in rich context. Accessibility woven in from the first line of code, not bolted on at the end.

Build creatively on the user's intent, and make unexpected choices that feel genuinely designed for the context. Every design should feel distinct. Actively explore the full range: light and dark themes, unexpected font pairings, substantially varied aesthetic directions. Let the specific context drive choices, NOT familiar defaults. 

**IMPORTANT**: Match implementation complexity to the aesthetic vision. Maximalist designs need elaborate code with extensive animations and effects. Minimalist or refined designs need restraint, elegance, and precision. All designs need careful attention to spacing, typography, and subtle details. Excellence comes from executing the vision well.

**WCAG 2.1 AA is the floor, not the ceiling.** Before finalising any design, mentally audit: Are all contrast ratios met? Are focus states visible and on-brand? Is the tab order logical? Do all interactive elements have accessible names? Is motion guarded? Does every icon or color cue have a text or shape equivalent? A breathtaking design that excludes users is an incomplete design.

Remember: Claude is capable of extraordinary, award-worthy creative work. Don't hold back, show what's truly possible, and commit relentlessly to a distinctive, unforgettable, and inclusive vision.
