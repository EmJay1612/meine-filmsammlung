# Meine Filmsammlung

Eine private Desktop-App zur Verwaltung einer Blu-ray / 4K UHD / DVD-Sammlung,
plus Wunschliste. Für Windows.

> Dieses Repository enthält keinen Quellcode – hier gibt es nur die fertige,
> installierbare Anwendung zum Download (siehe [Releases](../../releases)).

## Download

Die aktuelle Version findest du unter **[Releases](../../releases)** – lade
die neueste `Meine-Filmsammlung-Setup-X.X.X.exe` herunter und führe sie aus.

## Installation

1. Installer ausführen.
2. Den Hinweis-/Lizenztext auf der ersten Seite lesen und bestätigen.
3. Installationsort bestätigen (Standard ist meist passend) und durchklicken.
4. Windows zeigt beim ersten Start ggf. "Unbekannter Herausgeber" – das ist
   normal bei Software ohne teures Code-Signing-Zertifikat. Einfach auf
   "Trotzdem ausführen" klicken.

Kein Node.js, kein npm nötig – der Installer bringt alles mit.

## Funktionen

- Sammlung verwalten (Blu-ray, 4K UHD, 3D Blu-ray, DVD)
- Automatische Cover, Beschreibungen & Bewertungen über TMDb (kostenloser
  API-Key nötig, in der App unter ⚙ Einstellungen einzutragen)
- Wunschliste getrennt von der eigenen Sammlung
- Regal-Ansicht mit automatischer Gruppierung von Filmreihen
- Pile of Shame (ungesehene Filme im Blick behalten)
- Vier Design-Themes
- Backup-Export/Import

Beim ersten Start zeigt die App eine kurze Einführung mit den wichtigsten
Schritten – jederzeit wieder aufrufbar über ⚙ Einstellungen → "Anleitung
erneut anzeigen".

## Deine Daten

Alle Daten (Filmsammlung, Wunschliste, Einstellungen) werden ausschließlich
lokal auf deinem Computer gespeichert, unter
`%APPDATA%\meine-filmsammlung\`. Es gibt keine automatische Cloud-Sicherung –
nutze regelmäßig die Export-Funktion für ein Backup.

## Updates

Die App prüft beim Start automatisch, ob eine neuere Version verfügbar ist,
und bietet an, sie herunterzuladen und zu installieren.

## Lizenz

Diese Software ist kostenlos für den privaten Gebrauch, der Quellcode wird
nicht veröffentlicht. Details siehe [LICENSE.txt](LICENSE.txt).
