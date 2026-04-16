# HTTP Security Header Checker

Narzędzie do analizy nagłówków bezpieczeństwa HTTP. 
Sprawdza czy strona internetowa implementuje 
podstawowe zabezpieczenia rekomendowane przez OWASP.

## Demo

[link do GitHub Pages — instrukcja poniżej]

## Co sprawdza

- **HSTS** — wymuszenie HTTPS
- **Content-Security-Policy** — ochrona przed XSS
- **X-Frame-Options** — ochrona przed clickjacking
- **X-Content-Type-Options** — ochrona przed MIME sniffing
- **Referrer-Policy** — ochrona prywatności
- **Permissions-Policy** — kontrola dostępu do API przeglądarki

## Technologie

HTML, CSS, JavaScript

## Jak uruchomić lokalnie

Wystarczy otworzyć index.html w przeglądarce:

https://vrath.github.io/http-header-checker/

Nie wymaga instalacji ani backendu.
