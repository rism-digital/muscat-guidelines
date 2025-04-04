### Quellentyp (593)

**Pflichtfeld.**

Das Feld **Quellentyp** beschreibt sowohl die Beschaffenheit des Materials als auch dessen Inhalt.

#### Quellentyp (593 $a)

Der **Quellentyp** gibt die physische Form der Quelle wieder. Die angebotenen Optionen hängen von der gewählten Vorlage ab. Folgende Angaben sind möglich:

##### Für handschriftliches Material

- **Autograph manuscript = Autograph**: vollständig oder größtenteils geschrieben in der Hand des Komponisten. Wenn Sie Anonymus als Komponist eingegeben haben und hier Autograph auswählen, ergänzen Sie bitte eine Erklärung in den **Bemerukungen (500)** hinzu.
- **Possible autograph manuscript = fragliches Autograph**: Zeigt eine gewisse Unsicherheit an, ob das Manuskript von der Hand des Komponisten ist.
- **Partial autograph = Teilautograph**: Große Teile des Manuskripts sind in der Hand des Komponisten.
- **Manuscript copy = Abschrift**: Das Manuskript liegt in der Hand einer anderen Person als des Komponisten vor. Diese Einstellung wird standardmäßig ausgewählt, wenn eine Vorlage für handgeschriebenes Material ausgewählt wurde.
- **Manuscript copy with autograph annotations = Abschrift mit autographen Eintragungen**: Das Manuskript liegt in der Hand einer anderen Person als de Komponisten vor, enthält aber Korrekturen oder kleine Zusätze des Komponisten.
- **Additional printed material = zusätzlich gedrucktes Material**: gedrucktes Material ist vorhanden, wird aber nicht in einem eigenen Eintrag beschrieben (siehe unten).

##### Für gedrucktes Material

- **Print = Druck**: Diese Einstellung wird standardmäßig ausgewählt, wenn eine Vorlage für gedrucktes Material gewählt wurde.

In den Exemplareinträgen können Sie außerdem Folgendes auswählen:
- **Print = Druck**: Dies ist standardmäßig ausgewählt.
- **Print with autograph annotations = Druck mit autographen Eintragungen**: Mit handschriftlichen Anmerkungen des Komponisten.
- **Print with non-autograph annotations = Druck mit handschriftlichen Eintragungen**: Mit handschriftlichen Anmerkungen nicht vom Komponisten.
- **Additional manuscript material = zusätzlich handschriftliches Material**: handschriftliches Material ist vorhanden, wird aber nicht in einem eigenen Eintrag beschrieben (siehe unten).

##### Für Konvolutbände

- **Composite = Konvolut**: Diese Option ist standardmäßig ausgewählt.

For manuscript collections, select the source type that best represents the collection, or use multiple material groups to differentiate further.

##### Zusätzlich gedrucktes oder handschriftliches Material

Manuskriptvorlagen bieten die Option **Zusätzlich gedrucktes Material** und die Exemplareinträge bieten die Option **Zusätzlich handschriftliches Material** zu ergänzen. Dies dient dazu, in Ihrem Datensatz Platz für eine kurze Beschreibung von Materialien zu schaffen, die Ihre Hauptquelle begleiten, aber vom Vorlagentyp abweichen.

Sie haben zum Beispiel Aufführungsmaterial, das aus einem handschriftlichen Satz Stimmen und einer gedruckten Partitur besteht. Sie haben immer die Möglichkeit, das handschriftliche Material in einer Vorlage für Manuskripte und das gedruckte Material in einer Vorlage für Drucke zu beschreiben und mit Querverweisen auf die anderen Datensätze hinzuweisen. Denken Sie daran, dass separate Datensätze für gedrucktes Material anderen RISM-Nutzern den umfassendsten Zugang bieten.Es kann jedoch sein, dass nicht immer genügend Informationen vorhanden sind, um ein gedrucktes Objekt vollständig zu beschreiben, oder dass Sie es vorziehen, alle Ihre Materialien in einem Datensatz zu speichern. In solchen Fällen können Sie die zusätzlichen Materialien angeben und sie mit Hilfe dieser Optionen kurz beschreiben.

Wenn Sie eine Manuskriptvorlage verwenden, wird die erste Instanz des Feldes **Quellentyp** standardmäßig mit der Vorlage übereinstimmen und sich auf das handschriftliche Material beziehen. Fügen Sie eine zweite Materialgruppe hinzu und wählen Sie **Zusätzlich gedrucktes Material**. Beschreiben Sie dann Ihr gedrucktes Material wie üblich für diesen Abschnitt.

Wenn Sie eine Druckvorlage verwenden, wählen Sie in den Exemplareinträgen **Zusätzlich handschriftliches Material**. Manuscript material can be described briefly in this section, or in the field **General note (500)**.

#### Inhaltstyp (593 $b)

Der **Inhaltstyp** beschreibt die Form des Materials. Folgende Angaben sind möglich:
- **Notenmaterial**
- **Libretto**
- **Traktat**
- **Sonstige**: Sparsam verwenden, um andere Arten von Materialien zu beschreiben, die die Musikquelle begleiten.


Für Konvolutbände, die mehr als einen Inhaltstyp enthalten, können Sie auch wählen:

- **Gemischt**

#### Spezialfälle

##### Sammlungen

Sie können eine Kombination von Quellentyp und Inhaltstyp wählen, die die Sammlung als Ganzes am besten zusammenfaßt oder mehrere Materialgruppen für jede Art von Quelle hinzugefügen. Keep in mind that differentiated information will always be provided in the child record.

##### Komponisten, Bearbeiter und Schreiber

Bei autographen Handschriften und fraglichen Autographen sollte kein zusätzlicher Eintrag **(700)** mit dem Namen des Komponisten als Schreiber erstellt werden. Eine Ausnahme besteht jedoch, wenn die Identität des Kopisten feststeht, aber nicht sicher ist, ob der Schreiber auch der Komponist ist. In einem solchen Fall tragen Sie den Namen des Kopisten in das Feld **Nebeneintrag Personenname (700)** ein, fügen aber denselben Namen in das Feld Name des **Komponisten/Autors (100 $a)** mit dem entsprechenden **Zuschreibungsvermerk (100$j)** ein.

In einigen Fällen beispielsweise bei Teilautographen ist ein erklärender Vermerk im Feld **Bemerkungen (500)** sinnvoll.

Ist der Bearbeiter einer Komposition gleichzeitig auch deren Schreiber, gilt diese Quelle als **Abschrift** nicht als **Autograph**.

##### Other forms of notation

Use **Notated music** as a **Content type** for documents that can be considered performance material, even if they do not use staff notation. This includes graphic notation, letter notation, number notation, and documents that only consist of performance instructions.

##### Fotokopien

If your source is a mechanical reproduction (such as a photocopy) of a manuscript, follow these steps:

1\. Wählen Sie **Autograph**, **Abschrift** usw. aus (d.h. wählen Sie den Typ aus, der für die Originalquelle gilt).

2\. Wählen Sie die Art der Reproduktion im Feld **Spezielle Fertigungstechnik (340 $d)**.

##### Typewritten or computer-generated material

If your source is typewritten or computer generated, follow these steps:

1\. Wählen Sie eine Manuskriptvorlage.

2\. Select **Autograph manuscript** if the composer or author created the document themselves. Select **Manuscript copy** if someone other than the composer or author created the document.

3\. Select an appropriate printing technique from **Special production technique (340 $d)**, such as **Typescript** for typewritten items or **Computer printout** for computer-generated materials.

4\. Add an explanatory note in the field **General note (500)**.  
