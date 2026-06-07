# Fonts

This system uses two typefaces, both available on **Google Fonts** and loaded via the
`@import` at the top of `../colors_and_type.css` (and `<link>` tags in HTML artifacts):

| Role        | Family    | Foundry                         | Weights used            |
|-------------|-----------|---------------------------------|-------------------------|
| Display     | **Spectral** | Production Type               | 300, 400, 500 (+ italic 300/400) |
| UI / Body   | **Archivo**  | Omnibus-Type (Buenos Aires, AR) | 400, 500, 600           |

## Why these

- **Spectral** — a transitional serif designed for screen reading; refined, low-drama,
  elegant when set light at large sizes. Carries the "editorial monograph" register
  without the fashion-magazine flourish of higher-contrast didones.
- **Archivo** — a neutral grotesque drawn by an **Argentine** foundry, a quiet nod to
  Camila's Buenos Aires origins. Excellent for tracked uppercase labels and metadata.

## Substitution note (please confirm)

No brand font files were supplied. These two Google Fonts were chosen as the system's
canonical faces. If you license bespoke or studio faces (e.g. a Neue-Haas / Suisse-style
grotesque, or a specific serif), drop the `.woff2` files in this folder and replace the
`@font-face`/`@import` references in `colors_and_type.css`. The type *scale* and rules
will carry over unchanged.

Self-hosting: download the families from https://fonts.google.com (Spectral, Archivo),
place the `.woff2` files here, and swap the Google `@import` for local `@font-face` rules.
