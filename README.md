# 🚀 EPIQUIZ - Build Week 1
Benvenuto nel repository di **EPIQUIZ**, un'applicazione web interattiva per quiz a risposta multipla sul mondo dell'informatica. Il progetto è stato sviluppato come Single Page Application (SPA) incentrata sulla manipolazione dinamica del DOM e sulla gestione avanzata del tempo tramite JavaScript Vanilla.

---
## Indice dei Contenuti
1. [🎯 Obiettivi del Progetto](#obiettivi-del-progetto)
2. [💻 Tecnologie Utilizzate](#tecnologie-utilizzate)
3. [📂 Struttura del Progetto](#struttura-del-progetto)
4. [🔧 Architettura del Codice (State-Render-Events)](#architettura-del-codice-state-render-events)
5. [⚙️ Funzioni Principali](#funzioni-principali)
6. [💡 Funzionalità nel Dettaglio](#funzionalita-nel-dettaglio)
7. [🚀 Possibili Migliorie](#possibili-migliorie)
---
## Obiettivi del Progetto
L'obiettivo principale di questa Build Week è stato simulare un ambiente di lavoro reale in team, focalizzandoci su:
- **Manipolazione avanzata del DOM** senza l'ausilio di framework esterni.
- **Gestione dello stato globale** dell'applicazione in JavaScript.
- Controllo dei flussi temporali asincroni (`setInterval` e `setTimeout`).
- Integrazione di librerie esterne tramite CDN (Chart.js per i grafici dei risultati).
- Scrittura di codice moderno, modulare e pulito seguendo gli standard **ES6**.
---
## Tecnologie Utilizzate
L'applicazione è stata sviluppata utilizzando un parco tecnologie snello e performante:
<!-- eventualmente aggiungere badge, screenshot e quant'altro -->
- 🌐 **HTML** → Per definire la struttura della singola pagina
- 🎨 **CSS**  → Per controllare la parte stilistica del progetto
- ⚡ **JavaScript** → Per creare contenuti dinamici e manipolare i singoli eventi

---

## Struttura del Progetto
Il progetto è strutturato come una **Single Page Application (SPA)**. Il file HTML rimane fisso, mentre JavaScript si occupa di svuotare e ripopolare il tag `<main id="app">` in base alla schermata corrente.
```text
├── index.html                  # File HTML principale (Entry-point unico)
├── assets/
│   ├── css/
│   │   └── style.css           # Fogli di stile, layout e animazioni custom
│   ├── js/
│   │   └── script.js           # Stato globale, database domande e logica del quiz
│   ├── img/
│   │   ├── epicode-logo.png    # Logo istituzionale nell'header
│   │   └── bg.jpg              # Immagine di sfondo dell'applicazione
```

---

## Architettura del Codice (State-Render-Events)
L'applicazione segue il pattern architetturale **State ➡️ Render ➡️ Events**, garantendo una separazione netta tra i dati e l'interfaccia visiva:
-
-
-
-
-

---

## Funzioni Principali
Il comportamento e l'interattività dell'applicazione sono governati dalle seguenti funzioni JavaScript
-
-
-
-
-

---

## Funzionalità nel Dettaglio
L'applicazione integra accorgimenti specifici per ottimizzare l'esperienza utente ed evitare i bug tipici del DOM:
- Method sort(()=> Math.random() -0.5) ➤ Individuare un'array iniziale, generarne uno con diverso ordine delle domande e, in seguito, mischiare le risposte 
- Property innerHTML ➤ Gestire il contenuto delle singole pagine mostrate a schermo
- Method querySelector & querySelectorAll ➤ Collegare i tre linguaggi utilizzati e gestirne le funzionalità
- Method classList.add ➤ Per poter modificare stilisticamente determinati oggetti
- Method map(...).join("")  ➤ Trasformare le stringhe di un array in button e restituirgli il parametro stringa
- Method forEach  ➤ Aggiornare dinamicamente lo score del punteggio e mostrare alla fine il risultato ottenuto          
- Function setTimeout  ➤ Controllare il delay prima di mostrare la pagina successiva dopo il click dell'utente
- Function setInterval & clearInterval  ➤ Creare e rendere autonomo il timer delle domande
---

## Possibili Migliorie
Per futuri cicli di sviluppo, sono state identificate le seguenti ottimizzazioni:






