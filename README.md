# Pagina GitHub Pages per STAT PhD School

## Pubblicazione

1. Crea un repository GitHub, per esempio `stat-phd-school`.
2. Carica nella radice del repository il contenuto di questa cartella, conservando `_layouts/default.html` nella sottocartella `_layouts`.
3. Apri **Settings → Pages**.
4. In **Build and deployment**, scegli **Deploy from a branch**.
5. Seleziona il branch **main** e la cartella **/(root)**, poi **Save**.
6. Quando la pubblicazione termina, apri l'indirizzo mostrato da GitHub Pages.

Documentazione: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

Non aggiungere `.nojekyll`: questa versione usa Jekyll per convertire il Markdown in HTML.

## File

- `index.md`: testo della pagina, modificabile in Markdown.
- `_config.yml`: configurazione Jekyll.
- `_layouts/default.html`: impaginazione e stile responsive, senza dipendenze esterne.
- `Program-Draft_STAT-PhD-School_VIU_EN.pdf`: PDF originale collegato dalla pagina.

## Scelte editoriali e punti da completare

- Il titolo “STAT PhD School — AI in Research” e la descrizione introduttiva sono proposte editoriali, ricavate dal programma.
- La pagina rimane in inglese, come il PDF.
- Il 15 ottobre 2026 è la data del draft, non la data dell'evento.
- Il PDF non specifica date dell'evento, sede, contatti o modalità di iscrizione: aggiungerli quando disponibili.
- Gli orari sono quelli del draft, inclusa la sovrapposizione del Day 1: 16:50–17:50 e 17:40–18:10. La pagina la segnala esplicitamente; aggiornare orari e nota dopo la conferma.
- Nel Day 2, 11:35–12:30 sono 55 minuti, ma il PDF indica 45 minuti di talk + 15 di Q&A. La pagina conserva lo slot e omette la durata contraddittoria. Verificare prima della versione finale.
- Titoli TBD, ruoli e affiliazioni sono riportati dal draft e non verificati su fonti esterne.
- Il testo web sintetizza le descrizioni; il PDF incluso rimane la fonte integrale.

## Verifica

Controllati struttura dei file, collegamento al PDF, presenza di tutte le sessioni e mantenimento degli orari. La build su GitHub Pages non è stata eseguita in questo ambiente.
