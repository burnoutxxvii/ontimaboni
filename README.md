Onti ma Boni — sito statico

Questa repo contiene il sito per Onti ma Boni (repo: `ontimaboni`).

Deploy rapido con GitHub Pages

1. Crea una repository GitHub chiamata `ontimaboni` e push del contenuto su `main`.
2. Il workflow GitHub Actions (`.github/workflows/deploy.yml`) pubblicherà la root del repo sulla branch `gh-pages`.
3. Il file `CNAME` contiene `ontimaboni.capellconsulting.com` — aggiungi nel DNS del dominio `capellconsulting.com` un record CNAME per `ontimaboni` che punti a `<your-github-username>.github.io`.

Note rapide

- Se preferisci che il sito sia servito dalla root senza redirect, rinomina `OmB.html` in `index.html` e rimuovi il redirect inserito.
- Per aggiornamenti: committa e push; Actions si occuperà del deploy automatico.
