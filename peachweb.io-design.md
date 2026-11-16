---
version: alpha
name: Peachweb
description: A bright, futuristic landing-page system with airy spacing, soft neutrals, and a bold indigo core.
colors:
  primary: "#20174e"
  secondary: "#6b5bd2"
  tertiary: "#00f0ff"
  neutral: "#ffffff"
  surface: "#f5f1ec"
  on-surface: "#20174e"
  error: "#d64545"
  border: "#e5e7eb"
  accent: "#00f0ff"
typography:
  headline-display:
    fontFamily: Neuehaasdisplaylight
    fontSize: 72px
    fontWeight: 400
    lineHeight: 0.95
    letterSpacing: -0.03em
  headline-lg:
    fontFamily: Neuehaasdisplaylight
    fontSize: 56px
    fontWeight: 400
    lineHeight: 1
    letterSpacing: -0.03em
  headline-md:
    fontFamily: Neuehaasdisplayroman
    fontSize: 32px
    fontWeight: 700
    lineHeight: 38px
    letterSpacing: 0px
  headline-sm:
    fontFamily: Neuehaasdisplayroman
    fontSize: 24px
    fontWeight: 700
    lineHeight: 29px
    letterSpacing: 0px
  body-lg:
    fontFamily: Neuehaasdisplayroman
    fontSize: 18px
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: 0px
  body-md:
    fontFamily: Neuehaasdisplayroman
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.4
    letterSpacing: 0px
  body-sm:
    fontFamily: Neuehaasdisplayroman
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.4
    letterSpacing: 0px
  label-lg:
    fontFamily: Neuehaasdisplayroman
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.2
    letterSpacing: 0px
  label-md:
    fontFamily: Neuehaasdisplayroman
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.2
    letterSpacing: 0px
  label-sm:
    fontFamily: Neuehaasdisplayroman
    fontSize: 12px
    fontWeight: 400
    lineHeight: 1.2
    letterSpacing: 0px
  overline:
    fontFamily: Neuehaasdisplayroman
    fontSize: 12px
    fontWeight: 400
    lineHeight: 1
    letterSpacing: 0.08em
rounded:
  none: 0px
  sm: 4px
  md: 8px
  lg: 12px
  xl: 16px
  full: 9999px
spacing:
  xs: 8px
  sm: 16px
  md: 32px
  lg: 58px
  xl: 120px
components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.neutral}"
    typography: "{typography.label-lg}"
    rounded: "{rounded.sm}"
    padding: 8px 16px
    height: 40px
  button-primary-hover:
    backgroundColor: "{colors.secondary}"
    textColor: "{colors.neutral}"
    typography: "{typography.label-lg}"
    rounded: "{rounded.sm}"
    padding: 8px 16px
    height: 40px
  button-secondary:
    backgroundColor: "transparent"
    textColor: "{colors.primary}"
    typography: "{typography.label-lg}"
    rounded: "{rounded.sm}"
    padding: 8px 16px
    height: 40px
  button-link:
    backgroundColor: "transparent"
    textColor: "{colors.primary}"
    typography: "{typography.label-lg}"
    rounded: "{rounded.none}"
    padding: 0px
  card:
    backgroundColor: "{colors.neutral}"
    textColor: "{colors.on-surface}"
    rounded: "{rounded.md}"
    padding: 16px
  input:
    backgroundColor: "{colors.neutral}"
    textColor: "{colors.on-surface}"
    rounded: "{rounded.sm}"
    padding: 8px 16px
    height: 40px
---

# Peachweb

## Overview
Peachweb feels playful, futuristic, and premium, with a strong “creative tech” personality. The visual tone is airy and expansive, balancing a minimal UI shell with vivid, dreamlike 3D imagery. It is clearly aimed at design-forward SaaS buyers who want something expressive but still easy to scan and act on.

