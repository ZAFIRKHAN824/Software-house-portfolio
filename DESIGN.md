---
name: High-Tech Engineering System
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
  on-surface-variant: '#464555'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#777587'
  outline-variant: '#c7c4d8'
  surface-tint: '#4d44e3'
  primary: '#3525cd'
  on-primary: '#ffffff'
  primary-container: '#4f46e5'
  on-primary-container: '#dad7ff'
  inverse-primary: '#c3c0ff'
  secondary: '#565e74'
  on-secondary: '#ffffff'
  secondary-container: '#dae2fd'
  on-secondary-container: '#5c647a'
  tertiary: '#7e3000'
  on-tertiary: '#ffffff'
  tertiary-container: '#a44100'
  on-tertiary-container: '#ffd2be'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e2dfff'
  primary-fixed-dim: '#c3c0ff'
  on-primary-fixed: '#0f0069'
  on-primary-fixed-variant: '#3323cc'
  secondary-fixed: '#dae2fd'
  secondary-fixed-dim: '#bec6e0'
  on-secondary-fixed: '#131b2e'
  on-secondary-fixed-variant: '#3f465c'
  tertiary-fixed: '#ffdbcc'
  tertiary-fixed-dim: '#ffb695'
  on-tertiary-fixed: '#351000'
  on-tertiary-fixed-variant: '#7b2f00'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-md:
    fontFamily: Inter
    fontSize: 36px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 30px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.0'
    letterSpacing: 0.05em
  caption:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.4'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 4px
  xs: 8px
  sm: 16px
  md: 24px
  lg: 40px
  xl: 64px
  gutter: 24px
  container-max: 1280px
---

## Brand & Style

The design system is engineered for a software development house that balances technical rigor with approachable innovation. The brand personality is "The Expert Partner"—precise, reliable, and forward-thinking. It avoids the chaotic aesthetics of experimental tech in favor of a **Minimalist Corporate Modern** style that signals enterprise-ready stability.

The emotional response should be one of clarity and confidence. By utilizing expansive whitespace and a restrained color palette, the UI directs focus toward content and data, reflecting the efficiency of the code the firm produces. Interaction patterns are intentional and fluid, reinforcing the high-tech nature of the service without overwhelming the user.

## Colors

The palette is anchored by **Deep Indigo (#4F46E5)** as the primary driver of action and brand identity. This color is chosen for its association with intelligence and deep-focus work. **Electric Blue (#3B82F6)** is utilized sparingly as a high-visibility accent for success states or specific interactive highlights.

The neutral scale relies on a cool Slate palette. The background is pure white to maximize the feeling of "air" and premium space, while `surface-color` (Slate 50) provides subtle containment for cards and structural blocks. Typography primarily uses Slate 900 for high-contrast readability against the white canvas.

## Typography

This design system uses **Inter** for all primary interface elements. Inter’s tall x-height and geometric clarity provide the professional, systematic feel required for complex software workflows. For "Display" and "Headline" levels, we use tight letter-spacing and heavy weights to create a sense of architectural strength.

To nod to the software engineering core, **JetBrains Mono** is introduced for small labels, metadata, and technical indicators (like version numbers or status tags). This secondary typeface adds a layer of "High-Tech" authenticity, signaling that the product is built by developers, for developers.

## Layout & Spacing

The layout follows a **Fixed-Fluid Hybrid** model. Large desktop views are capped at 1280px to maintain line-length readability, while internal dashboards utilize a fluid 12-column grid. 

The spacing philosophy is "Generous but Mathematical," built on a 4px base unit. We prioritize vertical rhythm, using `lg` (40px) and `xl` (64px) spacing between major sections to emphasize the minimalist aesthetic. Margins and gutters are kept wide (24px) to ensure the interface never feels "cramped," reinforcing a premium, enterprise-grade experience.

## Elevation & Depth

Visual hierarchy is achieved through **Tonal Layers** and **Ambient Shadows**. Instead of traditional heavy drop shadows, this design system uses extremely diffused, multi-layered shadows with a slight indigo tint (`rgba(79, 70, 229, 0.08)`). 

Elevation levels are defined as:
- **Level 0 (Flat):** The main background canvas.
- **Level 1 (Surface):** Subtle containment using a 1px Slate-200 border, used for cards.
- **Level 2 (Raised):** Used for interactive elements like buttons or hover states, featuring a soft 12px blur shadow.
- **Level 3 (Overlay):** Used for modals and dropdowns, utilizing a significant 24px blur and a subtle 1px inner stroke to maintain edge definition.

## Shapes

The design system utilizes **Soft (0.25rem)** roundedness. This subtle rounding of corners strikes a balance between the clinical sharpness of high-tech "hard" hardware and the friendly accessibility of modern SaaS. 

- **Standard Elements (Buttons, Inputs):** 4px (0.25rem) radius.
- **Large Containers (Cards, Modals):** 8px (0.5rem) radius.
- **Micro Elements (Checkboxes, Tags):** 2px radius.

This consistency creates a cohesive, engineered look that feels intentional and disciplined.

## Components

### Buttons
Primary buttons use the Deep Indigo background with white Inter Bold text. They feature a subtle 1px top-highlight to give a slight "tactile" feel without moving into skeuomorphism. Secondary buttons use a ghost style with a Slate-200 border.

### Inputs & Forms
Input fields are minimalist, using a white background and a 1px Slate-200 border. Upon focus, the border transitions to Deep Indigo with a soft 3px "glow" shadow. Labels are consistently placed above the field in `label-md` (JetBrains Mono).

### Cards
Cards are the primary container. They use a white background with a 1px Slate-100 border. Shadows are only applied on hover to indicate interactivity, keeping the initial state clean and flat.

### Chips & Status Indicators
Status indicators (e.g., "Deployed", "In Progress") use the JetBrains Mono font. They are styled with a low-opacity background tint of the status color (e.g., light green for success) and high-contrast text to ensure accessibility.

### Developer-Specific Components
- **Code Snippets:** Dark-themed blocks using JetBrains Mono with a refined syntax highlighting palette.
- **Progress Steppers:** Vertical, thin lines with Indigo nodes to represent CI/CD pipelines or project milestones.