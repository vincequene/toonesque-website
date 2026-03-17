# toonesque. — landing page

Site officiel de [toonesque.](https://toonesque.com) — fait maison.

## C'est quoi

Landing page statique pour toonesque., un média qui fait des émissions sur tout ce qui est cartoonesque. Aucun framework, aucune dépendance — HTML, CSS et un peu de JS vanilla.

## Pages

- `index.html` — page d'accueil : hero, dernière vidéo, liens plateformes
- `about.html` — à propos : histoire du projet, les trois chapitres, les formats, l'équipe

## Stack

- HTML / CSS / JS vanilla
- [Font Awesome 6](https://fontawesome.com) — icônes
- [Google Fonts](https://fonts.google.com) — Barlow Condensed, Fredoka, Libre Franklin
- Alte Haas Grotesk — fonte locale (`/fonts`)
- [rss2json](https://rss2json.com) — fetch de la dernière vidéo YouTube

## Structure

toonesque-website/
├── index.html
├── about.html
├── favicon.ico
├── favicon-512.png
├── logoc.png
├── og.png
└── fonts/
├── AlteHaasGroteskBold.woff2
└── AlteHaasGroteskRegular.woff2

text

## Notes

- Le fond s'assombrit au scroll via un `--scroll-dark` CSS custom property
- Le logo a un effet parallaxe 3D au survol de la souris
- Les titres de saison ont chacun leur identité : première saison (Alte Haas), round 2 (EB Garamond italic), troisième acte (glitch animé)
- toonesque. fait partie du projet [TOONSQUAD](https://toonsquad.co)

## Crédits

Réalisé par [VincenTimes.](https://vincentimes.fr) — une production [cabinet26](https://cabinet26.com)
