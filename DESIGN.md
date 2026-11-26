---
name: Tri Ân Thầy Cô - Kawaii Tribute
colors:
  surface: '#fff8f7'
  surface-dim: '#e8d6d4'
  surface-bright: '#fff8f7'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fff0ef'
  surface-container: '#fdeae8'
  surface-container-high: '#f7e4e2'
  surface-container-highest: '#f1dedc'
  on-surface: '#231918'
  on-surface-variant: '#574144'
  inverse-surface: '#392e2d'
  inverse-on-surface: '#ffedeb'
  outline: '#8a7173'
  outline-variant: '#ddbfc2'
  surface-tint: '#a8334e'
  primary: '#a8334e'
  on-primary: '#ffffff'
  primary-container: '#ff758f'
  on-primary-container: '#74052a'
  inverse-primary: '#ffb2bc'
  secondary: '#78555e'
  on-secondary: '#ffffff'
  secondary-container: '#ffd1dc'
  on-secondary-container: '#7a5761'
  tertiary: '#4a654e'
  on-tertiary: '#ffffff'
  tertiary-container: '#8ca98f'
  on-tertiary-container: '#253e29'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffd9dd'
  primary-fixed-dim: '#ffb2bc'
  on-primary-fixed: '#400013'
  on-primary-fixed-variant: '#881938'
  secondary-fixed: '#ffd9e2'
  secondary-fixed-dim: '#e7bbc6'
  on-secondary-fixed: '#2d141c'
  on-secondary-fixed-variant: '#5e3e47'
  tertiary-fixed: '#cceacd'
  tertiary-fixed-dim: '#b1ceb2'
  on-tertiary-fixed: '#07200e'
  on-tertiary-fixed-variant: '#334d37'
  background: '#fff8f7'
  on-background: '#231918'
  surface-variant: '#f1dedc'
typography:
  display:
    fontFamily: Epilogue
    fontSize: 32px
    fontWeight: '800'
    lineHeight: 40px
  headline-lg:
    fontFamily: Epilogue
    fontSize: 26px
    fontWeight: '700'
    lineHeight: 34px
  headline-md:
    fontFamily: Epilogue
    fontSize: 22px
    fontWeight: '700'
    lineHeight: 28px
  headline-sm:
    fontFamily: Epilogue
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Quicksand
    fontSize: 16px
    fontWeight: '500'
    lineHeight: 24px
  body-md:
    fontFamily: Quicksand
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
  body-sm:
    fontFamily: Quicksand
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
  label-md:
    fontFamily: Quicksand
    fontSize: 13px
    fontWeight: '700'
    lineHeight: 18px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Noto Sans
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  full: 9999px
spacing:
  gutter: 0.75rem
  margin: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 0.875rem
  space-lg: 1.25rem
  space-xl: 1.75rem
---

## Brand & Style
This design system crafts a whimsical, heartwarming, and nostalgic mobile web experience commemorating Vietnamese Teachers' Day (Ngày Nhà Giáo Việt Nam - 20/11). Built around the genuine, lively dynamic between young university students and their beloved teacher—capturing moments from classroom engineering diagrams to Chinese calligraphy sessions—the aesthetic blends modern Kawaii sensibilities, scrapbook tactile warmth, and youthful celebration.

The visual style merges tactile scrapbook elements (polaroid frames, translucent washi tape strips, iridescent celebratory balloon badges) with clean, approachable pastel minimalism. The emotional response is pure affection, warmth, gratitude, and playful youthful joy.

## Colors
The palette balances creamy sweetness, festive vibrancy, and readability:

- **Warm Cream Canvas (`#FFF9F2`):** Forms the foundational surface background, evoking handmade stationery and soft sunlight.
- **Vibrant Candy Pink (`#FF758F` - Primary):** Serves as the key interactive accent, primary call-to-actions, badges, and heart-felt focal points.
- **Blush Pink (`#FFD1DC` - Secondary):** Deployed for soft card backgrounds, pill tags, and subtle gradient stops.
- **Soft Avocado Green (`#C8E6C9` - Tertiary):** Evokes classroom chalkboards and youthful freshness; ideal for positive status chips, secondary tags, and decorative accents.
- **Lilac Dream (`#E1D4F9`):** Accent tint for celebratory card surfaces, photo stickers, and washi accents.
- **Butter Yellow (`#FFF3B0`):** Warm spotlight tone used for sticky-notes, highlight states, and celebratory stars.
- **Deep Warm Charcoal (`#4A3E3D` - Neutral Text):** A soft, comforting dark tone ensuring accessible legibility without the harshness of pitch black.

