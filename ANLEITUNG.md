# Anleitung für Spielerinnen und Spieler

## Windows
1. Auf der Seite [Releases](https://github.com/SliverTW/ANDROMEDA-DEMO/releases) bei der gewünschten Version unter **Assets** die Datei `ANDROMEDA-Demo-Windows.zip` anklicken.
2. Die ZIP-Datei entpacken (Rechtsklick → „Alle extrahieren…“), z. B. auf den Desktop.
3. `ANDROMEDA.exe` im entpackten Ordner starten.
4. SmartScreen-Hinweis: „Weitere Informationen“ → „Trotzdem ausführen“.

**Voraussetzungen:** Windows 10 oder 11 (64 Bit), Grafik mit OpenGL 3.3 (fast jeder PC/Laptop der letzten zehn Jahre), ca. 300 MB freier Speicher.

**Steuerung:** Tastatur und Maus; die Belegung steht im Spiel in den Einstellungen. Gamepads werden unterstützt, wurden aber noch nicht mit einem echten Controller getestet.

**Spielstände** liegen unter `%APPDATA%\ANDROMEDA_Fable_Demo` (in die Adresszeile des Explorers eingeben). Zum Zurücksetzen den Ordner löschen.

**Prüfsumme (optional):** In PowerShell `Get-FileHash .\ANDROMEDA-Demo-Windows.zip` – das Ergebnis muss mit der SHA-256-Angabe in der Release-Beschreibung übereinstimmen.

## Neue Version installieren
Neue Version in einen eigenen Ordner entpacken. Spielstände bleiben erhalten, ob sie zu einer neuen Version passen, ist in einer frühen Demo aber nicht garantiert.

## Probleme melden
Am einfachsten direkt an SliverTW (z. B. per Nachricht). Hilfreich: Windows-Version, Grafikkarte, was passiert ist, wenn möglich ein Bildschirmfoto.
