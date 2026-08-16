---
name: Rukn Al-Halal Premium
colors:
  surface: '#fdf8f8'
  surface-dim: '#ddd9d8'
  surface-bright: '#fdf8f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f7f3f2'
  surface-container: '#f1edec'
  surface-container-high: '#ebe7e6'
  surface-container-highest: '#e5e2e1'
  on-surface: '#1c1b1b'
  on-surface-variant: '#444748'
  inverse-surface: '#313030'
  inverse-on-surface: '#f4f0ef'
  outline: '#747878'
  outline-variant: '#c4c7c7'
  surface-tint: '#5f5e5e'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#1c1b1b'
  on-primary-container: '#858383'
  inverse-primary: '#c8c6c5'
  secondary: '#6f5a4f'
  on-secondary: '#ffffff'
  secondary-container: '#f7dacc'
  on-secondary-container: '#745e53'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#1c1b1a'
  on-tertiary-container: '#868382'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e5e2e1'
  primary-fixed-dim: '#c8c6c5'
  on-primary-fixed: '#1c1b1b'
  on-primary-fixed-variant: '#474746'
  secondary-fixed: '#faddcf'
  secondary-fixed-dim: '#ddc1b4'
  on-secondary-fixed: '#271810'
  on-secondary-fixed-variant: '#564339'
  tertiary-fixed: '#e6e2df'
  tertiary-fixed-dim: '#cac6c4'
  on-tertiary-fixed: '#1c1b1a'
  on-tertiary-fixed-variant: '#484645'
  background: '#fdf8f8'
  on-background: '#1c1b1b'
  surface-variant: '#e5e2e1'
typography:
  headline-display:
    fontFamily: IBM Plex Sans Arabic
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: '0'
  headline-lg:
    fontFamily: IBM Plex Sans Arabic
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.3'
  headline-lg-mobile:
    fontFamily: IBM Plex Sans Arabic
    fontSize: 24px
    fontWeight: '700'
    lineHeight: '1.3'
  headline-md:
    fontFamily: IBM Plex Sans Arabic
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: IBM Plex Sans Arabic
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: IBM Plex Sans Arabic
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-bold:
    fontFamily: IBM Plex Sans Arabic
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.0'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-padding: 24px
  gutter: 16px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
---

## Brand & Style

The brand personality is rooted in the heritage of Saudi hospitality and the uncompromising quality of artisanal butchery. It targets a discerning clientele who views meat selection as a craft. The emotional response should be one of absolute trust, culinary prestige, and sensory indulgence.

The design style is **High-End Tactile Minimalism** with **Glassmorphic** accents. It utilizes depth through realistic shadows and subtle 3D lighting to mimic a premium physical boutique. The interface should feel "expensive"—achieved through generous whitespace, high-contrast typography, and light-refracting surfaces that suggest cleanliness and sophistication.

## Colors

The palette is inspired by the deep tones of aged meats, wood-fired cooking, and the golden glow of premium service.

- **Primary (#171717):** Used for primary text and structural elements to provide a grounded, authoritative feel.
- **Secondary (#3A2920):** A warm, dark brown used for depth, backgrounds of specialized sections, and rich iconography.
- **Accent (#C9A227):** Luxury Gold, reserved strictly for calls to action, premium badges, and highlights to signify quality and "Halal" certification.
- **Background (#F8F5EF):** A warm off-white that prevents the sterile feel of pure white, providing a canvas that feels like high-grade parchment or marble.

## Typography

This design system uses **IBM Plex Sans Arabic** across all levels to maintain a contemporary yet professional Saudi identity. The typeface offers a technical precision that aligns with the "butcher's craft" while remaining highly legible in RTL (Right-to-Left) layouts.

Headlines should utilize the bold weights to create a strong visual hierarchy. For display elements (like product names), use the `headline-display` role to command attention. Body text is set with generous line heights to ensure a premium, easy-reading experience.

## Layout & Spacing

The layout follows a **Fluid Grid** model with high internal margins to evoke a sense of space and exclusivity. 

- **Desktop:** 12-column grid with 24px gutters. Content is centered with a max-width of 1280px.
- **Mobile:** 4-column grid with 16px gutters and 20px side margins.
- **Rhythm:** Use an 8px base unit. Vertical spacing between sections should be aggressive (e.g., 80px or 120px) to allow the "3D" components enough room to breathe and cast shadows without visual clutter.

## Elevation & Depth

To achieve the "Premium 3D" look requested, depth is managed through a combination of **Ambient Shadows** and **Tonal Layers**:

1.  **Level 0 (Surface):** The `#F8F5EF` background.
2.  **Level 1 (Soft Cards):** White or slightly off-white surfaces with a very soft, multi-layered shadow (`0 10px 30px rgba(23, 23, 23, 0.05)`).
3.  **Level 2 (Active/Premium):** Glassmorphic overlays (Background blur: 12px, Opacity: 80% white) with a 1px inner stroke in Gold (`#C9A227`) at 20% opacity.
4.  **Lighting:** Apply a subtle top-down radial gradient on cards to simulate a soft overhead gallery light, enhancing the 3D "extruded" effect.

## Shapes

The shape language is **Rounded**, balancing the sharpness of a butcher's knife with the softness of a premium dining experience. 

- **Cards & Primary Containers:** Use `rounded-lg` (1rem / 16px) to create a friendly but structured appearance.
- **Buttons & Small Interactive Elements:** Use `rounded-xl` (1.5rem / 24px) for a "pill" feel that invites touch.
- **Images:** Product photography should always have rounded corners to match the UI containers, avoiding any harsh 90-degree angles.

## Components

- **Buttons:** Primary buttons use a solid `#171717` background with `#F8F5EF` text. Secondary buttons use a transparent background with a 1.5px gold (`#C9A227`) border. All buttons should have a subtle drop shadow that expands slightly on hover.
- **3D Product Cards:** These are the centerpiece. Use a white background, `rounded-lg` corners, and a realistic soft shadow. The product image should "float" or slightly overlap the card boundaries for a 3D pop-out effect.
- **Glassmorphic Navigation:** The top navigation bar should be a glassmorphic blur with a bottom border of 1px `#C9A227` at 10% opacity.
- **Input Fields:** Use a subtle inset shadow to create a "pressed" or carved-in effect, contrasting with the "raised" 3D cards.
- **Premium Badges:** Use gold (#C9A227) for "Halal" and "Premium Cut" labels, employing high-contrast black text for readability.
- **Lists:** Use custom icons (e.g., stylized butcher knives or meat hooks in Gold) instead of standard bullets to reinforce the brand identity.