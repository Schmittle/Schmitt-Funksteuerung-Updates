# Schmitt-Funksteuerung – Firmware-Updates

Öffentliches Update-Repository für die ESP32-Funksteuerung von Schmitt Metallbau.

**Quellcode und Konfigurationen bleiben im privaten Repository.** Hier werden ausschließlich veröffentlichte, für die jeweilige Hardware kompilierte Firmwaredateien und die dazugehörigen Versionsinformationen bereitgestellt.

## Struktur

- `empfaenger/manifest.json` – aktuell freigegebene Empfänger-Firmware
- `handsender/manifest.json` – aktuell freigegebene Handsender-Firmware
- `firmware/` – zukünftig geprüfte, kompilierte BIN-Dateien

## Status

Aktuell ist **keine Firmware zur Online-Installation freigegeben**. Die Platzhalter-Manifeste enthalten `available: false`. Ein ESP32 darf daraus kein Update installieren.

## Sicherheit

Firmware muss vor der Veröffentlichung auf der passenden ESP32-Hardware getestet werden. Die spätere Update-Funktion soll Versions-, Geräte-, Integritäts- und Berechtigungsprüfungen durchführen. Öffentliche Firmware-BIN-Dateien enthalten keine Geheimnisse, Passwörter oder GitHub-Tokens.
