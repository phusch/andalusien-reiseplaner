# Andalusien – Peter & Tanja · V1.2

Persönlicher Reiseführer für zwei Personen vom 16. bis 25. November 2026. Aufbau und Bedienung orientieren sich am gelieferten RdGA-Reiseführer, mit eigenem Farbcode in Terrakotta, Oliv und Sand.

## Schnellstart

**Online:** https://andalusien-peter-tanja-2026.huschel007.chatgpt.site

**Als ZIP:** Die ZIP vollständig entpacken. Alle Dateien und der Ordner `assets` müssen zusammenbleiben. Anschließend `index.html` in Safari, Chrome, Edge oder Firefox öffnen. Auf Mobilgeräten ist die Onlineversion der einfachste Weg; eine HTML-Datei in der Dateien-Vorschau führt JavaScript möglicherweise nicht aus.

Für Karten, berechnete Fahrstrecken, externe Bilder und Links ist Internet erforderlich. Die Texte, das Vejerfoto und die App-Icons liegen in der ZIP. Die App hat keinen Offline-Cache und ist kein Navigationsgerät.

## Installation auf iPhone und iPad

1. Die Onlineadresse in Safari öffnen und gegebenenfalls mit dem berechtigten ChatGPT-Konto anmelden.
2. Teilen öffnen und „Zum Home-Bildschirm“ wählen (gegebenenfalls in den Aktionen nach unten scrollen).
3. Als Namen „Andalusien“ verwenden und hinzufügen.
4. Anschließend über das neue Symbol starten. Das Apple-Touch-Icon ist bereits eingebunden.

Falls bereits ein älteres Symbol angelegt wurde und das neue Bild fehlt, den alten Startbildschirm-Link entfernen und aus Safari neu hinzufügen. Das Entfernen des Symbols ersetzt keine Datensicherung.

## Auf Mac und anderen Geräten

Auf dem Mac die Onlineversion im Browser verwenden. In Safari kann je nach macOS-Version über „Ablage → Zum Dock hinzufügen“ eine Web-App angelegt werden. In Chrome/Edge erscheint eine Installationsfunktion nur, wenn der Browser sie für diese Seite anbietet; andernfalls genügt ein Lesezeichen. Das Manifest und die Icons sind enthalten, eine Installationsschaltfläche wird jedoch nicht von jedem Browser angeboten.

## Eure Route und Übernachtungen

| Tag | Datum | Tagesziel | Übernachtungsvorschlag |
| --- | --- | --- | --- |
| 1 | Mo 16.11. | Ankunft Jerez | Casa Palacio Jerezana |
| 2 | Di 17.11. | Über Cádiz nach Vejer | El Cobijo de Vejer |
| 3 | Mi 18.11. | Vejer | El Cobijo de Vejer |
| 4 | Do 19.11. | Fahrt nach Tarifa | Posada La Sacristía |
| 5 | Fr 20.11. | Tarifa | Posada La Sacristía |
| 6 | Sa 21.11. | Bolonia / Baelo Claudia | Posada La Sacristía |
| 7 | So 22.11. | Über Casares nach Gaucín | La Fructuosa |
| 8 | Mo 23.11. | Gaucín → Ronda | Alavera de los Baños |
| 9 | Di 24.11. | Ronda → Málaga | Villa Alicia Guest House |
| 10 | Mi 25.11. | Málaga und Rückflug | — |

Neun Nächte insgesamt. Tarifa ist bewusst mit einem kleinen zentralen Stadthotel geplant. Alle Häuser sind Vorschläge; die App bestätigt keine Reservierung oder Verfügbarkeit.

## Bedienung

- Oben einen der zehn Tagesreiter wählen. Auf schmalen Displays lässt sich die Reiterleiste horizontal verschieben.
- Jeder Tag enthält Ablauf, Fahrzeitorientierung, Karte, Sehenswürdigkeiten, Hotel und eigene Notizen.
- Die Zeitangaben sind Vorschläge. „Optional“ und „Wahlprogramm“ sind Ergänzungen oder Alternativen, keine zusätzlichen Pflichttermine.
- Tarifa und Bolonia lassen sich abhängig vom Wetter tauschen.
- Aufklappbare Bereiche über ihre Überschrift öffnen oder schließen.
- Die Reiter lassen sich auch mit den Pfeiltasten links/rechts bedienen.
- „Reiseinfos & Sicherung“ enthält die geplanten Flüge, Mietwageninformationen und die Datensicherung.

