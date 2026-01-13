### Besetzung (594)

Das Feld **Besetzung** wird verwendet, um alle Stimmen oder Instrumente anzugeben, die benötigt werden, um das Stück auszuführen. Als „Besetzung“ werden auch „Ausführungsanweisungen“, „Ausführungsmedium“ oder „Instrumentierung“ (zu der auch die Vokalstimmen zählen) bezeichnet.

Während das Feld **Besetzungshinweis (240 $m)** die Besetzung eines Werks in Kurzform angibt, gibt das Feld **Besetzung** die vollständige Besetzung eines Werks an. Aus diesem Grund muss der **Besetzungshinweis** immer mit den Angaben in Besetzung korrelieren.

Die Besetzung sollte so vollständig wie möglich sein, unabhängig davon, ob die vorliegende Quelle vollständig ist.

#### Besetzung (594 $b)

**Pflichtfeld**

Geben Sie die Stimmen oder Instrumente mittels RISM-Abkürzungen ein. Bei der Eingabe können Sie das Autocomplete zu Hilfe nehmen. Eine alphabetische Liste der Instrumentenbezeichnungen finden Sie in der RISM Abkürzungsliste. Allgemeine Instrumentenbezeichnungen (z. B. strings - Streicher) stehen immer in englischer Sprache, die einzelnen Instrumente werden nach Möglichkeit in italienischer Sprache angegeben. Andere spezifische, regionale Instrumente sollten in der Originalsprache geschrieben werden.

Instrumentalstimmen beginnen mit einem Kleinbuchstaben und Vokalstimmen mit einen großen Anfangsbuchstaben. Soloinstrumente werden mit **iSol:** eingeleitet.

Wenn die vollständige Besetzung nicht angegeben ist oder Ihre Quelle unvollständig ist, sollten Sie die Besetzung aus dem Titel, dem Material selbst oder anderen Referenzwerken ermitteln. Ist die Besetzung unbekannt, schreiben Sie **no indication**. Jede Unsicherheit kann im Feld **Bemerkungen (500)** näher erläutert werden.

Wenn Sie einen bezifferten Bass haben, geben Sie das Instrument wie gewohnt ein, z. B. **b**, **bc**, **org** usw. (siehe auch die Tabellen im Abschnitt **Bezifferter Bass in Partituren und/oder Stimmen** als Orientierungshilfe für verwandte Felder).

Für transponierende Instrumente sind die Standard-Transpositionen in der Abkürzungsliste aufgeführt. Wenn die Stimmung in Ihrer Quelle von der Standardstimmung abweicht, geben Sie die Stimmung von der Quelle an (siehe: **in A**). Für Instrumente, die normalerweise in C stehen, muss "in C" nicht aufgeführt werden. Im Zweifelsfall sollten Sie die Stimmung auflisten. Die Instrumentenstimmungen sollten in Englisch angegeben werden. Siehe **Anhang: Tonarten**.

Wenn Sie ein Stück mit einer von der Quellenangabe abweichenden Besetzung haben, z. B. Musik für die Stimme Tenor 2 in einem Quinta vox (V 5)-Stimmbuch, verwenden Sie die spezifischere Besetzung, falls vorhanden. Enthält die Quelle keine solche Angabe, Sie können die tatsächliche Stimme jedoch mit Sicherheit bestimmen, dürfen Sie diese eingeben. Bei Unsicherheiten geben Sie einfach die Stimme wie in der Quelle an.

Wenn man versucht, zwischen ähnlichen Begriffen zu entscheiden, ist es in der Regel am besten, sich an der Quelle zu orientieren. Wenn der Name des Instruments in Ihrer Quelle von den RISM-Abkürzungen abweicht, können Sie den Begriff im Feld **Bemerkungen (500)** nennen.

Für die Nennung der Besetzung gilt folgende Reihenfolge:

- Solostimmen
- Chor
- Soloinstrumente
- Streichinstrumente
- Holzbläser
- Blechbläser
- Zupfinstrumente
- Schlagwerk
- Tasteninstrumente
- Basso continuo

Genannt werden die Stimmen jeweils von der höchsten zur tiefsten Stimmlage. Geben Sie ein Instrument pro Zeile ein. Alternativbesetzungen werden in Klammern der originalen Besetzung angehängt.

##### Beispiele

- S
- A
- T
- B
- Coro 1: T
- Coro 1: A
- Coro 2: S
- iSol: pf
- vl
- vla
- vlc
- b
- ob (fl)
- cl in A
- tr
- org

_MARC-Exporthinweis: Die Felder 594 $b und $c werden verkettet und als 594 $a exportiert._

#### Anzahl (594 $c)

Hier wird die Anzahl der jeweiligen Stimmen angegeben. Sind zwei Stimmen des gleichen Instruments beteiligt, erfolgt die Bezeichnung im Feld **Besetzung** und hier im Feld **Anzahl** die Angabe **2**.

Die Zahl bezieht sich auf die Instrumentenbezeichnung, nicht auf die Anzahl der Personen, die zum Spielen der Musik erforderlich sind, oder auf die Anzahl der in Ihrer Quelle erhaltenen Stimmen. Zum Beispiel bedeutet "Coro S" und "2", dass der Sopran in Sopran 1 und Sopran 2 aufgeteilt ist.  Ebenso bedeutet "vl" und "2", dass die Geigen in Violine 1 und Violine 2 aufgeteilt sind.

Bei unvollständigen Quellen oder wenn die Zahl unbekannt ist, kann anstelle einer Zahl ein **X** eingegeben werden.

##### Beispiele

- Für ein Stück mit Violine 1 und Violine 2:  
  vl  
  2
- Nur 1 Viola-Stimme:  
  vla  
  1
- Oboe 1 und Oboe 2:  
  ob  
  2
- Nur 1 Klarinettenstimme:  
  cl  
  1
- French horns present but it is not known how many:  
  cor  
  X   
