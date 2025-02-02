# Orbital-satellites-analysis
## 🌍 Lingua del progetto
Questo progetto è scritto interamente in **italiano**. Tutta la documentazione, le analisi e i commenti nel codice sono in lingua italiana.

# Analisi dei Satelliti Orbitali

## Introduzione
Questo progetto nasce dall'obiettivo di analizzare i satelliti orbitali per identificare le principali tendenze e comprendere come questi siano distribuiti per anno di lancio, tipologia di orbita e classificazione. Utilizzando un dataset pubblico che contiene informazioni su satelliti non classificati, è stato possibile esplorare e visualizzare dati importanti sul panorama attuale e passato dei lanci satellitari.

## Obiettivi
Gli obiettivi principali dell'analisi sono:
- Comprendere il trend storico del numero di satelliti lanciati ogni anno.
- Analizzare la distribuzione dei satelliti per tipologia di orbita (LEO, GEO, MEO, ecc.).
- Valutare eventuali limitazioni dei dati, come l'assenza di satelliti classificati.

## Dataset
Il dataset utilizzato è stato scaricato dal portale **CelesTrak**, che fornisce informazioni aggiornate sui satelliti orbitali. I dati includono dettagli come il nome del satellite, il tipo di orbita, il movimento orbitale e l'anno di lancio. È importante notare che il dataset contiene esclusivamente satelliti non classificati, rendendolo ideale per scopi analitici e divulgativi.

### Principali Campi del Dataset
- **OBJECT_NAME**: Nome del satellite.
- **OBJECT_ID**: Identificativo unico del satellite, che include l'anno di lancio.
- **ORBIT_TYPE**: Tipo di orbita (LEO, GEO, MEO, ecc.).
- **CLASSIFICATION_TYPE**: Classificazione del satellite (tutti i satelliti in questo dataset sono "Unclassified").
- **MEAN_MOTION**: Velocità media del satellite in orbita.

## Risultati Principali
### Crescita Esponenziale dei Lanci
L'analisi ha evidenziato un significativo aumento nel numero di satelliti lanciati annualmente, con una crescita esponenziale dopo il 2019. Questo trend è strettamente legato all'espansione delle costellazioni satellitari commerciali, come quelle utilizzate per la connettività globale (es. Starlink).

### Dominanza delle Orbite LEO
La maggior parte dei satelliti (oltre il 90%) è posizionata in orbita LEO (Low Earth Orbit), grazie ai costi di lancio ridotti, ai tempi di comunicazione più rapidi e alle applicazioni versatili, come osservazione della Terra e connessione internet. Le orbite GEO e MEO, invece, sono utilizzate principalmente per scopi specifici come navigazione e trasmissione televisiva.

### Classificazione
Il dataset include esclusivamente satelliti non classificati, rendendo i dati trasparenti e accessibili, ma escludendo informazioni relative a satelliti militari e governativi. Questo aspetto, pur limitando l'analisi, garantisce una base dati chiara e affidabile per usi commerciali o accademici.

## Processo di Analisi
1. **Esplorazione dei Dati**:
   - Controllo di eventuali valori nulli o duplicati.
   - Creazione di colonne aggiuntive, come quella per l'estrazione dell'anno di lancio.
   
2. **Analisi delle Orbite**:
   - Valutazione della distribuzione per tipologia di orbita.
   - Approfondimento della categoria "Altro" per identificare eventuali casi particolari.

3. **Visualizzazioni**:
   - Grafici a barre e a torta per rappresentare la distribuzione dei satelliti per orbita e classificazione.
   - Analisi del trend temporale con visualizzazioni annuali.

## Limitazioni
- **Assenza di Satelliti Classificati**: L'analisi non include informazioni su satelliti militari o governativi, riducendo la comprensione globale del settore.
- **Categorie Incomplete**: La categoria "Altro" non ha dettagli sufficienti per una valutazione approfondita.
- **Dataset Statico**: I dati riflettono uno snapshot aggiornato, ma non in tempo reale.

## Considerazioni Finali
L'analisi dei satelliti orbitali offre uno sguardo interessante sulle dinamiche del settore spaziale, mettendo in evidenza l'importanza delle costellazioni satellitari in orbita LEO e il ruolo sempre più rilevante delle aziende private. Tuttavia, l'assenza di dati classificati limita la possibilità di comprendere appieno il panorama globale. Progetti futuri potrebbero includere l'integrazione di ulteriori dataset o l'analisi di applicazioni specifiche, come il monitoraggio ambientale o la connettività.

## Come Utilizzare il Progetto
1. **Clona il repository**:
   ```bash
   git clone https://github.com/tuo-username/analisi-satelliti-orbitali.git
