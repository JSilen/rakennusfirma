# Baseball Terapia - Astro Template

Tämä on Astro-pohjainen template Baseball Terapia -podcastin verkkosivuille. Template on rakennettu [Astro](https://astro.build/) -frameworkilla ja käyttää [Tailwind CSS](https://tailwindcss.com/) -viitekehystä tyylimuotoiluun.

## Ominaisuudet

- 🚀 Nopeat, staattiset sivut Astrolla
- 🎨 Tailwind CSS -pohjainen design
- 🌙 Tumma teema baseball-aiheisilla väritehosteilla
- 📱 Täysin responsiivinen design
- 🔍 SEO-optimoitu
- 📝 Blogi-osio (valmiina Netlifyn CMS:n integrointia varten)
- 🎙️ Podcast-osio (valmiina Spotify API:n integrointia varten)
- 👥 Tietoa meistä -sivu
- ⚡ Minimaalinen JavaScript, parempi suorituskyky

## Sivut

- 🏠 **Etusivu**: Podcast-esittely, viimeisimmät jaksot ja blogikirjoitukset
- 📚 **Blogi**: Blogikirjoitusten listaus ja yksittäisten kirjoitusten näyttäminen
- 🎧 **Podcast**: Podcast-jaksojen listaus ja yksittäisten jaksojen näyttäminen
- ℹ️ **Tietoa meistä**: Tietoa podcast-tiimistä, FAQ ja yhteydenottolomake
- 🔍 **404**: Mukautettu 404-sivu

## Miten käyttää

### Asennus

1. Kloonaa repo:
```bash
git clone https://github.com/your-username/baseballterapia.git
cd baseballterapia
```

2. Asenna riippuvuudet:
```bash
npm install
```

3. Käynnistä kehityspalvelin:
```bash
npm run dev
```

### Rakennus tuotantoon

```bash
npm run build
```

Tuotantoversio generoidaan `dist/`-kansioon.

## Kustomointi

### Värit

Värit on määritelty `tailwind.config.mjs`-tiedostossa, josta voit muuttaa päävärejä:

```js
colors: {
  'bt-green': '#1A6340',
  'bt-dark': '#0F1112', 
  'bt-white': '#FFFFFF', 
},
```

### Fontit

Fontit on määritelty `tailwind.config.mjs`-tiedostossa:

```js
fontFamily: {
  head: ['Oswald', 'sans-serif'],
  body: ['Rubik', 'sans-serif'],
},
```

### Logo

Lisää logosi `public/`-kansioon ja päivitä viittaukset siihen `Layout.astro`-tiedostossa.

## Lisenssi

MIT