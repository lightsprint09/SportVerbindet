# SportVerbindet

Viele Menschen haben in den letzten Jahren die Aufmerksamkeit an Sportvereinen verloren. Ein Grund dafür, ist ein intransparentes Angbot von sportlichen Aktivitäten. Diese Projekt versucht einen 4 Stufigen Plan zu umschreiben, der es  Sportvereinen ermöglicht ihr Angebot wieder transparent zu machen.

## Stufe 1

Eine Datenbank der Sportvereine und deren Sportangebote in Deutschland.

Komunen bieten jetzt schon einen guten Überblick der Vereine in einer Stadt. Jedoch ist das Angobte und die Trainingzeiten der Vereine nicht direkt einsehbar. Es fällt schwer nach konkreten Sportangboten zu suchen, ohne bei jedem Verein den ganzen Trainingsplan zu durchsuchen.
Ziel der Datenbank wäre es Suchanfragen wie folgt zu stellen: 
```
Leichtathletik Gruppe im Alter ab 18 Jahre mit Trainingszeiten Montag bis Mittwoch 16:00 - 22:00 Uhr in Frankfurt 
```

## Stufe 2

Parrall zu Stufe 1 wird eine Web Platformen entstehen, die es Vereinen erlaubt, ihr Sportangebot einzutragen. Vereine und Komunen können Teile der WebPlatform auf ihren Websiten einbinden und das Sportangebot nicht doppelt zu plegen. Die Web Platform soll durch eine offenen API gespeißt werden, die für jeden frei zugänglich sein muss.
Die Web Platform soll folgende folgende Kriterien erfüllen.

* Mobil optimiert
* Progressive enhancement
* Barrierefrei
* Apassbarer Stil zum Einbindingen auf externen Websiten

## Stufe 3 (optinal)
Interaktion von Vereinen mit Mitgliedern.

Vereine sollen einen einfach Kanal haben, der Mitglieder über Ereignisse benachrichtet. So können Versammlungen, Trainingsausfälle oder ähnliches Komuniziert werden. Hier geht es nicht darum einen neuen Kanal zu schaffen, sondern bestehende Kanäle(Mail, SMS, WhatsApp, Facebook, etc) zu anzusprechen. 


## Stufe 4 (optinal)
Digitaler Mitgliedsantrag könnete den Eintritt in den Verein vereinfachen.

## Allgemeine Ziele des Projekts

* Schnelle Sportangebote finden
* Inklusiven Gedanken Stärken
* Kein Komerzielles Produkt
* Alle Daten offen zugänglich
* Keine Werbung
* Keine Socialmedia Funktionen


## Technische Aspekte der Datenbank (nicht final)
* Postgres Datenbank
* GraphQL Schnittstelle
* Leichter Export in gänige druckebare Formate (zum verteilen an Mitglieder)

### Verein (nicht final)
* id
* name
* Stadt
### Training (nicht final)
* id
* Sportart
* Altersgruppe
* Trainer
* Zeiten ??
* Trainingsort
* longitude
* latitude
* geschlecht
* telefon
* mail

##
