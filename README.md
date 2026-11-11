# Aura-Truhe – Android-Downloads

Dieses Repository stellt die installierbaren Android-Versionen von Aura-Truhe bereit. Es enthält **keinen App-Quellcode**. Der Quellcode wird separat und nicht öffentlich verwaltet.

## Aktueller Download: 0.2.2

- [Android-APK herunterladen](https://github.com/jemimakilab/aura-truhe-downloads/releases/download/v0.2.2/aura-truhe-v0.2.2.apk)
- [Release-Hinweise und Downloads](https://github.com/jemimakilab/aura-truhe-downloads/releases/tag/v0.2.2)
- [SHA-256-Prüfsumme](https://github.com/jemimakilab/aura-truhe-downloads/releases/download/v0.2.2/SHA256SUMS-0.2.2.txt)

Version 0.2.2 ist ein Vorabrelease. Sie erweitert die Ränge bis 1.000 und ergänzt zehn Rang-Erfolge. Die bisherigen Ränge 1–100, Aura-Chancen und Autoklicker-Laufzeiten bleiben unverändert.

## Installation und Updates

1. Vor einem Update zur Sicherheit den Spielstand in der App exportieren und außerhalb der App speichern.
2. Die Datei `aura-truhe-v0.2.2.apk` herunterladen und auf Android öffnen. Falls nötig, die Installation aus dieser Quelle erlauben.
3. Eine vorhandene, kompatibel signierte Aura-Truhe ab 0.1.0-alpha.1 kann aktualisiert werden. Nicht vorher deinstallieren, da dabei lokale App-Daten verloren gehen können. Das Update von 0.2.1-alpha auf 0.2.2 wurde im Android-Emulator mit erhaltenem Spielstand geprüft; ein echter Handytest steht aus.

Paketkennung: `de.jemimakilab.auratruhe`. Enthaltene Architekturen: ARM64 und x86_64. Die ursprüngliche, anders signierte Referenz-App ist kein kompatibles In-place-Update-Ziel; hier ist ein expliziter Spielstandexport/-import erforderlich.

## Download prüfen

SHA-256 der APK 0.2.2:

`477cb17639b2d7f87daf1e1fadeaeb7677561bc255354c3a539697dc9acc2b2a`

Unter Linux mit APK und Prüfsummendatei im selben Ordner:

    sha256sum -c SHA256SUMS-0.2.2.txt

Die bei GitHub automatisch angezeigten Dateien „Source code (zip/tar.gz)“ enthalten ausschließlich die Dateien dieses Download-Repositories, nicht den App-Quellcode. Zum Installieren die APK auswählen.

Die öffentliche Bereitstellung der APK ist keine Freigabe des App-Quellcodes oder eine Open-Source-Lizenz.
