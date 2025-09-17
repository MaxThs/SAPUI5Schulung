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
    Ihr habt zwei Bereiche. Einmal den Splitter mit den Tags ResponsiveSplitter selbst. Hier werden Kopfdaten festgehalten die für die Verarbeitung des Splitterfunktionen notwendig sind. Und dann noch der Container. Dieser beinhaltet wiederum SplitPanes, die eure XML Objekte kapseln. Diese SplitPanes bilden die einzelnen Bereiche die ihr per Splitter größer und kleiner schieben könnt. Im Container wird dann die ausrichtung definiert.
    </blockquote>
     <details>
  <summary>Welche Daten müsst ihr eintragen</summary>
    <blockquote>
    Wie immer sind die IDs zwangsweise notwendig. Zusätzlich könnt ihr auf dem Kopf die defaultPane eintragen und beim Container die Ausrichtung. Schaut das ihr hier Horizontal nehmt.
    </blockquote>
  </details>
  </details>
</details>

---


## Teil 2: Füge den HTML Container hinzu

**Beschreibung:**  
>🟩 Füge nun in den anderen bereich einen HTMl Container hinzu, in dem ihr eine HTML Seite anzeigen könnt. Das passende Objekt kann dabei ein ganz einfaches Objekt sein.<br>
<details>
  <summary>Welches Objekt sollte man nutzen</summary>
  <blockquote>
  Nutzt ein einfache Panel dafür. Hier könnt ihr den Inhalt später selbst definieren und er kann in belibigen Format vorliegen. Ihr brauch also kein eigenes HTML Objekt. Folg diesem <a href = "https://sapui5.hana.ondemand.com/#/entity/sap.m.Panel" >link </a>
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
