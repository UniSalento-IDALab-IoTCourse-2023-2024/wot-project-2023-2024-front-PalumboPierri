# Per vedere la Web Page [Progetto WoT - Palumbo & Pierri](https://unisalento-idalab-iotcourse-2023-2024.github.io/wot-project-presentation-PalumboPierri/)

# Progetto di Analisi Audio e Visualizzazione Dati con Tailwind CSS e Chart.js

## Descrizione

Questo progetto è una web application che permette di caricare un file audio, analizzare il suo livello di decibel e visualizzare lo spettro di frequenza in tempo reale utilizzando **Chart.js**. Inoltre, offre la possibilità di visualizzare i dati sotto forma di grafici a torta e istogrammi.

Il progetto utilizza **Tailwind CSS** per lo stile e un backend per l'esecuzione di analisi audio avanzate tramite **Python**.

## Funzionalità

- Caricamento di file audio e calcolo del livello di decibel.
- Visualizzazione dello spettro di frequenza in tempo reale.
- Monitoraggio del rumore con avvisi sui livelli di suono potenzialmente pericolosi (>85 dB).
- Grafici a torta e istogrammi per visualizzare statistiche relative agli eventi.
- Integrazione con backend Python per eseguire analisi aggiuntive.

## Struttura del Progetto

Il progetto è composto da tre pagine principali:

1. **Home /**
    - viene utilizzato per visualizzare il risultato della notifica intelligente e i grafici a riguardo

2. **Dashboard /dashboard**
    - Visualizza grafici a torta e istogrammi per monitorare categorie.
    - Permette di eseguire un'analisi audio.

3. **Analisi del Suono /analizzaaudio**
    - Carica e analizza un file audio per calcolarne il livello di decibel.
    - Mostra il grafico dello spettro di frequenza in tempo reale.

### File HTML

- **analizza_audio.html**: Pagina principale per l'analisi dell'audio. Consente il caricamento del file audio, mostra il livello di rumore in decibel e il grafico dello spettro delle frequenze.

- **dashboard.html**: Pagina che contiene grafici a torta e istogrammi, utilizzati per visualizzare i dati degli eventi. È presente un pulsante che esegue un'analisi audio utilizzando Python sul backend.

- **grafici.html**: Pagina di esempio che mostra l'uso di grafici creati con **Chart.js**. Include un grafico a torta e un istogramma per rappresentare dati fittizi.

## Tecnologie Utilizzate

- **HTML5**: Struttura di base del progetto.
- **Tailwind CSS**: Utilizzato per una rapida e flessibile gestione degli stili.
- **Chart.js**: Libreria per creare grafici dinamici.
- **JavaScript**: Usato per la logica dell'applicazione e la gestione del caricamento e analisi audio.
- **Python (Backend)**: Per eseguire analisi audio avanzate (non visibile dal frontend).
- **FileReader API**: Usato per caricare e leggere i file audio nel browser.
- **Web Audio API**: Per l'analisi dell'audio (calcolo RMS, decibel e spettro delle frequenze).

## Come Eseguire il Progetto

1. **Installazione delle dipendenze**  
   Assicurati di aver installato tutte le dipendenze necessarie per eseguire il progetto, incluse le librerie **Chart.js** e **Tailwind CSS**.


