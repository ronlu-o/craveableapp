# Craveable Support Style (Primer-inspired)

## Palette tokens
- `--token-ca491423-ed69-4073-9859-26d521a5ce20` `#ff6b00`: Accent (buttons, brand dot).
- `--token-f0aa30d0-ed2d-4ee4-8f5a-0a4b541f6ab8` `#fafafa` (light) / `#0d0d0d` (dark): Page background.
- `--token-3b0f98aa-c16a-4b12-80a4-e1056304b9fa` `#000` / `#fafafa`: Primary text.
- `--token-59e0057d-33bd-4745-b3ad-1acb6546c5ce` `#333` / `#c2c2c2`: Secondary text.
- `--token-ec5340ae-6550-4602-9d99-b1711e50337e` `#ccc` / `#2b2b2b`: Borders, dividers.
- `--token-e102ed96-0129-4d91-a500-6c51cf464136` `#f0f0f0` / `#121212`: Card background.
- `--token-a3d81e1f-e0a9-4a90-8faf-1201ae348f16` `#ff6a004d`: Soft accent glow for the brand dot.
- `--token-dcda7a06-a063-4e13-bdb5-b6cc4a0e2211` `#757575` / `gray`: Muted copy.
- `--token-490c8163-6119-48f4-a4f6-2848bc2c1f58` `#fafafa59`: Nav blur tint.

Dark mode swaps are handled with `prefers-color-scheme`.

## Typography
- Font stack: Geist (400/600/700/800) then Inter (400/600) then system.
- Base body: 15px, 1.6 line height, antialiased.
- Headings: tight letter-spacing (-0.02em), H1 clamp(32px, 4vw, 44px); H3 18px.
- Eyebrow: uppercase, 13px, accent color, 0.04em tracking.

## Layout and spacing
- Page max width: 960px with 20-36px side padding.
- Nav: sticky top, backdrop blur 5px, subtle border, inline nav links plus pill CTA.
- Sections: hero with stacked spacing, divider line, then card grids.
- Grid: `grid-template-columns: repeat(auto-fit, minmax(260px, 1fr))`, 16px gaps.

## Components
- Pill: rounded (999px), 10-14px padding, border 1px divider, card background fill; used as the sole nav CTA.
- Button primary: accent fill, white text, soft drop shadow.
- Button secondary: bordered, neutral fill, no heavy shadow.
- Card: neutral background, 1px divider border, 6px radius, 18px padding, 8px vertical gaps, subtle multi-stop shadow (0.6/2.29/10px stack).
- Inline list chips: bordered, 8-10px padding, 6px radius.
- Divider: 1px line using divider token.
- Footer: two-line flex row, muted text; wraps on small screens.

## Content model (this page)
- Nav CTA: single email pill to rzbyyy0@gmail.com.
- Hero: eyebrow, main headline, subhead, CTA buttons, SLA pill.
- Support grid: top fixes, what to send, contact channel.
- Updates: release tracker inline chips with below iOS 26 support, more LUTs, custom LUT imports plus beta note.

## Notes for future pages
- Reuse the grid, card, and pill classes for consistent spacing.
- Keep accent usages sparse (CTA, brand dot, eyebrow).
- Maintain plenty of white space; avoid background textures to match Primer's clean aesthetic.
