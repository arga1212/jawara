---
name: Jawara Semesta Identity
colors:
  surface: '#f8f9ff'
  surface-dim: '#cbdbf5'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e5eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d3e4fe'
  on-surface: '#0b1c30'
  on-surface-variant: '#45474c'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#75777d'
  outline-variant: '#c5c6cd'
  surface-tint: '#545f73'
  primary: '#091426'
  on-primary: '#ffffff'
  primary-container: '#1e293b'
  on-primary-container: '#8590a6'
  inverse-primary: '#bcc7de'
  secondary: '#0058be'
  on-secondary: '#ffffff'
  secondary-container: '#2170e4'
  on-secondary-container: '#fefcff'
  tertiary: '#111516'
  on-tertiary: '#ffffff'
  tertiary-container: '#26292b'
  on-tertiary-container: '#8d9092'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d8e3fb'
  primary-fixed-dim: '#bcc7de'
  on-primary-fixed: '#111c2d'
  on-primary-fixed-variant: '#3c475a'
  secondary-fixed: '#d8e2ff'
  secondary-fixed-dim: '#adc6ff'
  on-secondary-fixed: '#001a42'
  on-secondary-fixed-variant: '#004395'
  tertiary-fixed: '#e0e3e5'
  tertiary-fixed-dim: '#c4c7c9'
  on-tertiary-fixed: '#191c1e'
  on-tertiary-fixed-variant: '#444749'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.02em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 40px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
---

## Brand & Style

The design system is anchored in **Minimalist Modern Corporate** aesthetics, tailored for a high-end IT consultancy. It prioritizes clarity, precision, and a sense of "quiet authority." The visual language avoids decorative clutter, focusing instead on purposeful whitespace and premium typography to communicate reliability and technical expertise.

The target audience consists of enterprise executives and technical stakeholders who value efficiency and professional rigor. The UI should evoke a sense of calm, structured intelligence—moving away from the frantic energy of consumer apps toward a focused, SaaS-inspired productivity environment.

## Colors

The palette is restrained and sophisticated, utilizing high-contrast neutrals to establish hierarchy.

- **Primary (#1e293b):** A deep Navy Blue used for primary navigation, headings, and high-emphasis components. It represents stability and corporate depth.
- **Action (#3b82f6):** A vibrant Blue accent used sparingly for interactive elements like primary buttons, links, and active states to guide user focus.
- **Surface (#f8fafc):** A very light cool gray used for background sections, cards, and subtle UI partitioning to maintain a "clean" feel.
- **Background (#ffffff):** Pure white serves as the base for the entire system, ensuring maximum readability and a premium, spacious look.
- **Neutral (#64748b):** A balanced Slate used for body text and secondary icons to provide sufficient contrast without the harshness of pure black.

## Typography

This design system utilizes **Inter** exclusively to ensure a systematic and utilitarian feel across all platforms. The typographic scale is optimized for high readability in data-heavy enterprise contexts.

Headlines use semi-bold and bold weights with tighter letter spacing to create a strong visual anchor. Body text utilizes a generous line height (1.5x) to ensure long-form technical reports or consulting documents remain legible and approachable. Labels and metadata should use slightly increased letter spacing and medium weights for immediate scanning.

## Layout & Spacing

The system employs a **Fixed Grid** philosophy for desktop to maintain a premium "editorial" look, while transitioning to a fluid model for mobile devices.

- **Grid:** A 12-column grid is used for desktop (1280px max-width). Components should align to this grid to maintain structural integrity.
- **Spaciousness:** Emphasis is placed on "negative space." Use the `stack-lg` (32px) unit between major sections to prevent visual fatigue.
- **Breakpoints:** 
  - Mobile: < 640px (4 columns, 16px margins)
  - Tablet: 640px - 1024px (8 columns, 24px margins)
  - Desktop: > 1024px (12 columns, 40px margins)

## Elevation & Depth

Visual hierarchy is achieved through **Tonal Layering** and **Ambient Shadows**. Instead of heavy borders, depth is communicated through subtle shifts in surface color and soft shadows.

- **Layer 0 (Base):** White (#ffffff) background.
- **Layer 1 (Subtle Inset):** Surface Gray (#f8fafc) for grouping related content, like sidebar backgrounds or secondary dashboard sections.
- **Layer 2 (Raised):** Cards and floating elements use a white background with an extremely soft, diffused shadow: `0px 4px 12px rgba(30, 41, 59, 0.05)`.
- **Layer 3 (Overlay):** Modals and dropdowns use a more pronounced shadow: `0px 12px 24px rgba(30, 41, 59, 0.1)`.

Avoid hard black shadows or multi-colored glows. The goal is a "printed paper" effect where elements feel slightly lifted from the surface.

## Shapes

The design system uses a **Rounded (Level 2)** shape language to soften the corporate professional tone, making the software feel modern and user-friendly.

- **Standard Elements:** Buttons, input fields, and small chips use a 0.5rem (8px) corner radius.
- **Containers:** Large cards and section containers use a 1rem (16px) corner radius to create a distinct frame.
- **Media:** Images or interactive dashboard widgets use a 1.5rem (24px) corner radius for a high-end SaaS feel.

## Components

### Buttons
- **Primary:** Navy Blue (#1e293b) background with white text. High contrast, no border.
- **Secondary:** Transparent background with a 1px border of Slate (#64748b).
- **Ghost:** Minimal Blue (#3b82f6) text with no background, used for low-priority actions.

### Input Fields
Inputs should have a White background, an 8px corner radius, and a subtle light gray border (#e2e8f0). On focus, the border transitions to Action Blue (#3b82f6) with a 2px soft outer glow.

### Cards
Cards are the primary organizational unit. They must have a White background, 16px corner radius, and the Layer 2 ambient shadow. Do not use borders on cards unless they are on a White background, in which case a light gray (#f1f5f9) border is permitted.

### Chips & Tags
Use the Surface Gray (#f8fafc) as the background with Slate (#64748b) text for status indicators. Use small, all-caps labels for a professional, technical look.

### Lists
Lists should be spacious with a 1px bottom border (#f1f5f9) between items. Use the Inter Body-MD typography for list items to ensure clarity in enterprise data tables.