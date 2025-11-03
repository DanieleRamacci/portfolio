# Portfolio di Daniele Ramacci — GitHub Pages

Sito statico pronto per la pubblicazione su **GitHub Pages**.

## Struttura
- `index.html` — home con **timeline**, **progetti**, **sezione GitHub** dinamica (API pubbliche).
- `assets/` — metti qui PDF/immagini, es.:
  - `assets/CV-Daniele-Ramacci.pdf`
  - `assets/Presentazione-SaluLink.pdf`

## Pubblicazione
1. Crea un repository **pubblico** su GitHub (es. `portfolio`).
2. Carica `index.html` e la cartella `assets/`.
3. Vai su **Settings → Pages**:
   - *Build and deployment* → `Deploy from a branch`
   - Branch `main` e cartella `/root`
4. L’URL sarà `https://<username>.github.io/portfolio` (oppure `https://<username>.github.io/` se il repo si chiama `<username>.github.io`).

## Note
- La lista dei repo GitHub è letta via **fetch** dalle API pubbliche e mostra gli ultimi 6 aggiornati.
- Le pagine progetto sono gestite via **hash routing** (`#/p/salulink`, `#/p/smartkiosk`, `#/p/netbox`) e non richiedono configurazione 404.
- Sostituisci i link “Presentazione CCR Palau” e i file PDF con quelli reali.
