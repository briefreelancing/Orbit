# Orbit
Orbit takes one color and returns a complete brand system: five brand colors with hex and RGB, a full tint and shade ramp for each in 10% steps, a legibility matrix that catches unreadable pairings before they reach production, and a three-font type suite chosen to sit together.

Why
Most palette generators hand you five swatches and wish you luck. What's missing is everything that comes after the palette: the tints you actually need for hover states, the shades you need for borders, an honest answer on whether your body text is readable on your brand color, and a type pairing that doesn't fight the palette.
Orbit does the part that comes after.

What it does
One seed color, five brand colors. Enter a hex, pick from a swatch, or hit Surprise me. Orbit derives a Primary, Secondary, Accent, Neutral, and Contrast under a harmony rule you choose: analogous, complementary, split complementary, triadic, or monochrome plus accent. Every color ships with its hex and RGB values.

Already know part of your direction? Add up to two more seeds and they anchor the Secondary and Accent instead of being generated for you.

Tints and shades in 10% steps. Each of the five colors unspools into a 19-step ramp: nine shades down, the base, nine tints up. Hover any step to read its hex and RGB. Click to copy.

Legibility, checked and fixed. Every pair in the palette is scored against WCAG contrast and graded AAA, AA, or fail. Black on brown doesn't pass, and Orbit says so. More usefully, for every failing pair it scans the ramp and names the exact tint or shade that rescues it, so you stay inside your own system instead of reaching outside it.

A type suite from one font you like. Name a font. If it's on Google Fonts, Orbit loads it live. If it isn't, you get told plainly that it needs licensing, and previews render in the closest free stand-in while your font stays in the spec. Tell Orbit which role your font plays and it fills the other two, so the header, title, and paragraph faces read as one brand rather than three opinions.

See it in use, then take it. A live mock page renders the palette and type together, applying only the pairings that passed the contrast check. Export as CSS custom properties, a Tailwind config, JSON tokens, or a plain sheet with every hex and RGB value spelled out.
