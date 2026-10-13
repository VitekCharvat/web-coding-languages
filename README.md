# codebase – Programovací jazyky

Školní projekt pro výuku HTML a CSS. Jednostránkový web představuje Python, JavaScript, Javu a C++. Není oficiální stránkou těchto jazyků.

## Spuštění

Otevři `index.html` v prohlížeči. Není potřeba instalace ani sestavení. Internet je potřeba pro Google Fonts a ikony Font Awesome.

Publikovaná stránka: https://vitekcharvat.github.io/web-coding-languages/

## Soubory

- `index.html` – navigace, označení školního projektu, úvod, popis tématu, karty a zápatí.
- `style.css` – barvy, typografie, rozložení a responzivita. Složitější pravidla mají vysvětlující komentáře.
- `codebase-favicon.svg` – ikona stránky.
- `assets/` – barevné návrhy a schválený mockup. Přehled je v `assets/README.md`.

## Design a úpravy

Schválený návrh je `assets/mockup-04-puvodni-vzhled.png`. Používá tmavě modrou, žluté zvýraznění, krémové pozadí a barevné karty. Barvy a fonty lze změnit v bloku `:root` na začátku CSS; pravidla je používají přes `var()`.

Web používá pouze HTML a CSS, bez JavaScriptu. Na široké obrazovce jsou čtyři karty vedle sebe, do 850 px dvě a do 500 px jedna. V menším zobrazení zůstávají v navigaci pouze ikony; odkazy mají `aria-label` pro čtečky obrazovky.

## Validace

Ikony HTML a CSS v zápatí otevírají validátory W3C pro publikovanou stránku a její CSS. Nejde o certifikát úspěšné validace. Po změnách nejprve nahraj aktuální soubory na web a potom zkontroluj výsledky. Lokální soubory lze do validátorů také vložit ručně.

- HTML: https://validator.w3.org/nu/
- CSS: https://jigsaw.w3.org/css-validator/

## Zdroje a autorství

- Fonty DM Sans a Space Grotesk: Google Fonts, načtené pomocí CSS `@import`.
- Ikony: Font Awesome Free 6.7.2 přes CDN cdnjs.
- Autor školního projektu: Vít Charvát.
- Při návrhu a úpravách byla použita AI; odkaz na konverzaci je v zápatí. Mockupy jsou AI návrhy, nikoli přesné snímky implementace.
