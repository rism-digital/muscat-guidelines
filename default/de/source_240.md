### Einordnungstitel (240)

Das Feld **Einordnungstitel** ist für den Titel in standardisierter Form vorgesehen. Der standardisierte Titel fasst unterschiedlich benannte, aber gleiche oder ähnliche Kompositionen unter einem einheitlichen Titel zusammen. Auch Einordnungstitel oder Einheitssachtitel genannt.

_MARC-Exporthinweis:_  
Das Feld **Einordnungstitel** wird als MARC 130 exportiert, mit denselben Unterfeldern wie 240, wenn der Datensatz keinen Namen im Feld **Komponist/Autor (100)** enthält.

#### Einordnungstitel (240 $a)

**Pflichtfeld**

Geben Sie den Titel in standardisierter Form ein. Das Feld ist über $0 mit dem Index **Titel / Textincipits** verknüpft. Fragliche Titelansetzungen werden am Ende mit einem Fragezeichen gekennzeichnet (beispielsweise **Die Zauberflöte?**). Eckige und runde Klammern sind nicht zulässig. Alternative Titel werden bei **Alternativer Einordnungstitel (730)** eingetragen.

Als Einordnungstitel kommen in Frage:

1. Individualtitel
2. Textincipits
3. Gattungsbezeichnungen
4. Tempobezeichnungen

##### 1. Individualtitel

Mit einem Individualtitel werden in der Regel alle Arten von Bühnenwerken, Oratorien, Kantaten und Lieder oder auch Instrumentalwerke (z. B. Charakterstücke des 18. Jahrhunderts mit eindeutigem Individualtitel) eingeordnet.

