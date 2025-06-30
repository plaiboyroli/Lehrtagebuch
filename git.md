# Git mit Github.com

Git ist ein Version control system bei dem Server und Client Dateien und Programme miteinander synchronisieren.

## Localhost & Git Server


## Signatur und Tokens



## Datenspeicherung in GIT


### Commits
| Befehl | Beschreibung |
| --- | --- |
| git config | Dient zum Abfragen und Setzen von Repository-weiten, Benutzer-weiten oder globalen Optionen. |
| git status | Zeigt den Status der Arbeitskopie und des Staging-Bereichs an. Es listet Änderungen, die committet werden müssen, Änderungen im Arbeitsverzeichnis, die nicht gestaged sind, und Dateien, die von Git nicht verfolgt werden. |
| git log |Zeigt die Commit-Historie an.|
| git reset | Setzt den HEAD auf einen bestimmten Zustand zurück. Dies kann verwendet werden, um Commits rückgängig zu machen oder Änderungen aus dem Staging-Bereich zu entfernen. |
| git add | Fügt Dateiinhalte zum Index hinzu. Dies ist der erste Schritt im Git-Workflow: Dateien für den nächsten Commit "stagen". |
| git commit | Speichert die gestagten Änderungen dauerhaft im Repository. |
| git push | Lädt lokale Commits auf ein Remote-Repository hoch. |



### Remote Repository

| Befehl | Beschreibung |
| --- | --- |
| git fetch | Lädt Objekte und Referenzen von einem anderen Repository herunter. Es ruft die neuesten Änderungen vom Remote-Repository ab, ohne sie in den lokalen Arbeitsbaum zu integrieren. |
| git clone |Klont ein Repository in ein neues Verzeichnis. Es wird eine vollständige Kopie eines bestehenden Git-Repositories erstellt.|
| git init |Erstellt ein leeres Git-Repository oder reinitialisiert ein bestehendes. Dies ist der erste Befehl, der ausgeführt wird, wenn man ein neues Git-Projekt starten möchte.|
| git remote |Verwaltet die Menge der Remote-Repositorys, deren Lesezeichen im Repository gespeichert sind.|

### Commit, Branch und Work Tree


