# SnapSell für Android

Offizielle Download- und Update-Quelle für SnapSell. Hier werden APKs und die zugehörigen Update-Informationen veröffentlicht. Der App-Quellcode wird separat privat verwaltet.

## Aktuelle Version installieren

**[SnapSell APK herunterladen](https://github.com/alexxschenk-hub/snapsell-updates/releases/latest/download/SnapSell.apk)**

Die APK auf dem Android-Handy öffnen und die Installation beziehungsweise Aktualisierung bestätigen. Eine vorhandene SnapSell-Installation aus der nativen Version 1.0.0 muss dafür nicht deinstalliert werden. Artikel, Einstellungen und API-Schlüssel bleiben bei einem regulären Update erhalten.

Nach der einmaligen Installation von Version 1.1.0 findet sich die Update-Funktion in **Profil → Immer einen Schritt weiter → Nach Updates suchen**. Android benötigt gegebenenfalls einmalig die Freigabe „Unbekannte Apps installieren“ für SnapSell. Eine Installation wird immer am Handy bestätigt.

## Update-Quelle in der App

`https://github.com/alexxschenk-hub/snapsell-updates`

Die App prüft bei aktivierter automatischer Suche höchstens einmal täglich beim Start. Sie lädt Update-Informationen aus GitHub Releases, prüft die SHA-256-Prüfsumme sowie Paketkennung, Version und den vorhandenen Signaturschlüssel und öffnet anschließend den Android-Installer.

Android 8.0 oder neuer. Diese APK ist eine direkt verteilte, mit dem bisherigen Testschlüssel signierte Version. Nur über die bestehende native App `at.snapsell.app` aktualisierbar; die frühere Expo/PWA-App ist ein anderes Paket.

## Version 1.2.0

- Google-Anmeldung unter Profil mit nativer Google-Kontoauswahl.
- Kontoanzeige, Kontowechsel und Abmeldung; Anmeldung bleibt optional.
- Name und E-Mail werden separat auf dem Gerät gespeichert und nicht an KI-Anbieter übertragen.
- Inventar und KI-Schlüssel bleiben beim Update und bei der Google-Abmeldung erhalten.
- Keine Cloud-Synchronisierung. Vollständigen Google-Login mit dem eigenen Konto bitte am Handy prüfen.

## Version 1.1.0

- Modernes Design mit hellen Karten, abgerundeten Feldern und violetten Akzenten.
- Schwebende Navigation und überarbeitetes Inventar.
- Integrierter Updater mit öffentlicher Download-Quelle.
- Weiterhin direkte KI-Aufrufe über deinen eigenen Gemini- oder OpenAI-Schlüssel.

[Alle Versionen und Änderungen](https://github.com/alexxschenk-hub/snapsell-updates/releases)