## Karten und Fahrstrecken

Die Karten verwenden Leaflet mit OpenStreetMap-Daten; die Kartenkacheln stammen von OSM France / HOT.

- Terrakottafarbene Punkte markieren Attraktionen; antippen öffnet eine Beschreibung und einen Link.
- Die olivfarbene durchgezogene Linie ist ein berechneter Straßenvorschlag des öffentlichen OSRM-Routendienstes.
- Eine gestrichelte Linie zeigt nur die schematische Verbindung, solange die Straßenroute lädt oder der Dienst nicht erreichbar ist.
- Optionale Ausflüge sind nur als Orte markiert oder im Text beschrieben; sie sind nicht automatisch Teil der eingezeichneten Route.
- An autofreien Tagen werden die Sehenswürdigkeiten ohne feste Fahrstrecke gezeigt.
- Zoom über Plus/Minus oder Touchgesten. Das Mausrad-Zoomen ist bewusst deaktiviert, damit die Seite beim Scrollen nicht unbeabsichtigt die Karte verändert.

Die Routen beginnen und enden an Planungskoordinaten und sind keine exakten Hotelzufahrten oder Parkplatzangaben. Es gibt keine Live-Verkehrsdaten. Öffnungen, Sperrungen, Wetter und die aktuelle Navigation am Reisetag prüfen. Die Darstellung enthält keinen Flugpfad.

## Notizen und Checklisten

Notizen und Häkchen werden automatisch im lokalen Browser-Speicher abgelegt. Sie sind an Browser, Gerät und Seitenadresse gebunden. Onlineversion, lokale Datei und ein anderer Browser können deshalb verschiedene Einträge zeigen. Die App überträgt Notizen nicht automatisch zwischen Geräten und verbindet sich nicht mit dem RdGA-Speicher oder dessen GitHub-Daten.

Privater Browsermodus, das Löschen von Websitedaten oder ein Browserwechsel können Einträge entfernen. Die App kann nur speichern, wenn der Browser lokalen Speicher zulässt.

### Backup erstellen und übertragen

1. „Reiseinfos & Sicherung“ öffnen.
2. „Backup herunterladen“ wählen.
3. Die Datei `Andalusien_Notizen_Backup.json` an einem sicheren Ort ablegen.
4. Auf dem anderen Gerät dieselbe App öffnen und unter „Backup laden“ die Datei auswählen.
5. Das Laden ersetzt den aktuellen lokalen Notizen-/Checklistenstand und lädt die Seite neu. Vorher den bisherigen Stand sichern.

Das JSON sichert ausschließlich eigene Notizen und Häkchen. Reisebeschreibungen, Bilder, Karten und App-Dateien bleiben Bestandteil der veröffentlichten Version bzw. ZIP. Es gibt keine automatische Zusammenführung mehrerer Backups.

## Drucken und PDF

Über „Druckansicht“ den Browser-Druckdialog öffnen und bei Bedarf „Als PDF sichern“ wählen. Die Druckansicht zeigt alle Tagesbereiche. Für vollständige Notizen die gewünschten Aufklappbereiche vorher öffnen. Karten und externe Bilder werden erst beim Besuch des jeweiligen Tages geladen: vor einem Gesamtausdruck einmal alle zehn Reiter öffnen und das Laden abwarten. Ein Ausdruck ist ein statischer Stand und enthält keine interaktiven Kartenfunktionen.

## Flüge und Mietwagen

Geplante Flugverbindungen aus der Reiseplanung:

- 16.11.2026: TUIfly X3 2222, Stuttgart 05:50 → Jerez 08:50, nonstop.
- 25.11.2026: Eurowings EW2537, Málaga 20:25 → Stuttgart 23:05, nonstop.
- Alle Zeiten sind Ortszeiten. Vor dem Buchen und vor Abreise aktuell bestätigen.
- Mietwagenübernahme Jerez Flughafen 16.11. gegen 09:30–10:00 Uhr; Rückgabe Málaga Flughafen 25.11. gegen 17:15–17:30 Uhr.
- Einweggebühr, Versicherung, Tankregelung und die Parkmöglichkeiten bei den Altstadthäusern gesondert klären.

## App-Icon und Dateien

Das Icon zeigt weiße Häuser mit Torbogen, eine Sonne und eine geschwungene Route in der Farbwelt der App. Es ist eine für diesen Reiseführer erstellte grafische Illustration, keine Abbildung eines konkreten Gebäudes.

