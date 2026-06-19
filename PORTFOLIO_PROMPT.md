# Portfolio Prompt

Bouw en onderhoud een persoonlijke portfolio-website voor Marc René volgens Atomic Design.

## Doel

Maak een moderne, professionele portfolio met subtiele 8-bit accenten. De site moet zakelijk genoeg zijn voor opdrachtgevers, maar persoonlijk genoeg om hobby's, blog, muziek en projecten geloofwaardig samen te brengen.

## Informatiearchitectuur

- Topmenu: Home, CV, Projecten, Hobby's, Blog, Contact.
- Spotify staat niet in het topmenu.
- Spotify is bereikbaar via een CTA op de Hobby's-pagina.
- Blog gebruikt de Substack-link `https://marcren1.substack.com/` en toont recente posts via RSS/RSS2JSON.
- Projecten tonen `Opdrchtn.com`, `eyay.online` en `bousjans.paris`.
- CV-download gebruikt `assets/Marc_Rene_Principal_Consultant_Business_Consultant.pdf`.
- Home gebruikt de profielfoto uit het CV als `assets/marc-rene-profile.png`.

## Atomic Design

- Atoms: buttons, tags, labels, inputs, icon marks, typography tokens.
- Molecules: nav links, quick-link bento cards, project cards, hobby cards, timeline rows.
- Organisms: topnav, hero section, portfolio board, project grid, hobby grid, blog overview, Spotify embed, contact section.
- Templates: route layout met page header, content grid en CTA-zone.
- Pages: Home, CV, Projecten, Hobby's, Blog, Spotify, Contact.

## Visuele Richting

- Moderne kleuren, geen roze topmenu.
- Gebruik een felle cyan/blauwe navigatie-accentkleur.
- Gebruik moderne fonts: Inter, Space Grotesk en een subtiele mono voor labels.
- Geen zwaar arcade-font voor lange tekst.
- Home bevat een statische gegenereerde 8-bit headerafbeelding met de naam `Marc René`.
- Gebruik alleen eigen SVG/CSS pixel-art elementen of zelf gegenereerde assets; geen gekopieerde Shutterstock/Flaticon assets.
- Bento-kaarten krijgen een subtiele pixelated outline bij hover.
- Layout blijft licht, snel, responsive en toegankelijk.

## UX-regels

- Geen Spotify-link in het topmenu.
- Blog niet Substack noemen in de navigatie.
- Menu compact houden.
- Kaarten mogen speels zijn, maar tekst moet zakelijk en scanbaar blijven.
- Geen tekstoverlap op mobiel.
- Alle routes moeten via hash-navigatie blijven werken.
