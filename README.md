# Aura-Truhe – Android-Downloads

Dieses Repository stellt die installierbaren Android-Versionen von Aura-Truhe bereit. Es enthält **keinen App-Quellcode**. Der Quellcode wird separat und nicht öffentlich verwaltet.

## Aktueller Download: 0.3.0

- [Android-APK herunterladen](https://github.com/jemimakilab/aura-truhe-downloads/releases/download/v0.3.0/aura-truhe-v0.3.0.apk)
- [Release-Hinweise und Downloads](https://github.com/jemimakilab/aura-truhe-downloads/releases/tag/v0.3.0)
- [SHA-256-Prüfsumme](https://github.com/jemimakilab/aura-truhe-downloads/releases/download/v0.3.0/SHA256SUMS-0.3.0.txt)

Version 0.3.0 ist ein Vorabrelease mit automatischem Zehnsekunden-Grundtempo, Duplikat-Essenz, neuer Autoklicker-Abstimmung, 93 Auren mit eigenen Bildern, 45 neuen Rangtruhen bis Rang 1.000, Musik und Klicksound. Der gespeicherte Stand wird bereits während des Offline-Nachholens sichtbar; ausstehende Tipps bleiben sicher vorgemerkt. Seltene Zufallsfunde ab 1:1.000.000 erhalten eine Fundchronik mit Gesamtklicknummer, Datum und Uhrzeit. Alle Neuerungen sind in der App unter Einstellungen → Über erneut lesbar. Bestehende Spielstände und verdiente Freischaltungen bleiben erhalten.

## Installation und Updates

1. Vor einem Update zur Sicherheit den Spielstand in der App exportieren und außerhalb der App speichern.
2. Die Datei `aura-truhe-v0.3.0.apk` herunterladen und auf Android öffnen. Falls nötig, die Installation aus dieser Quelle erlauben. In Obtainium diese Repository-Adresse als Quelle nutzen und Vorabversionen einschließen.
3. Eine vorhandene, kompatibel signierte Aura-Truhe ab 0.1.0-alpha.1 kann aktualisiert werden. Nicht vorher deinstallieren und keine App-Daten löschen, da dabei lokale Spielstände verloren gehen können. Das Update von der veröffentlichten 0.2.2.1 auf 0.3.0 wurde im Android-Emulator mit erhaltenem Spielstand geprüft; ein neuer physischer Handytest steht aus.

Paketkennung: `de.jemimakilab.auratruhe`. Enthaltene Architekturen: ARM64 und x86_64. Die ursprüngliche, anders signierte Referenz-App ist kein kompatibles In-place-Update-Ziel; hier ist ein expliziter Spielstandexport/-import erforderlich.

## Download prüfen

SHA-256 der APK 0.3.0:

`9a227edeacf868e7af87e87cf4e52cb92bd284a95d64995e3b94f2bfdcbf349c`

Unter Linux mit APK und Prüfsummendatei im selben Ordner:

    sha256sum -c SHA256SUMS-0.3.0.txt

Die bei GitHub automatisch angezeigten Dateien „Source code (zip/tar.gz)“ enthalten ausschließlich die Dateien dieses Download-Repositories, nicht den App-Quellcode. Zum Installieren die APK auswählen.

Die öffentliche Bereitstellung der APK ist keine Freigabe des App-Quellcodes oder eine Open-Source-Lizenz.
