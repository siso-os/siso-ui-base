<!-- opendesign: title="Example" description="A neutral starting tenant: warm-neutral surfaces, one accent, deliberate non-round values." -->
# Example tenant DNA: the exact values, with the why

Copy this folder to `tenants/<your-project>/` and replace every value with your product's own. Agents read this file as the
authority on what is right for the project; the gates grep variations against it.

> **The meta-rule:** every value should be deliberate. Round defaults (16px, 700, #fff, 8px radius) are the signature of a
> value nobody chose.

## Color
- Surface `#16161a`, raised surface `#1d1d22`, hairline `rgba(255,255,255,0.07)`: warm-neutral, never pure black.
- Text `#ececf1`, muted text `#9a9aa6`.
- One accent, `#7c6cf2`, used only for the primary action and the active state.

## Type
- Body 13.5px / 1.45, weight 450. Labels 11.5px, weight 560, letter-spacing 0.02em.
- Numbers use tabular figures.

## Space and shape
- Spacing steps 3, 6, 10, 14, 22px. Radius 7px for controls, 11px for panels.

## Motion
- 140ms ease-out for state changes; nothing moves on its own.
