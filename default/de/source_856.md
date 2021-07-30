### Elektronische Lokalisierung und Zugriff (856)

Verlinkung einer elektronischen Ressourcen der vorliegenden Quelle.

**Uniform Resource Identifier (856 $u)**

Angabe einer persistenten URL.

**Für das Publikum bestimmte Fußnote (856 $z)**

Pflichtfeld, wenn Sie einen Link zu einer externen Ressource eingeben.   
Geben Sie eine kurze Beschreibung zur Erläuterung, warum die URL für die beschriebene Quelle relevant ist. Verwenden Sie Ihre Katalogisierungssprache.

_Beispiele:_  
Digital copy  
Wasserzeichen auf p. 4  
Projektwebseite  
Detail of binding  
Bibliographic record  
Link to record in Bach Digital  
Link zum Werk in Frescobaldi Thematic Catalogue Online  
Entry in the church registry  
Link to RISM ID no. 806155758, GB-Lbl Add. 14209 f.23r-27v, a setting by N. Porpora of this text   
Parallelquelle in GB-Ob

**Linktyp (856 $x)**  
Pflichtfeld, wenn auf eine elektronischen Ressource verlinkt wird. Wählen Sie eine Option aus dem Auswahlmenü:

- **Notendigitalisat** : Der Link führt zu einer externe Webseite mit einer digitalisierten Version der im Titel vorliegenden Quelle.   
Bevorzugt wird immer die digitale Sammlung der besitzenden Institution, dann externe Repertorien (Internet Archive oder IMSLP). Bei Sammlungen ist es nicht notwendig, den Lihk in den Teileinträgen zu wiederholen.  
_Beispiel_ :  
[https://mirador.acdh.oeaw.ac.at/musikarchivspitz/A-SPD\_A15](https://mirador.acdh.oeaw.ac.at/musikarchivspitz/A-SPD_A15/)  

- **IIIF manifest** : Das verknüpfte Objekt ist ein maschinenlesbares JSON-Objekt, das von einem internen Dokumentbetrachter wie diva.js verarbeitet wird. Das Dokument ist dirket in die Webseite eingebettet. In vielen Fällen erscheint "manifest", "iiif" oder Ähnliches im Link.  
_Beispiel_:  
[https://iiif.lib.harvard.edu/manifests/drs:2820650](https://iiif.lib.harvard.edu/manifests/drs:2820650)

Wenn sowohl Links zu einem externen Dokumentbetrachter als auch ein IIIF-Manifest verfügbar sind, wiederholen Sie das Feld und führen Sie beide Links einzeln auf.  
_Beispiel_:

- **Externe Ressource** : [http://nrs.harvard.edu/urn-3:FHCL.Loeb:537966](http://nrs.harvard.edu/urn-3:FHCL.Loeb:537966)  
**Fußnote** : digitized version  
**Linktyp** : digitized source
- **Externe Ressource** : [https://iiif.lib.harvard.edu/manifests/drs:2820650](https://iiif.lib.harvard.edu/manifests/drs:2820650)  
**Fußnote** : IIIF manifest  
**Linktyp** : IIIF manifest  
  

- **Sonstiges** : Link to other resources that are not the resource being described.

#### Arten von externen Ressourcen

**Linktyp 856 $x: Quellendigitalisat**  
Verlinken Sie nur auf die im RISM-Datensatz beschriebenen Quelle. Verwenden Sie nur Permalinks. Stehen keine Permalinks zur Verfügung, können Sie auf eine Seite verlinken, auf der der Link zur digitalisierten Quelle leicht zu finden ist (z. B. ein Datensatz in einem Bibliothekskatalog). Sie können auch Teile der digitalisierten Quelle (z. B. einige Seiten) angeben, wenn keine vollständig digitalisierte Version verfügbar ist.

Als Quellendigitalisat gekennzechnete Links erscheinen im Filter "Digitilisate" im OPAC (opac.rism.info).

**Linktyp 856 $x: Sonstiges**

Andere Arten von externen Ressourcen können Folgende sein. Stellen Sie sicher, dass dem Benutzer klar ist, warum ein Link aufgenommen wurde, z. B. durch eine **Bemerkung (500)**.

- **Details der Quelle**  
Angaben zur Quelle, die nur bestimmte Aspekte berücksichtigen, wie Wasserzeichen, Einband, Titelseite oder Umschlag.
- **Katalogeinträge/Datenbanken**  
Enthält bibliographische Einträge in externen Katalogen oder Einträge in externen Datenbanken. Externe wissenschaftliche Datenbanken, die nützliche Informationen liefern, können einbezogen werden. Bitte prüfen Sie vorab, ob eine Eintrag als Sekundärliteratur evtl. besser ist.
- **Elektronische Werkverzeichnisse, Online-Lexika, digitalisierte Parallelquellen**  
Verwenden Sie im allgemeinen die Felder **Literaturverweis (691)** oder **Werkverzeichnis (690)**, um auf Online-Nachschlagewerke wie Werkkataloge oder Enzyklopädien zu verweisen. Für den Benutzer kann es jedoch hilfreich sein, zusätzlich einen direkten Link zu einem bestimmen Ort innerhalb der Ressource über das Feld 856 einzubinden.
- **Archivarische, historische Quellen**  
Dazu gehören digitalisierte Stadtregister oder -Dokumente, digitalisierte Korrespondenz, historische Zeitungen. Stellen Sie sicher, dass die Relevanz der Archivquelle zunächst in einer allgemeine **Bemerkung (500)** deutlich wird, und fügen Sie hier den direkten Link hinzu. Bei historischen Zeitungen sollten Sie den Namen der Zeitung als Sekundärliteratur eingeben, aber Sie können auch auf die spezielle Seite verlinken, auf der sich der Artikel hier befindet; stellen Sie sicher, dass Informationen über den Artikel, wie z. B. Titel und Datum, in einer Bemerkung enthalten sind. 
- **Webseiten**  
Umfasst Projekt-Webseiten, Webseiten externer Geldgeber oder andere relevante Webseiten.
- **Andere RISM-Datensätze**  
Verlinken Sie nur dann auf einen anderen RISM-Datensatz, wenn der Datensatz einen direkten Bezug zu der beschriebenen Quelle hat. Verwenden Sie nur Permalinks aus dem RISM-OPAC ([https://opac.rism.info/](http://)). Dem Benutzer sollte klar sein, warum der Datensatz für die Quelle relevant ist. Benennen Sie mindestens die besitzende Bibliothek, die Signatur und die RISM-ID-Nummer in einer Bemerkung. Manchmal kann eine Verbindung zu einer anderen Quelle besser in einer allgemeinen **Bemerkung (500)** beschrieben werden.   
Wenn Sie an anderer Stelle in Ihrem Datensatz auf andere RISM-Datensätze verweisen, ist es nicht erforderlich, in diesem Feld darauf zu verweisen.   
Es ist nicht notwendig, hier auf alle übereinstimmenden Quellen in RISM zu verweisen, da die Zahl der Quellen in Muscat täglich wächst. 
- **Verweise auf relevante Quellen in anderen Bibliotheken, nicht in RISM**  
Wenn Sie auf eine Quelle verweisen möchten, die noch nicht in RISM enthalten ist, prüfen Sie, ob es für Ihre Arbeitsgruppe möglich ist, zuerst das digitalisierte Libretto, Manuskript oder die Abhandlung einzugeben oder Exemplare zu einem bestimmten Druck hinzuzufügen. Die Zentralredaktion hilft Ihnen gerne weiter, wenn Sie der Meinung sind, dass eine Quelle in RISM verzeichnet sein sollte, kann aber in diesem Fall keinen neuen Datensatz für die Quelle erstellen.
- **Andere relevante Quellen**  
Umfasst konkordante Quellen, konkordante Werke, konkordante Arien oder Werkteile, Quellen, die als Grundlage für die beschriebene Quelle dienten. Solche Links können zu den digitalisierten Objekten oder zu externen Katalogen sein.