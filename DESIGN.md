# Open Automations & Tech — Brand Design System

> Category: AI & LLM
> AI Automation Agency. Clean, trustworthy, technically premium. Signature indigo accent, weight-300 elegance, generous whitespace.

## 1. Visual Theme & Atmosphere

Clean white canvas with deep indigo headings and a signature indigo-violet (`#4f46e5`) that anchors the brand. The feel is technically premium — like a developer tool refined by a world-class design team. Generous whitespace gives the page room to breathe; content blocks sit on pure white with soft blue-tinted elevation. The overall impression: confident without being loud, technical without being cold.

Headlines use weight 300 at display sizes — light, confident, authoritative without needing to shout. Body text runs at weight 300-400, maintaining the airy, premium feel throughout. Indigo-violet is used sparingly for CTAs and interactive elements — never more than 2 per viewport.

Signature multi-layer shadows use blue-tinted `rgba(79,70,229,0.15)` paired with a neutral `rgba(0,0,0,0.06)` — creating elevation that feels on-brand without overwhelming.

## 2. Color Palette & Roles

### Primary
- **Indigo** (`#4f46e5`): Primary brand color, CTA backgrounds, link text, interactive highlights. A saturated blue-violet.
- **Deep Navy** (`#0f172a`): Primary heading color. Near-black with blue undertone for warmth and depth.
- **Pure White** (`#ffffff`): Page background, card surfaces, button text on dark.

### Brand Dark
- **Brand Dark** (`#0f172a`): Deep navy for dark sections, footer backgrounds, immersive brand moments.
- **Dark Surface** (`#1e293b`): Secondary dark surface for cards on dark backgrounds.

### Accent Colors
- **Cyan** (`#06b6d4`): Accent for decorative elements, secondary highlights, gradient companions.
- **Emerald** (`#10b981`): Success indicators, status badges, positive signals.

### Interactive
- **Indigo** (`#4f46e5`): Primary link color, active states, selected elements.
- **Indigo Hover** (`#4338ca`): Darker indigo for hover states on primary elements.
- **Indigo Light** (`#e0e7ff`): Soft indigo for subdued hover backgrounds, badges.

### Neutral Scale
- **Heading** (`#0f172a`): Primary headings, nav text, strong labels.
- **Label** (`#334155`): Form labels, secondary headings.
- **Body** (`#64748b`): Secondary text, descriptions, captions.
- **Subtle** (`#94a3b8`): Placeholder text, metadata.

### Surface & Borders
- **Border Default** (`#e2e8f0`): Standard border for cards, dividers, containers.
- **Border Indigo** (`#c7d2fe`): Active/selected state borders.
- **Border Light** (`#f1f5f9`): Subtle border for nested elements.

### Shadow Colors
- **Shadow Blue** (`rgba(79,70,229,0.15)`): Brand-tinted primary shadow.
- **Shadow Ambient** (`rgba(0,0,0,0.06)`): Soft ambient shadow for subtle elevation.
- **Shadow Deep** (`rgba(15,23,42,0.12)`): Deeper shadow for elevated elements.

## 3. Typography Rules

### Font Family
- **Primary**: `Inter`, with fallback: `SF Pro Display`, `-apple-system`, `BlinkMacSystemFont`, `system-ui`
- **Monospace**: `JetBrains Mono`, with fallback: `SF Mono`, `ui-monospace`

### Hierarchy

| Role | Size | Weight | Line Height | Letter Spacing |
|------|------|--------|-------------|----------------|
| Display Hero | 56px (3.5rem) | 300 | 1.05 | -0.025em |
| Display Large | 48px (3rem) | 300 | 1.1 | -0.02em |
| Section Heading | 36px (2.25rem) | 300 | 1.1 | -0.015em |
| Sub-heading | 24px (1.5rem) | 400 | 1.2 | -0.01em |
| Card Title | 20px (1.25rem) | 500 | 1.25 | normal |
| Body Large | 18px (1.125rem) | 300 | 1.5 | normal |
| Body | 16px (1rem) | 300 | 1.6 | normal |
| Button | 15px (0.938rem) | 500 | 1 | normal |
| Caption | 14px (0.875rem) | 400 | 1.4 | normal |
| Small | 13px (0.813rem) | 400 | 1.4 | normal |

### Principles
- Weight 300 as signature — lightness conveys confidence
- Negative tracking tightens proportionally with size
- Inter is always set at optical sizing `opsz 32` at display sizes
- No bold (700) in headings — reserve for emphasis inline only

## 4. Component Stylings

### Buttons

