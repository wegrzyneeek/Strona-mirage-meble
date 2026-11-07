# Mirage Meble – strona internetowa

Statyczna strona one-page (HTML + Tailwind CSS przez CDN + Font Awesome + Vanilla JS), gotowa do hostowania na GitHub Pages.

## Publikacja na GitHub Pages
1. Repozytorium → **Settings → Pages**.
2. *Source*: **Deploy from a branch**, gałąź `main`, folder `/ (root)` → **Save**.
3. Po ok. minucie strona będzie dostępna pod adresem `https://<użytkownik>.github.io/<repozytorium>/`.

## Co uzupełnić przed startem
- **Telefon / e-mail / adres** – wyszukaj w `index.html`: `+48 500 000 000`, `500000000`, `kontakt@miragemeble.pl`, `ul. Przykładowa 1`.
- **Formularz** – załóż darmowe konto na [formspree.io](https://formspree.io) i zamień `TWOJ_ID` w atrybucie `action` formularza. Do tego czasu formularz otwiera program pocztowy (mailto).
- **Logo** – w nagłówku zamień `<svg>` na `<img src="img/logo.png" alt="Mirage Meble" class="h-11">`.
- **Zdjęcia realizacji** – dodaj pliki do folderu `img/` i podmień adresy `src` w sekcji `#realizacje`.
- **Opinie** – zastąp przykładowe karty prawdziwymi opiniami (atrybut `data-source="google"` lub `"oferteo"`), a linki do profili Google/Oferteo i social media – własnymi adresami.
- **Liczby w Hero** (lata doświadczenia, liczba projektów, gwarancja) – atrybuty `data-count`.

## Paleta
| Rola | HEX |
|---|---|
| Butelkowa zieleń (główny) | `#14332A` |
| Zieleń głęboka (tła ciemne) | `#0B1F19` |
| Kremowa biel (tło) | `#F8F4EC` |
| Miedź / drewno (akcent) | `#C08A5B` |
| Jasna miedź (hover) | `#D4A373` |
| Grafit (tekst) | `#1E2421` |

Fonty: **Cormorant Garamond** (nagłówki) + **Montserrat** (tekst).
