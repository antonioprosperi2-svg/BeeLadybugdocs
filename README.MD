![BeeLadybug](https://beeenginejs.com/wp-content/uploads/2026/10/Gemini_Generated_Image_mkk161mkk161mkk1.jpg)

# BeeLadybug Docs

Sorgenti HTML della documentazione di [BeeLadybug](https://www.npmjs.com/package/bee-ladybug),
l'overlay di telemetria e ispezione visiva per Canvas, DOM, Python e AI.

Online: https://beeenginejs.com/ladybug/inizia/

## Struttura

- `preview.html` — pagina Inizia (installazione, quick start, tasti)
- `concetti.html` — pagina Concetti (Core cieco, contratto `sendData`, clock)
- `src/adapters/CanvasAdapter.html` — pagina CanvasAdapter (entità, opzioni, pacchetti, overlay, autoPump, metodi, report)
- `src/adapters/WebDOMAdapter.html` — pagina WebDOMAdapter (box model, hover, watch, mutazioni, metodi, report)
- `src/adapters/CSSAdapter.html` — pagina CSSAdapter (CSS hunt F6, scansione S, pin P, controlli, opzioni, Issues/Inspect, metodi, report, limiti)
- `src/core/`, `src/adapters/`, `src/python/` — pagine dei moduli. Gli altri file HTML sono ancora vuoti.
  Nel pacchetto npm il modulo Python sta in `src/adapters/python/PythonBridge.js`; qui `src/python/` è solo il segnaposto della sua pagina.

Ogni pagina pubblicata è un frammento da incollare in un blocco HTML personalizzato di WordPress.
Le pagine dei moduli si scrivono solo dopo una revisione del codice di quel modulo.
La documentazione segue la versione `0.6.4` di `bee-ladybug` (badge in alto e URL CDN negli snippet).

## Anteprima locale

Apri la cartella in VS Code e avvia **Go Live**, poi apri `preview.html`, `concetti.html`, `src/adapters/CanvasAdapter.html`, `src/adapters/WebDOMAdapter.html` o `src/adapters/CSSAdapter.html`.

## Stato

| Pagina | Stato |
| --- | --- |
| Inizia | pubblicata |
| Concetti | pronta in `concetti.html` |
| CanvasAdapter | pronta in `src/adapters/CanvasAdapter.html` |
| WebDOMAdapter | pronta in `src/adapters/WebDOMAdapter.html` |
| CSSAdapter | pronta in `src/adapters/CSSAdapter.html` |
| altri moduli (Core, Ant, Spider, Python) | non scritti |

## Licenza

MIT — Antonio Prosperi