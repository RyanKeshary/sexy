# Sexy: Unified Design Intelligence Rules

When working on UI, design, frontend styling, animations, or layouts in this workspace:

## 1. Golden Law: Automatic Micro-Interactions, UI/UX Excellence & Polish
**It goes without saying or explicit prompting**: every interface generated or touched by Sexy MUST ship with high-craft UI/UX, great micro-interactions, and deliberate animations, transitions, and effects.
- **Never wait for the user to ask for polish**: Polish is the baseline, not an extra step.
- **Fluid transitions**: Add subtle hover elevations, active press scales (`active:scale-[0.98]`), border-glow highlights, and spring-eased transitions (150–250ms).
- **Physical precision**: Enforce concentric radii ($R_{inner} = R_{outer} - padding$), subpixel font smoothing (`antialiased`), tabular numerals (`tabular-nums`) for dynamic metrics, and `text-wrap: balance` on headlines.

## 2. Landing Pages: Horizontal Scroll & 3D Spatial Interactions
Whenever creating, enhancing, or modifying landing pages:
- **Mandatory Horizontal Scroll Sections**: Always include **1 to 2 horizontal scroll sections**. Keep them concise, punchy, and meaningful (e.g. interactive product feature carousels, timeline journeys, or pinned horizontal gallery reveals). Ensure smooth scroll gestures and touch/drag responsiveness.
- **3D Spatial Interactions**: Always incorporate rich 3D elements and depth interactions — such as multi-layer parallax depth planes, subtle 3D card tilt on mouse movement (`transform: perspective(1000px) rotateX(...) rotateY(...)`), depth-mapped lighting gradients, interactive 3D canvas/Three.js/Spline focal objects, or dimensional glass-morphic surfaces.
- **Sensory & Visual Beauty**: Make the page breathtaking, distinctive, and emotionally engaging. Avoid generic AI-template layouts.

## 3. Activate the Unified 6-Engine Pipeline
- **Tokens & Architecture**: Use `design-md` and `ui-ux-pro-max` for cohesive token hierarchies (primitive → semantic → component).
- **Character & Direction**: Follow `hallmark` to ensure human, distinct, non-generic designs with zero AI slop.
- **Motion & Staging**: Follow `scroll-craft` for hero depth, dimensional planes, and cinematic scroll kinetics.
- **Micro-Details**: Apply `make-interfaces-feel-better` rules (concentric radii, spring curves, hit areas, optical alignment).
- **Craft Floor**: Apply `impeccable` design director standards before committing UI code.
- **Comprehensive Reference**: Refer to all bundled designing skills (`design-md`, `hallmark`, `scroll-craft`, `make-interfaces-feel-better`, `impeccable`, `ui-ux-pro-max`) whenever formulating solutions.

## 4. No Conflicts
- Honor the project's existing stack (Tailwind, CSS Modules, or Styled Components).
- Do not inject conflicting animation frameworks.
- Specific project design specifications (e.g. `DESIGN.md`) override generic aesthetic defaults.
