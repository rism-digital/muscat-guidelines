### Elektronische Lokalisierung und Zugriff (856)

Das Feld **Externe Ressource** wird verwendet, um auf eine externe Ressource zu verlinken, die eine direkte Verbindung zu der beschriebenen Quelle hat.

#### Elektronische Lokalisierung und Zugriff (856 $u)

Geben Sie die vollständige URL der externen Ressource ein. Immer Permalinks verwenden.

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
- **IIIF-Manifest (digitalisierte Quelle)** und **IIIF-Manifest (sonstige)**: Das verknüpfte Objekt ist ein maschinenlesbares JSON-Objekt. IIIF links should only be to the manifest, not to a digital surrogate. IIIF manifests do not display the image but rather consist of machine-readable text that must be processed by an internal document viewer such as diva.js before it displays a meaningful image. When viewing the manifest in a web browser, it will start with the curly bracket {. The document is embedded in the web page directly. In many cases, "manifest," "iiif," or similar appears in the link.   
  **IIIF manifest (digitized source)** should be used when the manifest represents a digital surrogate of the source being described.  **IIIF manifest (other)** should be used when the manifest represents an element other than the full source, such as a watermark.
 - Example [https://iiif.lib.harvard.edu/manifests/drs:2820650](https://iiif.lib.harvard.edu/manifests/drs:2820650)

 In cases where both links to an external viewer and an IIIF manifest are available, repeat the field and list both links separately.
 - Examples
   - External resource: [http://nrs.harvard.edu/urn-3:FHCL.Loeb:537966](http://nrs.harvard.edu/urn-3:FHCL.Loeb:537966)  
     Note: digitized version  
     Link type: digitized source
   - External resource: [https://iiif.lib.harvard.edu/manifests/drs:2820650](https://iiif.lib.harvard.edu/manifests/drs:2820650)  
     Note: IIIF manifest  
     Link type: IIIF manifest

- **Other**: Link to other resources that are not the resource being described.

#### Kinds of external resources

**Link type 856 $x: Digitized source**  
Link only to the source being described in the RISM record. Only use permalinks. If permalinks are unavailable, you may link to a page where the link to the digitized source can be easily found (such as a bibliographic record in a library catalog). You may include portions of the digitized source (such as a few pages) if a fully digitized version is not available.

**Link type 856 $x: Other**  
Other kinds of external resources can include the following. Make sure it is always clear to the user why a link is being included, such as in a **General note (500)**.

- **Details of sources**  
  Details of sources that only present certain aspects, such as a watermark, binding, title page, or cover.
- **Catalog records/Databases**  
  Includes bibliographic entries in external catalogs or entries in external databases. External scholarly databases that provide useful information might be included, but consider whether they might be better linked as secondary literature.
- **Electronic catalogs of works, online encyclopedias, digitized reference sources**  
  In general, use the fields **Secondary literature (691)** or **Catalog of works (690)** to refer to online reference works such as catalogs of works or encyclopedias. However, as a service to users, it might be helpful to additionally include a direct link to a certain place within the resource through the 856 field.
- **Archival sources, historical sources**  
  Includes digitized municipal registers or documents, digitized correspondence, historical newspapers. Ensure that the relevance of the archival source is first clear in a **General note (500)**, then include the direct link here. For historical newspapers, you should enter the name of the newspaper as secondary literature but you may link to the specific page where the article is found here; make sure information about the article, such as article title and date, is included in a note.
- **Websites**  
  Includes project websites, websites of external funding agencies, or other relevant websites.
- **Other RISM records**  
  Only link to another RISM record if the record has direct bearing to the source being described. Only use permalinks. It should be clear to the user why the record is relevant to the source. At a minimum, name the holding library, shelfmark, and RISM ID number in a note. Sometimes a connection to a different source might be better explained in a **General note (500)**.   
  If you refer to other RISM records elsewhere in you record, it is not required to link to them in this field.  
  It is not necessary to link to all concordant sources in RISM here; indeed, this is a futile pursuit because the number of sources grows in Muscat daily.
- **References to relevant sources in other libraries but not in RISM**  
  If you want to link to a source not yet in RISM, consider whether it is possible for your working group to first enter the digitized libretto, manuscript, or treatise, or add holdings to a particular print. The Editorial Center is happy to help you if you think a source should be in RISM. However, it is understandable if you are unable to create a new record for a source first.
- **Other relevant sources**  
  Includes concordant sources, concordant works, concordant arias or sections of works, sources that served as the basis for the source being described. Such links can be to the digitized objects or links to external catalogs.