## Colors
- **Primary (#20174e):** A deep indigo used for nav text, body copy, outlines, and the solid CTA button. It anchors the brand and keeps the interface legible against the luminous visuals.
- **Secondary (#6b5bd2):** A softer violet used as an interactive accent and supportive hover tone. It helps maintain the purple family without overpowering the composition.
- **Tertiary / Accent (#00f0ff):** A bright cyan highlight that adds a sci-fi shimmer to the palette. Use it sparingly for small emphasis, glow-like details, or attention cues.
- **Neutral (#ffffff):** Clean white is used for surfaces, cards, button text, and high-contrast overlays. It preserves the light, open feeling of the page.
- **Surface (#f5f1ec):** A warm off-white surface tone that can sit behind content blocks when pure white feels too stark.
- **On-surface (#20174e):** The primary readable text color on light backgrounds. It keeps typography crisp and calm.
- **Border (#e5e7eb):** A soft neutral border used for cards and subtle separation. It supports structure without creating hard seams.
- **Error (#d64545):** A restrained red for destructive or validation states. It should remain functional, not decorative.

## Typography
The system is built around a refined sans-serif family, with custom Neue Haas Display light and roman styles giving the brand its contemporary editorial feel. Headlines should lean light and spacious at large sizes, while smaller headings can use a stronger weight for clarity and hierarchy. Body copy stays regular-weight and compact, matching the clean, modern interface.

The display style on the hero is especially important: large, lightweight headlines create elegance and let the colorful 3D art breathe. Labels and buttons use the same sans family with no uppercase transformation by default. When overline-style treatment is needed, use subtle positive letter spacing rather than heavy styling.

## Layout
The page uses a wide, fluid landing-page layout with generous negative space and edge-to-edge hero imagery. Content is aligned in clear horizontal bands: top navigation, large central art, then lower-left messaging and lower-right utility cards. Spacing follows a relaxed rhythm using 8px, 16px, 32px, 58px, and 120px steps for small internal gaps through to major section breathing room.

Containers should feel expansive rather than boxed in; avoid overly narrow max-widths that compress the hero. Navigation and CTA clusters are compact and pill-like, while the main hero area should remain open and cinematic. Cards and small panels use modest internal padding so they don’t compete with the artwork.

## Elevation & Depth
Depth is achieved more through imagery, glow, and tonal contrast than through heavy UI shadows. The observed interface is mostly flat: buttons, cards, and nav elements rely on borders, color, and spacing instead of strong drop shadows. Where elevation is needed, use very soft shadowing at most, but prefer clean layering and contrast.

The illustration and reflective orbs carry the visual drama, so the UI should stay restrained. Light borders and subtle tonal shifts define separations without breaking the atmospheric feel.

## Shapes
The corner-radius language is soft and modern, with small radii rather than aggressive rounding. Interactive controls use 4px corners for a crisp, understated feel, while cards can open up slightly to 8px. Full pills are appropriate for floating chips, utility buttons, and nav group containers.

Overall, the geometry should feel tidy and deliberate, not bubbly. Keep shapes minimal so the vivid gradients and 3D objects remain the expressive part of the interface.

## Components
Buttons are a core brand signal. Use `button-primary` for the main filled CTA: deep indigo background, white text, 8px vertical and 16px horizontal padding, 40px height, and 4px radius. Use `button-secondary` for outlined actions with transparent fill and indigo border/text. Use `button-link` for simple nav/login actions with no box treatment and an underlined or plain text style depending on context. Hover states should move toward the softer violet tone via `button-primary-hover`.

Cards should follow the `card` token: white background, 1px neutral border, 8px radius, and 16px padding. Keep them lightweight and informational, not heavily elevated. If a card sits over a busy image area, increase contrast with a cleaner background rather than adding shadow.

Inputs should match the button language with 4px rounding, clear borders, and comfortable 16px horizontal padding. Use the same 40px control height for consistency across forms and small action rows. Focus states should be clear and accessible, but visually quiet.

Navigation items should remain text-forward and compact, with the primary CTA separated from secondary links. For chips or floating utility elements, use pill shapes and high-contrast text on solid fills. Any tooltip or helper bubble should remain simple, with minimal chrome and a soft, friendly presence.

## Do's and Don'ts
- Do keep the interface airy and let the hero artwork dominate the page.
- Do use the deep indigo primary color for core actions and important text.
- Do prefer flat or lightly bordered surfaces over heavy shadows.
- Do keep button sizing consistent at 40px height with compact horizontal padding.
- Don't introduce harsh blacks or highly saturated unrelated colors.
- Don't over-round controls; maintain the crisp 4px to 8px shape language.
- Don't crowd the layout with dense card grids or narrow containers.
- Don't make typography overly bold or uppercase-heavy; preserve the light editorial feel.