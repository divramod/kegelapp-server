Aufgabe 1 (2 Punkte)
====================

Erstellen Sie einen Server (das Backend / die API) für die Kegelapp.
Nutzen Sie dazu das NodeJs-Framework koa und dabei im Speziellen die koa api-boilerplate.(1) 
Installieren Sie sich dazu alle notwendigen Bibliotheken auf Ihrem Linux-System.
Da ein gemeinsames Arbeiten wichtig ist, sollen Ihre Arbeiten mittels git unter dem Repository kegelapp-server (2) abrufbar sein.

Um mit der Arbeit zu starten müssen Sie das Repository lokal clonen.
Nachdem Sie das Repository geklont haben, erstellen Sie einen eigenen git-Branch mit dem Namen Andy in dem Sie programmieren. Ihre Ergebnisse sollen unter dem Ordner api-andy im Repository abgelegt werden.

Hinweis 1: Koa (3) läuft aktuell nur mit NodeJs-Versionen >= 0.11.11 unter dem --harmony flag.
Hinweis 2: im Repository kegelapp-server befindet sich schon ein ordner api-arvid. dieser beinhaltet ein schon funktionierendes Beispiel für die Koa-Api-Boilerplate. 
Hinweis 3: Um das Koa-Api-Boilerplate-Beispiel lauffähig zu machen müssen Sie auch Reddis installieren.
Hinweis 4: für die Selektion einer NodeJS-Version gibt es das Tool n

Anforderungen / Funktionen an den Server
----------------------------------------
- nutzen Sie curl um die API zu testen (search curl)
- Speichern Sie die im Ordner data vorliegenden .json-Dateien in der MongoDB-Datenbank:
  - game
  - user
  - player (Spieler)
  - club (Verein)
  - alley (Spielort)
- Datenhaltung Aufgaben
  - Erstellen Sie ein Entity-Relationship-Modell für das Problem Kegelapp. Entnehmen Sie die Entitäten aus den Beispieldaten.
  - Prüfen Sie, ob das JSON in den Dateien valide ist (4)
  - Fügen Sie den Dateien weitere Beispieldaten hinzu
  - nutzen Sie mongoDB zur persitenten Speicherung von Daten (search mongoDB)
    - nutzen Sie mongoose als ORM (Object Relational Mapper)
  - speichern Sie die unter dem Ordner data vorliegenden Daten auch in einer mysql Datenbank
    - nutzen Sie auch hier einen ORM (Object Relational Mapper)
- Nutzen Sie die Sprache Englisch während des Programmierens im Projekt. also englische Funktionsname, Variablenname, Dateinamen, Ordnername, etc
- Nutzen Sie Passport (5) zur User-Authentizierung (search koa und passport)

Quellen
----------------------------------------
1 https://github.com/koajs/api-boilerplate.
2 https://github.com/divramod/kegelapp-server
3 https://github.com/koajs/koa
4 http://www.jslint.com/ 
5 http://passportjs.org/

