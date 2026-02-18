# 💻 Strona Agencji IT

Responsywna strona firmowa zbudowana w HTML, SCSS, Bootstrap i JavaScript.

## Sekcje strony

- Pełnoekranowa sekcja hero z efektem paralaksy
- O nas – karty z ikonami i opisem usług
- O nas (hero) – sekcja z tłem i wyróżnionymi cechami firmy
- Portfolio – karuzela z projektami (Bootstrap Carousel)
- Cennik – karty z pakietami cenowymi i efektem hover
- Zespół – karuzela ze zdjęciami członków zespołu (Slick Slider)
- Osiągnięcia – liczniki i statystyki firmy
- Kontakt – dane kontaktowe i media społecznościowe
- Nawigacja – navbar z automatycznym ciemnym tłem przy przewijaniu

## Technologie

| Technologia | Zastosowanie |
|---|---|
| HTML5 | Struktura strony |
| SCSS | Stylowanie |
| Bootstrap 5 | Grid, komponenty, navbar, karuzela |
| Vanilla JavaScript | Navbar scroll efekt, zamykanie menu |
| jQuery + Slick Slider | Karuzela zespołu |
| AOS | Animacje przy przewijaniu |
| Font Awesome | Ikony |
| Google Fonts | Czcionka Montserrat |

## Jak uruchomić

1. Sklonuj repozytorium
```bash
   git clone https://github.com/DanielSam1123/ProGamers.git
   cd ProGamers
```

2. Otwórz `index.html` w przeglądarce

3. Aby edytować style, skompiluj SCSS:
```bash
   sass --watch sass/main.scss css/main.css
```

## Responsywność

| Breakpoint | Układ |
|---|---|
| < 576px | Mobile – 1 karta zespołu |
| ≥ 576px | 2 karty zespołu |
| ≥ 768px | Większa typografia hero |
| ≥ 992px | 3 karty zespołu, pełny układ |
| ≥ 1200px | Pełnorozdzielcze tło hero |

## Licencja

Licencja MIT
