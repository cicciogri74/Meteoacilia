# 🌤️ Stazione Meteo - IROME8355

Dashboard meteo in tempo reale con supporto per:

- ✅ Dati in tempo reale (temperatura, umidità, vento)
- ✅ Previsioni meteo (3 giorni)
- ✅ Direzione e velocità del vento
- ✅ Qualità dell'aria (AQI)
- ✅ Radar meteo interattivo (Windy)
- ✅ Grafico della temperatura (ultime 24h)
- ✅ Mappa interattiva con marker (Leaflet)
- ✅ Layout responsive per smartphone e tablet

---

## 🔧 Requisiti

- Un browser moderno (Chrome, Firefox, Safari, Edge)
- Connessione a Internet
- API key Weather Underground attiva

---

## 🚀 Come usare

1. **Clona o scarica** questo repository
2. Apri il file `index.html` nel tuo browser
3. Verifica che i dati siano visibili entro qualche secondo

---

## 🛠️ Configurazione

Nel file HTML puoi personalizzare:

```js
const API_KEY = "YOUR_API_KEY";
const STATION_ID = "IROME8355";
const lat = 41.9;
const lon = 12.5;

