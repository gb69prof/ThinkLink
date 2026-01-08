# ThingLink-Lite (offline + GitHub Pages)

Questa è una web-app **single-file** (HTML+CSS+JS) per creare **immagini interattive con hotspot**, in stile ThingLink.

## Funzioni
- Carica un'immagine (anche da iPad) e aggiungi hotspot
- Tipi hotspot: testo, link, immagine, video, audio, PDF (via URL o percorso relativo)
- Modalità: Modifica / Visualizza
- Pan + Zoom (mouse wheel + touch pinch)
- Export/Import progetto in JSON
- Salvataggio rapido nel browser (localStorage)

## Uso rapido
1. Apri `index.html` nel browser
2. Carica un'immagine
3. In modalità **Modifica**:
   - **iPad**: pressione prolungata per creare hotspot
   - **desktop**: doppio click per creare hotspot (oppure SHIFT+click)
4. Imposta titolo/tipo/contenuto e salva
5. Passa a **Visualizza** e testa

## Pubblicazione su GitHub Pages
- Carica questa cartella in un repository
- Abilita GitHub Pages
- Metti media in `assets/` e usa URL relativi tipo `assets/file.pdf`

> Nota: se nel JSON salvi un'immagine come dataURL, il file può diventare grande.
