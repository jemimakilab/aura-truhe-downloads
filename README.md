# Aura-Truhe – Android-Downloads

Dieses Repository stellt die installierbaren Android-Versionen von Aura-Truhe bereit. Es enthält **keinen App-Quellcode**. Der Quellcode wird separat und nicht öffentlich verwaltet.

## Aktueller Download: 0.4.0

- [Android-APK herunterladen](https://github.com/jemimakilab/aura-truhe-downloads/releases/download/v0.4.0/aura-truhe-v0.4.0.apk)
- [Release-Hinweise und Downloads](https://github.com/jemimakilab/aura-truhe-downloads/releases/tag/v0.4.0)
- [SHA-256-Prüfsumme](https://github.com/jemimakilab/aura-truhe-downloads/releases/download/v0.4.0/SHA256SUMS-0.4.0.txt)

Version 0.4.0 ist ein Vorabrelease. Neu: 27 Mythen-Auren von Satyr bis Chaos, 16 Zeitfenster-Auren, die es nur zu bestimmten Zeiten durch eigene Tipps gibt (11:11, 13:37, Geisterstunde, Vollmond, Halloween, Schalttag und mehr – die Galerie zeigt, wann), 41 neue Erfolge mit Einblendung beim Freischalten und eine deutlich kleinere App (66 statt 96 MB) dank komprimierter Bilder. Weiterhin enthalten: Uhrschutz mit Spielverderber-Truhe, Tipp-Ladeleiste, 100 sammelbare Sprüche, Pech-Meter. Die App fragt nur nach Internet, Netzwerkstatus, Vibration und Audio-Einstellungen. Alle Neuerungen sind in der App unter Einstellungen → Über erneut lesbar. Bestehende Spielstände und verdiente Freischaltungen bleiben erhalten.

## Installation und Updates

1. Vor einem Update zur Sicherheit den Spielstand in der App exportieren und außerhalb der App speichern.
2. Die Datei `aura-truhe-v0.4.0.apk` herunterladen und auf Android öffnen. Falls nötig, die Installation aus dieser Quelle erlauben. In Obtainium diese Repository-Adresse als Quelle nutzen und Vorabversionen einschließen.
3. Eine vorhandene, kompatibel signierte Aura-Truhe ab 0.1.0-alpha.1 kann aktualisiert werden. Nicht vorher deinstallieren und keine App-Daten löschen, da dabei lokale Spielstände verloren gehen können. Das Update von der veröffentlichten 0.3.2 auf 0.4.0 wurde im Android-Emulator mit erhaltenem Spielstand geprüft; ein neuer physischer Handytest steht aus.

Paketkennung: `de.jemimakilab.auratruhe`. Enthaltene Architekturen: ARM64 und x86_64. Die ursprüngliche, anders signierte Referenz-App ist kein kompatibles In-place-Update-Ziel; hier ist ein expliziter Spielstandexport/-import erforderlich.

## Download prüfen

SHA-256 der APK 0.4.0:

`16e47003be3cddfa079380278e5a55072fe196ce70cb2565ac5e6accec4620f4`

Unter Linux mit APK und Prüfsummendatei im selben Ordner:

    sha256sum -c SHA256SUMS-0.4.0.txt

Die bei GitHub automatisch angezeigten Dateien „Source code (zip/tar.gz)“ enthalten ausschließlich die Dateien dieses Download-Repositories, nicht den App-Quellcode. Zum Installieren die APK auswählen.

Die öffentliche Bereitstellung der APK ist keine Freigabe des App-Quellcodes oder eine Open-Source-Lizenz.
