# CodeNest — Responsive Product Landing Page (IPS UI/UX with Figma)

A responsive landing-page design for **CodeNest**, a fictional beginner-friendly technology learning platform. This repository contains desktop and mobile visual references, design tokens, design rationale, and a working static website preview.

## Deliverables
- `figma/CodeNest_Desktop_1440x1900.svg` — desktop design reference (1440 px wide)
- `figma/CodeNest_Mobile_390x2350.svg` — mobile design reference (390 px wide)
- `docs/DESIGN_SYSTEM.md` — shared colors, typography, spacing, and component/Auto Layout recipe
- `docs/DESIGN_RATIONALE.md` — target audience and design choices
- `index.html`, `styles.css`, `script.js` — responsive browser preview

## Product and target audience
CodeNest helps students and beginners learn coding through short lessons, guided learning paths, and portfolio-ready projects. The target audience is students and career-switchers roughly aged 16–28.

## Preview locally
Open `index.html` in a browser. No build step or dependencies are required.

## Import the design references into Figma
1. In Figma, create a new design file and name it `CodeNest — Responsive Landing Page`.
2. Drag `figma/CodeNest_Desktop_1440x1900.svg` onto the canvas, or use **File → Place image** if available. Repeat for the mobile SVG.
3. These SVGs are visual references. To satisfy the Auto Layout and reusable-component requirement, rebuild the elements as native Figma frames/components:
   - Create `Button / Primary` and `Button / Secondary`.
   - Create three reusable feature-card components: `Feature Card / Learn by Doing`, `Feature Card / Real Projects`, `Feature Card / Confidence`.
   - Create course-card components and desktop/mobile header frames.
   - Apply Auto Layout using the measurements in `docs/DESIGN_SYSTEM.md`.
4. Create shared color and text styles from the same design-system file.
5. Verify the desktop and mobile frames at 100% zoom and inspect the layer names before submission.

> Important: SVG import preserves the appearance, not Figma-native Auto Layout, component instances, or editable text structure in every Figma version. The component and Auto Layout setup must be made as native Figma objects before claiming those specific Figma requirements are complete.

## GitHub Pages deployment
1. Create a public GitHub repository (for example, `codenest-ips-figma-landing-page`).
2. Upload the contents of this folder to the repository root. Make sure `index.html` is at the root.
3. Open **Settings → Pages**.
4. Under build and deployment, choose **Deploy from a branch**, branch `main`, folder `/(root)`, then Save.
5. Wait for the deployment URL to appear in the Pages section.

Official guide: https://docs.github.com/en/pages

## Suggested submission checklist
- [ ] Desktop frame exists in the Figma file.
- [ ] Header includes logo, navigation, and CTA.
- [ ] Hero includes heading, description, illustration, and primary button.
- [ ] At least three feature cards and a footer/CTA are present.
- [ ] Header, buttons, cards, and content sections use native Figma Auto Layout.
- [ ] At least three reusable Figma components are created.
- [ ] Shared color and typography styles are saved in Figma.
- [ ] Target audience and design rationale are included.
- [ ] GitHub repository link is submitted in the class Google Sheet.
