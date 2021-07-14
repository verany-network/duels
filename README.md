[![Discord](https://img.shields.io/discord/670667590812696623?color=fff&label=Discord&logo=discord&logoColor=fff)](https://discord.gg/Yn9Ws9w6d5)
![Twitter Follow](https://img.shields.io/twitter/follow/VeranyNET?color=919191&label=Folge%20%40VeranyNET&style=social)
![YouTube Channel Subscribers](https://img.shields.io/youtube/channel/subscribers/UCduDElXYi8zPjZMTIxCT45A?label=Abonniere%20VeranyNET&style=social)


Verany Duels Dokumentation
=============

Willkommen zur Dokumentation des Duels Spiels. Hier findet ihr Anleitungen zur Installation, Konfiguration und Weiterentwicklung. Zusätzlich dazu findet ihr hier eine Dokumentation über die Bestandteile des Projektes, darunter zählen zum Beispiel die Branches- und ihre Aufgaben die (wenn vorhanden) Module und weitere wichtige Hinweise, die noch vor dem eigentlichen entwickeln wichtig für euch sein können.

---
## Installation:
Die Installation des Duels Spiels erfolgt über das Klonen in GitHub. Wir empfehlen dir für deine Projekte einen WorkSpace Ordner zu erstellen, in welchem du dann einen GitHub Ordner hast, in welchem widerrum nach Usern oder in unserem Fall Organisationen spezifiziert wird. In diesem Beispiel sieht das dann so aus:

```
D:\Dokumente\WorkSpace\GitHub\verany-network\duels
```

### Das Projekt mit CLI klonen
```ssh
gh repo clone verany-network/duels
```

---
## Deployments & Tests:
Das Testen des Duels Spiels erfolgt auf einem von uns dafür angelegten Mirror Server. Dort könnt ihr die Spigot API / Core voll ausschöpfen ohne euch Sorgen um die User auf unserem Produktions-Server machen zu müssen. Aufrufen könnt ihr diesen Service unter **[demo.verany.net](https://demo.verany.net/mc/duels/)**. Bei einem Klick auf das entsprechende Projekt werdet ihr nach eurem Personal Development Key (PDK) gefragt. Dieser wurde euch bei eurer Teameinführung in dem Einführungsdokument übergeben. Dieser dient hier jetzt zur Identifizierung der Logins / Aktionen und somit auch als Passwort.

Um das Projekt auf eurem Stand überhaupt online zu bekommen müsst ihr jetzt noch den entsprechenden GitHub Workflow ausführen. Eine Auflistung der Workflows und ihre Funktionen findet ihr im Navigationsbereich unter **[Actions](https://github.com/verany-network/skyblock/duels)**.

---
## Branches:
* `production`: Produktionsbuild (Wird automatisch auf die entsprechenden Dienste deployed)
* `release/*`: Release Builds (z.B. `release/2021.7.4`, eine stabil laufende Version benannt nach dem Zeitpunkt)
* `feature/*`: Feature Update Branch (z.B. `feature/stats-update`, für große Updates)
* `dev/*`: Developer spezifischer Branch (z.B. `dev/nicokempe`, für kleine Änderungen und nur temporär ausgelegt)

---
## Lizensierung:
Niemand außer der Administration selbst und dem Nico Kempe Einzelunternehmen steht es zu den geschriebenen Code ohne Erlaubnis zu verwenden. Bei eigenem Einsatz in das Projekt gibt man automatisch alle Rechte an der aufgewendeten Arbeit ab.
