# Smart Parking — Firebase izdanje

Jednostavna web kontrolna tabla za postojeći ESP32 parking projekat. Stranica prikazuje stanje mesta, rampu, trajanje parkiranja, trenutnu cenu, vreme dolaska i poslednji račun. Automobil i rampa imaju CSS animacije.

## 1. Šta se nalazi u projektu

- `public/index.html` — web aplikacija za Firebase Hosting.
- `firebase.json` — Firebase Hosting i Realtime Database konfiguracija.
- `database.rules.json` — pravila pristupa bazi.
- `esp32/smart_parking_firebase.ino` — Arduino kod za WEMOS LOLIN32 / ESP32 sa Wi-Fi i Firebase slanjem podataka.

