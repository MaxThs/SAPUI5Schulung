# Git Repository

Als letztes könnt ihr noch euer Programm als Repository in GIT hochladen.

---

## Teil 1: Erstellt das Repository

Geht dafür über die Console in euer Projekt und gebt git init ein. Dies initialisiert euer Repository. Schaut das ihr im richtigen Ordner seid. Wenn ihr noch au Project seid, werden alle Programme in das Repository gebracht. <br>
Anschließend seht ihr auf der linken seite einen Reiter der nun eine Zahl beinhalten sollte. Dort könnt ihr zur grafischen Übersicht des Repositories.

---

## Teil 2: Remote

Geht in euer Github und erstellt ein neues Repository. Benennen könnt ihr es wie ihr wollt. Kopiert den HTTP Lik zum Repositroy und geht zurück zum BAS.<br>
Dort könnt ihr auf der grafischen Anzeige euer Repository anzeigen und über die drei punkte in der oberen rechten Ecke weiternavigieren. Wählt die option Remote->Addremote aus.<br>
Nun gebt ihr den Link an den ihr kopiert habt. Im folgenden wird euch BAS darum bitten SAP den Zugriff auf das Repository zu geben. Dafür kommt ein Popup mit einem 8 Stelligen Code. Freundlicherweiße bietet das popup auch direkt einen Button an um auf Github
zu wechseln und den Code gleichzeitig zu kopieren. Tut dies und gebt den Code ein. Anschließend wird noch nach eurem passwort gefragt.<br>
Nun kommen zwei Abfragen. Bei der Reihen folge bin ich mir nicht ganz sicher aber es müsste so sein:
Zuerst kommt die Frage wie das Remote genannt werden soll. Gebt hier einfach remote an. Dies hat nur den Grund das ihr mehrere Remotes dem repository hinzufügen könntet.
Zuletzt bekommt ihr am oberern Rand die Abfrage ob ihr die Verifizierung direkt iM BAS als Plain text abspeichern wollt. Dies könnt ihr gerne tun, wenn ihr plant später nocheinmal zurpck zu kommen. Ansonsten müsst ihr euch bei jeder Session authentifizieren

---

## Teil 3: Commit

Als Letztes müsst ihr eure Änderungen noch cimmiten. Über der Liste an changes seht ihr ein + mit dem Tooltip Stage all changes. Drückt darauf. Dies ist wichtig, da nur Changes die gestaged sind auch im Commit gespciehrt werden.
Gebt noch eine Commit nachricht ein und wählt dann neben dem Commit den Pfeil aus um das Dropdown zu öffnen. Hier wählt ihr den punkt commit&push aus. Anschließend sollte eine Abfrage komen das der Branach noch nicht
im Remote existiert und ob er angelegt werden soll. Dies könnt ihr mit ja abschließen.
