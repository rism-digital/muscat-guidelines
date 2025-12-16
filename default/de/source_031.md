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
- 1.3.1 = 1. Werk, 3. Satz, 1. Incipit

Die Punkte zwischen den Zahlen werden von Muscat automatisch eingefügt.

Die dreistellige Incipitnummer muss innerhalb eines Datensatzes eindeutig sein. Nummerieren Sie die Incipits fortlaufend und unter Berücksichtigung des betreffenden Datensatzes. Die Incipitnummer sagt nichts darüber aus, wo sich das Incipit in einer Quelle befindet. Die Nummerierung innerhalb der Quelle sollte sich in der Titelbeschreibung widerspiegeln, und etwaige Besonderheiten können in einer Bemerkung erläutert werden. Das bedeutet, dass das Incipit des vierten Lieds innerhalb einer Liedersammlung 1.1.1 wie bei allen anderen Liedern in der Sammlung lautet.

 Die fortlaufende Nummerierung muss auch dann eingehalten werden, wenn Inhalte in der Quelle fehlen. Wenn beispielsweise ein Lied aus einer Sammlung von sechs Liedern fehlt, beginnt die Werknummer jedes Incipits weiterhin mit einer 1. Wenn es sich bei der Quelle um eine dreisätzige Symphonie handelt, aber der Mittelsatz fehlt, werden die Incipits mit 1.1.1 und 1.2.1 (nicht 1.3.1) nummeriert.


#### Satztitel, Tempo (031 $d)

Der Satztitel, das Tempo oder ähnliche Angaben werdn in originaler Schreibweise wiedergegeben. Zeilenumbrüche werden durch den geraden Strich **\|** mit einem Leerzeichen davor und danach gekennzeichnet. Ergänzungen zum originalen Zitat stehen immer in eckigen Klammern; diese sollten einheitlich geschrieben werden. Mehrere Titel oder zusätzliche Tempoangaben können in separaten Feldern hinzugefügt werden. Bleibt die Angabe innerhalb eines Satzes gleich, wird der Titel bzw. das Tempo nur im ersten Incipit angegeben.

##### Beispiele
- All|o
- [vol. 1 p. 17:] N. 1: Recit. et Aria

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

**Gesonderte Regeln für lateinische Texte:** Geben Sie sowohl geistliche als auch weltliche lateinische Texte ein. Wird für das Textincipit als Einordnungstitel benutzt, so wird muss auf genaue Übereinstimmung der Schreibweise geachtet werden. Der lateinische Text wird im Einordnungstitel allerdings nur bis zu dem Trennungszeichen, einem Komma, angegeben. Lateinische Texte, die nicht in der Quelle genannt sind, sondern recherchiert wurden, werden in eckigen Klammern eingetragen.

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

Hier wird das zum Incipit gehörende Taktmaß als Bruch angegeben. Folgendes ist auch erlaubt:

