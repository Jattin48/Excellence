---
name: Academic Excellence
colors:
  surface: '#f9f9ff'
  surface-dim: '#d0daf0'
  surface-bright: '#f9f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f0f3ff'
  surface-container: '#e7eeff'
  surface-container-high: '#dee8ff'
  surface-container-highest: '#d9e3f9'
  on-surface: '#121c2c'
  on-surface-variant: '#43474e'
  inverse-surface: '#273141'
  inverse-on-surface: '#ebf1ff'
  outline: '#74777f'
  outline-variant: '#c4c6cf'
  surface-tint: '#455f88'
  primary: '#002045'
  on-primary: '#ffffff'
  primary-container: '#1a365d'
  on-primary-container: '#86a0cd'
  inverse-primary: '#adc7f7'
  secondary: '#875200'
  on-secondary: '#ffffff'
  secondary-container: '#ffb55c'
  on-secondary-container: '#744600'
  tertiary: '#1c2225'
  on-tertiary: '#ffffff'
  tertiary-container: '#31373b'
  on-tertiary-container: '#9aa0a4'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d6e3ff'
  primary-fixed-dim: '#adc7f7'
  on-primary-fixed: '#001b3c'
  on-primary-fixed-variant: '#2d476f'
  secondary-fixed: '#ffddba'
  secondary-fixed-dim: '#ffb866'
  on-secondary-fixed: '#2b1700'
  on-secondary-fixed-variant: '#673d00'
  tertiary-fixed: '#dee3e8'
  tertiary-fixed-dim: '#c2c7cc'
  on-tertiary-fixed: '#171c20'
  on-tertiary-fixed-variant: '#42474c'
  background: '#f9f9ff'
  on-background: '#121c2c'
  surface-variant: '#d9e3f9'
typography:
  display:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  display-mobile:
    fontFamily: Playfair Display
    fontSize: 36px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.3'
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '700'
    lineHeight: '1.3'
  headline-md:
    fontFamily: Playfair Display
    fontSize: 24px
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
  label-bold:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.05em
  caption:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: '1.4'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 48px
  xl: 80px
  container-max: 1200px
  gutter: 24px
---

## Brand & Style

The design system is built on the pillars of **authority, empowerment, and clarity**. It targets students and parents who seek a premium educational experience that balances traditional academic rigor with modern, personalized coaching. 

The aesthetic follows a **Corporate / Modern** direction with an editorial influence. It utilizes high-contrast color blocking and precise typography to create an environment that feels both prestigious and accessible. The interface avoids unnecessary flourishes, prioritizing information density and ease of navigation to reinforce a sense of organized, high-level mentorship.

**Emotional Response:**
- **Trust:** Established through deep navy tones and stable grid structures.
- **Optimism:** Driven by warm gold accents and open white space.
- **Focus:** Achieved through rigorous typographic hierarchy and minimal visual noise.

## Colors

The color strategy uses a foundational high-contrast relationship between deep authority and vibrant energy.

- **Primary (Deep Navy - #1A365D):** Used for headers, footers, primary buttons, and authoritative text. It represents the "Excellence" heritage.
- **Secondary (Academic Gold - #F6AD55):** Reserved for high-priority actions, highlights, and status indicators. It symbolizes the student’s spark and achievement.
- **Tertiary (Cool Slate - #EDF2F7):** A soft background color used to differentiate sections and card containers without introducing clutter.
- **Neutral (Charcoal - #2D3748):** Used for body text and secondary icons to ensure WCAG AA legibility against white and light-gray backgrounds.

## Typography

This design system employs a **dual-font strategy** to bridge the gap between tradition and modernity.

- **Headlines (Playfair Display):** These should be set with tight letter-spacing. Use the bold weight for primary headings to command attention. Always use Sentence case for headings to remain approachable.
- **Body & UI (Inter):** A highly legible sans-serif chosen for its neutral character and excellent performance in data-heavy contexts.
- **Captions & Labels:** Should often be set in uppercase with increased letter-spacing (0.05em) when used for navigation or small categorization tags to enhance scannability.

## Layout & Spacing

The system uses a **Fixed Grid** philosophy for desktop to maintain an editorial, structured feel, transitioning to a fluid model for mobile devices.

- **Desktop (1200px+):** 12-column grid with 24px gutters. Content is centered with generous outer margins to emphasize the "White Space" brand pillar.
- **Tablet (768px - 1199px):** 8-column grid with 24px gutters and 32px side margins.
- **Mobile (Under 767px):** 4-column fluid grid with 16px gutters and 16px side margins.

**Rhythm:** Spacing follows a base-8 scale. Section vertical padding should be aggressive (`xl` or 80px) to give the academic content room to breathe and appear premium.

## Elevation & Depth

This design system utilizes **Tonal Layers** supplemented by **Ambient Shadows**. The goal is to create a physical sense of "stationery" or "academic papers" stacked neatly.

- **Level 0 (Surface):** Pure white (#FFFFFF) used for the main background.
- **Level 1 (Sections):** Tertiary Light Gray (#EDF2F7) used to block out different content areas.
- **Level 2 (Cards):** White background with a very soft, large-radius shadow (Color: #1A365D, Opacity: 6%, Blur: 20px, Y-Offset: 4px). This creates a "lifted" effect without looking heavy.
- **Interactive States:** On hover, cards should increase their shadow spread slightly and shift -4px on the Y-axis to provide tactile feedback.

## Shapes

The shape language is **Soft (0.25rem)**. This decision preserves the "Clean Lines" requirement while removing the harshness of sharp corners, making the brand feel modern and student-friendly.

- **Standard Elements:** Inputs, small buttons, and tags use `rounded` (4px).
- **Containers:** Service cards and testimonial blocks use `rounded-lg` (8px).
- **Full Rounding:** Only used for small badge icons or profile avatars to provide visual contrast against the otherwise rectilinear layout.

## Components

### Buttons
- **Primary:** Navy background, white text. No border. High contrast for clear CTAs.
- **Secondary/Highlight:** Gold background, Navy text. Used for "Enroll Now" or urgent actions.
- **Ghost:** Navy 1px border, Navy text, transparent background. Used for secondary navigation.

### Cards
- Service cards feature a 1:1 aspect ratio image at the top with a subtle 4px corner radius.
- Card content is left-aligned with a `label-bold` category tag in Gold.

### Input Fields
- Fields use a 1px border (#E2E8F0) and 12px horizontal padding.
- On focus, the border transitions to Navy (#1A365D) with a subtle 2px outer glow in the same color at 10% opacity.

### Testimonials
- Testimonials are styled as "Editorial Quotes." They feature a large serif opening quotation mark in Gold, followed by `body-lg` text in italic Playfair Display. The author's name uses `label-bold` in Navy.

### Lists
- Bullet points use a custom Gold checkmark or a small square icon rather than standard circular dots to align with the "Excellence" branding.