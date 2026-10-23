# CodeNest Design System

## Product and audience
**Product:** CodeNest, a fictional beginner-friendly technology learning platform.  
**Target audience:** Students and career-switchers aged roughly 16–28 who want practical coding skills, guided learning paths, and portfolio-ready projects.

## Brand idea
Learn a little. Build a lot. The design uses a calm, welcoming visual language so beginners feel encouraged rather than overwhelmed.

## Color palette
- Primary purple: `#6557F5`
- Deep purple: `#342C91`
- Purple tint: `#EEEDFF`
- Lavender tint: `#F4F3FF`
- Main text: `#17182D`
- Secondary text: `#74778C`
- Page background: `#F8F9FC`
- Surface: `#FFFFFF`
- Success green: `#159B72`
- Success tint: `#DDF9ED`
- Border: `#E7E8F1`

## Typography
- Font family: Inter (fallback: Arial, sans-serif)
- H1: 58 px / ExtraBold (desktop), 37 px / ExtraBold (mobile)
- H2: 32 px / ExtraBold
- Card title: 20 px / Bold
- Body: 16–18 px / Regular
- Small labels: 10–12 px / Bold, uppercase where appropriate

## Spacing and shape
- Base spacing scale: 4, 8, 12, 16, 24, 32, 48, 64 px
- Main content max width: 1280 px
- Desktop page side margin: 80 px
- Mobile page side margin: 16 px
- Card radius: 18–22 px
- Button radius: 12–14 px
- Header radius: 22 px
- Buttons have at least 44 px height.

## Components to create in Figma
1. `Button / Primary` — purple fill, white label, 12 px radius, horizontal Auto Layout with 16 px padding and 12 px gap.
2. `Button / Secondary` — white fill, subtle border, dark label, same dimensions as primary.
3. `Feature Card / Learn by Doing` — icon tile, title, description, text link; vertical Auto Layout, 24 px padding, 16 px gap.
4. `Feature Card / Real Projects` — same structure, alternate icon and accent.
5. `Feature Card / Confidence` — same structure, alternate icon and accent.
6. `Course Card / Web Development`, `Course Card / Python Fundamentals`, `Course Card / UI/UX Foundations` — top illustration tile, title, category, metadata.
7. `Header / Desktop` and `Header / Mobile`.

## Auto Layout recipe
- Header: horizontal Auto Layout; space between; vertical alignment center; padding 16–24 px.
- Button: horizontal Auto Layout; center aligned; padding 12 px 18 px.
- Feature card: vertical Auto Layout; padding 24 px; gap 14–16 px; width fill container on mobile.
- Feature-card row: horizontal Auto Layout; gap 24 px on desktop; stack vertically with 16 px gap on mobile.
- Course cards: vertical Auto Layout; padding 16 px; gap 12 px.
- Main sections: vertical Auto Layout; padding 32–48 px; gap 24 px.
- Footer / CTA: horizontal Auto Layout on desktop; vertical on mobile.