- **c** = tempus imperfectum cum prolatione imperfecta
- **c/** = alla breve
- **3** = proportio tripla; auch **1**, **2**, etc.
- **c3** = proportio tripla
- **c3/2**
- **c.** = tempus imperfectum cum prolatione perfecta
- **o** = tempus perfectum cum prolatione imperfecta
- **o/** = tempus perfectum cum prolatione minore diminutum
- **o.**  = tempus perfectum cum prolatione perfecta

Ändert sich der Takt ständig, können Sie die erste Taktart gefolgt von der zweiten Taktart getrennt durch ein Leerzeichen angeben.

Wenn das Incipit keine Taktart enthält, fügen Sie eine hinzu und geben Sie auch eine Erklärung im Feld **Kommentar zum Incipit (031 $q)**, z. B. "Time signature added". Setzen Sie die ergänzte Taktart nicht in eckige Klammern.

**Altdaten**: Ältere Richtlinien erlaubten hier ein leeres Feld, wenn die Quelle keine Taktart enthielt.

##### Beispiele

- 4/4
- 6/8
- 3/4 4/4

Falls die Taktangabe in der Quelle offensichtlich falsch ist, muss das Taktmaß so angegeben werden, dass es mit dem tatsächlichen Incipit übereinstimmt. Dies kann unter **Kommentar zum Musikincipit ** näher ausgeführt werden.

#### Schlüssel (031 $g)

Wählen Sie einen Schlüssel aus der Auswahlliste aus. Die erste Stelle bezeichnet die Art des Schlüssels. Ein Bindestrich bedeutet moderne Notation. Ein Plus bedeutet Mensuralnotation. Die Zahl bezieht sich auf die entsprechende Notenlinie.

Wenn kein Notenschlüssel in der Quelle vorhanden ist, wählen Sie einen aus der Liste aus und geben eine erläuternde Notiz in **Kommentar zum Incipit (031 $q)**.

#### Gültigkeit (031 $s)

Dieses Feld nicht verwenden! (Es ist nur für Altdaten notwendig.)

#### Musicincipit (031 $p)

Das Musikincipit wird in kodierter Form nach dem Plaine & Easie code (siehe auch [https://www.iaml.info/plaine-easie-code](https://www.iaml.info/plaine-easie-code)) eingegeben. Das Incipit sollte mindestens zwei Takte oder sechs Noten lang sein.

##### 1. Akzidentien
' = in der 1. Oktave hoch  
'' = in der 2. Oktave hoch  
''' = in der 3. Oktave hoch  
, = in der 1. Oktave tief  
,, = in der 2. Oktave tief  
,,, = in der 3. Oktave tief

##### 2. Rhythmische Werte

0 = Longa  
9 = Brevis  
1 = Ganze Note / Semibrevis  
2 = Halbe Note / Minima  
4 = Viertelnote / crotchet / Semiminima  
8 = Achtelnote / quaver / Fusa  
6 = Sechzehntelnote / semiquaver / Semifusa   
3 = Zweiunddreissigstelnote / Demisemiquaver  
5 = Vierundsechzigstelnote / Hemidemisemiquaver  
7 = Einhundertachtundzwanzigstelnote / Semihemidemisemiquaver  
7\. = Choralnote

Punkte werden für punktierte Noten verwendet. Einer Note können mehrere Punkte hinzugefügt werden.

4\. = punktierte Viertelnote / dotted crotchet   
8.. = doppelt punktierte Achtelnote / double dotted quaver

##### 3. Vorschläge

x = Kreuz  
xx = Doppelkreuz  
b = b  
bb = Doppel-B  
n = Auflösungszeichen

##### 4. Tonbuchstaben

C, D, E, F, G, A, B [!]

##### 5. Taktstrich

g = kleiner Vorschlag (ohne rhythmischen Wert, vor dem Tonbuchstaben stehend)  
q = Vorschlag (mit rhythmischem Wert, vor dem Tonbuchstaben stehend)  
qq...r = mehrere zusammengehörige Vorschläge (mit rhythmischem Wert)

##### 6. Pausen

Das '-' (Minuszeichen) steht für eine einzelne Pause. Verwenden Sie '=' (Gleichheitszeichen) für eine Taktpause. Bei mehrtaktigen Pausen folgt dem = die Anzahl der Takte und ein Taktstrich.
- Achtelpause
 - 8-/
- ein Takt Pause
 - -/
 - =1/
- mehrere Takte Pause
 - =35/

##### 7. Taktstrich

/ = Taktstrich  
// = doppelter Taktstrich  
//: = doppelter Taktstrich mit Wiederholung  
:// = doppelter Taktstrich mit Wiederholung  
://: = doppelter Taktstrich mit Wiederholung

##### 8. Weitere Symbole

t = Triller (steht unmittelbar hinter dem Tonbuchstaben)

+ + Haltebogen (folgt unmittelbar auf die Note; nicht zu verwechseln mit einem Bindebogen)  
  () = Fermate (nur ein einzelner Tonbuchstabe oder eine einzelne Pause kann eingeklammert werden; Vorzeichen, Oktave etc. müssen außerhalb der Klammer stehen. Siehe auch **10. Sonderrhythmen**)

Geben Sie keine Bindebögen ein.

##### 9. Balkung

{ = Balkungsbeginn  
} = Balkungsende

###### Beispiel

{qq6'CDEDr}

##### 10. Sonderrhythmen

( = Beginn Sonderrhythmus  
) = Ende Sonderrhythmus

Vor **(** muss der Gesamtwert des Sonderrhythmus stehen. Nach **(** muss der rhythmische Wert der ersten Note stehen, auch dann, wenn er mit dem der Note vor dem Sonderrhythmus identisch ist. Vor **)** muss noch der Zählwert des Sonderrhythmus angegeben werden. Er wird mit **;** von der letzten Note getrennt.

###### Beispiele

- 8(3ABCDE;5) = Quintole, fünf Zweiunddreissigstel, Gesamtwert Achtel.
- 8({3ABCDE};5) = Quintole, fünf Zweiunddreissigstel, Gesamtwert Achtel, mit Balkung

Die Triole ist ein Sonderfall. Sie müsste eigentlich so kodiert werden:   
8(6ABC;3) oder 8({6ABC};3).  
Stattdessen ist folgende Abkürzung erlaubt:  
(6ABC)  
({6ABC})

Bitte nicht den rhythmischen Wert innerhalb der Klammer vergessen!

##### 11. Verkürzte Schreibweisen

###### 11.1. Figurwiederholung

! = Anfang und Ende der Passage  
f = Wiederholungsaufruf   
Die Figur wird so oft wiederholt wie **f** hinter dem zweiten **!** stehen. Diese Funktion ist nur innerhalb eines Taktes möglich.

###### Beispiel

- !{'8ABAG}!ff = diese Figur wird zweimal wiederholt

###### 11.2. Taktwiederholung

i = Taktwiederholungsaufruf  
'i' muss immer zwischen zwei Taktstrichen stehen.

###### Beispiel

- '4ABAG/i/i/ = der Takt wird zweimal wiederholt

###### 11.3. Rhythmisches Muster

Wenn sich eine rhythmische Abfolge mehrmals wiederholt, kann sie den betroffenen Tonbuchstaben als rhythmisches Muster vorangestellt werden.

Das rhythmische Muster endet, sobald ein anderer rhythmischer Wert folgt. Vergewissern Sie sich, dass alle Noten, die im Muster angegeben sind, mindestens einmal vorkommen.

###### Beispiel

- Anstelle von **8.A6B8C8.D6E8F** kann der Code **8.68ABCDEF** stehen


##### 12. Schlüsselwechsel

Verwenden Sie **%** für den Schlüsselwechsel. Der veränderten Globalangabe muss ein Leerzeichen folgen.

###### Beispiele

- %C-1 '2A
- %C-1 $xFC '8B

##### 13. Vorzeichenwechsel

Verwenden Sie **$** für den Vorzeichenwechsel. Der veränderten Globalangabe muss ein Leerzeichen folgen. Eine Tonart kann nur einmal pro Takt geändert werden. Sie können die vorherige Tonart mit $n aufheben oder direkt zur neuen Tonart wechseln.

###### Beispiele

- $nBE $xFC
- $xFC

##### 14. Taktwechsel

Verwenden Sie **@** für den Taktwechsel. Der veränderten Globalangabe muss ein Leerzeichen folgen.

###### Beispiele

- @3/2 '1C

##### 15. Abbreviaturen

Verkürzte Schreibweisen in den Noten, wie Tremolo auf Halbe D oder Faulenzer, müssen ihrer tatsächlichen Notierung gemäß aufgelöst werden.

###### Beispiele

- {'8DDDD} = Tremolo Halbe auf D

##### 16. Akkorde

Geben Sie Akkorde von der höchsten bis zur niedrigsten Note ein, getrennt durch ein **^**.

###### Beispiel

- 4’C^’G^E^C

**Altdaten**: In älteren Katalogisierungsprogrammen begann das Feld für die kodierte Notation mit dem Steuerzeichen $, gefolgt von der Vorzeichen ($xFC für $bBE) und dann einem Zeichen, das als ³ (hochgestellte 3) eingegeben, aber als _ (Unterstrich) angezeigt wurde. Incipits ohne Vorzeichen begannen direkt mit einem _.

#### Kommentar zum Musikincipit (031 $q)

Fügen Sie weitere Anmerkungen hinzu, z. B. die Tonhöhe transponierender Instrumente, Fehler im Incipit, den Text des Incipits mit der ursprünglichen Schreibweise und/oder Zeichensetzung oder etwaige Anpassungen, die Sie vornehmen mussten. Verwenden Sie Ihre Katalogisierungssprache.

**Altdaten**: Ältere RISM-Katalogrichtlinien erlaubten die Symbole **?**, **+**und **t** um standardisierte Anmerkungen zu repräsentieren. Diese Praxis wurde mit der Einführung von Muscat aufgegeben. Stattdessen werden Erläuterungen im Feld **Kommentar zum Musikincipit (031 $q)** gemacht. Die Symbole waren folgende:
- **?** = Fehler im Incipit konnte nicht korrigiert werden.
- **+** = Fehler im Incipit wurde korrigiert.
- **t** = Das Incipit wurde in die moderne Notation übertragen.


#### Besetzung Satz ($z)

In diesem Feld können besondere Angaben zur Besetzung des Satzes (beispielsweise innerhalb von umfangreichen Vokalwerken) eingetragen werden. Aufgeführt werden die Stimmbezeichnungen entsprechend der Standardreihenfolge (beschrieben in **Besetzungshinweis [240 $m]**). Die jeweiligen Stimmgruppen werden durch Semikolon getrennt.

##### Beispiele

- S (Enrico), T (Vanoldo); vl 1, 2, b; [winds]
- S 2 solo; Coro; ob obl; strings, bc
