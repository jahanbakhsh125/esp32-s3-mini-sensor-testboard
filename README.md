# ESP32-S3 MINI Sensor Testboard

KiCad-Schaltplanentwurf für ein Testboard mit ESP32-S3-MINI-1-Modul,
USB-C-Anschluss und HDC2080-Temperatur-/Feuchtesensor.

## Geplante Funktionsgruppen im Schaltplan

- ESP32-S3-MINI-1-Modul mit Reset- und Boot-Beschaltung.
- USB-C-Schnittstelle mit USB-Datenleitungen und Schutzbeschaltung.
- 3,3-V-Spannungsversorgung mit LM1117LD-3.3.
- HDC2080-Sensor mit I2C-Signalen.
- RGB-LED, Benutzer-Taster und herausgeführte Schnittstellensignale.

## Projekt öffnen

Die Datei [esp32-s3-mini-sensor-testboard.kicad_pro](esp32-s3-mini-sensor-testboard.kicad_pro)
mit KiCad öffnen. Die bereitgestellten Quelldateien stammen aus KiCad 10.0.

| Datei | Inhalt |
|---|---|
| `esp32-s3-mini-sensor-testboard.kicad_pro` | Projekteinstellungen |
| `esp32-s3-mini-sensor-testboard.kicad_sch` | Schaltplanentwurf |
| `esp32-s3-mini-sensor-testboard.kicad_pcb` | Noch leere Platinenlayout-Datei |

## Entwicklungsstand

Das Projekt dokumentiert den aktuellen Schaltplanentwurf. Das Platinenlayout
ist noch nicht ausgearbeitet. Es sind keine Gerber-Dateien, Bohrdaten oder
Firmware enthalten. Ein erfolgreich aufgebautes und getestetes Board wird
mit dieser Veröffentlichung nicht nachgewiesen.

Für die Weiterentwicklung sind insbesondere Schaltplanprüfung, vollständige
Footprint-Zuordnung, Platinenlayout, elektrische Regelprüfungen und praktische
Tests erforderlich.

## Bereinigung für die Veröffentlichung

Persönliche Angaben im Zeichnungskopf wurden entfernt. Lokale
Benutzereinstellungen, Wiederherstellungssicherungen und die alte KiCad-/Git-Historie
sind nicht enthalten. Projektdateien und interne Projektverweise wurden auf
den neuen Namen angepasst; elektrische Verbindungen und Bauteilwerte blieben erhalten.
