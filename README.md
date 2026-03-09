# 🏛️ Calcolatore Tassa Archivio Notarile (PWA)

Un'applicazione web leggera e veloce (Progressive Web App) progettata per il calcolo immediato della **Tassa Archivio** e degli oneri repertoriali per atti pubblici e scritture private. 

Ottimizzata per l'uso da mobile (iOS/Android), permette di ottenere stime precise basate sulle tabelle ministeriali vigenti.

## 🚀 Funzionalità principali

- **Calcolo Dinamico:** Basato sul valore dell'atto e sulla tipologia (Atto Pubblico vs Scrittura Privata).
- **Fattispecie Predefinite:** Supporto automatico per le percentuali di legge:
  - **70%**: Compravendita tra privati (Prezzo-Valore).
  - **50%**: Mutui Fondiari, Edilizia Convenzionata (PEEP), Divisioni.
  - **100%**: Atti standard (Donazioni, Compravendite da impresa, ecc.).
- **Focus Trasparenza:** Visualizzazione immediata dell'onorario di riferimento (in rosso) e avvisi specifici per l'inserimento del valore ipotecario nei mutui.
- **Override Manuale:** Possibilità di modificare manualmente la tassa calcolata e aggiungere note giustificative.
- **PWA Ready:** Installabile sulla home del telefono come una vera app.

## 🛠️ Tecnologie utilizzate

- **HTML5 / CSS3:** Layout responsive ottimizzato per Safari (iOS).
- **JavaScript (Vanilla):** Motore di calcolo logico basato su scaglioni estratti da database CSV.
- **Vercel:** Hosting e distribuzione continua.
- **PWA Manifest:** Per l'integrazione nativa su smartphone.

## 📱 Installazione su Smartphone

1. Visita l'URL del progetto su [Inserisci-Tuo-Link-Vercel.app]
2. Su **iPhone**: Tocca il tasto **Condividi** (quadrato con freccia) e seleziona **"Aggiungi alla schermata Home"**.
3. Su **Android**: Tocca i tre puntini in alto a destra e seleziona **"Installa applicazione"**.

## 📊 Struttura dei Dati

Il motore di calcolo utilizza scaglioni di valore aggiornati:
- Fino a € 37.000
- Da € 37.000 a € 55.800
- ...e così via fino agli scaglioni massimi.

L'algoritmo applica automaticamente la riduzione del **5% circa** per le scritture private rispetto agli atti pubblici, come previsto dalle tabelle ministeriali.

---
*Progetto sviluppato per consultazione rapida e professionale.*
