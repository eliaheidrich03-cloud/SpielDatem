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
- Beim Abpfiff wird eine JSON-Datei mit allen Markern heruntergeladen
  (Dateiname frei wählbar).
- Kamera-Verbindung per Bluetooth zeigt aktuell den Verbindungsstatus.
  Fernsteuerung der Aufnahme (Start/Stopp aus der App) ist als Ausbaustufe geplant
  und benötigt das genaue Kameramodell.
- Web-Bluetooth funktioniert auf Android mit Chrome. Auf iPhone/Safari nicht.
