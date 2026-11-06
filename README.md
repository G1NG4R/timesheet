# Timesheet-Generator

Erstellt aus dem Badge-Export (Pointages-CSV) automatisch das monatliche Timesheet – als **ODS**, **XLSX** oder **PDF**.

👉 **https://g1ng4r.github.io/timesheet/**

## Benutzung
1. Pointages-Export als CSV herunterladen
2. Seite öffnen, CSV reinziehen
3. Monat wählen, offene Tage (gelb markiert) mit CONGE / recup / Krank / Feiertag ausfüllen
4. Format wählen und herunterladen

## Regeln
- Schicht 08:00 / 09:00 / 10:00 wird aus dem Eintritt erkannt (pro Tag änderbar)
- Zeit vor Schichtbeginn zählt nicht
- Overtime erst nach Schichtende, nur in vollen 15 Minuten
- Zu spät kommen / früher gehen wird minutengenau abgezogen
- Luxemburger Feiertage werden automatisch eingetragen

## Datenschutz
Alles läuft lokal im Browser. Die CSV wird nirgendwo hochgeladen, Einträge werden nur im eigenen Browser gespeichert.

Eine einzige Datei (`index.html`), keine Abhängigkeiten.
