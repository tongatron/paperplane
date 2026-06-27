# ✈️ PaperPlane — Aeroplani di Carta che Volano Lontano

Guida interattiva, in italiano, per costruire passo dopo passo quattro aeroplani di
carta ottimizzati per il volo. Una singola pagina HTML autonoma, senza dipendenze
esterne e senza build: basta aprire `index.html` nel browser.

## ✨ Funzionalità

- **4 modelli** dal più facile al più tecnico:
  - **Il Dardo** — veloce e dritto, per la distanza pura
  - **L'Aliante** — planata dolce, massimo tempo di volo
  - **Il Falco** — design da competizione, distanza massima
  - **Nakamura Lock** — il più stabile e affidabile
- **Diagrammi SVG per ogni piega**, con linguaggio visivo coerente
  (linee di piega tratteggiate, frecce di movimento, linea centrale di riferimento).
- **Procedura guidata a schermo intero** per ogni aereo, un passo alla volta,
  con navigazione da tastiera (← →, Spazio, Esc).
- **Zoom delle immagini** — rotella, doppio click, pinch su touch, trascinamento
  per spostare, più i pulsanti +/−/⟳. Funziona anche cliccando i diagrammi inline.
- **Scheda PDF A4 stampabile** per ogni modello, generata al volo con i diagrammi
  delle pieghe ottimizzati per la stampa (linee marcate su sfondo bianco).
- **Grafico delle traiettorie** a confronto (altezza × distanza) con gli aerei animati.
- **I principi del volo** e la **tecnica di lancio** per volare il più lontano possibile.

## 🚀 Uso

Apri `index.html` in un browser moderno. Nessuna installazione richiesta.

Per servirlo da un server locale (utile su alcuni browser per la stampa):

```bash
python3 -m http.server 8123
# poi apri http://localhost:8123/index.html
```

## 🌐 Pubblicazione con GitHub Pages

Il file principale si chiama `index.html`, quindi la pagina è pubblicabile
direttamente: nelle impostazioni del repository abilita **Pages** sul branch
principale (cartella `/root`) e il sito sarà online.

## 🛠️ Tecnologia

HTML + CSS + JavaScript vanilla, tutto in un unico file. I diagrammi sono SVG
disegnati a mano. Nessun framework, nessuna dipendenza.

## 📄 Licenza

Uso libero personale ed educativo.
