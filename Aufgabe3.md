# Aufgabe 3 Controller anpassen

Eure letzte Aufgabe ist es jetzt eine HTML Seite in eueren Container auf dem Frontend zu laden. Dies kann statisch in der View gemacht werden indem wir den content per Hand füllen, oder Dynamisch im Coding. Aus Zeitgründen werden wir das ganze zwar Statisch machen, aber trotzdem im Coding, damit ihr auch mit dem Controller mal zu tun hattet.

---

## Teil 1: Macht euch mit dem Controller vertraut.
**Beschreibung:**  
>🟩 Öffnet den Controller und schaut ihn euch erst einmal an. Dieser besteht aktuell aus einem Definitionsbereich, in dem die Controller Library in den Namensraum "Controller" geladen wird und einer einzigen vordefineirten Methode onInit. Diese Methode wird vom Framework beim Aufbau der Seite aufgerufen und ist gut geeignet um Daten vorzubereiten.
>
---

## Teil 2: Frontend Objekt beziehen

**Beschreibung:**  
>🟩 Versucht im Controller euch einen Bezug zum Frontend Objekt zu holen. Schaut ob ihr eventuell Infos dazu im Demo Kit findet. Wenn nicht nutzt die Hints nach und nach.<br>
> Achtung: Schaut das ihr die Variablen richtig benahmt. Ein Objekt zum Beispiel wird immer mit einem führenden kleinen o angegeben, also zum Beispiel oTable, wenn ihr euch die Table vom Frontend holt. Strings dagegen mit einem s.

Hints:
<details>
  <summary>Wie kann ich ein Objekt aus dem Frontend beziehen</summary>
  <blockquote>
  Dies geht immer über die Funktion byId() des Controllers. Achtet immer auf die groß und Kleinschreibung.
  </blockquote>
  <details>
  <summary>Wie kann ich eine Funktion des Controllers ausführen</summary>
    <blockquote>
    Ihr seid im Controller. Verweißt einfach mit this auf den Controller. Bedeutet schreibt this.byId()
    </blockquote>
  </details>
  <details>
  <summary>Was muss ich als Parameter mitgeben</summary>
    <blockquote>
    Schreibt als Parameter die ID eures Frontendobjektes als String rein.
    </blockquote>
  </details>
</details>
  <details>
  <summary>Wie speichere ich mir das Objekt weg</summary>
    <blockquote>
    Nutzt dafür eine Konstante. Dies könnt ihr mit const oPanel machen. 
    </blockquote>
  </details>
  

  ---

  ## Teil 3: Library laden

  **Beschreibung:**
  >🟩 Ladet die Library für HTML vor. Ihr findet genauere Infos in der API Referenz. Wir reden dabei von der Core HTML Library. Schaut euch aber auch gerne nach Samples um. <br>
  >Achtung: Das erste Beispiel in den Samples macht alles nur in der View, nicht im Controller.

Hits:
  <details>
  <summary>Wie muss ich die Library laden</summary>
    <blockquote>
    Im Controller muss man erst im define den Pfad zur Library angeben und dann in der function einen Namen für die Referenz vergeben.
    </blockquote>
    <details>
      <summary>Wie ist der Pfad zur Library</summary>
      <blockquote>
         "sap/ui/core/HTML"
      </blockquote>
      <details>
        <summary>Wie sieht der Aufbau jetzt genau aus</summary>
        <blockquote>
            sap.ui.define([
            "sap/ui/core/mvc/Controller",
            "sap/ui/core/HTML"
            ], (Controller,HTML) => {
            ...
        </blockquote>
      </details>
    </details>
  </details>

  ---

  ## Teil 4: HTML erstellen und verbinden

  **Beschreibung:**
  >🟩 Dies ist nun der größte Teil. Erstelle neues HTML und gib dies an das Panel. Schau in den Beispielen ob du herausfindest was du machen musst.<br>
>Wenn ihr es einfach wollt, nehmt einfach folgenden Inhalt
 
  <details>
  <summary>Inhalt</summary>
    <blockquote>
    &lt;h1&gt;Glückwunsch, du hast es geschafft.&lt;/h1&gt;
    </blockquote>
  </details>


Hints:
  <details>
  <summary>Wie erstell ich ein neues HTML</summary>
    <blockquote>
    über den Befehl "new" kannst du eine neue Instanz von einem Objket erzeugem
    </blockquote>
    <details>
    <summary>Welche parameter brauche ich</summary>
      <blockquote>
      Du musst als erstes eine ID mitgeben und anschließend in Klammern den content und preferDOM : false.
      </blockquote>
      <details>
        <summary>Was muss in den Content</summary>
        <blockquote>
        Schreib in Content den oben angegeben Text als String oder such dir was eigenes raus.
        </blockquote>
      </details>
      <details>
        <summary>Was brauche ich als ID</summary>
        <blockquote>
        Eine ID musst du dir erstellen. Nutze die Controller Funktion createId() und vergib einen einfachen Namne als String
        </blockquote>
      </details>
    </details>  
  </details>
  <details>
  <summary>Wie füge ich jetzt die HTML dem Frontend hinzu</summary>
    <blockquote>
    Bei einem Panel gibt es die Möglichkeit die Funktion addContent() auszuführen
    </blockquote>
  </details>

