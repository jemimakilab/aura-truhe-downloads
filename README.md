# Aura-Truhe – Android-Downloads

Dieses Repository stellt die installierbaren Android-Versionen von Aura-Truhe bereit. Es enthält **keinen App-Quellcode**. Der Quellcode wird separat und nicht öffentlich verwaltet.

## Aktueller Download: 0.2.2.1

- [Android-APK herunterladen](https://github.com/jemimakilab/aura-truhe-downloads/releases/download/v0.2.2.1/aura-truhe-v0.2.2.1.apk)
- [Release-Hinweise und Downloads](https://github.com/jemimakilab/aura-truhe-downloads/releases/tag/v0.2.2.1)
- [SHA-256-Prüfsumme](https://github.com/jemimakilab/aura-truhe-downloads/releases/download/v0.2.2.1/SHA256SUMS-0.2.2.1.txt)

Version 0.2.2.1 ist ein Vorabrelease mit Startbildschirm-Hotfix: Offline-Fortschritt und Ladefehler bleiben nicht mehr hinter dem Startlogo verborgen. Das Nachholen selbst kann bei vielen ausstehenden Klicks weiterhin dauern. Ränge bis 1.000 und zehn Rang-Erfolge bleiben enthalten; Spielstände, Aura-Chancen und Autoklicker-Laufzeiten bleiben unverändert. Der Fix wurde im Emulator geprüft, nicht auf einem Samsung S26 Ultra; ein sofortiger nativer Absturz auf diesem Gerät ist damit nicht als behoben nachgewiesen.

## Installation und Updates

1. Vor einem Update zur Sicherheit den Spielstand in der App exportieren und außerhalb der App speichern.
2. Die Datei `aura-truhe-v0.2.2.1.apk` herunterladen und auf Android öffnen. Falls nötig, die Installation aus dieser Quelle erlauben. In Obtainium diese Repository-Adresse als Quelle nutzen und Vorabversionen einschließen.
3. Eine vorhandene, kompatibel signierte Aura-Truhe ab 0.1.0-alpha.1 kann aktualisiert werden. Nicht vorher deinstallieren und keine App-Daten löschen, da dabei lokale Spielstände verloren gehen können. Das Update von 0.2.2 auf 0.2.2.1 wurde im Android-Emulator mit erhaltenem Spielstand geprüft; ein echter Handytest steht aus.

Paketkennung: `de.jemimakilab.auratruhe`. Enthaltene Architekturen: ARM64 und x86_64. Die ursprüngliche, anders signierte Referenz-App ist kein kompatibles In-place-Update-Ziel; hier ist ein expliziter Spielstandexport/-import erforderlich.

## Download prüfen

SHA-256 der APK 0.2.2.1:

`31cefdb39bc6bbcff34cbb5a3995bd0fe2a61cd27abe490e40adad61a44c23c5`

Unter Linux mit APK und Prüfsummendatei im selben Ordner:

    sha256sum -c SHA256SUMS-0.2.2.1.txt

Die bei GitHub automatisch angezeigten Dateien „Source code (zip/tar.gz)“ enthalten ausschließlich die Dateien dieses Download-Repositories, nicht den App-Quellcode. Zum Installieren die APK auswählen.

Die öffentliche Bereitstellung der APK ist keine Freigabe des App-Quellcodes oder eine Open-Source-Lizenz.
