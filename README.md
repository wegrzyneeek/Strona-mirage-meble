# Mirage Meble – strona internetowa

Statyczna strona one-page (HTML + Tailwind CSS przez CDN + Font Awesome + Vanilla JS), gotowa do hostowania na GitHub Pages.

## Publikacja na GitHub Pages
1. Repozytorium → **Settings → Pages**.
2. *Source*: **Deploy from a branch**, gałąź `main`, folder `/ (root)` → **Save**.
3. Po ok. minucie strona będzie dostępna pod adresem `https://<użytkownik>.github.io/<repozytorium>/`.

## Co uzupełnić przed startem
- **Formularz** – działa przez FormSubmit.co bez zakładania konta. Po pierwszym wysłanym zgłoszeniu na skrzynkę meble.mirage24@gmail.com przyjdzie e-mail „Action Required: Activate FormSubmit” – kliknij przycisk aktywacji jeden raz.
- **Zdjęcia realizacji** – dodaj pliki do folderu `img/` i podmień adresy `src` w sekcji `#realizacje`.
- **Opinie** – sekcja pokazuje ocenę z Oferteo (5,0 / 24 opinie). Można dodać karty z prawdziwymi opiniami klientów.

## Materiały marki (folder `img/`)
| Plik | Zastosowanie |
|---|---|
| `logo-znak-jasny.png`, `logo-napis-jasny.png` | logo w nawigacji (przezroczyste tło) |
| `logo-mirage-jasne.png` | pełne logo na ciemne tła (stopka) |
| `logo-mirage-ciemne.png` | pełne logo na jasne tła |
| `logo-mirage-zielone.jpg`, `mirage-plakat.jpg` | oryginały (social media, podgląd linku) |
| `kuchnia-mirage.jpg` | kadr kuchni z plakatu – tło sekcji głównej |
| `favicon.png` | ikona karty przeglądarki |

## Paleta (pobrana z logo i plakatu)
| Rola | HEX |
|---|---|
| Najgłębsza zieleń (tło logo, sekcja główna) | `#0B231C` |
| Butelkowa zieleń (kolor główny) | `#0F2A21` |
| Kremowa biel (napis logo, tło) | `#F3EFE7` |
| Miedź z logo (akcent, przyciski) | `#C68760` |
| Ciemna miedź (tekst na kremowym tle) | `#A06B47` |
| Grafit (tekst) | `#1E2421` |

Fonty: **Cormorant Garamond** (nagłówki, jak na plakacie) + **Montserrat** (tekst, geometryczny jak napis w logo).
