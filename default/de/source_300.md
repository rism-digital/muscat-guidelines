### Material (300)

**Pflichtfeld**

Das Feld **Material** enthält eine eindeutige Beschreibung des erhaltenen Materials unter Angabe des Formats (z. B. Wenn Stimmen vorhanden sind, wird dieses Feld in Verbindung mit dem Feld **Stimmenmaterial (590)** verwendet, um die spezifischen Stimmen zu bezeichnen.

#### Quellenart, Umfang (300 $a)

Für alle Materialarten außer Stimmen besteht das Feld **Quellenart, Umfang (300 $a)** aus drei Komponenten: **Anzahl, Quellenart, Umfang.**

###### Beispiel

- 1 score: 35 p.

Bei Stimmenmaterial setzt sich das Feld **Quellenart, Umfang (300 $a)** aus zwei Komponenten zusammen: **Anzahl, Quellenart.** Die einzelnen Stimmen werden separat im Feld **Stimmenmaterial (590)** aufgeführt.

###### Beispiel

- 5 parts

##### Anzahl der Stimmen

Geben Sie die Anzahl der vorhandenen Stimmen an. Verwenden Sie **X** um eine unbekannte Anzahl anzugeben.

##### Quellenart

Verwenden Sie einen der folgenden englischen Begriffe, im Singular oder Plural.

###### Generell

- **Stimme**: Die Notation eines Werkes für ein Instrument oder eine Vokalstimme, unabhängig von der Anzahl der Notensysteme pro System (einschließlich Klavier, Orgel, vierhändiges Klavier, unabhängig von der Anzahl der Notensysteme). Auch für Stimmbücher zu verwenden.
- **Partitur**: Enthält alle Instrumente und/oder Stimmen einer Komposition, sofern mehr als eine ausführende Person beteiligt ist. Dies schließt Werke für Vokalstimme und Begleitung ein.

###### Arten von Partituren

- **vocal score**: Gesangspartitur: Ein Werk mit Stimmen und Instrumenten, bei dem die Gesangsstimme(n) vorhanden sind und die Begleitung für ein Tasteninstrument eingerichtet ist.
- **keyboard score**: Klavierauszug: Ein Werk für Instrumente, bei dem die Instrumente für ein Tasteninstrument arrangiert sind (keine Gesangsstimmen). Geben Sie unabhängig von der Anzahl der Notensysteme unmittelbar den Umfang an.
- **chorus score**: Chorpartitur: Ein Werk für Solostimmen, Chor und Instrumente, bei dem nur die Musik für den Chor in Partiturform vorliegt und die Solostimmen weggelassen werden; eine reduzierte Begleitung für ein Tasteninstrument kann vorhanden sein, muss aber nicht.
- **particella**: Eine Skizze oder ein Entwurf einer Komposition in Form einer kurzen Partitur.
- **short score**: wird angegeben, wenn nicht eindeutig zu bestimmen ist, um welche Art reduzierter Partitur es sich handelt.
- **tablature score - Tabulaturpartitur**
- **choirbook**: Chorbuch: Ein Buch, in dem alle Stimmen eines Werkes getrennt notiert sind, so dass der Chor die Noten aus einem Buch lesen kann. Chorbücher werden wie Partituren behandelt.

###### Spezielle Formate

- **tablature part**: Tabulaturstimme: Die Art der Tabulatur, falls bekannt, sollte im Feld **Bemerkungen (500)** angegeben werden.
- **sketch**: Für Skizzen verwenden, wenn die Art nicht genauer bestimmt werden kann.
- For texted scores, use **with text**, such as **keyboard score with text**. **Tkeyboard score with text**.
- **prompt book**: Soufflierbuch: Ein Dokument (Klavierauszug oder Text), das von einem Souffleur für ein Bühnenwerk verwendet wird.
- **table book**: Tischbuch: Stimmen, die so auf einem Blatt angeordnet sind, dass alle Interpreten an einem Tisch sitzend daraus lesen können.

###### Sonstige

- **various**: Verschiedene: Bitte für die übergeordneten Datensätze verwenden, wenn die Sammlung verschiedene Formate enthält (z. B. eine vollständige Partitur und einen Klavierauszug).
- **other**: Sonstige: Wenn keine der oben erwähnten Kategorien angewandt werden kann. Geben Sie in solchen Fällen eine Anmerkung im Feld **Bemerkungen (500)** ein. Die Anzahl der Elemente oder der Umfang ist nicht erforderlich.

Dirigierstimmen werden als **Stimme** mit der Bezeichnung **conductor part** im Feld **Vorhandene Stimmen (590)** eingetragen.

**text document**: Wird verwendet für Libretti, Abhandlungen und andere Textdokumente. Eine Anmerkung in **Bemerkungen (500)** ist möglicherweise notwendig.

##### Umfang

Bei allen Formaten - außer Stimmen - geben Sie die Anzahl der Seiten, Bögen oder Lagen an. Wählen Sie unter den folgenden Abkürzungen: **f** für Folio, **p** für Seite **lvs** für Bögen und **fds** für Lagen.

Bei übergeordneten Sammlungen sowie bei Einzeltiteln wird der Gesamtumfang angegeben, z. B. **35 p.**. Befindet sich ein Stück innerhalb einer Sammlung, wird der Umfang für dieses Stück angegeben, z. B. **p. 17-23.**

Verwenden Sie innerhalb einer Sammlung nur eine Methode der Foliierung oder Paginierung. Wenn Sie die Aufzählung der Vorder- und Rückseite verwenden, benutzen Sie sowohl **r** als auch **v**. Andere Einheiten (z. B. die Umrechnung von Folios in Seiten) geben Sie im Feld **Bemerkungen (500)** an.

Geben Sie hier nicht den Umfang der Stimmen an. Der Umfang wird in das Feld **Umfang Stimmenmaterial (590)** eingetragen.

###### Beispiele

- 1 score: 35 p.
- 1 score (2x): 2, 2 f.
- 1 short score: 8 f.
- 1 tablature score: p. 5-8
- 1 keyboard score: f. 2r-4v
- 1 choirbook: p. 45
- various: 101 p.
- 5 parts
- 1 part
- other: 10 p.


###### Beispiele für andere Blattangaben
Vorwort ist I-VIII nummeriert, gefolgt von 25 Seiten Noten

- VIII, 25 p.

1 Folio ist nummeriert, Vorwort I-VIII, gefolgt von 25 Seiten Musik

- 1 f., VIII, 25 p.

1 Folio ist nicht nummeriert, Vorwort I-VIII, gefolgt von 25 Seiten Musik

- [1] f., VIII, 25 p.

Seitenangaben wechseln von römischen zu arabischen Ziffern

- XII p., p. 13-36

Leere Seiten oder Unregelmäßigkeiten in der Foliierung können im Feld **Bemerkungen (500)** vermerkt werden.

- f. [2] leer
- p. 272 erscheint zweimal

#### Zusätzliche Materialbeschreibung (300 $b)

Das Vorhandensein von Abbildungen und anderen ergänzenden Elementen kann hier erwähnt werden. Verwenden Sie Ihre Katalogisierungssprache.

Beispiele hierfür sind:

- Anzeigen
- gravierte Titelseite
- Frontispiz
- Abbildungen
- Subskribentenliste
- Liste der Subskribenten durch Pränumeration (in Deutschland üblich)
- Porträts
- Verlagssignet
- Druckermarke
- Vignette

#### Format (300 $c)

Geben Sie die Abmessungen der Quelle an: Höhe x Breite in cm. Bruchteile von Zentimetern können entweder durch ein Komma oder einen Punkt angegeben werden. Ein zweites Maß kann in Klammern angegeben werden. Bei mehr als zwei verschiedenen Maßen ist der englische Begriff **Different sizes** einzutragen; weitere Angaben können im Feld **Bemerkungen (500)** vorgenommen werden. Formate wie **octavo**, **quarto**, etc. sollten im Feld **Buchformat (340 $m)** angegeben werden.

##### Beispiele

- 25.5 x 30.5 cm
- 36 x 25.5 cm
- 25,5 (21,5) x 32 (28,5) cm
- Different sizes

Bei Musikdrucken können Sie zusätzlich zu den Abmessungen der Quelle auch das Format des bedruckten Bereichs angeben. Verwenden Sie englische Hinweise wie "printed area (bedruckte Fläche)" oder "plate mark (Stichplatte)". Trennen Sie die Angaben durch ein Semikolon ab. Wenn die Maße variieren, messen Sie die Titelseite und die erste Notenseite aus (ggf. mit Angabe dessen, was gemessen wurde). Die vollständigen Abmessungen werden dann im Exemplareintrag angegeben.

##### Beispiele

- 20 x 16 cm; plate mark 18 x 15,5 cm
- Plate mark, title page: 20.2 x 27.7 cm; plate mark, music: 20.4 x 28.2 cm
- Printed area, title page: 20,2 x 27,7 cm; printed area, music: 20,4 x 28,2 cm
