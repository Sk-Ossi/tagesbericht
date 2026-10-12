# Tagesbericht · DTC Digital

Ein digitales Berichtsbuch für die tägliche Reflexion und den Austausch in einer einvernehmlichen BDSM-Dynamik zwischen Erwachsenen. Kostenlos, ohne Anmeldung und als einzelne HTML-Datei nutzbar.

## Version 1.0.0

Erste Veröffentlichung der bereitgestellten Datei. Die Funktionen und das Design des Tools wurden für diese Veröffentlichung nicht verändert.

## Funktionen

- Bericht mit Datum und Berichtsnummer erstellen.
- Alltag und persönliches Empfinden festhalten.
- Bereiche für Hingabe, Keuschheit, Gehorsam und weitere Anmerkungen.
- Entwürfe speichern, Berichte abschließen und vorhandene Berichte duplizieren.
- Archiv nach Datum oder Berichtsnummer durchsuchen und nach Status filtern.
- Berichte drucken oder über den Druckdialog als PDF speichern.
- Archiv als JSON-Backup exportieren und wieder importieren.

## Starten

1. `Tagesbericht.html` herunterladen; bei ZIP-Download zuerst entpacken.
2. Die HTML-Datei per Doppelklick in einem aktuellen Browser öffnen.
3. Bericht ausfüllen und **Speichern** oder **Bericht abschließen** anklicken.

Es ist kein Server und keine Installation erforderlich. Die Datei enthält ihre Gestaltung und Programmlogik selbst; externe Bibliotheken werden nicht geladen.

## Speicherung und Backups

Das Tool speichert Berichte im lokalen Browserspeicher. Es übermittelt sie nicht automatisch an DTC Digital, GitHub oder andere Personen. Browserprofile, andere Browser und andere Speicherorte der HTML-Datei können getrennte Archive haben. Die Datei selbst enthält deine später eingegebenen Berichte nicht.

Exportiere regelmäßig über **Backup exportieren** eine Sicherung, besonders bevor du die Datei verschiebst, aktualisierst oder Browserdaten löschst. Die lokale Speicherung ist browserabhängig und wird vom Tool bei einem Speicherfehler nicht ausdrücklich bestätigt. Das Archiv ist nicht verschlüsselt oder durch ein Passwort geschützt. PDF- und JSON-Exporte enthalten deine eingetragenen Daten.

Beim Import wird nach Bestätigung das aktuelle Archiv ersetzt. Bewahre das bisherige Backup deshalb auf.

## Veröffentlichung in GitHub

Repository: `Sk-Ossi/tagesbericht` (öffentlich).

Empfohlene Repository-Beschreibung:

> Digitales Tagesberichtsbuch für einvernehmliche BDSM-Dynamiken: lokales Archiv, PDF-Druck und Backup, ohne Anmeldung.

Release-Tag: `v1.0.0`

Release-Titel: `Tagesbericht 1.0.0`

Release-Datei: `Tagesbericht-v1.0.0.zip` oder direkt `Tagesbericht.html`.

Die DTC-Digital-Bibliothek erkennt das öffentliche Repository automatisch und zeigt nach Veröffentlichung des stabilen Releases die Version und angehängten Dateien an. Ohne angehängte Release-Datei erscheint noch kein direkter Dateidownload.
