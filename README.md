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
- Method sort(()=> Math.random() -0.5) ➤ Utilizzato per randomizzare l’ordine delle domande e mischiare dinamicamente le risposte del quiz
- Property innerHTML ➤ Impiegata per aggiornare e gestire i contenuti mostrati nelle diverse schermate dell’applicazione
- Method querySelector & querySelectorAll ➤ Utilizzati per selezionare e manipolare gli elementi del DOM, collegando struttura, stile e logica del progetto
- Method classList.add ➤ Per poter modificare stilisticamente determinati oggetti
- Method map(...).join("")  ➤ Sfruttato per generare dinamicamente elementi HTML a partire dagli array, creando automaticamente i pulsanti delle risposte
- Method forEach  ➤ Utilizzato per aggiornare in tempo reale il punteggio e gestire la visualizzazione del risultato finale          
- Function setTimeout  ➤ Impiegata per controllare il delay tra l’azione dell’utente e il caricamento della schermata successiva
- Function setInterval & clearInterval  ➤ Utilizzate per creare, aggiornare e interrompere il timer automatico delle domande
---

## Possibili Migliorie
Per futuri cicli di sviluppo, sono state identificate le seguenti ottimizzazioni:






