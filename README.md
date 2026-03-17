# Sito statico (HTML + CSS + JS)

Questa versione è pensata per essere pubblicata come sito statico (GitHub Pages, Netlify, ecc.)
senza roba da sviluppo (HMR / dev-server).

## File
- index.html
- styles.css
- script.js

## Personalizzazione rapida (senza toccare la logica)
1) Immagini: metti i tuoi file in `/assets/` e usali in CSS (background, hero, ecc.)
2) Colori/font/spazi: modifica solo `styles.css` (consigliato: cerca la sezione "safe to edit" se presente)

### Consiglio pratico
Se vuoi che testi/immagini siano modificabili da un singolo punto (tipo `config.js`),
serve che il progetto nasca con sorgenti (non da bundle). Questa build mantiene funzioni e resa,
ma `script.js` resta un bundle.
