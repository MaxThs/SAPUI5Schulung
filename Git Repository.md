# Git Repository

Als letztes könnt ihr noch euer Programm als Repository in GIT hochladen.

---

## Teil 1: Erstellt das Repository

zuerst erstellen wir das Repositroy auf dem BAS.
1. Geht über die Console in euer Projekt und gebt git init ein. Dies initialisiert euer Repository. Schaut das ihr im richtigen Ordner seid. Wenn ihr noch auf Project seid, werden alle Programme in das Repository gebracht.
2. Anschließend seht ihr auf der linken seite einen Reiter der nun eine Zahl beinhalten sollte. Dort könnt ihr zur grafischen Übersicht des Repositories.

---

## Teil 2: Remote

Um das ganze zu pulishen brauchen wir ein Remote auf Github das iwr mit unserem Repository verbinden wollen.
1. Geht in euer Github und erstellt ein neues Repository. Benennen könnt ihr es wie ihr wollt.
2. Kopiert den HTTP Lik zum Repositroy und geht zurück zum BAS.
3. Dort könnt ihr auf der grafischen Anzeige euer Repository anzeigen und über die drei punkte in der oberen rechten Ecke weiternavigieren. Wählt die option Remote->Addremote aus.
4. Nun gebt ihr den Link an den ihr kopiert habt.
5. BAS wird euch darum bitten SAP den Zugriff auf das Repository zu geben. Dafür kommt ein Popup mit einem 8 Stelligen Code. Freundlicherweiße bietet das popup auch direkt einen Button an um auf Github zu wechseln und den Code gleichzeitig zu kopieren. Tut dies und gebt den Code ein.
6. Anschließend wird noch nach eurem passwort gefragt.
7. Dann kommt die Frage wie das Remote genannt werden soll. Gebt hier einfach remote an. Dies hat nur den Grund das ihr mehrere Remotes dem repository hinzufügen könntet.
8. Zuletzt bekommt ihr am oberern Rand die Abfrage ob ihr die Verifizierung direkt iM BAS als Plain text abspeichern wollt. Dies könnt ihr gerne tun, wenn ihr plant später nocheinmal zurpck zu kommen. Ansonsten müsst ihr euch bei jeder Session authentifizieren

---

## Teil 3: Commit

Als Letztes müsst ihr eure Änderungen noch commiten und pushen.
1. Über der Liste an changes seht ihr ein + mit dem Tooltip Stage all changes. Drückt darauf. Dies ist wichtig, da nur Changes die gestaged sind auch im Commit gespciehrt werden.
2. Gebt  eine Commit Nachricht ein- Wenn ihr dies nicht macht, kommt ein weiterer Reiter bei dem ihr die Commit nachricht eingeben und in der oberern linken Ecke dann per Häckchen bestätigen. müsst.
3. Wählt dann neben dem Commit den Pfeil aus um das Dropdown zu öffnen. Nicht auf Commit direkt drücken.
4. Hier wählt ihr den Punkt commit&push aus. Solltet ihr commit direkt gedrückt haben, müsst ihr über die drei Punkte gehen und die option Pull/Push->Push zusätzlich die Daten auf das Repositor pushen.
5. Anschließend sollte eine Abfrage komen das der Branch noch nicht im Remote existiert und ob er angelegt werden soll. Dies könnt ihr mit ja abschließen.
