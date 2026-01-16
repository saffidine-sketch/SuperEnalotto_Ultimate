# Progetto KARIM - SuperEnalotto Ultimate

## 🔭 Panoramica
Questo progetto ospita una suite avanzata per l'analisi statistica, il monitoraggio e la previsione delle estrazioni del SuperEnalotto. Il core del sistema è un'applicazione web client-side (v5.0) che elabora dati storici per generare sistemi ridotti e strategie di gioco ottimizzate.

## 📂 Struttura del File System

### Applicazioni Principali
*   **`ANALYZER_PRO_v5.0_DYNAMIC.html`**: L'ultima versione stabile dell'analizzatore.
    *   **Caratteristiche**: Interfaccia "Cyberpunk", analisi in tempo reale, peso dinamico (frequenza/ritardo/recenza), generatore di sistemi ridotti (G3, G4, G5) e Super Sistema (Union/Intersection).
    *   **Tecnologia**: HTML5, CSS3, Vanilla JS (nessun framework esterno).
*   **`SuperEnalotto Analyzer PRO.html`**: Versione precedente dell'analizzatore.

### Dati e Archivi
*   **`Archivio_Master.txt`**: Il database principale contenente lo storico completo delle estrazioni.
    *   *Formato*: `num1,num2,num3,num4,num5,num6|SS: superstar`
*   **`Archivio_2025.txt`**: Archivio dedicato alle estrazioni dell'anno corrente. **File target prioritario per i nuovi inserimenti.**
*   **`data.js`**: Contiene la variabile `DEMO_ARCHIVE` con i dati storici formattati per l'uso diretto o demo.

## 🤖 Istruzioni Operative per Gemini

### 1. Gestione Nuove Estrazioni
Quando l'utente comunica una nuova estrazione (Sestina + SuperStar):
1.  **Salvataggio**: Aggiungere immediatamente la nuova riga in **`Archivio_2025.txt`** rispettando il formato esistente.
2.  **Aggiornamento**: Se richiesto, aggiornare anche `Archivio_Master.txt`.
3.  **Feedback**: Confermare l'avvenuto salvataggio e procedere con l'analisi previsionale se richiesta.

### 2. Generazione Previsioni
Nel fornire pronostici, simulare la logica interna di `ANALYZER_PRO_v5.0`:
*   **Analisi**: Considerare frequenza globale, ritardi attuali e "peso recente" (trend delle ultime 10 estrazioni).
*   **Strategie**:
    *   *Bilanciata*: Mix di frequenti e ritardatari.
    *   *Hot*: Numeri con frequenza elevata nel breve periodo.
    *   *Cold*: I massimi ritardatari.

## 🚀 Utilizzo Standalone
Per utilizzare il software senza l'assistente:
1.  Aprire il file `ANALYZER_PRO_v5.0_DYNAMIC.html` con un browser (Chrome, Edge, Firefox).
2.  Caricare i dati:
    *   Cliccare su `[ CARICA_ARCHIVIO ]` e selezionare `Archivio_Master.txt`.
    *   Oppure incollare manualmente i dati nell'area di testo.
3.  Utilizzare i pannelli per generare sistemi o analizzare statistiche.

## 🛠 Convenzioni di Sviluppo
*   **Lingua**: Tutto il codice, i commenti e l'interfaccia devono essere rigorosamente in **Italiano**.
*   **Stile Code**: JavaScript Vanilla moderno (ES6+), codice leggibile e ben commentato.
*   **UI/UX**: Tema scuro, contrasto elevato (colori neon: verde, viola, arancio), font monospazio.
