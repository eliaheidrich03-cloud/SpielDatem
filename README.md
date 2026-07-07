# Spieltag Marker

Web-App zum Setzen von Zeitmarkern (Tor, Gegentor, Chance, Foul …) mit Kommentaren am Spielfeldrand — synchron zur laufenden Kameraaufnahme (z. B. DJI Osmo). Läuft als installierbare App (PWA) auf dem Handy.

## Auf GitHub veröffentlichen (einmalig, ~5 Minuten)

1. Auf github.com einloggen → oben rechts **+** → **New repository**
2. Name z. B. `spieltag-marker`, **Public**, dann **Create repository**
3. **uploading an existing file** anklicken und **alle Dateien aus diesem Ordner** hochladen
   (index.html, manifest.webmanifest, sw.js und den Ordner icons mit beiden Bildern)
4. **Commit changes**
5. Im Repository: **Settings → Pages** → unter *Branch* `main` und `/ (root)` wählen → **Save**
6. Nach 1–2 Minuten ist die App erreichbar unter:
   `https://DEIN-BENUTZERNAME.github.io/spieltag-marker/`

## Als App aufs Handy

1. Die URL auf dem Handy in **Chrome (Android)** öffnen
2. Menü (⋮) → **Zum Startbildschirm hinzufügen** / **App installieren**
3. Die App liegt dann wie eine normale App auf dem Homescreen und funktioniert
   nach dem ersten Öffnen auch ohne Internet (wichtig am Sportplatz!)

## Hinweise

- Marker werden automatisch auf dem Gerät gespeichert — auch wenn die App
  zwischendurch geschlossen wird, geht während des Spiels nichts verloren.
- Beim Abpfiff werden zwei .txt-Dateien nacheinander heruntergeladen:
  eine fürs Video-Analyzer-Programm, eine ausführliche mit Kommentaren.
- **Kamera-Aufnahme per Bluetooth starten/stoppen (experimentell):**
  Nach dem Verbinden erscheint ein "Aufnahme starten"-Button. Nutzt das
  offizielle DJI-R-SDK-Protokoll, gültig für die ganze Osmo-Action-Reihe.
  Da dies ohne Testgerät entwickelt wurde, kann es Anpassung brauchen —
  der "Protokoll"-Button zeigt ein Diagnose-Fenster mit den gesendeten/
  empfangenen Bluetooth-Daten.
- **Wichtig für iPhone:** Safari unterstützt kein Web-Bluetooth. Für die
  Kamera-Funktionen die kostenlose App **"Bluefy – Web BLE Browser"**
  aus dem App Store nutzen und die GitHub-Pages-URL darin öffnen.
  Android mit Chrome funktioniert direkt.
- Vor dem Verbinden die DJI-Mimo-App auf dem Handy schließen, damit sie
  nicht gleichzeitig eine eigene Bluetooth-Verbindung zur Kamera hält.
- Web-Bluetooth funktioniert auf Android mit Chrome. Auf iPhone/Safari nicht.
