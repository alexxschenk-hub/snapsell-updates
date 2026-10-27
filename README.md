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

## Vorabversion 1.5.1 – lokale Formularhilfe ohne JEV-Key

**[Neue APK herunterladen](https://github.com/alexxschenk-hub/snapsell-updates/releases/download/v1.5.1/SnapSell.apk)** · [Hinweise und Prüfstand](https://github.com/alexxschenk-hub/snapsell-updates/releases/tag/v1.5.1)

Laya Multilingual INT8 und lokale Regeln ersetzen die JEV-API auf Android. Nach dem Update unter Profil → Lokales Formularmodell einrichten einmalig rund 358 MB herunterladen, ohne API-Key. Formularentscheidungen laufen danach auf dem Gerät; willhaben benötigt weiterhin Internet. Fotoanalyse und Inseratstext-Erstellung behalten ihre bisherige KI-Anbindung. Veröffentlichung manuell, vollständiger willhaben-Live-Test weiterhin offen. Der App-Updater findet diese Vorabversion. 1.4.0 bleibt das neueste stabile Release.

## Vorabversion 1.5.0 – willhaben & JEV

**[Vorabversion herunterladen](https://github.com/alexxschenk-hub/snapsell-updates/releases/download/v1.5.0/SnapSell.apk)** · [Hinweise und Prüfstand](https://github.com/alexxschenk-hub/snapsell-updates/releases/tag/v1.5.0)

Einmalige willhaben-Anmeldung im App-Browser und JEV-Formularhilfe mit eigenem TypeSafe-Schlüssel. Veröffentlichung manuell. Der vollständige Live-Ablauf bis zum gespeicherten willhaben-Entwurf ist noch nicht bestätigt; Kategorieauswahl, Fotos und Pflichtangaben können manuelle Schritte benötigen. Die Automatik läuft bei geöffneter App. Der SnapSell-Updater berücksichtigt diese Vorabversion. 1.4.0 bleibt das neueste stabile Release.

## Version 1.4.0

- Scan zeigt immer „Neuen Verkauf starten“ und ausschließlich offene Verkäufe zum Fortsetzen.
- Gespeicherte Artikel erscheinen nur im Inventar.
- Neue Verkäufe starten leer und überschreiben keine offenen Entwürfe.
- Fotos, Antworten und Notizen unfertiger Verkäufe bleiben lokal erhalten.
- Inventar mit umschaltbarer Karten- und kompakter Listenansicht; Auswahl bleibt gespeichert.

## Version 1.3.0

- Kopierbutton für jedes Inseratsfeld, eBay-Merkmale und ergänzende Artikeldaten.
- Vollständiges automatisches Speichern: Fotos, Analyse, Rückfragen, Verkaufsangaben und beide Plattform-Inserate.
- Änderungen werden automatisch nachgesichert; bei Ansichtswechsel sofort.
- „Fertig & zum Inventar“ schließt den Assistenten ab. Später über „Öffnen / bearbeiten“ wiederverwenden.
- Keine Duplikate beim Bearbeiten oder Wiederöffnen; bisheriger Status bleibt erhalten.

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
