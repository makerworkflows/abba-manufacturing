---
version: alpha
name: ABBA Manufacturing
colors:
  primary: "#1B2A3D"
  secondary: "#2563EB"
  tertiary: "#F97316"
  neutral: "#F9FAFB"
  surface: "#FFFFFF"
  on-surface: "#1F2937"
  on-surface-variant: "#6B7280"
  outline: "#E5E7EB"
  error: "#DC2626"
  success: "#16A34A"
typography:
  headline-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: 800
    lineHeight: 1.1
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: 700
    lineHeight: 1.2
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: 700
    lineHeight: 1.3
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: 400
    lineHeight: 1.7
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.6
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.5
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: 600
    lineHeight: 1
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: 600
    lineHeight: 1
    letterSpacing: 0.05em
rounded:
  sm: 4px
  md: 8px
  lg: 12px
  xl: 16px
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 40px
  xxl: 64px
  section: 80px
  container-max: 1200px
components:
  button-primary:
    backgroundColor: "{colors.secondary}"
    textColor: "{colors.surface}"
    typography: "{typography.label-md}"
    rounded: "{rounded.md}"
    padding: 12px 24px
  button-primary-hover:
    backgroundColor: "#1D4ED8"
  button-secondary:
    backgroundColor: transparent
    textColor: "{colors.secondary}"
    rounded: "{rounded.md}"
    padding: 12px 24px
  card-service:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.on-surface}"
    rounded: "{rounded.lg}"
    padding: "{spacing.lg}"
  badge-iso:
    backgroundColor: "{colors.success}"
    textColor: "{colors.surface}"
    typography: "{typography.label-sm}"
    rounded: "{rounded.sm}"
    padding: 4px 12px
  nav-link:
    textColor: "{colors.surface}"
    typography: "{typography.label-md}"
  nav-link-hover:
    textColor: "{colors.tertiary}"
  cta-phone:
    backgroundColor: "{colors.tertiary}"
    textColor: "{colors.surface}"
    typography: "{typography.label-md}"
    rounded: "{rounded.md}"
    padding: 14px 28px
---

# ABBA Manufacturing Design System

## Overview

ABBA Manufacturing's web presence communicates industrial reliability, ISO-certified precision, and local RGV trust. The design is clean, professional, and conversion-focused -- built for procurement managers and business owners evaluating packaging suppliers, not consumers browsing casually.

The emotional tone is: authoritative but approachable. The site should feel like walking into a well-organized, modern manufacturing facility -- everything has a purpose, nothing is decorative for its own sake.

Target audience: B2B procurement managers, business owners, operations directors searching for packaging suppliers in South Texas.

## Colors

The palette balances industrial authority with clear calls to action.

- **Primary (#1B2A3D):** Deep navy used for the navigation bar, hero backgrounds, and section headers. Conveys trust, stability, and manufacturing professionalism.
- **Secondary (#2563EB):** Clean blue used for text links, secondary buttons, and interactive elements. Provides a modern, digital-forward feel.
- **Tertiary (#F97316):** Warm orange reserved exclusively for primary CTAs -- phone buttons, quote request buttons, and the most important action per page. High contrast against the navy ensures visibility.
- **Neutral (#F9FAFB):** Light gray background for alternating content sections. Prevents visual fatigue on long-form pages.
- **Surface (#FFFFFF):** Pure white for cards, content areas, and service grids.

## Typography

The entire site uses **Inter** -- a geometric sans-serif chosen for screen clarity at all sizes, strong readability on mobile, and professional tone appropriate for B2B manufacturing.

- **Headlines:** Inter Extra Bold (800) and Bold (700) for page titles and section headers. Negative letter-spacing tightens the visual rhythm at large sizes.
- **Body:** Inter Regular (400) at 16-18px with generous line-height (1.6-1.7) for comfortable reading of service descriptions and technical content.
- **Labels:** Inter Semi-Bold (600) with positive letter-spacing for badges, navigation links, and ISO certification callouts.

Single font family keeps page weight low and load times fast -- critical for PageSpeed scores and mobile users on variable RGV network conditions.

## Layout & Spacing

The layout follows a single-column, full-width model optimized for scanning and conversion.

- **Container max-width:** 1200px centered, with 24px horizontal padding on mobile.
- **Section rhythm:** 80px vertical spacing between major sections creates clear visual breaks.
- **Card grids:** 2x2 on desktop, single column on mobile. 24px internal padding, 16px gap between cards.
- **Hero sections:** Full-width navy background with centered text, 80-100px vertical padding.
- **8px base grid:** All spacing values are multiples of 8px for consistent rhythm.

## Elevation & Depth

The design is intentionally flat. Depth is communicated through color contrast and spatial separation, not shadows.

- **Cards:** No box-shadow. White cards on neutral gray backgrounds create sufficient visual separation.
- **Navigation:** Solid navy background creates a distinct layer above page content.
- **Hover states:** Color change only (darken by 10%), no elevation shift.
- **ISO badge:** Green background on navy hero creates a layered trust signal without shadow.

## Shapes

The shape language is minimal and industrial.

- **Cards and containers:** 12px border-radius -- modern but not playful.
- **Buttons:** 8px border-radius -- tactile and clickable.
- **Badges (ISO cert):** 4px border-radius -- compact and utilitarian.
- **No circles or pill shapes** except for the full-round phone icon if used.
- **No decorative border-radius mixing** -- all elements on a page use consistent corner radius.

## Components

### Navigation
Solid navy bar with white text links. Phone CTA button in orange (tertiary) anchored to the right. Mobile hamburger menu. Logo left-aligned.

### Hero Section
Full-width navy background. White headline text (Inter 800). ISO certification badge in green. Single primary CTA button in orange. Optional subtitle in lighter gray text.

### Service Cards
White background, 12px radius, 24px padding. Bold service name as H3, descriptive paragraph below. Arranged in a 2x2 grid on desktop.

### FAQ Section
H2 section title, then repeating H3 question / paragraph answer pairs. No accordion behavior -- all answers visible for SEO extraction and AI citation.

### CTA Section
Centered text on navy or neutral background. Large headline, supporting paragraph, orange phone button. Phone number as tel: link.

### Footer
Single line with copyright, address, and website link. Minimal -- no multi-column footer needed for a manufacturing site.

## Do's and Don'ts

- Do use orange (tertiary) only for the single most important CTA per section
- Do maintain WCAG AA contrast ratios (4.5:1 minimum for body text)
- Do keep all pages under 7 seconds LCP on mobile
- Do use real manufacturing language -- "RSC boxes," "die-cut," "flute profiles" -- not generic marketing copy
- Don't use more than 2 font weights on a single page (Regular + Bold or Extra Bold)
- Don't add decorative elements, gradients, or illustrations -- the content is the design
- Don't use stock photography -- facility photos or no photos
- Don't mix rounded and sharp corners in the same view
- Don't add animation or transitions -- static, fast, professional
