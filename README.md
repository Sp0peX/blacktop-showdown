# Blacktop Showdown

Basket da strada 2 contro 2 in 3D, dentro il browser. Nessuna installazione,
nessuna dipendenza esterna: tutto il gioco sta in un unico file HTML.

**Gioca: <https://sp0pex.github.io/blacktop-showdown/>**

## Regole del campetto

Si gioca a 21. Canestro da dentro l'arco **1 punto**, da fuori **2**.
Chi subisce canestro riparte con la palla e deve **liberarla** oltre l'arco
prima di poter attaccare. 20 secondi per concludere l'azione.

Il misuratore di **stile** si riempie con canestri, schiacciate, crossover
riusciti, stoppate e palle rubate. A barra piena parte lo **Showdown**:
tempo rallentato, canestro che vale doppio e un punto tolto agli avversari.

## Comandi

**Da tastiera** — `WASD` muoviti · `Shift` sprint · `Spazio` tieni premuto per
caricare il tiro, in corsa sotto canestro parte la schiacciata · `E` passa ·
`Q` trick in attacco, ruba in difesa · `F` Showdown · `Esc` pausa

**Da telefono** — stick fluttuante a sinistra (spingi a fondo per sprintare),
tasti a destra. Il tiro si carica nell'anello attorno al tasto TIRA: rilascia
quando entra nel verde.

Il gioco riconosce da solo con cosa stai giocando e cambia i comandi quando
passi dal touch alla tastiera.

## Dettagli tecnici

- **Three.js r128** incorporato nel file (licenza MIT)
- Font Bungee e Barlow incorporati come woff2 in base64 (licenza SIL OFL)
- **Zero richieste di rete** a runtime: funziona anche offline, aperto dal disco
- Tre livelli di qualita grafica scelti in base al dispositivo, con riduzione
  automatica del carico se il frame rate scende
- Texture di campo, murale e pallone generate proceduralmente su canvas
- Personaggi animati proceduralmente: corsa, palleggio, tiro, schiacciata,
  posizione difensiva

## Licenza

Codice del gioco: usalo come vuoi.
Three.js e i font restano soggetti alle rispettive licenze (MIT e SIL OFL).
