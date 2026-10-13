# codebase – Programovací jazyky

Školní projekt pro výuku HTML a CSS. Jednostránkový web představuje obory programování, používané jazyky a krátké ukázky kódu. Není oficiální stránkou těchto jazyků.

## Spuštění

Otevři `index.html` v prohlížeči. Není potřeba instalace ani sestavení. Internet je potřeba pro Google Fonts a ikony Font Awesome.

Publikovaná stránka: https://vitekcharvat.github.io/web-coding-languages/

## Soubory

- `index.html` – navigace, označení školního projektu, úvod, rozbalovací témata a zápatí.
- `style.css` – barvy, typografie, rozložení a responzivita. Složitější pravidla mají vysvětlující komentáře.
- `codebase-favicon.svg` – ikona stránky.
- `assets/` – barevné návrhy a schválený mockup. Přehled je v `assets/README.md`.

## Design a úpravy

Schválený návrh je `assets/mockup-04-puvodni-vzhled.png`. Používá tmavě modrou, žluté zvýraznění a krémové pozadí. Původní karty jazyků byly nahrazené rozbalovacími tématy. Barvy a fonty lze změnit v bloku `:root` na začátku CSS; pravidla je používají přes `var()`.

Web používá pouze HTML a CSS. Rozbalování zajišťují nativní prvky `details` a `summary`; fungují i klávesnicí a více témat může být otevřených současně. V menším zobrazení zůstávají v navigaci pouze ikony; odkazy mají `aria-label` pro čtečky obrazovky. Dlouhý kód lze vodorovně posouvat uvnitř bloku.

## Témata a ukázky

- Vývoj her
- Umělá inteligence (AI)
- Strojové učení
- Vývoj webů
- Mobilní aplikace
- Data a databáze
- Automatizace a skripty
- Systémy a vestavěná zařízení

Každé téma obsahuje loga jazyků, rozšířený popis, příklady využití, doporučení pro začátečníka a ilustrační příklad s vysvětlením. Ukázky jsou pouze text v `pre/code` a web je nespouští, ani JavaScript v ukázce webového vývoje. Předpoklady jednotlivých příkladů jsou uvedené nad kódem. Pro přidání dalšího tématu zkopíruj blok `details class="topic"` v HTML.

Barevnost kódu je zapsaná ručně pomocí `span` s třídami `token-keyword`, `token-string`, `token-number`, `token-function` a `token-comment`. Při změně příkladů je potřeba upravit i tyto značky. Loga jazyků jsou místní SVG z Deviconu v `assets/logos/`; zdroje popisuje `assets/logos-sources.md`.

## Validace

Ikony HTML a CSS v zápatí otevírají validátory W3C pro publikovanou stránku a její CSS. Nejde o certifikát úspěšné validace. Po změnách nejprve nahraj aktuální soubory na web a potom zkontroluj výsledky. Lokální soubory lze do validátorů také vložit ručně.

- HTML: https://validator.w3.org/nu/
- CSS: https://jigsaw.w3.org/css-validator/

## Zdroje a autorství

- Fonty DM Sans a Space Grotesk: Google Fonts, načtené pomocí CSS `@import`.
- Ikony: Font Awesome Free 6.7.2 přes CDN cdnjs.
- Autor školního projektu: Vít Charvát.
- Při návrhu a úpravách byla použita AI; odkaz na konverzaci je v zápatí. Mockupy jsou AI návrhy, nikoli přesné snímky implementace.
