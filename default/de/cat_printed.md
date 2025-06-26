## Printed editions in RISM

The section **Printed editions in RISM** outlines some considerations that are particular to printed music, including the scope of printed editions in RISM, core records vs. copy-specific information, when to input a new record, standardized titles, multiple copies, record splits and mergers, and printed editions from Series B.

### Scope of printed editions in RISM

RISM seeks to document printed music from the beginnings of music printing through around 1945.

In the course of the 20th century and up to today, we see a sharp increase in commercial music publishing and distribution. The amount of music considered "rare" or undocumented through other resources is much less when compared to previous centuries. Music published by modern commercial publishers, printed in large quantities, widely available, and meant for active use by library patrons would be better documented in cooperative library catalogs such as [WorldCat](http://www.worldcat.org/).

RISM will consider printed music that falls outside of its scope on a case-by-case basis. Relevant cases could include defunct publishers or smaller, regional publishers of historical significance, or modern editions that are part of a collection with historical value, such as the private library of an individual.

### Core records vs. copy-specific information

Muscat has a two-tiered structure for printed editions: a core bibliographic level and the holdings level. Information that is true for the edition as a whole is entered on a core bibliographic level, and information specific to a library's copy is entered on the holdings level.

Information for the core level includes composer, publisher, title, instrumentation, plate number, and format. Information for the holdings level includes holding library, shelfmark, missing parts, handwritten additions, previous owners, bindings, and ownership stamps. MARC fields on the holdings record are linked through $3.

### When to input a new record

RISM treats each manuscript as a unique item and therefore each manuscript has its own RISM record. Even though Muscat has records for over 125,000 printed editions and chances are high that records already exist for music published before 1800, catalogers might notice significant variations that mean a new record must be created. Printed materials are different, however, in that multiple copies of the same edition can be described using the same record; here, libraries simply add their holdings information and note any copy-specific differences.

The following offers guidelines as to which variations justify a new record and which do not. (This section draws heavily from [Descriptive Cataloging of Rare Materials (Music)](http://rbms.info/dcrm/)).

**A new record is required** if your item shows one or more of these differences when compared to the RISM record:

- **Different content**: Differences in the title or authors/contributors. Edition statement that indicates corrections, revisions, expansions, abridgments, or the inclusion of supplementary materials.
- **Different publisher.**
- **Different setting of the printing type**: Different plates (excluding replacement plates). Changes in the statement of extent. Change in bibliographical or musical format. Differences in music line-endings and catchwords (revealed by the comparison of multiple copies).
- **Different publication status**: An original title page has been canceled and replaced. Original sheets have been issued in a new publisher’s cover bearing more recent information than that provided on the title page. Series title page is new. A new label is covering the original publication, distribution, production, etc., statement and indicates a new publisher.
- **Different plate and/or publisher numbers**.

**Do not create a new record** if your item has one of these differences. If your item has _more than one_ of these differences, you must decide if a new record is necessary.

- Different statement of printing: For example, "Fifth printing"
- Different printer or other manufacturer but same publisher
- Different printing date but same publication date
- Different publisher’s cover that does not provide evidence of a discrete publishing unit (for example, a change of color in publisher’s cloth)
- Different kind of binding from the publisher
- Different publisher’s advertisements or catalogs (unless they are integral to the publication)
- Corrections made in the course of a single press run (stop-press corrections)
- Presence or absence of an errata slip

These guidelines mean that a single record can be used to represent multiple impressions, states, and binding variants relating to a single edition or issue. In your holdings information, you can enter details about variants and information specific to your copy.

#### Examples

Example 1: You are looking at RISM ID number 1001031016: Beethoven, "Adelaide," op. 46, no date, Bonn, N. Simrock, text in German and French. Spelling error on title page: "à une vois [!] Seule".

1. Copy 1: Same publication information but spelling has been corrected. This alone would not warrant a new record, but there is an additional text language in Italian. **New record required** (different content/expansion). Result: 1001031017

2. Copy 2: As copy 1, but a price has been engraved on the title page. **Do not create a new record** (no evidence of discrete publishing unit). Add your holdings and mention the price in the holdings information.

3. Copy 3: As RISM ID number 1001031016 (but spelling has been corrected), but an additional publisher is named: "chez L. PLATTNER à ROTTERDAM." **New record required** (different publication status). Result: 1001031022

Example 2: You are looking at RISM ID number 990044663: Mozart, Quartets, Bonn, Köln, N. Simrock.

1. Copy 1: Same title but a label has been stuck over the publication information: Köln, P.J. Simrock. Simrock. You can see that the label is covering up the Bonn/Köln information. **New record required** (different publication status/label indicates a different publisher). Result: 1001141767

Example 3: You are looking at RISM 990024126: Gyrowetz, Symphonies, op. 9. The RISM record represents a set of multiple symphonies. Each symphony is available as a separate publication with separate plate numbers, issued as _livres_ 1, 2, and 3.

1. Option 1, the quick solution: If your library only has one of the items in the set, **add your holdings** and in the field "Material held" note which symphony (livre) you have.
2. Option 2, a better solution, but takes more time: **Notify the Editorial Center** about this record and we will split the record into 3, one record for each symphony. Then, add your holdings to the record for the symphony you have.

### Standardized titles for printed music

#### Individualtitel

Printed music bears distinctive titles much more frequently than music manuscripts do. Observe the following for the field **Standardized title (240)** when cataloging printed music.

1. **Spelling**

Enter standardized titles using modern orthography, but do not overcorrect archaic usage or dialect/regionalisms. Frequent changes include _v_ to _u_, _i_ to _j_ , _y_ to _i_, and _uu_ to _w_. Additional variations can be entered in the field **Additional title (730)**.

##### Beispiel

- RISM ID no. 991009151
 - Titel auf der Quelle: Musicalische Grab=schrifft.
 - Einordnungstitel: Musikalische Grabschrift


2. **Deriving a standardized title**

Standardized titles should consist of the title of the print up to a natural break, frequently a comma, period, or a statement of the author, instrumentation, number, or imprint. Sometimes a distinctive title appears on a page other than the title page.

##### Beispiele

- RISM ID no. 990003743
   - Titel auf der Quelle: Vezzo di perle musicali modernamente conteste alla regia sposa effigiata nella sacra cantica; opera ventesima terza
   - Einordnungstitel: Vezzo di perle musicali

- RISM ID no. 990006458
   - Titel auf der Quelle: Novo giardino de concerti a quattro voci, per cantare a due chori con due voci, e due tromboni, o altri stromenti, o voci, secondo la comodità de cantori ... nel quale li contengono alquante antifone del cantico della Beata Virgine, di alcune solennità principali del anno, & altri motetti, con il basso principale per l'organo, opera undecima
   - Einordnungstitel: Novo giardino de concerti

#### Allgemeine Titel

Standard RISM rules for generic titles apply (see **Standardized title (240)**), but bear in mind that even generic titles, especially in older imprints, are frequently cited in the literature as if they were distinctive titles. Use the field **Additional title (730)** to enter such titles in a standardized form. For guidance, refer to standard reference works such as Grove and MGG, and authority files from the [Library of Congress](http://id.loc.gov/authorities/names.html) or [VIAF](http://www.viaf.org/). If the title indicates that the item has an affiliation with another item, such as libro/Buch/livre or Teil/part/tomus, enter the component in the original language (but standardized spelling) and the Arabic numeral following the title.

##### Beispiele

  - RISM ID no. 990048285
    - Titel auf der Quelle: CANTVS \| IOANNIS PETRALOYSII \| PRAENESTINI \| Missarum cum quatuor, quinque, & sex vocibus. \| LIBER DVODECIMVS. \| Nunc primum in lucem editus. \| VENETIIS, Apud Haeredem Hieronymi Scoti. MDCI
    - Einordnungstitel: Missarum, liber 12
    - Alternativer Titel: 6 Masses

  - RISM ID no. 993000147
    - Titel auf der Quelle: Ander Theil \| Der Preussischen \| Fest-Lieder/ \| Von Ostern an biß Advent \| Mit 5/ 6/ 7/ 8. Stimmen. \| JOHANNIS ECCARDI MULHUSINI THURINGI, \| vnd \| JOHANNIS STOBAEI GRUDENTINI BORUSSI. \| Beyder Chur: vnd Fürstlicher Brandeb. Capell= \| meistern in Preussen. \| DISCANTVS. \| Gedruckt zu Königsberg durch Johann Reusnern An: 1644.
    - Einordnungstitel: Preussische Festlieder, Teil 2


### Mehrere Exemplare in einer Institution

If your institution owns multiple copies (exemplars) of the same printed edition, create separate holdings records for each copy.

### Mikrofilmkopien

Microfilm copies of printed editions are not added as separate copies but are described with the holdings information of the original copy on which the microfilm is based. Links to a description of the microfilm in your institution's local catalog may be added if available. If the microfilm is available digitally, it can be added as a link to an external resource (856). Notify the Editorial Center if you wish to mention your microfilm copy but cannot edit the holdings record.

#### Beispiel
- RISM ID no. 990052954, Exemplar in B-Bc:  
  Mikrofilm im Deutschen Musikgeschichtlichen Archiv (D-Kdma) vorhanden
- RISM ID no. 1000000576, Exemplar in D-B:  
  Digital copy of microfilm available from DiZbi.HAZU | Digitalna zbirka i katalog Hrvatske akademije znanosti i umjetnosti


### Record splits and mergers

#### Hintergrund
Die ersten Katalogprojekte von RISM in den 1950er bis 1970er Jahren konzentrierten sich auf die Musikdrucke. Es wurden viele Abkürzungen vorgenommen, um den Herausforderungen der Zusammenstellung von Katalogkarten aus dem weltweiten Netzwerk der RISM-Mitwirkenden und den Platzbeschränkungen gedruckter Bücher gerecht zu werden. Die in den Serien A/I, B/I und B/II des RISM veröffentlichten Bände fassten häufig mehrere Ausgaben in einem einzigen Eintrag zusammen und verwiesen ohne weitere Ausführungen auf mögliche Unterscheidungsmerkmale. Gleichzeitig führte die Beteiligung mehrerer Mitwirkender manchmal dazu, dass dieselbe Ausgabe unbeabsichtigt mehrfach beschrieben wurde, jedoch aus unterschiedlichen Blickwinkeln.

Heute ermöglicht die Online-Umgebung die Flexibilität, dass ein Datensatz eine Ausgabe beschreibt. Das bedeutet, dass Datensätze, die mehrere Ausgaben beschreiben, idealerweise aufgeteilt werden sollten. Umgekehrt sollten mehrere Datensätze, die dieselbe Ausgabe beschreiben, zusammengeführt werden.

##### Splittung von Datensätzen

Ein Datensatz muss aufgesplittet werden, wenn es Hinweise dafür gibt, dass mehrere verschiedene gedruckte Ausgaben in einem Datensatz beschrieben wurden. Die Bedeutung einer eigenständigen Ausgabe besteht darin, dass sie vom Verlag als Einheit konzipiert wurde und separat auf dem Markt erhältlich war. Das Ergebnis war, dass Verbraucher (und später auch Bibliotheken) die Ausgabe separat erwerben konnten, mit oder ohne die anderen Ausgaben der Reihe oder des Sets.

Sie können das Vorhandensein verschiedener Editionen an Konventionen wie den folgenden in den Datensätzen erkennen.

Im Feld **Diplomatischer Titel (245)** werden oft mehrere Teile oder mehrere Tonarten genannt:
- Concerto [A (B, Es)] à flûte principale ... N\|o 1 (2, 3)
- Sinfonie [C, F, A] à grand orchestre
- Concert pour la flûte traversière ... libro I(-VI)
- Divine harmony. Six select anthems … (Divine harmony. The 2\|d collection being select anthems ...)

Das Feld **Plattennummer (028)** listet mehrere Platten mit aufeinanderfolgenden Nummern in Klammern auf:
- 1192
- (1198)
- (1199)
- (1217)
- (1218)

Im Feld **Bemerkungen (500)** oder in den **Exemplarinformationen** werden mehrere Ausgaben, meist in deutscher oder englischer Sprache, genannt:

- Mehrere Ausgaben
- GB-Lbl (2 verschiedene Ausgaben)

In den **Exemplarinformationen** gibt es in der Regel Hinweise darauf, dass nur ein bestimmter Teil oder ein bestimmtes Buch vorhanden ist, und die Sprache der Angabe folgt in der Regel der Sprache des Titels der Ausgabe:

- F-Pc K-733 [libro II]
- D-F Mus. pr. Q 55/349 [livre 1]
- CH-Bu [2., 3. Buch]

Bei einer Splittung von Datensätzen wird die RISM-Seriennummer auf alle neu erstellten Datensätze übertragen.

##### Record mergers

Catalogers should be aware that duplicates in the database can sometimes be found. Some duplicates originated in the printed RISM A/I or B series: pasticcios or other collaborative works were entered under multiple composers, an edition classified in the B/I series was also published in A/I, or an edition was simply entered twice within a long list. In addition, sometimes catalogers inadvertently create duplicate records.

Duplicate records are not allowed and must be merged when identified. When merging records, criteria are in place regarding what record will be the final record and what record will be merged. Preference is given to the A/I or B/I record (generally identifiable through a RISM ID number that begins with 990 or 993), and an older record is preferable to a newer record (identifiable through the record's creation date). Holdings are transferred to the final record and when appropriate the edition is used as the examination copy. A note such as "This record was merged with RISM ID no. A note such as "This record was merged with RISM ID no. XXX" is always included to keep track of the old RISM numbers. A note such as "This record was merged with RISM ID no. XXX" is always included to keep track of the old RISM numbers.


##### Vorgehensweise

Die Aufteilung und Zusammenführung von Datensätzen kann nur von der Zentralredaktion durchgeführt werden und erfolgt ad hoc. Wenn Sie einen Fall bemerken, in dem Datensätze geteilt oder zusammengeführt werden sollten, wenden Sie sich bitte an die Zentralredaktion.

#### Gedruckte Ausgaben der Serie B

Die Zentralredaktion führte automatisierte Importe für die Einträge aus A/I und B/I durch. Für andere Bände der Serie B sind keine weiteren automatisierten Importe geplant. Es ist jedoch willkommen und wünschenswert, dass RISM-Mitwirkende die in den B-Bänden genannten Ausgaben manuell hinzufügen. Füllen Sie dabei das Feld **RISM-Serien (510)** aus, um anzugeben, zu welcher Serie die Ausgabe gehört. Bitte teilen Sie der Zentralredaktion solche Ergänzungen mit, damit wir weitere Bibliotheken, die diese Ausgabe besitzen, gemäß den Beschreibungen in den B-Bänden hinzufügen können.     
