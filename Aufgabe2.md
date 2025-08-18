# Aufgabe 2 View erweitern

Hier sollt ihr jetzt im Frontend weiter Objekte hinzufügen, die wir in Aufgabe 3 dann befüllen.

---

## Teil 1: Container hinzufügen

**Beschreibung:**  
>🟩 Fügt einen Container um eure Tabelle und die FilterBar hinzu. Diese sollte am besten individuell verschiebbar sein. Schaut ob ihr was passendes findet. Ansonsten schaut in die Hinweise. <br>

Hints:
<details>
  <summary>Welches Objekt sollte man nutzen</summary>
  <blockquote>
  Nutzt den Splitter Container dafür. Folgt folgendem <a href="https://sapui5.hana.ondemand.com/#/entity/sap.ui.layout.ResponsiveSplitter">link</a>.
  </blockquote>
  <details>
  <summary>Wie funktioniert der Splitter</summary>
    <blockquote>
    Ihr habt drei Teile. Einmal den Splitter selbst. hier werden Kopfdaten festgehalten. Der Container beinhaltet dann immer ein paar an SplitPanes die verschoben werden können. Die wiederum sind dann eure Objekte die alle weiteren XML Objekte beinhalten.
    </blockquote>
  </details>
</details>

---


## Teil 2: Füge den HTML Container hinzu

**Beschreibung:**  
>🟩 Füge nun in den anderen bereich einen HTMl Container hinzu, in dem ihr eine HTML Seite anzeigen könnt. Das passende Objekt kann dabei ein ganz einfaches Objekt sein.<br>
<details>
  <summary>Welches Objekt sollte man nutzen</summary>
  <blockquote>
  Nutzt ein einfache Panel dafür. Hier könnt ihr den Inhalt später selbst definieren. Folg diesem <a href = "https://sapui5.hana.ondemand.com/#/entity/sap.m.Panel" >link </a>
  </blockquote>
</details>


---

##Häufige Fehler
 <details>
  <summary>Fehlende ID</summary>
    <blockquote>
    Jedes Objekt in der View braucht eine ID, auch der Container und der Splitter. Wenn ihr das nicht haben wollte, müsst ihr das in der Manifest ausschalten. Dies würde ich aber vorzugsweise erst mal sein lassen. 
    </blockquote>
  </details>
