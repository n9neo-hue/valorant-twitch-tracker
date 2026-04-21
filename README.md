# valorant-twitch-tracker
Twitch Overlay for tracking Valorant stats and match data
# 🎮 Valorant Rank & Match Widget (Overlay / Stream UI)

Ein modernes, animiertes Valorant-Overlay Widget zur Anzeige von:
- Aktuellem Rank + RR
- Lifetime Peak Rank
- W/L Statistik des Tages
- Match History (Visual Dots)
- Live API Sync

Design im futuristischen "N9NE / esports HUD" Style.

---

## 🚀 Features

- 🔴 Live Rank Tracking
- 📊 RR Progress Bar + Change Indicator
- 🏆 Lifetime Peak Rank Tracking
- ⚔️ Daily Win/Loss Tracker
- ⚡ Auto Refresh (alle 5 Minuten)
- 🎨 Modern Animated UI (Glitch / Neon Style)

---

## 🔧 Installation

1. Lade die HTML-Datei herunter
2. Passe die Konfiguration im Script an (siehe unten)
3. Öffne  OBS (Browser Source) und füge es als Broswer Quelle in OBS hinzu.
4. Fertig ✅

---

## ⚙️ Setup (WICHTIG)

Du musst **eigene API Daten eintragen**, sonst funktioniert das Widget nicht.

### 🔑 1. API Key erstellen
Erstelle deinen Key hier:
👉 https://api.henrikdev.xyz/dashboard/

---

### 🧾 2. Konfiguration im Code

Öffne den `<script>` Bereich und passe diese Werte an:

```js
const API_KEY = 'YOUR API KEY -> https://api.henrikdev.xyz/dashboard/ U CAN CREATE IT HERE';
const NAME    = 'INGAME NAME';
const TAG     = '#XXXX';
const REGION  = 'eu'; // mögliche Werte: eu, na usw.
