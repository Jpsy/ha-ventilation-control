# ha-ventilation-control

**EN:**

Home Assistant project

### Making a conventional MVHR smart

This project integrates a Viessmann 300-W with control panel LB1 into Home Assistant as a smart home center. The logic in Home Assistant is implemented using the Add-On Node RED. The microcontrollers are also programmed directly from Home Assistant using the ESPHome add-on.

The project was originally published on the German branch of makeprojects.com. Unfortunately, this offshoot no longer exists and the article is no longer available there. A dump of the article can be found in [this PDF](Die%20klassische%20KWL%20wird%20smart!%20_%20Make_%20Projects%20De.pdf) (in German). All companion files can be found (somewhat disorganized) in the subdirectories of the repo:

* /ESPHome =  
all ESPhome YAML files to program the different ESP8266 MCUs of the project. I used D1 mini MCUs.
* /HomeAssistant =  
files that contain YAML snippets to add to your configuration.yaml and to your Lovelace dashboard
* /NodeRED =  
Import this into your NodeRED add-on as a new flow. It contains the full HA logic.
* /diagram =  
Some diagrams and graphics showing details of the project (also found in the PDF above, but here in better resolution)
* /img =  
Photos of several components of the project, partially also contained in the PDF above

As time allows I will try to publish a new project description in the Home Assistant community forum.  
But for now this is all I have for you. **Sorry for the mess.**


----
**DE:**

Home Assistant Projekt

### Eine klassische KWL smart machen

Dieses Projekt bindet eine Viessmann 300-W mit Bedienteil LB1 in Home Assistant als Smart Home-Zentrale ein. Die Programmierung der Steuerung in Home Assistant erfolgt mit dem Home Assistant Add-On Node RED. Die Microcontroller werden ebenfalls direkt aus Home Assistant heraus mit dem Add-On ESPHome programmiert.

Das Projekt wurde ursprünglich im deutschen Ableger von makeprojects.com veröffentlicht. Leider existiert dieser Ableger nicht mehr und der Artikel ist dort nicht mehr verfügbar. Ein Dump des Artikels findet sich in [diesem PDF](Die%20klassische%20KWL%20wird%20smart!%20_%20Make_%20Projects%20De.pdf). Die ergänzenden Dateien finden sich (etwas ungeordnet) in den Unterverzeichnissen des Repos:

* /ESPHome =  
Alle ESPhome-YAML-Files um die verschiedenen ESP8266-MCUs des Projekts zu programmieren. Verwendet werden D1 mini-MCUs.
* /HomeAssistant =  
Dateien mit YAML-Snippets, die zum Hinzufügen zur configuration.yaml und zum Lovelace-Dashboard
* /NodeRED =  
Diese Datei kann im NodeRED Add-On als neuer Flow importiert werden, und enthält die gesamte HA-Logik.
* /diagram =  
Einige Diagramme und Grafiken zu Details des Projekts. Sie sind teilweise auch in obigem PDF enthalten, dort aber in schlechterer Qualität.
* /img =  
Fotos von diversen Komponenten des Projektes. Sie sind teilweise auch in obigem PDF enthalten.

Wenn meine Zeit es erlaubt, werde ich im Home Assistant Community-Forum eine neue Projektbeschreibung erstellen.  
Aber im Moment gibt es leider nur diese Fragmenten hier. **Sorry für das Chaos.**