- `index.html`: Einstieg, Reiseinfos, Links und Metadaten.
- `style.css`: Gestaltung, mobile Ansicht und Druckregeln.
- `data.js`: Hotels, Tagesabläufe, Attraktionen und Wegpunkte.
- `app.js`: Reiter, Karten, Bildladen, Notizen und JSON-Backup.
- `vejer.jpg`: fest eingebundenes Foto für Tag 3.
- `manifest.webmanifest`: App-Name, Startadresse und Startbildschirm-Angaben.
- `assets/app-icon.svg`: bearbeitbare Vektorillustration.
- `assets/app-icon-1024.png`: großes App-Icon.
- `assets/icon-512.png` und `assets/icon-192.png`: Web-App-Icons.
- `assets/apple-touch-icon.png`: 180-Pixel-Icon für Apple-Geräte.
- `assets/favicon-32.png`: kleines Browser-Icon.
- `README.md`: diese Anleitung.

Für eigenes Hosting den gesamten Ordnerinhalt zusammen auf einen Webserver legen. HTTPS ist für eine verlässliche Web-App-Nutzung empfehlenswert. Keine Zugangsdaten oder privaten GitHub-Tokens in die Dateien eintragen.

## Bilder, Quellen und externe Dienste

Vejerfoto: Picustratos, „Vejer de la Frontera.jpg“, Wikimedia Commons, CC BY-SA 3.0 ES. Das Foto wurde verkleinert. Quelle: https://commons.wikimedia.org/wiki/File:Vejer_de_la_Frontera.jpg · Lizenz: https://creativecommons.org/licenses/by-sa/3.0/es/

Weitere Ortsbilder werden aus Wikipedia/Wikimedia geladen; die jeweilige Quelle ist beim Bild verlinkt. Sie können durch Erreichbarkeit, Rechteänderungen oder Änderungen der externen Dienste zeitweise fehlen. Die Informationslinks führen überwiegend zu Hotelwebsites und Tourismusstellen.

Karten: © OpenStreetMap-Mitwirkende, https://www.openstreetmap.org/copyright · Leaflet: https://leafletjs.com/ · OSRM: https://project-osrm.org/ · Kartenkacheln OSM France / HOT.

Beim Laden von externen Karten, Bildern und Routen entstehen Verbindungen zu den jeweiligen Anbietern. Die App lädt keine persönlichen Notizen zu diesen Diensten hoch; Routendienste erhalten die zur Berechnung verwendeten Wegpunkte. Die Onlineveröffentlichung hat die bestehende private Zugriffsregelung.

## Fehlerhilfe

**Alte Version sichtbar:** Seite neu laden; falls nötig Browser-Cache aktualisieren. Vor dem Löschen von Websitedaten ein JSON-Backup erstellen.

**Bild fehlt:** Internet prüfen. Das Bild von Vejer an Tag 3 ist lokal enthalten; bei der ZIP müssen `vejer.jpg` und `index.html` im selben Ordner liegen.

**Karte leer / Strecke gestrichelt:** Internet oder externer Dienst möglicherweise nicht verfügbar. Kartenlinks der Attraktionen öffnen und eine eigene Navigations-App verwenden.

**Keine Häkchen gespeichert:** Nicht im Privatmodus öffnen und Browser-Speicher erlauben. Regelmäßig JSON sichern.

**Backup wird abgelehnt:** Nur eine von dieser Andalusien-App exportierte JSON-Datei verwenden. Eine ZIP oder ein RdGA-Backup ist nicht kompatibel.

**Startbildschirm-Icon fehlt:** Onlineversion in Safari öffnen, neu laden und Startbildschirm-Link neu anlegen. Die PNG-Dateien müssen unter `assets` verfügbar sein.

## Versionsverlauf

- V1.0: Zehn Tagesreiter, beschlossene Route, Hotels, OpenStreetMap-Karten, Flüge, Notizen und Backup.
- V1.1: Alle Tage erweitert, zusätzliche Attraktionen auf den Karten, Vejerfoto für Tag 3 fest eingebunden.
- V1.2: Ausführliche README, App-Icon in mehreren Größen, Apple-Touch-Icon, Favicon und Web-App-Manifest.

V1.2 ergänzt Dokumentation und App-Ausstattung. Der Stand der Reiseplanung ist weiterhin November 2026; konkrete Buchungen und Öffnungen sind vor Reisebeginn zu bestätigen.
