# Design System: VedaCare Global

## 1. Visual Theme & Atmosphere

**VedaCare Global** merges two distinct worlds: **Modern Clinical Excellence** and **Heritage Indian Luxury**. The design must evoke absolute medical trust and state-of-the-art capability while wrapping the user in the warmth, hospitality, and premium service associated with Indian luxury hospitality (think Taj or Oberoi hotels).

The visual language eschews sterile, cold hospital blues in favor of a regal **Deep Teal** and **Champagne Gold**. The interface feels like a high-end concierge service. Imagery is critical: we juxtapose crisp, bright, cutting-edge operating rooms and robotic surgery equipment with warm, serene imagery of Himalayan wellness retreats and luxury recovery suites.

**Key Characteristics:**
- **Backgrounds**: Warm off-whites (`#F9F9F9`) and pure whites for cards.
- **Accents**: Champagne Gold (`#C5A059`) for primary actions, subtle borders, and icons.
- **Trust Elements**: Deep Teal (`#004D40`) for headers, footers, and authoritative typography.
- **Depth**: Elegant, soft shadows on cards and journey timelines that lift elements smoothly off the page.
- **Imagery**: A balance of hyper-modern medical facilities and breathtaking, luxurious Indian recovery landscapes.

## 2. Color Palette & Roles

### Brand Colors
- **Deep Teal (`#004D40`)**: The anchor color. Represents clinical authority, depth, and reliability. Used for primary typography, header backgrounds, and solid contrast sections.
- **Champagne Gold (`#C5A059`)**: The luxury accent. Represents premium service, healing, and heritage. Used for primary CTAs, active states, icons, and subtle dividers.
- **Gold Hover (`#D4AF37`)**: Slightly brighter gold for hover states.

### Background & Surface
- **Off-White Base (`#F9F9F9`)**: The primary page background. Softer than pure white, reducing eye strain and feeling more organic.
- **Pure White (`#FFFFFF`)**: Used for elevated cards, forms, and timeline containers to pop against the off-white base.
- **Teal Surface (`#00332A`)**: A darker variant of Deep Teal for footer or secondary dark sections.

### Text Scale
- **Primary Text (`#004D40`)**: Used for headings and primary emphasis.
- **Body Text (`#333333`)**: Dark charcoal for high readability on body copy.
- **Secondary Text (`#666666`)**: For dates, small labels, and less critical information.

## 3. Typography Rules

The typography system uses a classic Serif/Sans-Serif pairing to balance heritage with modernity.

### Font Families
- **Headings**: `Playfair Display`, serif. (Fallbacks: `Georgia`, `Times New Roman`). Evokes tradition, luxury, and premium quality.
- **Body & Data**: `Montserrat`, sans-serif. (Fallbacks: `system-ui`, `-apple-system`, `sans-serif`). Clean, geometric, and highly legible for medical data, forms, and body copy.

### Hierarchy
- **Hero Title**: Playfair Display, 56px–72px, Weight 700 (Bold), Line Height 1.1.
- **Section Heading**: Playfair Display, 36px–48px, Weight 600 (Semi-Bold), Line Height 1.2.
- **Card Title**: Montserrat, 20px–24px, Weight 600, Line Height 1.3.
- **Body Large**: Montserrat, 16px–18px, Weight 400 (Regular), Line Height 1.6.
- **Body Small / UI Elements**: Montserrat, 13px–14px, Weight 500 (Medium), uppercase for small labels with 1px letter-spacing.

## 4. Component Stylings

### Buttons & Call-to-Actions (CTAs)
- **Primary Button**: Solid Deep Teal (`#004D40`) background, White text. Champagne Gold (`#C5A059`) 2px border. Hover: Background shifts to Champagne Gold, text shifts to Deep Teal.
- **Secondary/Gold Button**: Solid Champagne Gold (`#C5A059`), White text. Hover: Brightens to `#D4AF37`.
- **Button Shape**: Slight rounding (`rounded-md` or `4px` radius) to maintain a structured, clinical feel but avoid harsh, cheap edges.

### Cards (Hospitals, Doctors, Retreats)
- **Background**: Pure White (`#FFFFFF`).
- **Border**: Very subtle 1px border (`#E5E5E5`) or Champagne Gold (`#C5A059`) on hover.
- **Shadows**: Soft, diffused shadows: `box-shadow: 0 10px 30px rgba(0, 77, 64, 0.08);`
- **Image Treatment**: Images should have sharp, crisp edges at the top, leading into clean typography below.

### Patient Journey Timeline
- **Structure**: A vertical or horizontal track connecting milestones.
- **Nodes**: Circular nodes bordered in Champagne Gold. Active nodes filled with Deep Teal.
- **Lines**: Champagne Gold connecting lines.
- **Cards**: Each milestone step uses a soft-shadowed white card describing the phase (e.g., "Consultation", "Arrival & Luxury Transfer", "Procedure", "Himalayan Recovery").

## 5. Layout & Spacing Principles

- **Rhythm**: Use a 8px baseline grid. Vertical spacing between major sections should be generous (e.g., `120px` or `py-24`) to let the design breathe and convey luxury.
- **Alignment**: Left-alignment is preferred for narrative text to ensure readability, while center-alignment works well for hero text and section intros.
- **Containers**: Max-width of `1200px` to keep content structured.
- **Borders & Dividers**: Use Champagne Gold thin lines (`1px`) sparingly to separate content sections or frame important information.

## 6. Imagery Guidelines

- **Clinical Excellence**: Bright, high-contrast, blue/white-toned images of modern medical equipment, pristine operating rooms, and confident, approachable surgeons.
- **Heritage Luxury**: Warm, golden-hour photography of Indian palaces, luxury ward suites, wellness resorts, and serene Himalayan or Kerala backwater landscapes.
- **Integration**: Never mix the two styles in the *same* image. Instead, place them side-by-side or in alternating sections to show the seamless transition from high-tech procedure to high-end recovery.
