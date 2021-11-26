In diesem Abschnitt wird beschrieben, wie Sie spezielle Arten von Quellen katalogisieren: Sammlungen, Sammelbände, Kontrafakturen, Kompilationen, Parodien, gemischte Materialien (Manuskripte und Drucke, die zusammen aufbewahrt werden), Musik in Zeitschriften, Musik in nicht-musikalischen Publikationen, Abhandlungen und Klavierarrangements.

### Erfassung von Sammlungen  

In RISM ist ein Sammlung sowohl eine bewusst angelegte Musikhandschrift als auch eine Anthologie mit mehreren Teilen, die wiederum zwei oder mehr Werke enthalten.

Für die Erfassung von Sammlungen gelten folgende Regeln:

1. Sämtliche Angaben, welche auf die gesamte Sammlung zutreffen, werden im übergeordneten Eintrag eingetragen.
2. Angaben, die nur für einzelne Teile aus der Sammlung zutreffen, werden in den entsprechenden Einzeleinträgen gemacht.  

Wenn die Werke einer Sammlung unterschiedliche Komponisten, Besetzungen, Quellentypen etc. haben, geben Sie diese nicht in den übergeordneten Eintrag ein.     



Bei Sammlungen, in denen die Werke sehr ähnlich sind, ist es gut, einen vollständigen ersten Teileintrag anzulegen und den Datensatz mit der Funktion "Kopieren" zu duplizieren. Für die folgenden Datensätze müssen Sie dann nur noch Felder wie Titel und Seitenzahl etc. ändern.  



Ein Haupteintrag einer Sammlung darf nicht mit einem weiteren Haupteintrag einer Sammlung verknüpft sein. Verwenden Sie stattdessen eine flachere Hierarchie durch einzelne Datensätze und erläutern Sie die Struktur, den Aufbau oder die Organisation des Objekts in einer Bemerkung.   




### Erfassung von Konvoluten
Ein **Konvolut** besteht aus Elementen, die separat erstellt, aber später zusammengebunden wurden, typischerweise von einem Eigentümer oder einer Institution. Zu den Konvoluten gehören sowohl Bände, in denen einzelne Drucke, als auch Drucke und Manuskripte zusammengebunden sind.  

Es gibt zwei Möglichkeiten, einen Konvolut zu kennzeichnen. Die erste und einfachste Möglichkeit ist, die Einheiten mit der gleichen Signatur zu versehen; ein Vermerk ist ebenfalls hilfreich. Die zweite Möglichkeit ist die Verwendung der Vorlage für Konvolute.  

Der Konvolutdatensatz dient dazu, alle gebundenen Einheiten mit einem einzigen Datensatz zu verknüpfen und dem Benutzer so einen bequemen Überblick über den gesamten Inhalt zu geben.  


Die Datensätze für ein Konvolut sollten einfach gehalten werden. Wie bei den Datensätzen für einen Haupteintrag einer Sammlungen sollten die im Datensatz für ein Konvolut angegebenen Informationen für alle Komponenten des Bandes zutreffen. Erstellen Sie keine separaten Datensätze für mehrere zusammengesetzte Bände, die zusammengehören, wie z. B. ein Satz von Stimmbüchern, die nach Stimmtyp gebunden sind; diese sollten im selben Datensatz beschrieben werden. In vielen Fällen werden Sie eine Vielzahl von Feldern leer lassen.



Sie werden entweder einen Manuskripteintrag oder einen Druckeintrag mit einem Konvolut-Datensatz verknüpfen. Diese werden unterschiedlich verknüpft.  

    1. Erstellen Sie zunächst den Datensatz für das Konvolut, speichern Sie ihn und notieren Sie die RISM-Nummer.  
    2. Bei Handschriften: Gehen Sie im Bearbeitungsmodus des Datensatzes für Ihr Manuskript in das Feld **Übergeordneter Eintrag** (773). Klicken Sie auf die zweite Schaltfläche, um nach dem Konvolut zu suchen.  
    3. Bei Musikdrucken: Suchen Sie im Exemplareintrag das Feld **Zusammengebunden mit** (973) und klicken Sie auf die Lupe. Suchen Sie den Konvolut-Datensatz und wählen Sie ihn aus  



### Erfassung von Kontrafacta   

Contrafacta are vocal pieces in which the text is changed without significant change to the music, such as retexting a secular work with sacred text, or the other way around. The derivation is almost mechanical; there is little creativity on the part of the arranger, but there is a significant change in the musical purpose (such as from a theatrical context to a religious one).

Please note that RISM considers contrafacta to be separate from parody and parody masses, which typically involve a more significant transformation of the musical material.  

Take note of the following fields when cataloging contrafacta. RISM ID no. 300234487, a sacred contrafactum of an aria from Josef Mysliveček's opera Il Bellerofonte, will be used as an example.