**Primary Indigo**
- Background: `#4f46e5`
- Text: `#ffffff`
- Padding: 10px 24px
- Radius: 8px
- Font: 15px Inter weight 500
- Hover: `#4338ca` background, translateY(-1px)
- Shadow: `0 4px 12px rgba(79,70,229,0.3)`
- Use: Primary CTA ("Book a Call", "Get Started")

**Ghost / Outlined**
- Background: transparent
- Text: `#4f46e5`
- Padding: 10px 24px
- Radius: 8px
- Border: `1.5px solid #e2e8f0`
- Hover: border `#4f46e5`, background `rgba(79,70,229,0.04)`
- Use: Secondary actions

**Dark CTA**
- Background: `#0f172a`
- Text: `#ffffff`
- Padding: 10px 24px
- Radius: 8px
- Hover: `#1e293b`
- Use: CTAs on light backgrounds as alternative to indigo

### Cards
- Background: `#ffffff`
- Border: `1px solid #e2e8f0`
- Radius: 12px
- Shadow: `rgba(79,70,229,0.08) 0px 8px 24px -6px, rgba(0,0,0,0.04) 0px 2px 8px`
- Hover: shadow deepens, slight translateY(-2px)

### Navigation
- Clean horizontal nav on white, sticky with blur backdrop
- Brand logotype left-aligned
- Links: Inter 14px weight 500, `#0f172a` text
- CTA: indigo button right-aligned
- Mobile: hamburger toggle

### Badges
- Background: `rgba(79,70,229,0.08)`
- Text: `#4f46e5`
- Padding: 4px 12px
- Radius: 100px
- Font: 13px Inter weight 500

### Inputs
- Border: `1px solid #e2e8f0`
- Radius: 8px
- Focus: `2px solid #4f46e5` ring
- Padding: 12px 16px

## 5. Layout Principles

### Spacing System
- Base unit: 8px
- Scale: 4, 8, 12, 16, 20, 24, 32, 40, 48, 64, 80, 96

### Grid & Container
- Max content width: 1120px
- Hero: centered single-column
- Feature sections: 3-column grid, 2-column on tablet, single on mobile
- Section spacing: 96px desktop, 64px tablet, 48px mobile

### Border Radius
- Small: 6px (badges, tags)
- Medium: 8px (buttons, inputs)
- Large: 12px (cards, containers)
- XLarge: 16px (hero sections, modals)

## 6. Depth & Elevation

| Level | Treatment | Use |
|-------|-----------|-----|
| Flat | none | Page background |
| Ambient | `rgba(0,0,0,0.04) 0px 1px 3px` | Subtle lift |
| Raised | `rgba(79,70,229,0.08) 0px 8px 24px -6px, rgba(0,0,0,0.04) 0px 2px 8px` | Cards |
| Elevated | `rgba(79,70,229,0.12) 0px 16px 40px -12px, rgba(0,0,0,0.06) 0px 4px 16px` | Featured cards, modals |
| Deep | `rgba(15,23,42,0.15) 0px 24px 60px -20px` | Dropdowns, popovers |

## 7. Voice & Tone

- **Confident but warm**: Authoritative without arrogance. "We build" not "We help you build."
- **Technical but accessible**: Use plain language for concepts. "AI agents" + "eliminate busywork."
- **Direct**: Short sentences. Active voice. No filler.
- **Banned words**: "amazing", "incredible", "unleash", "revolutionary", "game-changer", "synergy", "next-level"
- **Pronouns**: "We" + "you" — partnership frame.
- **CTAs**: Action-oriented. "Book a Call", "See What We Do", "Get Started"

## 8. Brand Elements

- **Logo mark**: Stylized "O" with indigo gradient
- **Clear space**: Minimum 24px around logo
- **Logo on dark**: White version on `#0f172a` backgrounds
- **Gradient**: Indigo (`#4f46e5`) to Cyan (`#06b6d4`) for hero decorations
- **Photography**: Abstract tech / network visuals. Blue-toned preferred.
- **Do not**: Stretch logo, add effects, place on busy backgrounds

## 9. Anti-Patterns

- Forbidden: Purple gradient hero backgrounds (keep it clean white)
- Forbidden: Emoji icons in CTAs
- Forbidden: The word "AI" in body copy more than once per section
- Forbidden: Auto-scale animations on hover
- Forbidden: Bouncy or playful easing curves
- Forbidden: Heavy font weights (700+) in headings
- Forbidden: Pill-shaped buttons (radius no larger than 8px for CTAs)
- Forbidden: Rainbow/multi-color palettes
- Forbidden: Particle effects, confetti, or decorative animations
- Forbidden: Stock photo clichés (handshake, server room, generic robots)
