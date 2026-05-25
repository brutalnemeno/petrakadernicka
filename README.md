# Petra Kaderníčka - kadernícka stránka

Hotová statická stránka je v súbore `index.html`. Dá sa otvoriť priamo v prehliadači.

## Ako upraviť základné údaje

- Názov, texty, služby a ceny upravíš v `index.html`.
- E-mail pre kontaktný formulár upravíš v `script.js` v riadku `email`.
- Odkazy na sociálne siete upravíš v `script.js` v časti `socials`.
- Telefón, adresa a otváracie hodiny sú v `index.html`.

## Ako pridať vlastné obrázky

Najjednoduchšie je nahradiť tieto súbory vlastnými obrázkami:

- `assets/images/hero.svg` - hlavná veľká fotka
- `assets/images/gallery-1.svg` - prvá fotka v galérii
- `assets/images/gallery-2.svg` - druhá fotka v galérii
- `assets/images/gallery-3.svg` - tretia fotka v galérii

Ak použiješ JPG alebo PNG, zmeň aj názvy v `index.html`, napríklad:

```html
<img class="hero-image" src="assets/images/hero.jpg" alt="Moderné kaderníctvo" />
```

## Kontaktný formulár

Formulár aktuálne otvorí e-mailovú aplikáciu s pripravenou správou. Na reálne odosielanie bez e-mailovej aplikácie treba pridať službu ako Formspree, Netlify Forms alebo vlastný backend.