**Composer (100)**    
Enter the composer of the original music.

- Mysliveček, Josef

**Standardized title (240)**  
Use the standardized title of the original piece. **Excerpts** may be added. Do not use **Arr**.

- Il Bellerofonte. Excerpts

**Alternative title (730)**  
If there is a new, distinct standardized title for the piece in hand, you can enter it here. Do not enter text incipits here.

**Subject headings (650)**  
Add at least 3 subject headings (more if appropriate), in this order:  
Contrafacta  
Current genre  
Original genre

- Contrafacta
- Sacred songs
- Operas

**Description summary (520)**  
Add a short description in English that explains the situation as a benefit to other RISM users.

- Sacred contrafactum of an aria from Mysliveček's opera Il Bellerofonte.

**Language of text (041)**  
Fill out both of these fields:  
Language of text (041 $a): The current text of the source in hand  
Language of original text (041 $h): Language of the original piece

- Language of text: Latin
- Language of original text: Italian

**Text incipit (031 $t)**  
You will enter two text incipits (use the + to add a new line).  
The text incipit of the current text  
The text incipit of the original text, if known, in square brackets.

- Alma redemptoris mater, quae pervia caeli
- [Giusti dei che ben vedete]

**Other fields**

All other fields, such as liturgical feasts and instrumentation, should refer to the source in hand, that is, the contrafactum itself, and not the original work on which it was based.  


### Erfassung von Compilations

Compilations are new, independent works made from parts of one or more other works and can also include new material. Frequently, the resulting work is of a different genre than the component parts, such as when arias or duets from an opera become a cantata, or excerpts from an opera become an instrumental suite. This also includes pasticcios. While the boundary between a compilation and a pasticcio is not always clear, pasticcios can be generally be characterized by one of these features: (1) arias, duets, or larger parts of dramatic works that are adapted to a new libretto; (2) several independent works combined to create a new work; or (3) collaborative compositions conceived as such from the beginning.

Compilations may be entered on a single record, or they may be entered as collections.

Take note of the following fields when cataloging compilations.

**Composer/Author (100)**  
The composer is always **Compilations**.

**Additional personal name (700)**  
The name of the compiler can be added with the function **Editor**.  

If you have a compilation, enter the composer(s) of the original material and select the function **Composer cross-reference**. Enter the composer(s) of the new material and select the function **Co-composer**.

If you have a pasticcio, do not enter composers as a composer cross-references. Instead, enter all composers as **Co-composer** s.

**Standardized title (240)**  
Enter the standardized title of the source in hand. For pasticcios, add **Excerpts** or **Arrangement** as appropriate.

**Language code (041)**  
For the field **Language of text**, enter the language of the source in hand. If appropriate, the language of the original work can be entered in **Language of original text**.

**Subject heading (650)**  
The first subject heading should be **Compilations** and/or **Pasticcios**. The second should be the genre of the source in hand. If you have excerpts, the genre of the excerpt can be added. **Collaborative compositions** is also an option.

**Description summary (520)**  
Use this field to describe in general the nature of the source.  
_Example_:  
Act 1 by Amadei, act 2 by Bononcini, overture and act 3 by Händel

**Alternate title (730)**  
Enter the standardized title of the original piece(s), adding **Excerpts** or **Arrangement** as appropriate. You can also enter ossia titles.

**Catalog of works (690)**  
You can enter the catalog of works number for both the compilation and the original works.

**Text incipit (031)**  
Enter the text of the source in hand. If known, enter the original text in square brackets.

**General note (500)**  
Always use a note for clarification, especially if the works of separate composers are involved. This ensures that the composers are matched to the works used in the compilation.

**Note on performance (518)**  
Performances should be noted only as they relate to the compilation itself.

**Examples of compilations**:

230001408: Cantata made from opera arias with newly composed recitatives

702000623: Suite made from parts of an opera

700007222: Several works by a single composer used to create a new cantata

702000642, 702000643: Several works by several composers used to create a new suite

452505748: An opera pasticcio consisting of 3 acts by 3 different composers

** **

### Erfassung von Parodien

A parody is a composition based on pre-existing material that results in a new work. In the 19th century, the term gains a satirical flavor.  

The record 150205470 will be used as an example.

**Composer (100)**

Enter the composer of the music for the source in hand.

- Weyse, Christoph Ernst Friedrich

**Additional personal name (700)**

Enter the composer of the pre-existing material and select the function Composer cross-reference.

- Rossini, Gioachino

**Standardized title (240)**

Enter the standardized title of the source in hand.

- Dannemark hellige lyd

**Additional title (730)**

Enter the title of the pre-existing material. Add Excerpts as appropriate. Do not use Arrangement or Variations.

- Tancredi. Excerpts

**Subject heading (650)**  
Enter Parodies as the first subject heading. Enter the genre of the source in hand for the second, and the genre of the pre-existing material as the third.

