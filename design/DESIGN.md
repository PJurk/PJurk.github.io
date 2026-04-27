---

name: Organic Sophistication
colors:
  surface: '#fff8f3'
  surface-dim: '#e0d9d2'
  surface-bright: '#fff8f3'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#faf2eb'
  surface-container: '#f4ede5'
  surface-container-high: '#eee7e0'
  surface-container-highest: '#e9e1da'
  on-surface: '#1e1b17'
  on-surface-variant: '#42493e'
  inverse-surface: '#33302b'
  inverse-on-surface: '#f7efe8'
  outline: '#72796e'
  outline-variant: '#c2c9bb'
  surface-tint: '#3b6934'
  primary: '#154212'
  on-primary: '#ffffff'
  primary-container: '#2d5a27'
  on-primary-container: '#9dd090'
  inverse-primary: '#a1d494'
  secondary: '#7d562d'
  on-secondary: '#ffffff'
  secondary-container: '#ffca98'
  on-secondary-container: '#7a532a'
  tertiary: '#373b22'
  on-tertiary: '#ffffff'
  tertiary-container: '#4e5237'
  on-tertiary-container: '#c1c5a3'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#bcf0ae'
  primary-fixed-dim: '#a1d494'
  on-primary-fixed: '#002201'
  on-primary-fixed-variant: '#23501e'
  secondary-fixed: '#ffdcbd'
  secondary-fixed-dim: '#f0bd8b'
  on-secondary-fixed: '#2c1600'
  on-secondary-fixed-variant: '#623f18'
  tertiary-fixed: '#e1e6c2'
  tertiary-fixed-dim: '#c5c9a7'
  on-tertiary-fixed: '#1a1d07'
  on-tertiary-fixed-variant: '#45492f'
  background: '#fff8f3'
  on-background: '#1e1b17'
  surface-variant: '#e9e1da'
typography:
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.5'
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 48px
  container-max: 1280px

## gutter: 24px

## Brand & Style

The design system is built on the principle of "Organic Sophistication." It moves away from the sterile, clinical nature of traditional SaaS interfaces toward a "living" aesthetic that feels premium yet deeply human. The target audience values quality, mindfulness, and clarity, expecting an experience that feels like a well-appointed physical space rather than a digital tool.

The style is a blend of **Modern Minimalism** and **Tactile Depth**. It prioritizes heavy whitespace and refined typography while using subtle physical cues—like soft shadows and organic curves—to evoke a sense of touch and warmth. The UI should feel "alive," responding to user interaction with fluidity and grace, suggesting a high-end, bespoke environment.

## Colors

This design system utilizes a palette rooted in nature to evoke warmth and reliability. The foundation is built on **Off-Whites** (Alabaster) and **Warm Greys** (Taupe), which provide a soft, low-contrast canvas that reduces eye strain and feels more inviting than pure white and cold grey.

The **Vibrant Forest Green** serves as the primary accent, used intentionally for call-to-actions, successes, and brand moments to inject vitality. Secondary accents of **Muted Gold/Ochre** are used for highlights and interactive states, adding to the high-end, sophisticated feel. Gradients should be extremely subtle, moving between slightly different tones of the same hue to mimic natural light hitting a surface.

## Typography

The typography system leverages **Plus Jakarta Sans** for its unique balance of geometric precision and friendly, open counters. This choice ensures that even dense data feels approachable and easy to digest.

Headlines use a tighter tracking and heavier weight to establish a bold, confident hierarchy. Body text is set with generous line heights to enhance readability and contribute to the "breathable" feel of the layout. Labels utilize a slight letter-spacing increase and uppercase styling where necessary to provide clear architectural signposting without cluttering the interface.

## Layout & Spacing

The design system employs a **Fixed-Fluid Hybrid Grid**. Content is housed within a centered container with a maximum width of 1280px to maintain readability on large displays. We utilize a 12-column grid with a 24px gutter, allowing for flexible arrangements that feel structured yet rhythmic.

Spacing is strictly governed by an 8px base unit. Negative space is treated as a first-class citizen; generous margins (xl) are used between major sections to prevent the UI from feeling "crowded," maintaining the high-end, calm atmosphere. Padding within components like cards and modals should favor the `lg` (24px) unit to ensure content has room to breathe.

## Elevation & Depth

Depth in this design system is created through **Ambient Shadows** and **Tonal Layering**. Unlike harsh, traditional dropshadows, our shadows are extra-diffused and carry a subtle tint of the primary neutral color (#4A4641) at very low opacities (5-10%). This makes elements appear as though they are gently floating above a warm surface rather than being glued to a screen.

We utilize three tiers of elevation:

1. **Flat:** Background surfaces and low-priority containers.
2. **Raised:** Interactive cards and secondary buttons (using a soft, wide-blur shadow).
3. **Floating:** Modals, menus, and primary action buttons (using a dual-layered shadow for increased tactile presence).

Subtle inner-shadows or "top-lights" can be used on primary buttons to create a slightly convex, pressable feel.

## Shapes

The shape language is defined by the **ROUND_EIGHT** philosophy. A base border-radius of 0.5rem (8px) is applied to standard components like buttons and input fields. Larger containers, such as cards and sections, scale up to 1rem (16px) or 1.5rem (24px) to emphasize the friendly, welcoming nature of the brand.

Avoid sharp 90-degree angles entirely. Even iconography and decorative elements should mirror these soft radii to maintain a cohesive, "liquid" visual flow. The goal is to make every touchpoint feel safe, approachable, and high-quality.

## Components

### Buttons

Primary buttons use the Forest Green accent with a subtle top-to-bottom linear gradient (lighter at the top) and white text. They feature a soft shadow that deepens slightly on hover. Secondary buttons use a warm grey outline or a subtle off-white fill to remain distinct but less prominent.

### Cards

Cards are the primary container for information. They should have a white surface, a 16px border radius, and a soft ambient shadow. Avoid heavy borders; instead, use the shadow and whitespace to define the card's boundaries.

### Input Fields

Inputs use a warm grey border (#E5E1DA) and a soft off-white background. Upon focus, the border transitions to Forest Green with a subtle "glow" (a spread shadow in the primary color at 10% opacity).

### Chips & Tags

Chips use a pill-shape (fully rounded) and are rendered in the tertiary color palette (Sage/Ochre) with dark neutral text for high legibility and a sophisticated "color-coded" look.

### Navigation

The navigation should be airy, using Plus Jakarta Sans in a medium weight. Active states are indicated by a small, organic "dot" or a soft underline in Forest Green, avoiding heavy blocks of color that might disrupt the minimalist aesthetic.