## Typography
Typographic hierarchy pairs bubbly expressive headings with rounded, comfortable body text:

- **Display & Headings:** Rendered with expressive personality and full Vietnamese diacritic support, balancing celebratory boldness with friendly softness.
- **Body & Captions:** Handled by **Quicksand**, bringing rounded terminals that echo the pill and sticker visual motifs.
- **Multilingual & Calligraphy Accents:** Hanzi and East Asian study accents (such as classroom calligraphy cards: 福, 爱, 安) fall back smoothly onto **Noto Sans**, ensuring stroke weight harmony alongside Quicksand.

## Layout & Spacing
Designed natively for mobile portrait viewports (390px base width, expanding to 430px):

- **Grid & Margins:** A compact 4-column layout with 16px (`1rem`) outer canvas margins and 12px (`0.75rem`) gutters ensures maximum photo canvas size on hand-held devices.
- **Scrapbook Rhythm:** Slight deliberate rotation angles (-2° to +2.5°) applied to photos break rigid vertical columns without disturbing baseline reading flow.
- **Safe Areas:** Generous bottom padding accommodates floating message inputs and quick-reaction balloon triggers above standard device gesture bars.

## Elevation & Depth
Depth mimics physical layers in a memory scrapbook rather than stark computational shadows:

1. **Layer 0 (Base Canvas):** Warm cream `#FFF9F2` matte finish.
2. **Layer 1 (Card & Polaroid Tiles):** White `#FFFFFF` frames with a soft ambient peach-tinted drop shadow: `0 8px 20px -4px rgba(255, 117, 143, 0.12), 0 2px 6px 0 rgba(74, 62, 61, 0.04)`.
3. **Layer 2 (Washi Tape & Stickers):** Semi-opaque tinted overlays (`rgba(225, 212, 249, 0.85)` or `rgba(200, 230, 201, 0.85)`) placed across photo corners with subtle edge texture and zero box-shadow.
4. **Layer 3 (Floating Balloons & Interactive Modals):** High-diffuse elevated glow: `0 12px 28px -6px rgba(255, 117, 143, 0.25)`, paired with holographic gloss gradients (`linear-gradient(135deg, rgba(255,255,255,0.7) 0%, rgba(255,209,220,0.3) 50%, rgba(225,212,249,0.5) 100%)`).

## Shapes
A deeply rounded, pill-dominant shape profile (`roundedness: 3`) reinforces cuteness, safety, and touchability. Buttons, notification tags, and input boxes adopt full circular caps, while memory cards feature comforting 24px (`1.5rem`) to 32px (`2rem`) corner radii.

## Components

### Polaroid & Scrapbook Memory Cards
- **Structure:** Crisp white background with an asymmetric border layout (8px top/sides, 32px bottom chin for handwritten student messages).
- **Accents:** Semi-transparent washi tape stripes positioned across top corners at alternating angles (-3° to +3°).
- **Caption:** Handwritten or warm italicized body copy centered in the lower chin.

### Buttons & Interactive CTAs
- **Primary Action (Send Wish / Heart Burst):** Pill-shaped container filled with vibrant candy pink (`#FF758F`), crisp white text, and a micro-glow drop shadow. On press, smooth scale down to `0.96`.
- **Secondary Action (Browse Album / Filter Class):** Butter yellow (`#FFF3B0`) or lilac (`#E1D4F9`) surface with charcoal text (`#4A3E3D`).

### Badges & Category Chips
- Pill form factor (`rounded-full`), padded with 6px vertical and 14px horizontal space.
- Pastel backgrounds (Blush, Mint, Butter) paired with matching 1px semi-translucent borders for crispness.

### Input Fields & Wish Box
- Soft cream/white input surfaces with a 1.5px candy pink outline on focus.
- Placeholder text in muted warm charcoal with cute emoji prompts (e.g., "Gửi lời chúc ấm áp đến cô... ✨💌").

### Balloon & Celebration Floaters
- Micro-badges styled with soft spherical gradients, specular highlights, and slight floating keyframe animations.