- Parodies
- National anthems
- Operas

**Language code (041)**

Enter the language for the source in hand in the field Language of text. Enter the language of the pre-existing material in the field Language of original text.

- Danish
- Italian

**Text incipits (031)**

Enter the text incipit of the source in hand. If the original text is known, enter it in square brackets.

- Dannemark hellige lyd
- [Di tanti palpiti]

**Other fields**

All other fields, such as performance information, should relate only to the source in hand.

** **

### Erfassung von gemischtem Material (manuscripts and printed items stored together)

It is not uncommon for manuscript and printed items to be found together in the same folder or with the same shelfmark: for example, a printed score with handwritten parts, or a group of printed parts together with some handwritten ones.

Ideally, the printed material should be cataloged in a separate record, because it is possible that other libraries have copies of the same edition. Create one record for the printed item, add your holdings, and create another record for the manuscript materials. Include cross-references to each so that the user understands what the library has.   
Example: 280000006 is a record for 4 handwritten parts to an overture. 990055636 is a record for the printed parts. The library has added its holdings to the parts. A note in each record refers the user to the other material.

It is not always feasible to create two records: perhaps your printed item does not contain enough information to create an adequate record. In such cases, proceed as follows: Catalog your material using a manuscript template. In the material description section, describe materials of one type (such as the manuscript materials). Add an additional material group, and describe the materials of the other type (such as the printed materials).   



### Erfassung von Noten in Zeitschriften
There are two ways to catalog periodicals that contain music: as a collection or as a single work. In either case, the title of the periodical, with the issue number and year, is entered in the field **Additional title (730)**.  


**Collections** can be appropriate when the periodical consists of all or mostly music and the item was collected and preserved as a whole. Holdings are attached to the collection level. Individual entries are created for each piece in the issue.  
_Example_:  
1001097294: January issue (precise year unknown) of the _Kleine Pianoforte-Bibliothek_, containing 5 pieces. There is one record for the collection parent record, and five individual entries for each piece.

**Single works** can be appropriate when works were included as insertions or additions to periodicals without a notated music focus. Frequently, such items are preserved outside of their original publication context.  
_Examples_:    
991018149: "The Pantheon" published in _The Lady's Magazine_, August 1784  
990042111: "L'amour folâtrant l'autre jour" published in _Nouveau Mercure galant_, May 1679

###   
Erfassung von Musik in nicht-musikalischen Publikationen
RISM enthält auch Werke, die in gedruckten Publikationen gefunden wurde, die nicht primär Musikdokumente sind. Der Schwerpunkt des RISM-Datensatzes liegt dennoch auf der Musik.   

_Beispiel_:   
990026614: 3 Songs von John Isaac Hawkins, die in Charles Willson Peales _Discourse introductory to a course of lectures on the science of nature_ (1800) erschienen.  
**Komponist/Autor (100)**: Komponist des Songs  
**Nebeneintragung Person (700)**: Autor des Buchs mit Indikator **Sonstige Funktion**  
**Diplomatischer Titel (245)**: Titel des Buchs  
**Einordnungstitel (240)**: Entsprechend den RISM-Richtlinien, beispielsweise **3 Songs**  
**Material (300)**: Beschreibung des Notenmaterials, beispielsweise **1 score: 5 p. **   

Teileinträge für jedes Werk können entsprechend den RISM-Richtlinien erstellt werden.  



### Erfassung von Theoretika

Bei der Katalogisierung von Theoretika sollte das Feld **Quellenart, Umfang (300 $a)** mit "text document" ausgefüllt werden.   

Geeignete Schlagwörter sind:

- **Treatises**
- **Writings**
- **Music theory**
- **Theory of harmony**
- **Tutors (inst.)**
- **Tutors (voc.)**
- **Contrapuntal studies (inst./voc.)**
- **Solfeggios (voc.)**
- **Solfeggios (inst.)**
- **Scales (inst./voc.)**   

Weitere Schlagwörter können hinzugefügt werden.

### Erfassung von Klavierarrangements

Geben Sie Klavierbearbeitungen wie folgt an.

-

Im Feld **Einordnungstitel (240):**

  -

Wähle **Bearbeitung** bei **Bearbeitung**.

  -

Unter **Besetzungshinweis** wird die Besetzung des Arrangements eingetragen, wie **pf** oder **V, pf**. Hier wird nicht die Originalbesetzung des Werks genannt.

-

Im Feld **Besetzung (594)** wird die gesamte Besetzung des Arrangements eingetragen. Hier wird nicht die Originalbesetzung des Werks genannt.

-

Im Feld **Material (300)** wird **keyboard score** für eine reine Klavierbearbeitung verwendet. Nutzen Sie **vocal**  **score** wenn es sich um eine Bearbeitung für Gesang und Klavier handelt.
