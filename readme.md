# xBackup

![Status](https://img.shields.io/badge/status-active-success)
![Platform](https://img.shields.io/badge/platform-macOS-black)
![Architecture](https://img.shields.io/badge/architecture-Apple%20Silicon-blue)
![Intel](https://img.shields.io/badge/Intel-not%20supported-red)
![Device](https://img.shields.io/badge/device-iPhone-informational)

**xBackup** ist eine macOS-Anwendung für Apple-Silicon-Macs, die sich mit einem iPhone verbinden kann, Geräteinformationen ausliest, diese übersichtlich anzeigt und Backup- sowie DFU-Funktionen bereitstellt.

Diese README richtet sich an Kunden und Endanwender der App.

---

## Überblick

xBackup wurde entwickelt, um iPhone-Geräte unter macOS einfach und übersichtlich zu verwalten.

Die App kann ein verbundenes iPhone erkennen, wichtige Geräteinformationen anzeigen und ausgewählte Wartungs-, Backup- und Wiederherstellungsfunktionen bereitstellen.

---

## Wichtig

**xBackup unterstützt keine Intel-Macs.**

Die App ist ausschließlich für Macs mit Apple-Silicon-Prozessoren vorgesehen, zum Beispiel:

- Apple M1
- Apple M2
- Apple M3
- Apple M4 oder neuer

Intel-basierte Macs werden nicht unterstützt.

---

## Hauptfunktionen

- Verbindung mit einem iPhone über macOS
- Anzeige erkannter iPhone-Geräte
- Auslesen wichtiger Geräteinformationen
- Übersichtliche Darstellung der Gerätedaten
- Backup-Funktionen
- Wiederherstellungsfunktionen
- DFU-Funktionen
- Geräteprüfung und Statusanzeige
- Einfache Benutzeroberfläche
- Für Apple Silicon optimiert

---

## Geräteinformationen

xBackup kann je nach Gerät und Verbindung verschiedene Informationen anzeigen.

Mögliche Informationen:

- Gerätename
- Modell
- iOS-Version
- Seriennummer
- Gerätekennung
- Verbindungsstatus
- Akkustatus
- Speicherinformationen
- Backup-Status
- Wiederherstellungsstatus
- DFU- oder Recovery-Status

Die tatsächlich angezeigten Informationen können je nach iPhone, iOS-Version und Systemfreigabe variieren.

---

## Backup-Funktionen

xBackup bietet Funktionen zur Sicherung von iPhone-Daten.

Mögliche Backup-Funktionen:

- Backup starten
- Backup-Status anzeigen
- Backup-Fortschritt anzeigen
- vorhandene Backups erkennen
- Backup-Informationen anzeigen
- Backup-Wiederherstellung vorbereiten

Vor jedem Backup sollte ausreichend Speicherplatz auf dem Mac vorhanden sein.

---

## DFU- und Recovery-Funktionen

xBackup kann Funktionen rund um DFU- und Recovery-Modus bereitstellen.

Mögliche Funktionen:

- Gerät im Recovery-Modus erkennen
- Gerät im DFU-Modus erkennen
- Status des verbundenen Geräts anzeigen
- Wiederherstellungsabläufe unterstützen
- Hinweise zur Geräteverbindung anzeigen

DFU- und Wiederherstellungsfunktionen sollten nur verwendet werden, wenn du genau weißt, was du tust.

Eine falsche Verwendung kann dazu führen, dass ein Gerät zurückgesetzt oder Daten verloren gehen.

---

## Systemanforderungen

| Komponente | Voraussetzung |
|---|---|
| Betriebssystem | macOS |
| Prozessor | Apple Silicon |
| Intel-Macs | Nicht unterstützt |
| Gerät | iPhone |
| Verbindung | USB-Kabel empfohlen |
| Rechte | Gerätefreigabe und Systemberechtigungen erforderlich |
| Speicherplatz | Ausreichend freier Speicher für Backups erforderlich |

---

## Installation

1. Lade die aktuelle Version von xBackup herunter.
2. Öffne die heruntergeladene Datei.
3. Ziehe xBackup in den Ordner `Programme`.
4. Starte xBackup.
5. Bestätige macOS-Sicherheitsabfragen nur, wenn die App aus einer vertrauenswürdigen Quelle stammt.

---

## iPhone verbinden

1. Verbinde dein iPhone per USB-Kabel mit dem Mac.
2. Entsperre das iPhone.
3. Bestätige auf dem iPhone die Meldung **Diesem Computer vertrauen**, falls sie angezeigt wird.
4. Starte xBackup.
5. Warte, bis das Gerät erkannt wird.
6. Prüfe die angezeigten Geräteinformationen.

---

## Nutzung

Empfohlener Ablauf:

1. xBackup starten
2. iPhone verbinden
3. iPhone entsperren
4. Vertrauen am iPhone bestätigen
5. Gerät in xBackup auswählen
6. Geräteinformationen prüfen
7. Backup- oder Wartungsfunktion auswählen
8. Hinweise sorgfältig lesen
9. Aktion starten

---

## Sicherheitshinweise

Bitte beachte vor der Nutzung:

- Verwende xBackup nur mit eigenen Geräten oder mit ausdrücklicher Erlaubnis.
- Erstelle vor Wiederherstellungs- oder DFU-Aktionen ein Backup.
- Trenne das iPhone während laufender Vorgänge nicht vom Mac.
- Schließe xBackup während eines Backups oder einer Wiederherstellung nicht.
- Sorge für ausreichend Akkuladung am iPhone.
- Verwende ein zuverlässiges USB-Kabel.
- Prüfe vor kritischen Aktionen, ob das richtige Gerät ausgewählt wurde.

xBackup ist nicht dafür gedacht, Gerätesperren, Aktivierungssperren oder Sicherheitsfunktionen zu umgehen.

---

## Datenschutz

xBackup liest Geräteinformationen aus, um diese innerhalb der App anzuzeigen und Funktionen wie Backups oder Wiederherstellung bereitzustellen.

Je nach Funktion können lokale Daten auf dem Mac gespeichert werden.

Empfehlungen:

- Backups sicher aufbewahren
- Backups nicht an unbekannte Personen weitergeben
- Mac mit Passwort oder Touch ID schützen
- sensible Daten nur auf vertrauenswürdigen Systemen sichern
- alte Backups regelmäßig prüfen und bei Bedarf löschen

---

## Fehlerbehebung

### iPhone wird nicht erkannt

Prüfe bitte:

- ob das iPhone entsperrt ist
- ob das USB-Kabel funktioniert
- ob das iPhone dem Mac vertraut
- ob macOS das Gerät erkennt
- ob xBackup neu gestartet werden muss
- ob ein anderes USB-Kabel oder ein anderer Anschluss hilft

### Backup startet nicht

Prüfe bitte:

- ob genug Speicherplatz auf dem Mac vorhanden ist
- ob das iPhone entsperrt ist
- ob die Verbindung stabil ist
- ob das iPhone dem Computer vertraut
- ob xBackup die erforderlichen Berechtigungen besitzt

### DFU-Modus wird nicht erkannt

Prüfe bitte:

- ob das Gerät korrekt in den DFU-Modus versetzt wurde
- ob das USB-Kabel zuverlässig ist
- ob der Mac das Gerät erkennt
- ob xBackup neu gestartet werden sollte
- ob das iPhone-Modell unterstützt wird

### App startet nicht

Prüfe bitte:

- ob du einen Apple-Silicon-Mac verwendest
- ob dein Mac kein Intel-Modell ist
- ob macOS aktuell genug ist
- ob die App vollständig heruntergeladen wurde
- ob macOS den Start aus Sicherheitsgründen blockiert

---

## Bekannte Hinweise

- Intel-Macs werden nicht unterstützt.
- Manche Funktionen können je nach iOS-Version eingeschränkt sein.
- DFU- und Recovery-Funktionen können Datenverlust verursachen.
- Backups benötigen ausreichend freien Speicherplatz.
- Ein beschädigtes USB-Kabel kann Verbindungsprobleme verursachen.
- Sicherheitssoftware oder macOS-Berechtigungen können bestimmte Funktionen blockieren.

---

## Release-Hinweise

Diese Version von xBackup konzentriert sich auf:

- iPhone-Erkennung
- Anzeige von Geräteinformationen
- einfache Benutzeroberfläche
- Backup-Funktionen
- DFU- und Recovery-Unterstützung
- stabile Verbindung unter macOS
- Optimierung für Apple Silicon

---

## Support

Bei Problemen bitte folgende Informationen bereithalten:

- xBackup-Version
- macOS-Version
- Mac-Modell
- iPhone-Modell
- iOS-Version
- genaue Fehlermeldung
- Beschreibung des Problems
- Schritte zum Reproduzieren
- Screenshot, falls möglich

---

## Haftungsausschluss

xBackup befindet sich in aktiver Entwicklung.

Die Nutzung erfolgt auf eigene Verantwortung.

Der Entwickler übernimmt keine Haftung für:

- Datenverlust
- fehlgeschlagene Backups
- beschädigte Wiederherstellungen
- fehlerhafte Bedienung
- falsche Geräteauswahl
- Schäden durch unsachgemäße Nutzung
- Probleme durch Beta- oder Testversionen

Vor kritischen Aktionen wird immer ein vollständiges Backup empfohlen.

---

## Lizenz

xBackup ist eine geschützte Software.

Die Weitergabe, Veränderung, Dekompilierung oder unerlaubte Veröffentlichung ist nicht gestattet, sofern keine ausdrückliche schriftliche Erlaubnis vorliegt.

```text
Copyright © 2026
Alle Rechte vorbehalten.
