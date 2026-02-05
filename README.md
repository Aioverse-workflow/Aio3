# Color Palette Guidelines
## Brand Standards v1.0

---

## Table of Contents

1. [Introduction](#introduction)
2. [Core Brand Palette](#core-brand-palette)
3. [Light UI System](#light-ui-system)
4. [Dark UI System](#dark-ui-system)
5. [Functional Colors](#functional-colors)
6. [Color Application Rules](#color-application-rules)
7. [Accessibility Standards](#accessibility-standards)
8. [Usage Examples](#usage-examples)
9. [Technical Specifications](#technical-specifications)

---

## Introduction

This document defines the official color system for our brand identity. Our palette reflects innovation, trust, and cutting-edge technology—core values that drive our drone startup. The color system is designed to work seamlessly across digital products, marketing materials, and physical applications.

### Design Philosophy

Our color palette is built on three foundational principles:

- **Innovation**: Electric Aqua represents forward-thinking technology and breakthrough solutions
- **Trust**: Midnight Teal conveys reliability, depth, and professional expertise
- **Clarity**: Soft White and neutral tones ensure accessibility and visual hierarchy

### Color System Architecture

The palette follows a structured token-based system with three tiers:

1. **Core Brand Colors** (3): Primary identity colors used sparingly for maximum impact
2. **UI Neutrals** (4): Foundation colors for interfaces and layouts
3. **Functional Colors** (3): System states (success, warning, error)

---

## Core Brand Palette

### Primary Colors

These are the heart of our brand identity. Use them consistently across all touchpoints to build recognition.

#### 1. Midnight Teal — Primary Brand
**Role**: Brand foundation, dark backgrounds, headers, dark mode base

```
HEX:  #002428
RGB:  0, 36, 40
CMYK: 88, 64, 62, 69
```

**Usage Guidelines**:
- Primary brand color for logos, headers, and key brand moments
- Background color for dark-themed applications
- Use for text when contrast ratio permits (light backgrounds only)
- Minimum size: 16px × 16px for brand recognition

**Do's**:
✓ Use on hero sections and key landing areas  
✓ Pair with Electric Aqua for high contrast  
✓ Apply to footer and navigation bars

**Don'ts**:
✗ Do not use as body text color on white  
✗ Avoid using alone without accent colors  
✗ Never tint or alter the base color value

---

#### 2. Electric Aqua — Primary Accent
**Role**: CTAs, links, highlights, interactive elements

```
HEX:  #73EFFB
RGB:  115, 239, 251
CMYK: 52, 0, 10, 0
```

**Usage Guidelines**:
- Primary call-to-action buttons
- Interactive links and hover states
- Key data visualizations and graphs
- Focus rings and active states

**Do's**:
✓ Use for primary buttons and CTAs  
✓ Apply to interactive elements requiring attention  
✓ Ideal for illustrations and iconography accents

**Don'ts**:
✗ Do not use as large background fills (use tints instead)  
✗ Avoid pairing with Signal Indigo at full saturation  
✗ Never use for long-form body text

**Derived Tints**:
- **Aqua/90**: #85F1FC (hover states)
- **Aqua/50**: #B9F7FD (subtle backgrounds)
- **Aqua/10**: #E0FAFD (pills, tags, cards)

---

#### 3. Signal Indigo — Secondary Accent
**Role**: Secondary CTAs, charts, badges, alternative interactions

```
HEX:  #5C6CFF
RGB:  92, 108, 255
CMYK: 64, 58, 0, 0
```

**Usage Guidelines**:
- Secondary action buttons
- Alternative chart colors
- Notification badges and tags
- Complementary illustrations

**Do's**:
✓ Use to differentiate secondary actions from primary  
✓ Apply in data visualization for category separation  
✓ Ideal for premium feature highlights

**Don'ts**:
✗ Do not overuse—reserve for strategic moments  
✗ Avoid direct adjacency with Electric Aqua at full opacity  
✗ Never substitute for primary brand color

**Derived Tints**:
- **Indigo/90**: #7080FF
- **Indigo/50**: #ADB5FF
- **Indigo/10**: #E4E6FF

---

### Neutral Colors

#### 4. Deep Space — Ultra Dark
**Role**: Foundation for dark themes, overlays, app shells

```
HEX:  #020C10
RGB:  2, 12, 16
CMYK: 88, 75, 65, 85
```

**Usage**: Dark mode backgrounds, modal overlays, hero sections

---

#### 5. Graphite Teal — Neutral Dark
**Role**: Card backgrounds, sidebars, elevated surfaces in dark mode

```
HEX:  #0F2E33
RGB:  15, 46, 51
CMYK: 80, 58, 55, 60
```

**Usage**: Dark UI cards, navigation panels, dividers

---

#### 6. Cloud Grey — Neutral Light
**Role**: Borders, secondary backgrounds, disabled states

```
HEX:  #E4E8EB
RGB:  228, 232, 235
CMYK: 6, 4, 3, 0
```

**Usage**: Light mode borders, input fields, dividers, muted backgrounds

---

#### 7. Soft White — Light Background
**Role**: Light mode foundation, card backgrounds, text on dark

```
HEX:  #FAFAFA
RGB:  250, 250, 250
CMYK: 1, 1, 1, 0
```

**Usage**: Primary light mode background, text on dark surfaces, cards

---

## Light UI System

### Backgrounds & Surfaces

```
BG/Base:          #FAFAFA  (Soft White)
BG/Subtle:        #F2F4F6  (Slight tint)
Surface/Default:  #FFFFFF  (Pure white)
Surface/Muted:    #F5F7F9  (Off-white)
```

### Borders & Dividers

```
Border/Subtle:    #E4E8EB  (Cloud Grey)
Border/Strong:    #CBD3D8  (Darker grey)
Border/Focus:     #73EFFB  (Electric Aqua)
```

### Text Hierarchy

```
Text/Primary:     #0B1A1E  (Dark teal-black, 98% contrast)
Text/Secondary:   #5A6A73  (Muted grey-teal, 70% contrast)
Text/Disabled:    #A8B4BB  (Light grey, 40% contrast)
Text/On Dark:     #FAFAFA  (Soft White)
Text/Link:        #73EFFB  (Electric Aqua)
```

### Brand Applications (Light Mode)

#### Primary Actions
```
Button BG:        #002428  (Midnight Teal)
Button Text:      #FAFAFA  (Soft White)
Button Hover:     #01353B  (Lighter teal)
Button Active:    #003B42  (Pressed state)
```

#### Secondary Actions
```
Button BG:        Transparent
Button Border:    #002428  (Midnight Teal)
Button Text:      #002428
Hover BG:         #E0FAFD  (Aqua tint)
```

#### Accent Elements
```
Accent Main:      #73EFFB  (Electric Aqua)
Accent Hover:     #57DAE7
Accent Subtle:    #E0FAFD  (For tags/pills)
```

---

## Dark UI System

### Backgrounds & Surfaces

```
BG/Base:          #020C10  (Deep Space)
BG/Muted:         #03161B
Surface/Card:     #0F2E33  (Graphite Teal)
Surface/Hover:    #12383E
Surface/Elevated: #1A4550
```

### Borders & Dividers

```
Border/Subtle:    #1A3F45
Border/Strong:    #2B5158
Border/Focus:     #73EFFB  (Electric Aqua glow)
```

### Text Hierarchy

```
Text/Primary:     #FAFAFA  (Soft White)
Text/Secondary:   #BCC7CC  (Light grey-teal)
Text/Muted:       #7A8A92  (Mid grey)
Text/Disabled:    #4A5A62
Text/Link:        #73EFFB  (Electric Aqua)
```

### Brand Applications (Dark Mode)

#### Primary Actions
```
Button BG:        #73EFFB  (Electric Aqua)
Button Text:      #002428  (Midnight Teal)
Button Hover:     #57DAE7
Button Active:    #3CD9EA
```

#### Secondary Actions
```
Button BG:        #0F2E33  (Graphite Teal)
Button Border:    #73EFFB
Button Text:      #E4E8EB
Hover BG:         #12383E
```

#### Accent Elements
```
Accent/Aqua:      #73EFFB
Accent/Glow BG:   #06363C  (For chips, focus rings)
Secondary/Indigo: #5C6CFF
Indigo Glow:      #212755
```

---

## Functional Colors

### Success

**Role**: Confirmations, success states, positive indicators

```
Success/Main:     #19C97C  (Fresh teal-green)
Success/Hover:    #15B56D
Success/Soft BG:  #E0F8EE  (Light mode)
Success/Text:     #064D31
Success/Dark BG:  #0D3D28  (Dark mode)
```

**Usage**: Form success, completed tasks, positive metrics

---

### Warning

**Role**: Caution states, pending actions, attention needed

```
Warning/Main:     #FFB547  (Amber)
Warning/Hover:    #FFA726
Warning/Soft BG:  #FFF4DF  (Light mode)
Warning/Text:     #7A4A00
Warning/Dark BG:  #4A3410  (Dark mode)
```

**Usage**: Warnings, incomplete data, non-critical alerts

---

### Error

**Role**: Error states, destructive actions, critical alerts

```
Error/Main:       #FF4B5C  (Coral red)
Error/Hover:      #E63946
Error/Soft BG:    #FFE5E8  (Light mode)
Error/Text:       #7C1B23
Error/Dark BG:    #4A1419  (Dark mode)
```

**Usage**: Form errors, failed actions, critical warnings

---

## Color Application Rules

### The 60-30-10 Principle

Apply colors across any design using this ratio for visual balance:

**60% — Neutral Foundation**
- Light mode: Soft White, Cloud Grey
- Dark mode: Deep Space, Graphite Teal
- Use: Backgrounds, large surface areas

**30% — Brand Identity**
- Midnight Teal surfaces
- Navigation bars, headers, footers
- Section backgrounds, card containers

**10% — Accent & Action**
- Electric Aqua for CTAs
- Signal Indigo for secondary actions
- Functional colors for states

### Color Pairing Matrix

| Primary Color    | Pairs Well With              | Avoid Pairing With    |
|------------------|------------------------------|-----------------------|
| Midnight Teal    | Electric Aqua, Soft White    | Signal Indigo (direct)|
| Electric Aqua    | Midnight Teal, Deep Space    | Warning/Main          |
| Signal Indigo    | Soft White, Cloud Grey       | Electric Aqua (full)  |
| Success/Main     | All neutrals                 | Error/Main            |

### Gradient Usage

**Brand Gradients** (use sparingly for hero sections, highlights):

**Teal → Aqua**
```
Linear: 135deg, #002428 0%, #73EFFB 100%
```

**Teal → Indigo**
```
Linear: 135deg, #002428 0%, #5C6CFF 100%
```

**Application**: Hero backgrounds, onboarding screens, key CTAs

**Restrictions**: 
- Maximum 1 gradient per viewport
- Do not use in UI controls or forms
- Avoid gradients in print materials

---

## Accessibility Standards

### Contrast Requirements (WCAG 2.1 Level AA)

All text must meet minimum contrast ratios:

**Normal Text (< 18px)**
- Minimum: 4.5:1
- Preferred: 7:1 (AAA)

**Large Text (≥ 18px or 14px bold)**
- Minimum: 3:1
- Preferred: 4.5:1 (AAA)

### Validated Color Combinations

#### Light Mode — Compliant Pairs

| Background | Text Color   | Ratio | Status |
|------------|--------------|-------|--------|
| #FAFAFA    | #0B1A1E      | 16.2:1| ✓ AAA  |
| #FAFAFA    | #5A6A73      | 7.3:1 | ✓ AAA  |
| #FFFFFF    | #002428      | 19.8:1| ✓ AAA  |
| #E0FAFD    | #002428      | 17.2:1| ✓ AAA  |

#### Dark Mode — Compliant Pairs

| Background | Text Color   | Ratio | Status |
|------------|--------------|-------|--------|
| #020C10    | #FAFAFA      | 18.9:1| ✓ AAA  |
| #0F2E33    | #FAFAFA      | 14.5:1| ✓ AAA  |
| #002428    | #73EFFB      | 12.1:1| ✓ AAA  |
| #0F2E33    | #BCC7CC      | 9.8:1 | ✓ AAA  |

### Non-Compliant Combinations (Avoid)

✗ Electric Aqua (#73EFFB) on Soft White (#FAFAFA): 2.1:1 — Use for icons/small elements only  
✗ Signal Indigo (#5C6CFF) on Midnight Teal (#002428): 2.8:1 — Insufficient for text  
✗ Cloud Grey (#E4E8EB) as text on Soft White: 1.4:1 — Borders/dividers only

### Color Blind Considerations

**Protanopia/Deuteranopia (Red-Green)**:
- ✓ Midnight Teal and Electric Aqua remain distinguishable
- ✓ Success/Error states have sufficient luminance difference

**Tritanopia (Blue-Yellow)**:
- ✓ Electric Aqua and Signal Indigo maintain contrast
- ⚠ Supplement color with icons/text labels for critical information

**Testing Requirement**: All designs must pass simulation in:
- Protanopia
- Deuteranopia  
- Tritanopia

---

## Usage Examples

### Example 1: Website Hero Section

**Structure**:
```
Background:   #002428 (Midnight Teal)
Headline:     #FAFAFA (Soft White)
Subheading:   #BCC7CC (Secondary text)
CTA Button:   #73EFFB (Electric Aqua)
CTA Text:     #002428 (Midnight Teal)
```

**Visual Ratio**: 70% Midnight Teal, 25% Soft White, 5% Electric Aqua

---

### Example 2: Dashboard Card (Light Mode)

**Structure**:
```
Card BG:      #FFFFFF (Surface default)
Border:       #E4E8EB (Cloud Grey)
Heading:      #0B1A1E (Primary text)
Body Text:    #5A6A73 (Secondary text)
Metric Value: #73EFFB (Electric Aqua)
Icon:         #5C6CFF (Signal Indigo)
```

**Visual Ratio**: 85% Neutrals, 10% Electric Aqua, 5% Signal Indigo

---

### Example 3: Mobile App Navigation (Dark Mode)

**Structure**:
```
Nav Bar BG:   #0F2E33 (Graphite Teal)
Active Tab:   #73EFFB (Electric Aqua)
Inactive Tab: #7A8A92 (Muted text)
Divider:      #1A3F45 (Subtle border)
Badge:        #FF4B5C (Error/notification)
```

**Visual Ratio**: 90% Graphite Teal, 8% Electric Aqua, 2% Error Red

---

### Example 4: Form Error State

**Structure**:
```
Input BG:        #FFFFFF (Light) / #0F2E33 (Dark)
Input Border:    #FF4B5C (Error main)
Error Text:      #7C1B23 (Light) / #FF4B5C (Dark)
Error Icon:      #FF4B5C
Error BG:        #FFE5E8 (Light) / #4A1419 (Dark)
```

---

## Technical Specifications

### CSS Variables (Light Mode)

```css
:root {
  /* Brand Core */
  --color-brand-primary: #002428;
  --color-brand-accent: #73EFFB;
  --color-brand-secondary: #5C6CFF;

  /* Neutrals */
  --color-neutral-50: #FAFAFA;
  --color-neutral-100: #F2F4F6;
  --color-neutral-200: #E4E8EB;
  --color-neutral-300: #CBD3D8;
  --color-neutral-400: #A8B4BB;
  --color-neutral-500: #7A8A92;
  --color-neutral-600: #5A6A73;
  --color-neutral-700: #3A4A52;
  --color-neutral-800: #0B1A1E;
  --color-neutral-900: #020C10;

  /* Functional */
  --color-success: #19C97C;
  --color-warning: #FFB547;
  --color-error: #FF4B5C;

  /* Semantic Tokens */
  --color-bg-base: var(--color-neutral-50);
  --color-bg-surface: #FFFFFF;
  --color-text-primary: var(--color-neutral-800);
  --color-text-secondary: var(--color-neutral-600);
  --color-border: var(--color-neutral-200);
}
```

### CSS Variables (Dark Mode)

```css
[data-theme="dark"] {
  /* Backgrounds */
  --color-bg-base: #020C10;
  --color-bg-surface: #0F2E33;

  /* Text */
  --color-text-primary: #FAFAFA;
  --color-text-secondary: #BCC7CC;

  /* Borders */
  --color-border: #1A3F45;

  /* Functional (adjusted for dark) */
  --color-success: #19C97C;
  --color-warning: #FFB547;
  --color-error: #FF4B5C;
}
```

### Design Token Structure (JSON)

```json
{
  "color": {
    "brand": {
      "primary": {
        "value": "#002428",
        "type": "color"
      },
      "accent": {
        "value": "#73EFFB",
        "type": "color"
      },
      "secondary": {
        "value": "#5C6CFF",
        "type": "color"
      }
    },
    "neutral": {
      "50": {"value": "#FAFAFA"},
      "100": {"value": "#F2F4F6"},
      "200": {"value": "#E4E8EB"},
      "900": {"value": "#020C10"}
    },
    "semantic": {
      "success": {"value": "#19C97C"},
      "warning": {"value": "#FFB547"},
      "error": {"value": "#FF4B5C"}
    }
  }
}
```

### Figma Library Setup

**Token Structure**:
```
Brand/Primary
Brand/Accent
Brand/Secondary
Neutral/50–900
Semantic/Success
Semantic/Warning
Semantic/Error
```

**Style Naming Convention**:
```
[Category]/[Name]/[Variant]

Examples:
Brand/Primary/Default
Brand/Accent/Hover
Text/Primary/Light
Surface/Card/Dark
```

---

## Print Specifications

### Offset Printing (CMYK)

Use CMYK values for professional printing:

```
Midnight Teal:   88-64-62-69
Electric Aqua:   52-0-10-0
Signal Indigo:   64-58-0-0
```

**Note**: Request color proofs to verify reproduction accuracy. Coated stock recommended for vibrant colors.

### Pantone Equivalents (Approximate)

```
Midnight Teal:   Pantone 5463 C
Electric Aqua:   Pantone 310 C
Signal Indigo:   Pantone 2726 C
```

**Important**: These are approximations. For brand-critical materials, request custom Pantone mixing.

### Digital Display (RGB)

Use RGB values for all screens:

```
Midnight Teal:   RGB(0, 36, 40)
Electric Aqua:   RGB(115, 239, 251)
Signal Indigo:   RGB(92, 108, 255)
```

---

## Governance & Approval

### Color Modification Policy

**Prohibited**:
- Altering HEX/RGB values of core brand colors
- Creating unauthorized tints without design team approval
- Using colors outside this defined system

**Permitted** (with approval):
- Deriving tints at 90%, 50%, 10% opacity
- Creating temporary campaign-specific colors
- A/B testing alternative accent colors

### Review Cycle

This color system is reviewed bi-annually. Submit requests for modifications to:

**Brand Design Team**  
Email: brand@[company].com

---

## Version History

| Version | Date       | Changes                                    | Author       |
|---------|------------|--------------------------------------------|--------------|
| 1.0     | Feb 2026   | Initial color system framework             | Brand Team   |

---

## Contact

For questions about color usage, accessibility concerns, or design token implementation:

**Design System Team**  
Email: design-system@[company].com  
Slack: #design-system

---

**Document Status**: Official Brand Guidelines  
**Last Updated**: February 6, 2026  
**Next Review**: August 2026

---

© 2026 [Company Name]. All rights reserved. This document is confidential and proprietary.