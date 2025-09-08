# Sito Dietista – Dott. Roberto Soave

Landing page responsive (HTML/CSS) pensata per GitHub Pages.

## Pubblicazione rapida su GitHub Pages
1. Crea un repository (es. `dietista`) pubblico.
2. Carica questi file nella root del repo.
3. In **Settings → Pages** imposta:
   - **Source**: Deploy from a branch
   - **Branch**: `main` – **Folder**: `/ (root)`
4. Salva: dopo poco il sito sarà disponibile a `https://<utente>.github.io/dietista/`

> Se vuoi un sito principale senza il suffisso `/dietista/`, crea un repo chiamato **<utente>.github.io**.

## Personalizzazioni
- In `index.html` sostituisci: email, telefono, WhatsApp, indirizzo e mappa.
- Aggiorna i link a Privacy/Cookie Policy.
- (Opzionale) Usa un servizio form (es. Formspree) al posto di `mailto:`.

## Struttura
```
.
├─ index.html
├─ assets/
│  └─ css/
│     └─ style.css
├─ robots.txt
└─ .nojekyll
```
