# Good Bowl Gold — Web Design Principles

Source of truth: `design-concept.png` (Visual Brand Direction / Website Concept).
Every page for Good Bowl Gold follows these rules.

**Tagline:** ART, OBJECTS & LITTLE STORIES — ศิลปะ • งานคราฟต์ • เรื่องราวเล็กๆ ที่น่ารัก
**Sign-off:** *Good art brings good days*

## Color palette

| Token | Name | Hex | Use |
|---|---|---|---|
| `--paper` | Warm Paper | `#F6F1E8` | Page background (always) |
| `--ink` | Ink | `#242321` | Text, lines, logo |
| `--cobalt` | Cobalt | `#315A9A` | Primary accent, buttons |
| `--coral` | Coral | `#E97862` | Accent / motifs |
| `--ochre` | Ochre | `#D7A24A` | Accent / motifs |
| `--aqua` | Muted Aqua | `#9BBDB6` | Accent / motifs |

Accents are for brush marks, buttons and small highlights — never large flat fills behind text.

## Typography

- **Headline / Display:** contemporary serif, bold, uppercase for big brand moments → `DM Serif Display` (+ `Noto Serif Thai` for Thai).
- **Interface / Body:** clean friendly sans → `Montserrat` (+ `Noto Sans Thai` for Thai).
- Small labels: Montserrat, uppercase, letter-spacing ~0.15em, 11–13px (e.g. `SELECTED WORKS`, `VIEW ALL →`).
- Handwritten note (sign-off only): script font, cobalt, slightly rotated.

## Image treatment

- Hand-painted / gouache texture, visible brush strokes and paper grain.
- Rich, natural colors — not overly saturated.
- Cropped, organic compositions; collage of artwork + photos of objects.
- Authentic, personal, expressive. Real work only in production (current `assets/` crops are placeholders).

## Graphic motifs

- Brush marks, organic blobs, hand-drawn lines, little flowers/leaves.
- Playful and imperfect; used as accents and frames at section edges, never over content.

## Layout

- Generous whitespace; editorial, balanced grid.
- Strong visual hierarchy: big serif headline → small uppercase label → short body.
- Mix of large imagery + simple text. Clean and readable.
- Section header pattern: `LABEL ———————————— VIEW ALL →` (thin ink rule).
- Work cards: image, then uppercase caption with `→` on the right.
- Mobile: stacked single column, same hierarchy; nav collapses to a menu icon.

## Buttons & links

- Primary: cobalt brush-stroke shape, white uppercase text + `→` (`EXPLORE WORKS →`).
- Secondary: text link, uppercase, underlined with a thin ink rule (`VIEW MORE →`).

## Tech rules

- Plain HTML + CSS, JavaScript only if truly needed.
- Colors as CSS custom properties on `:root` (names above).
- Deployed via GitHub Pages from `main` — push to publish.
