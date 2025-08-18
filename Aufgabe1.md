# Aufgabe 1 View erstellen

Willkommen. Hier starten wir mit dem ersten Teil der Aufgaben. Ihr sollt am Ende eine View generiert haben, die aus einer Tabelle mit einer FilterBar besteht.
Ihr Habt die Möglichkeit euch für jeden Teil Hilfen einblenden zu lassen. Wer will kan sich aber auich gerne auf eigeen Faust nur mithilfe des gezeigten SAPUI5 DemoKits durcharbeiten

---

## Teil 1: Table hinzufügen

**Beschreibung:**  
>🟩 Versucht die Tabelle in der View anzuzeigen. Nutzt dafür ein passendes Objekt. <br>

Hints:
<details>
  <summary>Welches Objekt sollte man nutzen</summary>
  <blockquote>
  Am Besten Nutzt ihr eine SmartTable. Diese haben wir bereits angesprochen. Schau dafür in folgenden <a href="https://sapui5.netweaver.ondemand.com/sdk/#/entity/sap.ui.comp.smarttable.SmartTable">link</a>
  </blockquote>
  <details>
  <summary>Welche Felder in der SmartTabel sind wichtig?</summary>
    <blockquote>
    Vorerst sind nur die Felder id, TableType und entitySet wichtig
    </blockquote>
<details>
  <summary>Welchen Table Type verwende ich am Besten</summary>
    <blockquote>
    Nutze die ResponsiveTable. Du kannst in der API Reference der Smarttable nach dem Feld schauen und dort sehen welche Inhalte erlaubt sind.
    </blockquote>
  </details>
    <details>
    <summary>Wo bekomme ich das EntitySet her?</summary>
      <blockquote>
      Am Besten geht das über die metadaten. Hier kannst du per Rechtsklick den Data Editor anzeigen lassen. 
      </blockquote>
    </details>
  </details>
</details>

---

##  Teil 2: Führe die App aus
**Beschreibung:**  
>🟩 Führe App aus und schau was dir angezeigt wird. Nutze dafür die Konsole.<br>
>Navigiere in deinen Order und führe deine App mit "npm start" aus.<br>
>Achtung: Es werden noch keine Daten angezeigt. Das passiert erst nach Teil 3. <br>

Hints:
<details>
  <summary>Wie komme ich in die Konsole.</summary>
    <blockquote>
    Schau in der oberen rechten Ecke nach diesem Symbol <img width="20" height="20" alt="image" src="https://github.com/user-attachments/assets/0f6a4aca-bd57-4756-b5a5-1e43575d45f0" />. 
    Wähle dann im Layout Manager das Panel aus. Dort kannst du die Konsole ansehen.
    </blockquote>
  </details>
<details>
  <summary>Wie navigiere ich in der Konsole in meinen Ordner.</summary>
    <blockquote>
    Wie auch bei Windows oder Linux könnt ihr über den Befehl "cd" in ordner navigieren. schreibt also einfach cd und den namen eures Projektes. mithilfe von Tab wird euch der Name vervollständigt.
    </blockquote>
  </details>
  
---

##  Teil 3: FilterBar

**Beschreibung:**  
>🟩 Füge nun eine Filterbar hinzu. Pass auf das du die Filterbar mit deiner Table verbindest.<br>

Hints:

<details>
  <summary>Welches Objekt nutze ich hier</summary>
    <blockquote>
    Auch hier gibt es das eine Smart Objekt. In dem Fall die SmartFilterBar. Schaun dir diesen <a href ="https://sapui5.netweaver.ondemand.com/sdk/#/entity/sap.ui.comp.smartfilterbar.SmartFilterBar">link</a> an.
    </blockquote>
  <details>
  <summary>Welche Felder muss ich hier nun anzeigen.</summary>
    <blockquote>
    Du benötigst hier nur die id und das Entity Set
    </blockquote>
  </details>
  <details>
  <summary>Was muss ich noch beachten</summary>
    <blockquote>
    Schau das du in der SmartTable jetzt auch einen verweis auf die Smartfilterbar macht. Dafür gibt es das Feld SmartFilterID
    </blockquote>
  </details>
  </details>

---

## Bonus: Fügt ein Variante hinzu
**Beschreibung:**
>🟩 Fügt eine Funktion hinzu um Varianten zu speichern. Heißt wo definiert wird, nach welchen Sachen autoamtisch gefiltert werden oder welche Felder in welcher Reihenfolge angezeigt werden sollen.

Hints:
<details>
  <summary>Welches Objekt nutze ich hierfür.</summary>
    <blockquote>
    Auch hier gibt es wieder etwas von den Smart Objekten, nämlich die SmartVariantManagement. Schau dir den <a href="https://sapui5.hana.ondemand.com/sdk/#/api/sap.ui.comp.smartvariants.SmartVariantManagement%23overview">link</a> dazu an.
      Hier gibt es leider keine direkten Samples. Schau aber mal op ihr dennoch was findest. Vor allem die API hilf eucht sehr.
    </blockquote>
  <details>
  <summary>Welche Felder braucht man</summary>
    <blockquote>
    Das Objekt hat zwei Felder und beide werden benötigt. Aber ihr müsst das Management auch in die FilterBar und die Table eintragen.
    </blockquote>
  </details>
  </details>
  
---

##  Häufige Fehler
<details>
  <summary>Importiert die Libraries</summary>
    <blockquote>
      Wenn ihr die Smarttable oder andere Objekte verwendet, müsst ihr die Libraries im Head der View hinzufügen. Dies macht BAS automatisch, wenn ihr das Objekt mit der Autovervollständigung hinzufügen lasst. 
      Passt dabei aber auf. Die Autovervollständigung ändert Groß und Klein Schreibung im Import, aber nicht im Aufruf. Diese muss aber immer gleich sein.
    </blockquote>
  </details>
  
##  Hilfen Allgemein
<details>
  <summary>Schaut euch den Batch an</summary>
    <blockquote>
    Geht über F12 in die Developertools und wechselt auf Network. Dort Schreibt in den Filter "$batch" rein. Damit seht ihr welche Anfragen an das Backend gesendet wurden 
    </blockquote>
  </details>
  <details>
  <summary>Fehler</summary>
    <blockquote>
    Etwaige Fehler in der Konsole können sehr unübersichtlich wirken. Viele der Fehler könnt ihr ignorieren. Mit der Zeit lernt ihr was relevante Fehler sind.
    </blockquote>
  </details>

---

## ✨ Viel Erfolg beim Lösen der Aufgaben!
