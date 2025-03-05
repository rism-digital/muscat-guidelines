## Suchen

Die **Suche** in Muscat ist über die **Filter** auf der Hauptseite der Quellen möglich. Für eine umfangreichere Suche, einschließlich einer Musikincipit-Suche, verwenden Sie die öffentlichen Kataloge, den [RISM Catalog](https://opac.rism.info/) und [RISM Online](https://rism.online/).

### Muscat-Filter

Der Muscat-**Filter** bietet eine einfache, aber leistungsstarke Suche.

Sie können in jedem Feld eingeben:

- Einzelne Worte
- Mehrere Wörter:  
  entweder ohne Anführungszeichen: **lass noch**   
  oder mit Anführungszeichen: **"lass noch"**
- Trunkierung mit ? oder \*  
  **?**: Das Fragezeichen ersetzt exakt einen Buchstaben. **B?cher** findet Bucher und Bacher.   
  **\***: Das Sternchen kann verwendet werden, um eine beliebige Anzahl von Buchstaben zu kürzen oder zu ersetzen. **B\*cher** findet Bucher und Bacher, aber auch Boucher und Bötticher.
- UND, ODER, NICHT, ( ): Nutzen Sie die Vorteile der booleschen Suche. Verwenden Sie Klammern zur Gruppierung Ihrer Suche. Beispiele:
    - Komponist enthält: **(Bach UND Johann) NICHT Sebastian**  
      Um Johann Michael Bach und Johann Christian Bach zu finden, aber nicht Johann Sebastian Bach
    - Sigel enthält: **D-B UND (I-\* OR F-P\*)**   
      Um alle Drucke in der Bibliothek D-B zu finden, von denen es auch Exemplare in Italien oder Paris gibt

Für alle Abschnitte ist Folgendes zu beachten:

- **Datum**

    - **Suche nach Datum:** Geben Sie die Daten im Format JJJ-MM-TT ein. Standardmäßig ist der Tag auf Mitternacht gesetzt.
    - **Ein einzelnes Datum („von“):** Wenn Sie nur das linke Feld („von“) ausfüllen, erhalten Sie alle Datensätze, die seit diesem Datum geändert wurden oder **seit** diesem Datum erstellt wurden (einschließlich der Datensätze, die im Laufe des Tages an diesem Datum erstellt wurden)   
      . Beispiel: Letzte Änderung   
      **2012-02-07** - [leer]  
      werden alle Datensätze angezeigt, die seit dem 7. Februar 2012 bearbeitet wurden.
    - **Ein einzheolnes Datum ("bis")**: Wenn Sie nur das rechte Feld ("bis") ausfüllen, erhalten Sie alle Datensätze, die **bis** zu diesem Datum um Mitternacht geändert oder erstellt wurden.  
      Beispiel: Letzte Änderung  
      [leer] -  **2012-02-07**  
      wird alle Datensätze abrufen, die seit Beginn des Zeitraums bis zum 7. Februar 2012 um Mitternacht bearbeitet wurden (d. h. Datensätze, die während des Arbeitstages am 7. Februar erstellt wurden, werden nicht berücksichtigt).
    - **Datumsbereich**: Da der Tag auf Mitternacht festgelegt ist, müssen Sie beispielsweise für die Suche nach allen Datensätzen, die am 7. Februar 2012 erstellt wurden, das Startdatum 2012-02-07 (verstanden als Mitternacht des 7. Februar) und das Enddatum 2012-02-08 (verstanden als Mitternacht des 8. Februar) eingeben. Dazu gehören alle Quellen, die im Laufe des Tages erstellt wurden. Eine Suche vom 2012-02-07 bis 2012-02-07 wird zu keinem Ergebnis führen!

Bei der Suche nach **Quellen** sind folgende Punkte zu beachten:

- **Sigel**: Suche nach Buchstaben in einem Sigel. In diesem Feld wird zwischen Groß- und Kleinschreibung unterschieden. Zum Beispiel:  
  **D-*** = alle Quellen in Deutschland  
  **D-B*** = alle Quellen in deutschen Städten, die mit B  
  beginnen ** D-B** = alle Quellen aus der Staatsbibliothek zu Berlin

### Personennamen

Bei der Suche nach **Personen** sind folgende Punkte zu beachten:

- **Name**: Durchsucht die Felder **Ansetzungsform (100 $a)** und **Namensvarianten (400 $a)**.
- **Lebensdaten**: Durchsucht die Felder **Geburts- und Todesdaten (100 $d)**, bedeutet Jahre und die folgenden Abkürzungen: sc a p c \* + /
- **Orte**: Durchsucht das Feld **Ort (551)**. Dazu gehören Geburts-, Sterbe-, Herkunfts- oder Wirkungsorte.
