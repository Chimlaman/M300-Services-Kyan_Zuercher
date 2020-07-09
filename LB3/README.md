# M300
## Repository for Module 300 LB3

### Hier werde ich im Bezug auf die LB's des M300 die Technischenschritte, Konfiguration und Dokumetation fest halten.

# Documentation:

## K1

Umgebung auf eigenem Notebook eingerichtet und funktionsfähig
- VirtualBox
- (Vagrant)
- Visualstudio-Code
- Git-Client
- SSH-Key für Client erstellt

### Reflexion:

All die Punkte in diesem Block sind schon erledigt, da wir diese auch für die LB2 braucheten.

## K2

Eigene Lernumgebung ist eingerichtet
- GitHub oder Gitlab-Account ist erstellt
- Git-Client wurde verwendet
- Dokumentation ist als Mark Down vorhanden
- Markdown-Editor ausgewählt und eingerichtet
- Markdown ist strukturiert
- Persönlicher Wissenstand im Bezug auf die wichtigsten Themen ist dokumentiert (Containerisierung / Docker, Microservices)
- Wichtige Lernschritte sind dokumentiert

### Reflexion:

All diese Punkte in diesem Block werden sehr einfach sein, da wir diese schon ähnlich oder fast gleich in dem LB2 erfüllen mussten.

## K3

- Bestehenden Docker-Container kombinieren
- Bestehende Container als Backend, Desktop-App als Frontend  einsetzen
- Volumes zur persistenten Datenablage eingerichtet
- Kennt die Docker spezifischen Befehle
- Eingerichtete Umgebung ist dokumentiert (Umgebungs-Variablen, Netzwerkplan gezeichnet, Schichtenmodell, Sicherheitsaspekte)
- Funktionsweise getestet inkl. Dokumentation der Testfälle
- Projekt mit Git und Markdown dokumentiert

### Reflexion:

Da ich zuhause schon einigemale mit Docker herumgespielt habe (auf meinem Homeserver), habe ich schon eine bestehende Dockerumgebung auf der ich gearbeitet habe.
Ich werde auch alles mit Kubernetes machen, da ich Docker schon recht gut kenne und es nicht so eine Herausforderung finde.
In desem Block habe ich mit docker und Kubernetes einen hello Wold Container erstallt, jedoch musste ich für das zuerst noch einen Kubernetes Cluster erstllen, sonst kann man garnichts mit Kubernetes machen.

Ich habe zusätzlich versucht einen Webserver mit einer verbunden DB zum laufen zu bringen, jedoch habe ich es nur geschaft einen nginx zumlaufen zu bringen. Container in Kubernetes zu verknüfen da steige ich noch nicht ganz durch.

Hedoch habe ich nur mit Docker schon ihn einem früheren Projekt einen Wordpress und Mysql zusammen per Kompose zum laufen gebracht.

### Doku:

Siehe Screenshots.

## K4

Sicherheitsaspekte sind implementiert
- Service-Überwachung ist eingerichtet
- Aktive Benachrichtigung ist eingerichtet
- mind. 3 Aspekte der Container-Absicherung sind berücksichtigt
- Sicherheitsmassnahmen sind dokumentiert (Bezug zur eingerichteten Umgebung ist vorhanden)
- Projekt mit Git und Markdown dokumentiert


### Reflexion:

Da Kubernetes den der Orchestrator für Docker ist übernimmt dieser auch den Security Teil, über den Habe ich micht auf der Kubernetes seite schlau gemacht: https://kubernetes.io/docs/tasks/administer-cluster/securing-a-cluster/

## K5

Zusätzliche Bewertungspunkte allgemein
Allgemein
- Kreativität
- Komplexität
- Umfang
Umsetzung eigener Ideen
- Übungsdokumentation als Vorlage für Modul-Unterlagen erstellt 
Persönlicher Lernentwicklung
- Vergleich Vorwissen - Wissenszuwachs
- Reflexion

### Reflexion

Wie schon erwähnt habe ich schon in der Arbeit/ Zuhause und auch in der Schule einige Sachen mit Docker gemacht, darum wollte ich mehr Erfahrungen mit Kubernetes sammeln.
Gerlent habe ich als erstes mit den kubectl Befehlen einen Cluster zu erstellen und einzele Container zu erstellen, nacher habe ich mich noch einbischen auseinander gesetzt wie ich den nginx den ich per Komandozeile erstellt habe, wie ich das per yaml file erstllen kann.

### Doku:

Siehe Screenshots und deployment yaml.

## K6

Zusätzliche systemtechnische Bewertungspunkte
- Umfangreiche Vernetzung der Container-Infrastruktur (Ansätze für reale Nutzungszenarien)
- Image-Bereitstellung
- Continuous Integration
- Cloud-Integration
- Elemente aus Kubernetesübung sind dokumentiert
