# Fairground Online – MP Peeps (`FairgroundMPPeeps.dll`)

Eine **BepInEx 6 (IL2CPP)** Mod für **Fairground Online**, die während der Fahrt automatisch dynamische und zufällige Besucher-Reaktionen (Hände hoch, Klatschen, Schreien) auslöst.

> **Kompatibilität:** Aktualisiert für **Fairground Online v1.1.3**.

---

## Features
- **Automatische Besucher-Reaktionen während der Fahrt** (keine Hotkeys oder manuelle Eingaben nötig)
- **Geschwindigkeits- & Kick-Erkennung:** Reagiert auf die aktuelle Fahrgeschwindigkeit und plötzliche Beschleunigungs-Kicks (65 % Chance auf sofortige *Hände hoch / Schrei*-Reaktion)
- **Dynamische Aktionen:** `Hands_Up` (Hände hoch), `Clap` (Klatschen) & `Scream` (Schreien mit Audio)
- **Automatisches Zurücksetzen:** Stoppt die Animationen sauber, sobald das Fahrgeschäft anhält
- **Unterstützte Fahrgeschäfte:** Break Dance, Booster, AirWolf, Pinball *(sowie weitere über `Peep_Interaction_Controller`)*

---

## Installation
1. Stelle sicher, dass **BepInEx 6 (Unity IL2CPP)** für *Fairground Online* installiert ist (z. B. über [Fairground-Online-BepInEx](https://github.com/BlackMautz/Fairground-Online-BepInEx)).
2. Kopiere die Datei `BepInEx/plugins/FairgroundMPPeeps.dll` in deinen Spielordner unter:
   ```text
   Fairground Online\BepInEx\plugins\FairgroundMPPeeps.dll
   ```
3. Spiel starten – die Mod ist sofort aktiv.
