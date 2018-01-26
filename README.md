# Training

## console + xml

Neues Projekt anlegen mit `dotnet new console`. Einlesen der Datei mit XDocument.Load (using System.Xml.Linq) vom web oder von einer lokalen datei. 

Zuerst machma ah consolen anwendung de einfach eine XML Datei einliest. (XML Datei von https://www.w3schools.com/xml/simple.xml)
  1. Ausgabe wieviele foods im breakfast_menu sind
  2. Ausgabe der calories addiert
  3. Füge ein zusätliches food hinzu und speichere die Datei Lokal

## asp.net core rest api

Neues Projekt anlegen mit `dotnet new webapi`.

  1. Nun bauen wir einen Controller der Foods zurück gibt. Fürs erste nur eine einfache liste mit objekten.
  2. Nun tauschen wir die liste der objekte mit einer datenbank aus die lokal oder in der cloud läuft und uns das speichern von foods ermöglicht.
  3. Postman installieren und Food objekte erstellen

## JavaScript Anwendung das die rest api verwendet

  Erstelle Javascript anwendung die auf den webservice von vorher zugreift
