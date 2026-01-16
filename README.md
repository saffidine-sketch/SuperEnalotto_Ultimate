# 🎱 SuperEnalotto Ultimate Analyzer

![Version](https://img.shields.io/badge/version-5.0_Dynamic-blueviolet)
![Status](https://img.shields.io/badge/status-active-success)
![Technology](https://img.shields.io/badge/tech-HTML5%20%7C%20JS%20Vanilla-yellow)

**SuperEnalotto Ultimate** è una suite avanzata per l'analisi statistica, il monitoraggio e la previsione delle estrazioni del SuperEnalotto. Progettato con un'interfaccia "Cyberpunk" moderna, offre strumenti professionali per giocatori esperti e appassionati di statistica.

## ✨ Caratteristiche Principali

*   **⚡ Analisi Dinamica in Tempo Reale**: Algoritmi che pesano frequenza storica, ritardi attuali e "recenza" (trend delle ultime 10 estrazioni).
*   **🎯 Generatore di Sistemi Ridotti**: Crea sistemi matematicamente validati (Garanzia 3, 4 o 5) per ottimizzare il budget.
*   **🧬 Super Sistema**: Modalità avanzata che combina diverse strategie (Union, Intersection) per una copertura massima.
*   **📊 Strategie Multiple**:
    *   ⚖️ **Bilanciata**: Equilibrio tra frequenti e ritardatari.
    *   🔥 **Hot Numbers**: Focus sui numeri più "caldi" del momento.
    *   ❄️ **Cold Numbers**: Caccia ai massimi ritardatari.
    *   🔄 **Contrarian**: Strategia anti-folla.
*   **💻 Zero Dipendenze**: Funziona interamente nel browser. Nessun server, nessuna installazione complessa.

## 🚀 Come Iniziare

### Prerequisiti
Tutto ciò che ti serve è un browser web moderno (Chrome, Edge, Firefox, Safari).

### Installazione e Utilizzo

1.  **Clona il repository** (o scarica lo ZIP):
    ```bash
    git clone https://github.com/saffidine-sketch/SuperEnalotto_Ultimate.git
    ```
2.  **Avvia l'Analizzatore**:
    Fai doppio click sul file:
    `ANALYZER_PRO_v5.0_DYNAMIC.html`
3.  **Carica i Dati**:
    *   Nell'interfaccia, clicca su `[ CARICA_ARCHIVIO ]`.
    *   Seleziona il file `Archivio_Master.txt` presente nella cartella scaricata.
    *   *Opzionale*: Puoi inserire manualmente nuove estrazioni nel pannello "Aggiornamento Live".

## 📂 Struttura del Progetto

*   `ANALYZER_PRO_v5.0_DYNAMIC.html`: **IL CORE**. L'applicazione principale (v5.0).
*   `Archivio_Master.txt`: Database storico completo delle estrazioni (formato: `n1,n2,n3,n4,n5,n6|SS:ss`).
*   `Archivio_2025.txt`: Archivio specifico per l'anno corrente, per inserimenti rapidi.
*   `data.js`: Libreria dati per uso demo/sviluppo.
*   `SuperEnalotto Analyzer PRO.html`: Versione precedente (v4.0/Legacy).

## 🛠 Tecnologie

Il progetto è costruito puramente in **Vanilla JavaScript**, **HTML5** e **CSS3**.
*   Nessun framework esterno (React/Vue/Angular) per garantire la massima velocità e portabilità.
*   Design responsivo adatto a Desktop e Tablet.

## 🤝 Contribuire

Le estrazioni vengono aggiornate manualmente nei file di testo.
1.  Apri `Archivio_2025.txt`.
2.  Aggiungi la nuova estrazione in cima al file nel formato: `01,02,03,04,05,06|SS: 90`.
3.  Salva e ricarica l'applicazione.

---
*Progetto sviluppato per scopi statistici e di studio. Il gioco è vietato ai minori e può causare dipendenza patologica.*
