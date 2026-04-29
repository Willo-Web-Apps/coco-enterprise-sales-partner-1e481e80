# Design DNA — EdgeSales

## Visual Personality: dark-modern
## Layout: enterprise
## Typography: bold-display

### Color Palette
- Primary (Amber Gold): #F59E0B → oklch(0.78 0.17 75)
- Accent (Deep Slate): #1E293B → oklch(0.24 0.025 250)
- Surface (Near-black): #0F172A → oklch(0.15 0.025 258)
- Text Light: #F8FAFC → oklch(0.99 0.002 250)
- Text Muted: #94A3B8 → oklch(0.65 0.04 250)

### Font Pairing
- Display: Bebas Neue — 400 (ultra-bold condensed for hero headlines)
- Subheadings / UI: Barlow — 400, 500, 600, 700
- Body: Barlow — 400, 300

### Unique Design Choices
1. **Amber glow hero**: A radial gradient "glow" emanates from behind the headline text in amber/gold — like a spotlight on a dark stage. Feels like a trading floor at 2am, all business.
2. **Off-axis stat bar**: The proof/metrics row uses an angled cut divider between the hero and the next section — not a flat horizontal line, but a CSS clip-path skew to create visual momentum.
3. **Card depth system**: Feature cards use `#1E293B` (deep slate) as the base, with a 1px amber top border on hover — communicates "clickable premium" without flashy effects. Section backgrounds alternate between `#0F172A` and `#111827` for rhythm without using light sections.
4. **Amber-on-dark CTA section**: Final CTA section uses an amber fill for the button against pure near-black, creating maximum contrast and urgency. The heading scales up to create a typographic statement that's impossible to ignore.
