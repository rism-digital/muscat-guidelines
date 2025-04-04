### Elektronische Lokalisierung und Zugriff (856)

Das Feld **Externe Ressource** wird verwendet, um auf eine externe Ressource zu verlinken, die eine direkte Verbindung zu der beschriebenen Quelle hat.

#### Elektronische Lokalisierung und Zugriff (856 $u)

Geben Sie die URL ein. Geben Sie nur eine URL pro Feld ein. Alle URLs müssen mit **http** oder **https** beginnen. Immer Permalinks verwenden.

#### Für das Publikum bestimmte Fussnote (856 $z)

**Pflichtfeld, wenn Sie einen Link auf eine externe Ressource eingeben.**

Geben Sie eine kurze Beschreibung zur Erläuterung, warum die URL für die beschriebene Quelle relevant ist. Verwenden Sie Ihre Katalogisierungssprache.

##### Beispiele

- Digitalisat
- Wasserzeichen auf S. 4
- Projektseite
- Details der Bindung
- Bibliographischer Eintrag
- Link zu Bach Digital
- Link zum Thematischen Katalog Frescobaldi Online
- Eintrag im Kirchenregister


#### Linktyp (856 $x)

**Pflichtfeld, wenn Sie einen Link auf eine externe Ressource eingeben.**

Folgende Angaben sind möglich:

