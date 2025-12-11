# PSI - Flexbox Layout Example

Prosta strona demonstrująca układ Flexbox z nagłówkiem, trzema kolumnami i stopką.

## GitHub Pages

Ta strona jest automatycznie publikowana na GitHub Pages poprzez GitHub Actions.

### Jak to działa

1. Każde push do gałęzi `main` uruchamia workflow GitHub Actions
2. Workflow wdraża zawartość repozytorium na GitHub Pages
3. Strona jest dostępna pod adresem: `https://hurabura.github.io/psi/`

### Ręczne wdrożenie

Możesz również uruchomić wdrożenie ręcznie:
1. Przejdź do zakładki "Actions" w repozytorium
2. Wybierz workflow "Deploy static content to Pages"
3. Kliknij "Run workflow"

## Struktura

- `index.html` - główna strona z układem Flexbox
- `.github/workflows/static.yml` - konfiguracja GitHub Actions dla automatycznego wdrożenia
