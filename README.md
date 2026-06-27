# 🪶 PaperPlane — Aeroplani di Carta che Volano Lontano

Guida interattiva, in italiano, per costruire passo dopo passo quattro aeroplani di
carta ottimizzati per il volo. Una singola pagina HTML, leggera e (quasi) senza
dipendenze: basta aprire `index.html` nel browser.

**🌐 Sito live:** https://tongatron.org/paperplane/

## ✨ Funzionalità

- **4 modelli** dal più facile al più tecnico:
  - **Il Dardo** — veloce e dritto, per la distanza pura
  - **L'Aliante** — planata dolce, massimo tempo di volo
  - **Il Falco** — design da competizione, distanza massima (con winglet)
  - **Nakamura Lock** — il più stabile e affidabile
- **Vista 3D interattiva** dell'aereo completo per ogni modello: rotazione
  automatica, trascinamento per ruotare e rotella per lo zoom (Three.js/WebGL).
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

## 🌐 Pubblicazione

Il sito è pubblicato con **GitHub Pages** ed è servito sotto il dominio
personalizzato `tongatron.org` (sito utente), quindi è raggiungibile su
**https://tongatron.org/paperplane/**. Il file principale è `index.html`.

## 🛠️ Tecnologia

HTML + CSS + JavaScript vanilla, tutto in un unico file. I diagrammi delle pieghe
sono SVG disegnati a mano. L'unica dipendenza esterna è **Three.js** (caricato da
CDN) per le viste 3D; il resto della pagina funziona anche offline. Le viste 3D
vengono renderizzate solo quando sono visibili a schermo (IntersectionObserver).

## 📄 Licenza

Uso libero personale ed educativo.