Geben Sie den Titel entsprechend der Schreibweise in (1) New Grove, (2) MGG, (3) Werkverzeichnisse, (4) weitere Nachschlagewerke ein. Lassen Sie den Artikel zu Beginn nicht weg (the, a, an, der, die, le, l', etc.).

Titel von Drucken und populäre Namen (wie „Eroica“ oder „Nelson-Messe“ etc.) gelten nicht als Einordnungstitel. Solche Namen werden in **Alternativer Einordnungstitel (730 $a)** eingegeben.

Im Englischen wird die Großschreibung von Satzanfängen bevorzugt. Im Französischen werden die vereinfachten französischen Regeln ([Règles simplifiées](https://fr.wikipedia.org/wiki/Usage_des_majuscules_en_fran%C3%A7ais#Titres_d%E2%80%99%C5%93uvres_ou_de_p%C3%A9riodiques)) bevorzugt.

###### Beispiele

- Die Forelle
- Die Zauberflöte
- The beggar's opera
- L'italiana in Algeri

##### 2. Textincipit

Hat ein Vokalwerk keinen Individualtitel, tritt das Textincipit an seine Stelle.

Entsprechendes gilt für Rezitativ und Cavatine, Scena und Rondo oder ähnliche Kombinationen. Besteht eine Handschrift aus Rezitativ und Arie oder Scena und Aria wird grundsätzlich das Textincipit der Arie zum Einordnungstitel. Wenn eine einzeln überlieferte Arie vorliegt, deren Operntitel unbekannt ist, geben Sie das Textincipit der Arie ein.

Bei Kantaten dagegen wird der Text des ersten Vokalstücks zum Einordnungstitel, unabhängig davon, ob es ein Rezitativ, eine Arie oder ein Chor ist.

Messen, Requiems, Exsequien, Litaneien und Offiziumskompositionen werden hingegen immer mit der Gattungsbezeichnung eingeordnet. Dasselbe gilt für vollständige Opern und Oratorien mit unbekanntem Individualtitel.

Bezeichnungen für „Gott“ (Herr, Dieu, Dio, Deus, Lord etc.) werden stets groß geschrieben. Die Groß- und Kleinschreibung richten sich nach den Regeln der jeweiligen Sprache. Interpunktionszeichen und Wiederholungen entfallen beim Einordnungstitel. Bei eindeutigen Übersetzungen wird nach Möglichkeit das Textincipit in der Originalsprache eingetragen.

Das Textinicipit muss mit demjenigen im Feld **Textincipit (031 $t)** in Schreibweise und Länge übereinstimmen. Bei lateinischen Texten verwenden Sie den Text vor dem Komma (siehe auch Liste im Anhang) als standardisierten Titel. Verwenden Sie jedoch den gesamten Text als Textincipit.

###### Beispiele

- Der Mond ist aufgegangen
- Gloria [mit Textincipit: Gloria, in excelsis Deo et in terra pax]

##### 3. Gattungsbezeichnungen

Kommen weder Individualtitel noch Textincipit als Einordnungstitel in Frage, wird hier die entsprechende Gattung eingetragen. Der Gattungsbegriff als Einordnungstitel wird in der Regel englischsprachig und im Plural angesetzt (beispielsweise **Operas**). Bei einem Gattungsbegriff als Einordnungstitel korrespondiert dieser zumeist mit dem **Schlagwort (650)**. Weitere Informationen finden Sie Anhang **Einordnungstitel - Schlagworte** der **Richtlinien**.

###### Beispiele

- Symphonies
- Allemandes

##### 4. Tempobezeichnungen

Lässt sich keine Gattung ermitteln, so kann auch eine Tempobezeichnung eingesetzt werden. Erst wenn auch diese nicht zur Verfügung steht, kann auf folgende Termini zurückgegriffen werden:

- Songs (Gesangsstück)
- Pieces (nicht näher definierbares musikalisches Stück)
- Movements (Einzelsatz eines unbestimmten Instrumentalstücks ohne Tempobezeichnung)

###### Beispiele

- Presto
- Lento

#### Besondere Regelungen

##### Collections - Sammlungen

In diesen Fällen wird eine Nummer plus das Genre eingegeben. Geben Sie eine arabische Ziffer ein, die angibt, wie viele Werke zur Sammlung gehören, gefolgt von einer möglichst umfassenden Gattungsbezeichnung.

###### Beispiele

- 25 Arias
- 3 Instrumental pieces

##### Composite volumes - Konvolutbände

Geben Sie eine Zahl entsprechend der Nummer der Einheiten mit dem englischen Begriff "Items" an.

###### Beispiel

- 11 Items

##### Variations - Variationen

Geben Sie hier **Variations** als Einordnungstitel ein. Geben Sie im Feld **Alternativer Titel (730)** das Werk ein, auf dem die Variation basiert, und wählen Sie **Variationen** unter **Bearbeitung** aus.

##### Insertions - Einlagen

Tragen Sie hier das Textincipit des eingefügten Stückes als Einordnungstitel ein. Geben Sie im Feld **Alternativer Titel (730)** den Namen der Oper oder eines größeren Werks ein und wählen Sie **Insertions** als zusätzliches **Schlagwort.**

##### Nicht-lateinische Schriften

Wenn Ihre Quelle einen Titel in nicht-lateinischen Buchstaben oder Zeichen aufweist (griechisches / hebräisches / koreanische / kyrillisches etc. Alphabet, chinesische Zeichen etc.) wird dieser in der ursprünglichen Schrift im **Einordnungstitel** eingetragen. Übersetzungen oder Transliterierungen sind fakultativ und werden im Feld **Alternativer Titel (730)** gemacht.

#### Bearbeitung (240 $o)

Handelt es sich bei vorliegendem Werk um eine Bearbeitung eines anderen Werks, wird das in diesem Feld mit **Arrangement** gekennzeichnet.

Transpositionen und Umtextierungen gelten nicht als Bearbeitungen. In solchen Fällen wird der entsprechende Name des Bearbeiters, sofern bekannt, unter **Nebeneintragung Personen (700)** angegeben. Obwohl es sich dabei nicht um Bearbeitungen handelt, werden die entsprechenden Personen dort als „Bearbeiter“ bezeichnet.

Bearbeitungen sind ebenfalls zu unterscheiden von eigenständigen Werken (freie Bearbeitungen) wie Variationen, Paraphrasen, Parodien und Phantasien über ein Thema der Vorlage.

#### Unterteilung nach der Form (240 $k)

Hier wird ein Vermerk zu besonderen Ausgabeformen gemacht. Folgende Angaben sind möglich:

- **Auszüge**: wenn nur ein oder mehrere Abschnitte des Gesamtwerks vorhanden sind
- **Fragmente**: wenn nur Fragmente des Werkes vorhanden sind
- **Skizzen:** wenn nur Skizzen zu einem Werk vorliegen

#### Tonart (240 $r)

**Besondere Regelungen:**

Handelt Wählen Sie die Tonart des gesamten Werks (auch für Ausschnitte).

Bei Bearbeitungen wird die Tonart des Originalwerks eingegeben. In diesem Fall ist eine entsprechende Bemerkung im Feld **Bemerkungen (500)** notwendig.

Ist auf der Quelle keine Tonart vorhanden, darf sie nur ergänzt werden, wenn sie eindeutig zu bestimmen ist.

Die Angabe entfällt bei: Opern, Oratorien und Kantaten; Recitativen ohne anschließende Arie und wenn sie nicht eindeutig zu bestimmen ist.

Modale Tonarten werden nicht in moderne Tonartenbezeichnungen übertragen.

Folgende westliche Kirchentonarten stehen zur Verfügung:
- 1. Ton (Dorisch)
- 1. Ton (Dorisch), transponiert
- 2. Ton (Hypodorisch)
- 2. Ton (Hypodorisch), transponiert
- 3. Ton (Phrygisch)
- 3. Ton (Phrygisch), transponiert
- 4. Ton (Hypophrygisch)
- 4. Ton (Hypohrygisch), transponiert
- 5. Ton (Lydisch)
- 5. Ton (Lydisch), transponiert
- 6. Ton (Hypolydisch)
- 6. Ton (Hypolydisch), transponiert
- 7. Ton (Mixolydisch)
- 7. Ton (Mixolydisch), transponiert
- 8. Ton (Hypomixolydisch)
- 8. Ton (Hypomixolydisch), transponiert
- 9. Ton (Aeolisch)
- 9. Ton (Aeolisch), transponiert
- 10. Ton (Hypoaeolisch)
- 10. Ton (Hypoaeolisch), transponiert
- 11. Ton (Ionisch)
- 11. Ton (Ionisch), transponiert
- 12. Ton (Hypoionisch)
- 12. Ton (Hypoionisch), transponiert

Folgende byzantinische Kirchenmodi stehen zur Verfügung:
- Ēchos prōtos (Erster Modus der byzantinischen Musik)
- Ēchos deuteros (Zweiter Modus der byzantinischen Musik)
- Ēchos tritos (Dritter Modus der byzantinischen Musik)
- Ēchos tetartos (Vierter Modus der byzantinischen Musik)
- Ēchos plagios prōtos (Erster plager Modus der byzantinischen Musik)
- Ēchos plagios deuteros (Zweiter plagaler Modus der byzantinischen Musik)
- Ēchos barys (Dritter plager Modus der byzantinischen Musik)
- Ēchos plagios tetartos (Vierter plagaler Modus der byzantinischen Musik)

**Altdaten**: Ältere RISM-Katalogisierungsrichtlinien erlaubten die Eingabe mehrerer Tonarten in diesem Feld, getrennt durch ein Semikolon. Diese Praxis wurde mit der Einführung von Muscat eingestellt.

#### Besetzungshinweis (240 $m)

**Pflichtfeld außer bei: Opern und Oratorien mit der Standardbesetzung V (X), Coro, orch**

Bei Skizzen oder Sammlungen werden nur Angaben fällig, sofern sie sinnvoll erscheinen.

Der Besetzungshinweis dient als kurze Zusammenfassung der Gesamtbesetzung (Instrumentierung). Trennen Sie die einzelnen Elemente der Besetzungsangaben durch Kommas. Geben Sie maximal vier Elemente ein. Die ausführliche Auflistung der Besetzung erfolgt im Feld **Besetzung (594)**. Der Besetzungshinweis wird in einer Zeile angegeben; wiederholen Sie das Feld nur, um alternative Instrumentierungen anzugeben (siehe unten).

Es gelten die Bezeichnungen gemäß **Abkürzungsliste**. Darin nicht enthaltene Begriffe werden auf Englisch und ausgeschrieben angegeben.

Ordnen und gruppieren Sie die Besetzung anhand folgender Begriffe:

- Solostimmen
- Chor
- Soloinstrumente
- Streicher
- Holzbläser
- Blechbläser
- Zupfinstrumente
- Schlagwerk
- Tasteninstrumente
- Basso continuo

Bei mehreren gleichen Gesangsstimmen oder Instrumenten wird die Anzahl in runden Klammern angegeben, z. B. **B (2)**. Eine unbekannte Anzahl Stimmen wird mit nachgestelltem **(X)** ausgedrückt. Verwenden Sie **V** auch um unterschiedliche Stimmlagen zu gruppieren, z. B. **V (8)**. Eine unbekannte Anzahl Stimmen wird mit nachgestelltem **(X)** ausgedrückt.

Als Soloinstrumente werden nur solche bezeichnet, die gegenüber einem Orchester eine durchgehende Solofunktion haben (vor allem im Solokonzert). Bitte keine Stimmen angeben, die aus dem Tutti heraus einzelne Solopassagen übernehmen (z. B. ein Oboensolo innerhalb eines Kantatensatzes).

Bei einer Bearbeitung wird die Besetzung der vorliegende Quelle angegeben. Ist die Besetzung des Originalwerks bekannt, wird diese im Feld **Bemerkungen (500)** angegeben. Bei einer **Collection** wird die Besetzung nur angegeben, wenn sie auf alle in der Sammlung enthaltenen Werke zutrifft.

Das Feld kann wiederholt werden, um Alternativbesetzungen anzugeben, z. B. ein Lied sowohl für Sopran als auch für Tenor. In solchen Fällen geben Sie jede mögliche Instrumentierung in ein separates Feld ein: zum Beispiel **S, pf** in einer Zeile und **T, pf** in der nächsten.

Wenn Sie einen bezifferten Bass haben, geben Sie das Instrument wie gewohnt ein, z. B. **b**, **bc**, **org** usw. (siehe auch die Tabellen im Abschnitt **Bezifferter Bass in Partituren und/oder Stimmen** als Orientierungshilfe für verwandte Felder).

Machen Sie keine Angaben, wenn die Besetzung unbekannt oder unsicher ist.

##### Beispiele
- A, Coro, orch
- Bariton, pf
- V (3), strings, bc
- V (4), Coro, orch, org   _für eine Messe_
- cl, orch _für ein Klarinettenkonzert_

Verwenden Sie gegebenenfalls die folgenden Standardbesetzungen.

Streichquartett
- vl (2), vla, vlc

Streichquintett (2 Violen)
- vl (2), vla (2), vlc

Streichquintett (2 Celli)
- vl (2), vla, vlc (2)

Streichquintett (mit Kontrabass)
- vl (2), vla, vlc, cb

Klaviertrio
- vl, vlc, pf

Bläserquintett
- fl, ob, cl, cor, fag

Flötenquartett (nur Flöten)
- fl (4)

Flötenquartett (Flöte mit Streicher)
- fl, vl, vla, vlc
