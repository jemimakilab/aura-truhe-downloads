# Aura-Truhe – Android-Downloads

Dieses Repository stellt die installierbaren Android-Versionen von Aura-Truhe bereit. Es enthält **keinen App-Quellcode**. Der Quellcode wird separat und nicht öffentlich verwaltet.

## Aktueller Download: 0.3.2

- [Android-APK herunterladen](https://github.com/jemimakilab/aura-truhe-downloads/releases/download/v0.3.2/aura-truhe-v0.3.2.apk)
- [Release-Hinweise und Downloads](https://github.com/jemimakilab/aura-truhe-downloads/releases/tag/v0.3.2)
- [SHA-256-Prüfsumme](https://github.com/jemimakilab/aura-truhe-downloads/releases/download/v0.3.2/SHA256SUMS-0.3.2.txt)

Version 0.3.2 ist ein Vorabrelease. Neu: Tipps, die genau während einer fälligen automatischen Ziehung kommen (vor allem bei laufendem Autoklicker), zeigen ihre Funde, Hinweise und Sprüche jetzt wie jeder andere Tipp. Seit 0.3.1.1 erscheint bei leeren Tipps kein grauer Überlagerungstext mehr, der Hinweis „Tipp gespeichert“ nur noch beim echten Offline-Nachholen, und ein alter Spruch ist entfernt. Neu seit 0.3.1: Uhrschutz – Offline-Zeit wird höchstens sieben Tage nachgeholt, und wer die Gerätezeit zurückdreht, bekommt für 24, dann 48, dann 72 Stunden die Spielverderber-Truhe, auf der Tippen nicht zählt. Eine Tipp-Ladeleiste belohnt 1.000, 2.000 und 5.000 eigene Tipps am Tag mit einem Autoklicker. Die Truhe lästert mit 100 sammelbaren Sprüchen in vier Seltenheitsstufen (abschaltbar), die Statistik zeigt ein Pech-Meter, und die Truhe federt bei jedem Tipp. Die App ist deutlich kleiner und fragt nicht mehr nach Mikrofon, Overlay oder Speicherzugriff. Alle Neuerungen sind in der App unter Einstellungen → Über erneut lesbar. Bestehende Spielstände und verdiente Freischaltungen bleiben erhalten.

## Installation und Updates

1. Vor einem Update zur Sicherheit den Spielstand in der App exportieren und außerhalb der App speichern.
2. Die Datei `aura-truhe-v0.3.2.apk` herunterladen und auf Android öffnen. Falls nötig, die Installation aus dieser Quelle erlauben. In Obtainium diese Repository-Adresse als Quelle nutzen und Vorabversionen einschließen.
3. Eine vorhandene, kompatibel signierte Aura-Truhe ab 0.1.0-alpha.1 kann aktualisiert werden. Nicht vorher deinstallieren und keine App-Daten löschen, da dabei lokale Spielstände verloren gehen können. Das Update von der veröffentlichten 0.3.1.1 auf 0.3.2 wurde im Android-Emulator mit erhaltenem Spielstand geprüft; ein neuer physischer Handytest steht aus.

Paketkennung: `de.jemimakilab.auratruhe`. Enthaltene Architekturen: ARM64 und x86_64. Die ursprüngliche, anders signierte Referenz-App ist kein kompatibles In-place-Update-Ziel; hier ist ein expliziter Spielstandexport/-import erforderlich.

## Download prüfen

SHA-256 der APK 0.3.2:

`f209757cfca2ed55dc9748a56e7d7da581249ec253015041a2571719864595f9`

Unter Linux mit APK und Prüfsummendatei im selben Ordner:

    sha256sum -c SHA256SUMS-0.3.2.txt

Die bei GitHub automatisch angezeigten Dateien „Source code (zip/tar.gz)“ enthalten ausschließlich die Dateien dieses Download-Repositories, nicht den App-Quellcode. Zum Installieren die APK auswählen.

Die öffentliche Bereitstellung der APK ist keine Freigabe des App-Quellcodes oder eine Open-Source-Lizenz.
