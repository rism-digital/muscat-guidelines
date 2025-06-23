### Incipit (031)

Das Feld **Incipit** wird für musikalische Informationen über die ersten Takte des Stücks verwendet und umfasst sowohl Noten- als auch Textincipits. Incipits helfen Werke zu identifizieren und Quellen zu vergleichen. Bei Instrumentalwerken bietet es sich an, Incipits für eine Ober- und eine Unterstimme anzugeben (beispielsweise vl 1 und b). Für Vokalmusik geben Sie ein Musikincipit für die höchste Vokal- als auch Instrumentalstimme an.

Ist die benötigte Notation mit dem Plain & Easy-Code nicht verfügbar, transkribieren Sie die Musik so gut wie möglich und fügen Sie eine Bemerkung hinzu. Sie können zur weiteren Verdeutlichung ein Bild des Incipits aus der Quelle anhängen.

Beachten Sie, dass die Incipittranskription in erster Linie zur Suche und Identifizierung dient und nicht dazu, das visuelle Erscheinungsbild der Partitur zu reproduzieren. Der Plaine & Easie-Code ist eine bewusste Vereinfachung der westlichen Notenschrift, und nicht alle Details können (oder sollten) kodiert werden.

Hilfe bei der Transkription von Mensuralnotation finden Sie in „Basic Mensural Notation Reference“ von Ted Dumitrescu ([http://www.cmme.org/misc/refsheet.pdf](http://www.cmme.org/misc/refsheet.pdf))).

<!-- Note to translators: If you know of a standard reference document or website for transcribing mensural notation in your language, please use that instead. If not, feel free to link to this English document. -->  

_MARC-Exportnotiz:_  
Datensätze, die ein Incipit enthalten (alles in Feld 031), erhalten beim Speichern den Wert „$2pe“, was darauf hinweist, dass das Incipit mit dem Plaine & Easie-Code erstellt wurde.

#### Werknummer, Satznummer, Incipitnummer (031 $a, b, c)

**Pflichtfeld, wenn in diesem Teil irgendein Feld ausgefüllt ist.**

Die Incipitnummer besteht aus drei Ziffern, welche für das Werk, den Satz und das Incipit stehen.

Die erste Zahl ist immer eine 1. Die Werknummer bezieht sich auf die Position des Incipits im betreffenden Datensatz und nicht auf die Position in der Quelle insgesamt. In RISM werden Werke in separaten Datensätzen unter Verwendung einer übergeordneten/untergeordneten Hierarchie katalogisiert, sodass jeder Datensatz nur ein Werk enthält.

Sätze beziehen sich auf eindeutige Abteilungen im Werk (wie in einer Sinfonie oder einer Arie und Rezitativ innerhalb einer Oper). Die Nummern der Sätze können identisch sein, wenn mehrere Incipits für ein und denselben Satz eingegeben werden.

Die Incipitnummer ist in die Satz- oder Werkhierarchie eingebettet. Incipits mit unterschiedlichen Ziffern am Schluss, aber identischen Zahlen an zweiter Stelle, zeigen ein gleichzeitiges Erklingen an, wie beispielsweise eine vl 1 und ein Bass.

##### Beispiele

- 1.1.1 = 1. Werk, 1. Satz, 1. Incipit
- 1.1.2 = 2. Incipit zum 1. Satz (erklingt gleichzeitig mit 1.1.1)
- 1.2.1 = 1. Werk, 2. Satz, 1. Incipit
- 1.3.1 = 1. Werk, 3.

Die Punkte zwischen den Zahlen werden von Muscat automatisch eingefügt.

Die dreistellige Incipitnummer muss innerhalb eines Datensatzes eindeutig sein. Nummerieren Sie die Incipits fortlaufend und unter Berücksichtigung des betreffenden Datensatzes. Die Incipitnummer sagt nichts darüber aus, wo sich das Incipit in einer Quelle befindet. Die Nummerierung innerhalb der Quelle sollte sich in der Titelbeschreibung widerspiegeln, und etwaige Besonderheiten können in einer Bemerkung erläutert werden. Das bedeutet, dass das Incipit des vierten Lieds innerhalb einer Liedersammlung 1.1.1 wie bei allen anderen Liedern in der Sammlung lautet.

 Die fortlaufende Nummerierung muss auch dann eingehalten werden, wenn Inhalte in der Quelle fehlen. Wenn beispielsweise ein Lied aus einer Sammlung von sechs Liedern fehlt, beginnt die Werknummer jedes Incipits weiterhin mit einer 1. Wenn es sich bei der Quelle um eine dreisätzige Symphonie handelt, aber der Mittelsatz fehlt, werden die Incipits mit 1.1.1 und 1.2.1 (nicht 1.3.1) nummeriert.


#### Satztitel, Tempo (031 $d)

Der Satztitel, das Tempo oder ähnliche Angaben werdn in originaler Schreibweise wiedergegeben. Zeilenumbrüche werden durch den geraden Strich **\|** mit einem Leerzeichen davor und danach gekennzeichnet. Ergänzungen zum originalen Zitat stehen immer in eckigen Klammern; diese sollten einheitlich geschrieben werden. Mehrere Titel oder zusätzliche Tempoangaben können in separaten Feldern hinzugefügt werden. Bleibt die Angabe innerhalb eines Satzes gleich, wird der Titel bzw. das Tempo nur im ersten Incipit angegeben.

**Altdaten**: Ältere RISM-Richtlinien erlaubten die Formulierung "Without tempo", um anzuzeigen, dass ein Satz mehrere Tempoangaben hat, von denen eine oder mehrere nicht bekannt sind. Mehrere Tempobezeichnungen wurden nacheinander, durch Semikolon getrennt, eingegeben.


#### Besetzung (031 $m)

Geben Sie die Vokalstimme oder das Instrument mit Hilfe der Liste **RISM-Instrumentenabkürzungen** ein. Verwenden Sie **V** für eine unbekannte Vokalstimme. Verwednen Sie **i** für ein unbekanntes Instrument. Die Stimmung des Instruments wird im Feld **Bemerkungen** genannt. Wenn es sich um ein transponierendes Instrument handelt, können Sie es in der notierten oder der klingenden Tonhöhe eingeben. Geben Sie im Feld **Kommentar zum Incipit (031 $q)** an, welche Option Sie verwendet haben.

##### Beispiele

- pf
- Coro T
- org with text

**Altdaten**: Ältere RISM-Richtlinien verlangten, dass Notenincipits für transponierende Instrumente in klingender Tonhöhe eingegeben werden müssen.

#### Rolle (031 $e)

Angabe der zum Incipit gehörenden Rolle in standardisierter Form. Wenn Sie dieses Feld ausfüllen, müssen Sie auch das Feld **Rollennamen (595)** ausfüllen. Mit eckigen Klammern wird eine Ergänzung gekennzeichnet. Mit Fragezeichen wird eine unsichere Rollenangabe gekennzeichnet.

#### Textincipit (031 $t)

Ein Textincipit besteht aus den ersten Wörtern eines Textes oder Abschnitts. Es kann sich dabei um die erste Zeile, den ersten Satz oder eine andere Gruppe von Wörtern handeln, die sprachlich Sinn ergeben. Textincipits dienen dazu, den verwendeten Text zu identifizieren, und müssen nicht unbedingt mit der Länge der Notenincipits übereinstimmen. Texincipits können unabhängig von der Eingabe eines Musikincipits aufgenommen werden. Beachten Sie, dass für Texte in lateinischer Sprache gesonderte Regeln gelten (siehe unten).

Textincipits werden in standardisierter Form angegeben. Geben Sie das Textincipit in moderner Rechtschreibung ein. Normieren Sie die Eingabe mit Hilfe des Index **Titel/Textincipit**. Geben Sie neue Texte ein, sofern diese noch nicht im Index vorhanden sind.

Teilklammerungen des Textes sind nicht erlaubt. Emphatische Akzente, Satzzeichen und Wiederholungen im Text entfallen.

Akzente werden nur so verwendet, wie sie im Wörterbuch stehen und grammatikalisch richtig sind. Ziffern zu Beginn des Textes werden in Worte umgeschrieben. Die Groß-/Kleinschreibung richtet sich nach den Regeln der jeweiligen Sprache; jedoch werden Bezeichnungen für Gott (Herr, Dio, Dieu, Signore, Lord, etc.) stets groß geschrieben. Wird für den Einordnungstitel (240) das Textincipit verwendet, muss auf genaue Übereinstimmung in Länge und Schreibweise geachtet werden.

Wenn Sie den Text nicht lesen können, lassen Sie ihn vollständig weg und fügen Sie einen Vermerk wie „Text unleserlich“ oder ähnliches hinzu.

Nach Apostroph wird in den romanischen Sprachen immer ohne Leerzeichen weiter geschrieben. Ausnahme von der Regel: wenn der Anfangsbuchstabe eines Wortes durch Apostroph ersetzt ist (z. B. Fra l'amante e 'l genitor).

Zusätzlich ermittelte Texte, die nicht in der Quelle stehen, können hier angegeben werden. In solchen Fällen steht der gesamte Text in eckigen Klammern. Dazu gehören:

- Ergänzte Texte, wenn Vokalstimmen fehlen
- Textincipits in der Originalsprache des Werks, wenn die Quelle eine übersetzte Fassung bietet
- Texte von Vokalkompositionen, die Thema einer Variation oder Vorlage einer instrumentalen Bearbeitung wurden

**Nicht-lateinische Schriften:** Wenn Ihre Quelle ein Textincipit enthält, das nicht-lateinische Buchstaben oder Zeichen verwendet (kyrillisches/griechisches/hebräisches/koreanisches Alphabet, chinesische Schriftzeichen usw.), geben Sie das **Textincipit** in der Originalschrift ein. Übersetzungen oder Transliterierungen sind fakultativ und können als zusätzliches Textincipit eingetragen werden. Fügen Sie Übersetzungen, die nicht in der Quelle enthalten sind, in eckigen Klammern hinzu. Sie können in jede der RISM-Sprachen übersetzen.

**Gesonderte Regeln für lateinische Texte:** Geben Sie sowohl geistliche als auch weltliche lateinische Texte ein. Das Feld ist mit der Normdatei **Titel/Textincipit** verknüpft. Innerhalb des Indexes **Titel / Textincipit** können Sie sich durch den Indikator **t** über den genauen liturgischen Kontext, Varianten und anderes in formieren. Wird für das Textincipit als Einordnungstitel benutzt, so wird muss auf genaue Übereinstimmung der Schreibweise geachtet werden. Der lateinische Text wird im Einordnungstitel allerdings nur bis zu dem Trennungszeichen, einem Komma, angegeben. Lateinische Texte, die nicht in der Quelle genannt sind, sondern recherchiert wurden, werden in eckigen Klammern eingetragen.

Lateinische Standardtexte entsprechen in der Regel den Texten im _Liber usualis_. In RISM enthalten diese Texte normalerweise ein Komma. Wenn Sie z. B. nach dem Text "Et in terra pax" suchen, erhalten Sie etwa ein Dutzend Optionen, aber nur eine davon hat ein Komma, und diese Quelle wird in der Datenbank 4.800 Mal verwendet. Deshalb ist es genau das, was wir wollen - vorausgesetzt, es stimmt mit Ihrer Quelle überein. Wenn Ihr Textinicpit nur "Et in terra pax" lautet, dann bedeutet dies, dass Ihre Quelle (1) nur diese Worte enthält oder (2) in einer Weise fortgesetzt wird, die sich vom _Liber usualis_ unterscheidet. Das ist natürlich möglich, aber in den meisten Fällen ist die Version mit dem Komma vorzuziehen.


#### Tonart, Modus (031 $r)

Wählen Sie einen Tonart aus der Auswahlliste aus.

**Altdaten**: Ältere RISM-Katalogisierungsrichtlinien erlaubten die Eingabe mehrerer Tonarten in diesem Feld, getrennt durch ein Semikolon. Diese Praxis wurde mit der Einführung von Muscat eingestellt.

#### Globalvorzeichen (031 $n)

Kreuztonarten werden mit **x**, B-Tonarten mit **b** gekennzeichnet, gefolgt von den Großbuchstaben der Tonhöhen, die erhöht oder erniedrigt werden sollen. Steht ein Stück eindeutig in einer bestimmten Tonart, aber ist ein Kreuz oder ein b nicht in der Tonartvorzeichnung enthalten, können die fehlenden Kreuze oder b in eckigen Klammern hinzugefügt werden.

Sind keine Globalvorzeichen vorhanden, bleibt das Feld leer.

##### Beispiele

- xF = Ton F wird erhöht => G-Dur oder e-Moll
- bBE = Töne B und E werden erniedrigt = B-Dur oder g-Moll
- xFC[G] = Töne F und C werden erhöht. Das Stück steht jedoch eindeutig in A-Dur. Also ist die letzte Erhöhung zu ergänzen

#### Metrum (031 $o)

Enter time signatures as fractions. The following are also allowed:

- **c** = common time or tempus imperfectum cum prolatione imperfecta
- **c/** = cut time, alla breve
- **3** = proportio tripla; also **1**, **2**, etc.
- **c3** = proportio tripla
- **c3/2**
- **c.** = tempus imperfectum cum prolatione perfecta
- **o** = tempus perfectum cum prolatione imperfecta
- **o/** = tempus perfectum cum prolatione minore diminutum
- **o.**  = perfect time, tempus perfectum cum prolatione perfecta

If the meter changes constantly, you can write the first time signature followed by the second, separated by a space.

If the incipit is without a time signature, add one and also add an explanation in the field **General note (031 $q)** such as "Time signature added." Do not put the inferred time signature in square brackets.

**Obsolete procedures**: Older guidelines allowed a blank field here if the source lacked a time signature.

##### Examples

- 4/4
- 6/8
- 3/4 4/4

If the time signature in the source is obviously wrong, correct it to match the incipit given. Include an explanatory note in the field **General note**.

#### Clef (031 $g)

Select a clef from the list. The letter indicates the kind of clef. A hyphen means modern notation. A plus sign means mensural notation. The number refers to position on the staff line.

If no clef is on the source, select one from the list and include an explanatory note in the field **General note (031 $q)**.

#### Validity (031 $s)

Do not enter anything into this field! (It is only used for old data.)

#### Music incipit (031 $p)

Enter the music incipit in encoded form using the Plaine & Easie code (see also [https://www.iaml.info/plaine-easie-code](https://www.iaml.info/plaine-easie-code)). The incipit should be at least two bars (measures) or six notes long.

##### 1. Octaves
' = in the 1st octave above middle C  
'' = in the 2nd octave above middle C  
''' = in the 3rd octave above middle C  
, = in the 1st octave below middle C  
,, = in the 2nd octave below middle C  
,,, = in the 3rd octave below middle C

##### 2. Rhythmic values

0 = longa  
9 = breve  
1 = whole note / semibreve  
2 = half note / minim  
4 = quarter note / crotchet / semiminim  
8 = eighth note / quaver / fusa  
6 = 16th note / semiquaver / semi fusa   
3 = 32nd note / demisemiquaver  
5 = 64th note / hemidemisemiquaver  
7 = 128th note / semihemidemisemiquaver  
7\. = neumatic notation

Periods are used for dotted notes. Multiple periods can be added to a note.

4\. = dotted quarter note / dotted crotchet   
8.. = double dotted eighth note / double dotted quaver

##### 3. Accidentals

x = sharp  
xx = double sharp  
b = flat  
bb = double flat  
n = natural

##### 4. Note names

C, D, E, F, G, A, B

##### 5. Grace notes and ornaments

g = acciaccatura (without rhythmic value, precedes the note name)  
q = appoggiatura (with rhythmic value, precedes the note name)  
qq...r = several appoggiaturas or ornaments which belong together (with rhythmic value)

##### 6. Rests

The '-' (minus sign) is for a single-note rest. Use '=' (equal sign) for a measure rest. For multiple measures of rest, follow the = with the number of measures and a bar line.
- Eighth-note rest
 - 8-/
- One measure of rest
 - -/
 - =1/
- Multiple measures of rest
 - =35/

##### 7. Bar lines

/ = bar line  
// = double bar line  
//: = double bar line with repeat  
:// = double bar line with repeat  
://: = double bar line with repeat

##### 8. Other symbols

t = trill (immediately follows the note)

+ = tie (immediately follows the note; not to be confused with a slur)  
  () = fermata/hold/pause (only a single note letter name or a single rest can be bracketed; accidentals, pitch indications, etc. must be outside the parentheses; see also **10. Special rhythms**, below)

Do not enter slurs.

##### 9. Beaming

{ = beginning of beaming  
} = end of beaming

###### Example

{qq6'CDEDr}

##### 10. Special rhythms

( = beginning of special rhythm  
) = end of special rhythm

The total duration value of the group must be written before the **(**. The rhythmic value of the first note must be given after **(**, even if it is identical with that of the note immediately before the section of special rhythm. The number of notes in the group must be indicated before **)**. It is separated from the last note by **;**.

###### Examples

- 8(3ABCDE;5)   = quintuplet, five demisemiquavers/32nd notes, in the space of a quaver/eighth note.
- 8({3ABCDE};5) = quintuplet, five demisemiquavers/32nd notes, in the space of a quaver/eighth note, beamed

The triplet is a special case. Strictly speaking, it should be encoded as:  
8(6ABC;3) or 8({6ABC};3).  
Instead though, the following shortcut is permitted:  
(6ABC)  
({6ABC})

Do not forget the rhythmic value within the bracket!

##### 11. Shortcuts

###### 11.1. Repeated figures

! = beginning and end of passage  
f = repeat indication   
The figure will be repeated as often as **f** is repeated after the second **!**. This is only possible within a bar.

###### Example

- !{'8ABAG}!ff = this figure will be repeated twice

###### 11.2. Repeated bars

i = repeat last bar  
'i' always goes between two bar lines.

###### Example

- '4ABAG/i/i/ = the bar will be repeated twice

###### 11.3. Rhythmic patterns

When a certain rhythmic sequence is repeated several times, the rhythmic pattern can be given before the respective note letter names.

The rhythmic sequence ends as soon a different rhythmic value occurs. Make sure that all notes as indicated by the pattern are present at least once.

###### Example

- Instead of **8.A6B8C8.D6E8F** the code can be **8.68ABCDEF**


##### 12. Change of clef

If the clef changes within the music incipit, use **%** to change the clef. Follow this with the new clef and a space.

###### Examples

- %C-1 '2A
- %C-1 $xFC '8B

##### 13. Change of key

If the key changes within the music incipit, use **$** to change the key. Follow this with the new key signature and a space. A key signature can only be changed once per measure. You can cancel the previous key signature with $n or move directly to the new key signature.

###### Examples

- $nBE $xFC
- $xFC

##### 14. Change of time signature

If the time signature changes within the music incipit, use **@** to change the time signature. Follow this with the new time signature and a space.

###### Examples

- @3/2 '1C

##### 15. Abbreviations

Abbreviated forms of notation found within the music, such as tremolos or simile signs for repeats, must be written out in full using the actual notation.

###### Examples

- {'8DDDD} = minim/ half tremolo on D

##### 16. Chords

Enter chords from the highest to the lowest note, separated by a **^**.

###### Example

- 4’’C^’G^E^C

**Obsolete procedures**: In older cataloging programs, the field for encoded notation began with the control character $ followed by the key signature ($xFC for $bBE), and then a character that was entered as a ³ (superscript 3) but displayed as an _ (underscore). Incipits with no key signature started directly with an _.

#### General note (031 $q)

Add any other comments, such as the pitch of transposing instruments, mistakes in the incipit, the text incipit with the original spelling and/or punctuation, or any adjustments you had to make. Enter using your cataloging language.

**Obsolete procedures**: Older RISM cataloging guidelines allowed the symbols **?**, **+**, and **t** to represent standardized remarks. This practice was discontinued with the introduction of Muscat, and instead explanatory notes in natural language are put into the field **General note (031 $q)**. The symbols were the following:
- **?** = Error in the incipit could not be corrected.
- **+** = Error in the incipit has been corrected.
- **t** = The incipit has been transcribed into modern notation.


#### Scoring in movement (031 $z)

In this field, you can indicate the specific scoring for the particular movement in question (such as a movement within a complex vocal piece). List the scoring on one line using RISM instrument abbreviations and in the standard order (described in **Scoring summary [240 $m]**). Use a semicolon to separate instrument families.

##### Examples

- S (Enrico), T (Vanoldo); vl 1, 2, b; [winds]
- S 2 solo; Coro; ob obl; strings, bc
