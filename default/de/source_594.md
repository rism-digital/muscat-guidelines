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

For non-C instruments, standard tunings are listed in the abbreviation list. If the tuning in your source deviates from the standard tuning, list the tuning in the source (see: **in A**). For instruments that are normally in C, "in C" does not need to be listed. If in doubt, list the tuning. Instrument tunings should be given in English. See **Appendix: Keys**.

If you have a piece with an instrumentation that differs from the label on the source, such music for the Tenor 2 voice in a Quinta vox (V 5) partbook, use the more specific instrumentation if available. If the music is lacks such an indication but you are able to determine the actual voice with certainty, you are permitted to enter the actual voice. If there is any uncertainty, simply enter the part as on the source.

When trying to decide between similar terms, it is usually best to go with what is on the source. If the name of the instrument in your source deviates from the RISM abbreviation, you may write the term as on the source in the field **General note (500)**.

List the scoring in the following order:

- Solo voices
- Chorus
- Solo instruments
- Strings
- Woodwinds
- Brass
- Plucked instruments
- Percussion
- Keyboard instruments
- Basso continuo

List parts from the highest to the lowest range. Enter one instrument per line. Add alternative scoring possibilities to the original requirements in parentheses.

##### Examples

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

_MARC export note: The fields 594 $b and $c are concatenated and exported as 594 $a._

#### Number (594 $c)

Indicate the total number of parts here. If a piece includes two parts for the same instrument, enter the single instrument in the field **Scoring** and **2** in the field **Number**.

The number refers to the music, not to the number of people needed to play the music or the number of parts preserved in your source. For example, "Coro S" and "2" means that the soprano part is divided into soprano 1 and soprano 2.  Likewise, "vl" and "2" means that the violins are divided into violin 1 and violin 2.

For incomplete sources or if the number is unknown, an **X** can be entered instead of a number.

##### Examples

- For a piece with violin 1 and violin 2:  
  vl  
  2
- Only 1 viola part:  
  vla  
  1
- Oboe 1 and oboe 2:  
  ob  
  2
- Only 1 clarinet part:  
  cl  
  1
- French horns present but it is not known how many: cor X  
