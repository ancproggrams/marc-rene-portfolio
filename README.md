# Marc René Portfolio

Persoonlijke portfolio-website van Marc René: business, IT, continuïteit,
digitale projecten, blog en marcsmusic in een lichte 8-bit stijl.

## Stack

- Statische HTML/CSS/JavaScript
- Assets in `assets/`
- Kleine Node.js static server voor Railway
- Geen frontend build step en geen runtime dependencies

## Lokaal starten

```bash
npm start
```

De site draait standaard op `http://localhost:4173`.

Een andere poort gebruiken:

```bash
PORT=4180 npm start
```

## Railway deployment

Railway kan de site starten met:

```bash
npm start
```

De server luistert naar `process.env.PORT`, zoals Railway verwacht.

## Belangrijke bestanden

- `index.html` - volledige website
- `server.js` - productie static server
- `assets/marc-rene-8bit-header.png` - homepage header
- `assets/marcsmusic-waveform.png` - marcsmusic waveform
- `assets/marc-rene-profile.png` - profielfoto
- `assets/Marc_Rene_Principal_Consultant_Business_Consultant.pdf` - downloadbare CV

## Content aanpassen

- Paginateksten staan direct in `index.html`.
- Projectdata staat in `siteData.projects` onderaan `index.html`.
- Blog staat ingesteld op `https://marcren1.substack.com/`.
- Spotify staat ingesteld op de aangeleverde Spotify embed.

## Domein

Voor een custom domain via Cloudflare:

- Voeg het domein eerst toe in Railway.
- Neem de Railway `CNAME` en `TXT` verificatierecords over in Cloudflare.
- Gebruik één canonieke host, bijvoorbeeld root of `www`.
- Zet HTTPS aan en voorkom dubbele redirectregels.