- **Notendigitalisat**: Der Link führt zu einer externe Webseite mit einer digitalisierten Version der im Titel vorliegenden Quelle. Bevorzugt wird immer die digitale Sammlung der besitzenden Institution, dann externe Repertorien (Internet Archive oder IMSLP). Bei Sammlungen ist es nicht notwendig, den Lihk in den Teileinträgen zu wiederholen.
 - Beispiel  
   [https://mirador.acdh.oeaw.ac.at/musikarchivspitz/A-SPD\_A15/](https://mirador.acdh.oeaw.ac.at/musikarchivspitz/A-SPD_A15/)
- **IIIF-Manifest (digitalisierte Quelle)** und **IIIF-Manifest (sonstige)**: Das verknüpfte Objekt ist ein maschinenlesbares JSON-Objekt. IIIF-Links sollten nur zum Manifest und nicht zu einem digitalen Surrogat gehören. IIIF-Manifeste zeigen das Bild nicht an, sondern bestehen aus maschinenlesbarem Text, der von einem internen Dokumentenbetrachter wie diva.js verarbeitet werden muss, bevor es ein aussagekräftiges Bild anzeigt. Wenn Sie das Manifest in einem Web-Browser ansehen, beginnt es mit der geschweiften Klammer {. Das Dokument ist direkt in die Webseite eingebettet. In vielen Fällen erscheint "manifest", "iiif" oder ähnliches im Link.   
  **IIIF-Manifest (digitalisierte Quelle)** sollte verwendet werden, wenn das Manifest einen digitalen Ersatz für die beschriebene Quelle darstellt.  **IIIF-Manifest (sonstige)** sollte verwendet werden, wenn das Manifest ein anderes Element als die vollständige Quelle repräsentiert, wie zum Beispiel ein Wasserzeichen.
 - Beispiel [https://iiif.lib.harvard.edu/manifests/drs:2820650](https://iiif.lib.harvard.edu/manifests/drs:2820650)

 Wenn sowohl Links zu einem externen Dokumentbetrachter als auch ein IIIF-Manifest verfügbar sind, wiederholen Sie das Feld und führen Sie beide Links einzeln auf.
 - Beispiele
   - Externe Ressource: [http://nrs.harvard.edu/urn-3:FHCL.Loeb:537966](http://nrs.harvard.edu/urn-3:FHCL.Loeb:537966)  
     Fußnote: Digitalisat  
     Linktyp: Quellendigitalisat
   - Externe Ressource: [https://iiif.lib.harvard.edu/manifests/drs:2820650](https://iiif.lib.harvard.edu/manifests/drs:2820650)  
     Fußnote: IIIF-Manifest (digitalisierte Quelle)  
     Linktyp: IIIF-Manifest

- **Sonstige**: Link zu anderen Ressourcen, die nicht die beschriebene Quelle darstellen.

#### Arten von externen Ressourcen

**Link Typ 856 $x: Digitalisierte Quelle**  
Link nur auf die im RISM-Eintrag beschriebene Quelle. Verwenden Sie nur Permalinks. Stehen keine Permalinks zur Verfügung, können Sie auf eine Seite verlinken, auf der der Link zur digitalisierten Quelle leicht zu finden ist (z. B. ein Datensatz in einem Bibliothekskatalog). Sie können auch Teile der digitalisierten Quelle (z. B. einige Seiten) angeben, wenn keine vollständig digitalisierte Version verfügbar ist.

**Linktyp 856 $x: Sonstiges**  
Andere Arten von externen Ressourcen können Folgende sein. Stellen Sie sicher, dass dem Benutzer klar ist, warum ein Link aufgenommen wurde, z. B. durch eine **Bemerkung (500)**.

- **Details zur Quelle**  
  Angaben zur Quelle, die nur bestimmte Aspekte berücksichtigen, wie Wasserzeichen, Einband, Titelseite oder Umschlag.
- **Katalogeinträge/Datenbanken**  
  Enthält bibliographische Einträge in externen Katalogen oder Einträge in externen Datenbanken. Externe wissenschaftliche Datenbanken, die nützliche Informationen liefern, können einbezogen werden, aber überlegen Sie, ob man sie nicht besser als Sekundärliteratur verknüpfen sollte.
- **Elektronische Werkverzeichnisse, Online-Lexika, digitalisierte Parallelquellen**  
  Verwenden Sie in der Regel die Felder **Sekundärliteratur (691)** oder **Werkverzeichnis (690)**, um auf Online-Nachschlagewerke wie Werkverzeichnisse oder Enzyklopädien zu verweisen. Für den Benutzer kann es jedoch hilfreich sein, zusätzlich einen direkten Link zu einem bestimmen Ort innerhalb der Ressource über das Feld 856 einzubinden.
- **Archivquellen, historische Quellen**  
  Dazu gehören digitalisierte Stadtregister oder -Dokumente, digitalisierte Korrespondenz, historische Zeitungen. Stellen Sie sicher, dass die Relevanz der Archivquelle zunächst in einer allgemeine **Bemerkung (500)** deutlich wird, und fügen Sie hier den direkten Link hinzu. Bei historischen Zeitungen sollten Sie den Namen der Zeitung als Sekundärliteratur eingeben, aber Sie können auch auf die spezielle Seite verlinken, auf der sich der Artikel hier befindet; stellen Sie sicher, dass Informationen über den Artikel, wie z. B. Titel und Datum, in einer Bemerkung enthalten sind.
- **Webseiten**  
  Umfasst Projekt-Webseiten, Webseiten externer Geldgeber oder andere relevante Webseiten.
- **Andere RISM-Datensätze**  
  Verlinken Sie nur dann auf einen anderen RISM-Datensatz, wenn der Datensatz einen direkten Bezug zu der beschriebenen Quelle hat. Verwenden Sie nur Permalinks. Dem Benutzer sollte klar sein, warum der Datensatz für die Quelle relevant ist. Nennen Sie mindestens die besitzende Bibliothek, die Signatur und die RISM ID Nummer in einer Bemerkung. Manchmal kann eine Verbindung zu einer anderen Quelle besser in einer allgemeinen **Bemerkung (500)** erklärt werden.   
  Wenn Sie an anderer Stelle in Ihrem Datensatz auf andere RISM-Datensätze verweisen, ist es nicht erforderlich, in diesem Feld darauf zu verweisen.  
  Es ist nicht notwendig, hier auf alle übereinstimmenden Quellen in RISM zu verweisen, da die Zahl der Quellen in Muscat täglich wächst.
- **Verweise auf relevante Quellen in anderen Bibliotheken, nicht in RISM**  
  Wenn Sie auf eine Quelle verweisen möchten, die noch nicht in RISM enthalten ist, prüfen Sie, ob es für Ihre Arbeitsgruppe möglich ist, zuerst das digitalisierte Libretto, Manuskript oder die Abhandlung einzugeben oder Exemplare zu einem bestimmten Druck hinzuzufügen. Die Zentralredaktion hilft Ihnen gerne weiter, wenn Sie der Meinung sind, dass eine Quelle in RISM verzeichnet sein sollte. Sie kann aber in diesem Fall keinen neuen Datensatz für die Quelle erstellen.
- **Andere relevante Quellen**  
  Umfasst konkordante Quellen, konkordante Werke, konkordante Arien oder Werkteile, Quellen, die als Grundlage für die beschriebene Quelle dienten. Solche Links können zu den digitalisierten Objekten oder zu externen Katalogen führen.
