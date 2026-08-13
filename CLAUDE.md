# lockbolt-calculator

Two standalone, static HTML pages. No build system, no package manager, no dependencies, no tests, no linter.

- `index.html` — Lockbolt Shear & Tensile Strength Calculator (EN8D steel). Computes cross-sectional area from bolt diameter, then tensile/shear force from UTS and shear strength inputs. All logic is in an inline `<script>` block (`calculateStrength()`).
- `portfolio.html` — Investment Portfolio Timeline projector. Compounds a monthly contribution at a given annual return over a time horizon and renders a year-by-year table. Logic is in an inline `<script>` block (`projectPortfolio()`).

Both pages are self-contained (inline `<style>` and `<script>`, no external assets, no CDN links) and can be opened directly in a browser — no server or install step required.

When editing, keep changes inline in the existing `<script>`/`<style>` blocks rather than introducing a build step, unless the user explicitly asks for one.
