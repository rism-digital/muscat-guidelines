### Íncipits (031)

The field **Incipit** is used for musical information about the opening few measures of the piece and includes music incipits as well as text incipits. Los íncipits ayudan a identificar las obras y facilitan la comparación de las fuentes entre sí. Para la música instrumental se prefiere el registro de fragmentos de una parte aguda y de una parte grave, como vl 1 y bajo. En el caso de la música vocal-instrumental, incluya íncipits de la voz más aguda y el primer violín o la parte instrumental más aguda.

En caso de que la notación del fragmento que necesita transcribir no pueda representarse con código _Plaine & Easie_, transcriba la música de la manera más fiel posible e incluya una nota aclaratoria al respecto. Puede adjuntar una imagen del íncipit en la fuente para mayor claridad.

Keep in mind that incipit transcription is primarily used for searching and identification, not for replicating the visual appearance of the score. The Plaine & Easie Code is an intentional simplification of Western notation and not all details can (or should) be encoded.

For assistance with transcribing mensural notation, see "Basic Mensural Notation Reference" by Ted Dumitrescu ([http://www.cmme.org/misc/refsheet.pdf](http://www.cmme.org/misc/refsheet.pdf))).

<!-- Note to translators: If you know of a standard reference document or website for transcribing mensural notation in your language, please use that instead. If not, feel free to link to this English document. -->  

_MARC export note:_  
Records that contain an incipit (anything in field 031) receive $2pe upon saving, indicating that the incipit was created using the Plaine & Easie code.

#### Número de obra, número de movimiento, número de íncipit (031 $a, b, c)

**Campos requeridos en caso de que se utilice cualquier otro campo de esta sección.**

The incipit number consists of three digits, which stand for work, movement, and incipit.

El primer dígito es siempre 1. The work number refers to the position of the incipit in the record in question, not its position in the source as a whole. Works in RISM are cataloged in separate records using a parent/child hierarchy, so the each record only has one work.

Movements refer to both the work as a whole but also significant sections of a work, whether they are technically movements (such as a symphony) or different sections (such as a recitative and aria). Movement numbers can be identical if multiple incipits are entered for the movement.

The incipit number is embedded within the hierarchy of the movement or work. Identical movement numbers but different incipit numbers mean that the incipits sound simultaneously, such as a vl 1 and bass.

##### Examples

- Texto de una parte vocal faltante
- Íncipits literarios en el idioma original de la obra, cuando la fuente presenta una versión traducida
- 1.2.1 = 1st work, 2nd movement, 1st incipit
- 1.3.1 = 1st work, 3rd movement, 1st incipit

Periods between the numbers are automatically added by Muscat.

The three-figure incipit number must be unique within a record. Number incipits consecutively and with respect to the record in question. The incipit number may not imply any comment on the position of the item in a source. Numbering within the source should be reflected in the title description, and any particularities can be explained in a note. This means that the incipit for the fourth song in a song collection will be 1.1.1, as with all songs in the collection.

 Consecutive numbering must be followed even if content is missing from the source. For example, if one song is missing from a collection of six songs, the work number of each incipit will still start with a 1. If the source is a three-movement symphony but the middle movement is missing, the incipits will be numbered 1.1.1 and 1.2.1 (not 1.3.1).


#### Título del movimiento, tempo (031 $d)

Registre el título del movimiento y el tempo –o indicaciones similares–, si aparecen especificados, tal como figuran en la fuente. Use **\|** (the vertical pipe) with a single space before and after the sign to show a line break. Use corchetes para indicar agregados al original; los agregados deben tener una ortografía consistente. Pueden añadirse múltiples títulos o marcas de tempo adicionales en campos separados. Si registra varios íncipits para los cuales el título y la indicación de tempo coinciden, ingrese el dato solo en el primer íncipit.

**Obsolete procedures**: Older RISM guidelines allowed the phrase "Without tempo" to indicate that a movement has several tempo indications, of which one or several are not known. Multiple tempo indications were entered after each other, separated by semicolons.


#### Voz/instrumento (031 $m)

Registre la parte vocal o instrumental correspondiente al íncipit siguiendo la lista de **abreviaturas de instrumentos de RISM**. Use **V** para una parte vocal desconocida e **i** para una parte instrumental desconocida. Enter **i** for an unknown instrumental part. Indique la afinación del instrumento en el campo **Nota general**. If the instrument is a transposing instrument, you may enter it at notated pitch or at sounding pitch. In the field **General note (031 $q)**, indicate which option you used.

##### Examples

- |
- Coro T
- org with text

**Obsolete procedures**: Older RISM guidelines required music incipits for transposing instruments to be entered at sounding pitch.

#### Personaje (031 $e)

Registre el nombre estandarizado del personaje en este campo. If you fill out this field, make sure to also fill out the field **Dramatic role named (595)**. Indique cualquier agregado editorial con corchetes. Señale cualquier información dudosa con un signo de interrogación.

#### Text incipit (031 $t)

El íncipit literario consiste en las primeras palabras de una pieza o sección y puede equivaler al primer verso, la primera frase u otro grupo de palabras del texto que tenga sentido lingüístico. Los íncipits literarios sirven para identificar el texto utilizado y no precisan corresponderse con la longitud del íncipit musical necesariamente. Los mismos pueden registrarse sin importar si se ingresa un íncipit musical o no. Note that separate rules apply to texts in Latin (see below).

Los íncipits literarios se presentan de forma estandarizada. Registre el íncipit literario con ortografía moderna. Refer to the index **Title/text incipits** to help standardize your entry. Registre íncipits nuevos en caso de el índice no los incluya.

Do not put portions of the text in square brackets or supply missing words. Omita los signos de puntuación y las repeticiones del texto.

Las tildes deben usarse sólo si aparecen en el diccionario o si son gramaticalmente correctas. Escriba los números de principio del texto como palabras. Upper- and lower-case letters follow the rules of the respective language, except that designations for God (Herr, Dio, Dieu, Signore, Lord, etc.) always start with a capital letter. Upper- and lower-case letters follow the rules of the respective language, except that designations for God (Herr, Dio, Dieu, Signore, Lord, etc.) always start with a capital letter.

Omita el texto por completo si no puede leerlo y añada una nota que diga “Texto ilegible” o algo similar.

En lenguas romances, los apóstrofos van seguidos inmediatamente por el texto, sin que medien espacios. La excepción a esta regla se da cuando la primera letra de una palabra es remplazada por un apóstrofo (por ejemplo: Fra l’amante e ‘l genitor).

En este campo también pueden registrarse textos relacionados que no aparezcan en la fuente, pero igualmente puedan vincularse a ella por verificación o derivación. En este caso, ponga todo el texto entre corchetes. Among these texts are:

- Texts if a vocal part is missing
- Text incipits in the original language of the work when the source contains a translated version
- Texts of vocal compositions which became the theme of a variation or the basis of an instrumental arrangement

**Non-Latin scripts:** If your source has a text incipit that uses non-Latin letters or characters (Cyrillic/Greek/Hebrew/Korean etc. alphabet, Chinese characters, etc.) enter the **Text incipit** using the original script. Las traducciones o transliteraciones son opcionales y pueden añadirse en campos de íncipit literario adicionales. Add translations not on the source in square brackets. Se puede traducir a cualquiera de los idiomas RISM.

**Reglas especiales para textos en latín** : ingrese los textos en latín, tanto sacros como seculares. The field is linked to the file **Title/text incipits**. Within the file **Title/text incipits**, a term preceded by the indicator **t** means that you can get information about the exact liturgical context, variant versions, and other matters. Si el íncipit literario se usa además como Título Uniforme, asegúrese de que la ortografía sea idéntica; no obstante, recuerde que en los títulos uniformes el texto en latín se ingresa sólo hasta la coma. Use corchetes para registrar textos en latín que no aparecen en la fuente pero han sido determinados por vía de la investigación.

Los textos normalizados en latín suelen corresponderse con las versiones del _Liber usualis_. En RISM, estos textos incluyen generalmente una coma. Por ejemplo, si busca el texto “Et in terra pax”, encontrará alrededor de una docena de resultados, pero sólo uno incluye una coma, y verá que esta fuente ha sido usada 4800 veces en la base de datos. Se trata del registro que deseamos usar como íncipit –asumiendo que el mismo se corresponda con su fuente–. If your text incipit is only "Et in terra pax" then this means your source (1) contains only these words or (2) continues in a way that is different from the _Liber usualis_. Por supuesto, cabe la posibilidad de que esto suceda. Sin embargo, en la mayoría de los casos se optará por la versión con la coma.


#### Tonalidad o modo (031 $r)

Select the key or mode of the incipit from the list.

**Obsolete procedures**: Older RISM cataloging guidelines allowed multiple key signatures to be entered in this field, separated by a semicolon. This practice was discontinued with the introduction of Muscat.

#### Armadura de clave (031 $n)

Ingrese **x** para armaduras con sostenidos o **b** para armaduras con bemoles, seguido de las letras mayúsculas correspondientes a las alturas alteradas por la armadura. If a piece is clearly in a certain key but a sharp or flat is not in the key signature, the missing sharps or flats may be added in square brackets.

Si no hay armadura de clave, deje el campo en blanco.

##### Examples

- xF = F is sharp = G major or E minor
- bBE = B and E are flat = B-flat major or G minor
- xFC[G] = F and C are sharp in the source but the piece is clearly in A major, so the last sharp is added in square brackets

#### Indicación de compás (031 $o)

Registre la indicación de compás como una fracción. También se permiten las siguientes opciones:

- **c** = common time or tempus imperfectum cum prolatione imperfecta
- **c/** = cut time, alla breve
- **3** = proportio tripla; also **1**, **2**, etc.
- **c3** = proportio tripla
- **c3/2**
- **c.** = tempus imperfectum cum prolatione perfecta
- **o** = tempus perfectum cum prolatione imperfecta
- **o/** = tempus perfectum cum prolatione minore diminutum
- **o.**  = perfect time, tempus perfectum cum prolatione perfecta

Si la métrica cambia constantemente, puede escribir la primera indicación de compás seguida de la segunda, separadas por un espacio.

If the incipit is without a time signature, add one and also add an explanation in the field **General note (031 $q)** such as "Time signature added." Do not put the inferred time signature in square brackets.

**Obsolete procedures**: Older guidelines allowed a blank field here if the source lacked a time signature.

##### Examples

- 4/4
- 6/8
- 3/4 4/4

If the time signature in the source is obviously wrong, correct it to match the incipit given. Incluya una nota aclaratoria al respecto en el campo **Nota general**.

#### Clave (031 $g)

Seleccione una clave de la lista. La letra indica el tipo de clave. El guión (-) indica notación moderna. El signo más (+) indica notación mensural. El número se refiere a la posición de la clave en el pentagrama.

If no clef is on the source, select one from the list and include an explanatory note in the field **General note (031 $q)**.

#### Validez (031 $s)

¡No ingrese nada en este campo! (Solo se usa para datos antiguos). (It is only used for old data.)

#### Íncipit musical (031 $p)

Registre el íncipit musical de forma codificada, haciendo uso del código _Plaine & Easie_ (véase también [https://www.iaml.info/plaine-easie-code](https://www.iaml.info/plaine-easie-code)). Es necesario que el íncipit tenga por lo menos dos compases o seis notas de longitud.

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
7\. = notación neumática

Se usan puntos para las notas apuntilladas. Se pueden agregar varios puntos a una nota.

4\. = negra con puntillo  
8.. = corchea con doble puntillo

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

The '-' (minus sign) is for a single-note rest. Utilice “=” (signo igual) para indicar un silencio de compás. For multiple measures of rest, follow the = with the number of measures and a bar line.
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

{qq6’CDEDr}

##### 9. Beaming

{ = beginning of beaming  
} = end of beaming

###### Example

{qq6’CDEDr}

##### 10. Special rhythms

( = beginning of special rhythm  
) = end of special rhythm

La duración total del grupo debe escribirse antes de **(**. El valor rítmico de la primera nota debe escribirse después de **(**, aunque sea idéntico al de la nota inmediatamente antes de la sección con figuras irregulares. El número de notas del grupo debe indicarse antes de **)**, separado de la última nota por **;**. It is separated from the last note by **;**.

###### Examples

- 8(3ABCDE;5)   = quintuplet, five demisemiquavers/32nd notes, in the space of a quaver/eighth note.
- 8({3ABCDE};5) = quintuplet, five demisemiquavers/32nd notes, in the space of a quaver/eighth note, beamed

El tresillo constituye un caso especial. En sentido estricto, debería codificarse como:  
8(6ABC;3) o 8({6ABC};3)

Do not forget the rhythmic value within the bracket!

##### 11. Shortcuts

###### 11.1. Repeated figures

! ! ! ! ! ! ! ! ! ! ! ! ! ! ! ! ! ! ! Figuras repetidas</strong>  
! = inicio y fin de un pasaje  
f = repetir la indicación  
El pasaje será repetido cada vez que aparezca  **f**  después del segundo **!**. This is only possible within a bar.

###### Example

- !{'8ABAG}!ff = this figure will be repeated twice

###### 11.2. Repeated bars

i = repeat last bar  
'i' always goes between two bar lines.

###### Example

- '4ABAG/i/i/ = the bar will be repeated twice

###### 11.3. Rhythmic patterns

_Ejemplos_:

The rhythmic sequence ends as soon a different rhythmic value occurs. Make sure that all notes as indicated by the pattern are present at least once.

###### Example

- _Ejemplo:_  
  **8.A6B8C 8.D6E8F** puede reemplazarse por **8.68ABCDEF**  
  La secuencia rítmica se termina apenas se presenta un valor rítmico distinto.


##### 12. Change of clef

If the clef changes within the music incipit, use **%** to change the clef. Follow this with the new clef and a space.

###### Examples

- %C-1 '2A  
  %C-1 $xFC '8B  
  @3/2 '1C  
  $nBE $xFC
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

**11.2 Compases repetidos**  
i = repetir el último compás.  
La “i” siempre va entre dos barras de compás

###### Example

- 4’’C^’G^E^C

**Obsolete procedures**: In older cataloging programs, the field for encoded notation began with the control character $ followed by the key signature ($xFC for $bBE), and then a character that was entered as a ³ (superscript 3) but displayed as an _ (underscore). Incipits with no key signature started directly with an _.

#### Nota general (031 $q)

Utilice este campo para registrar cualquier otro comentario, como la afinación de los instrumentos transpositores, la presencia de errores en el íncipit, el texto del íncipit con la ortografía y/o puntuación original, o cualquier otro ajuste que desee hacer. Regístrelo usando su idioma de catalogación.

**Obsolete procedures**: Older RISM cataloging guidelines allowed the symbols **?**, **+**, and **t** to represent standardized remarks. This practice was discontinued with the introduction of Muscat, and instead explanatory notes in natural language are put into the field **General note (031 $q)**. The symbols were the following:
- **?** = Error in the incipit could not be corrected.
- **+** = Error in the incipit has been corrected.
- **t** = The incipit has been transcribed into modern notation.


#### Plantilla/orgánico del movimiento (031 $z)

En este campo puede indicar la plantilla/orgánico específica para el movimiento en cuestión (por ejemplo, el caso de un movimiento dentro de una pieza vocal compleja). List the scoring on one line using RISM instrument abbreviations and in the standard order (described in **Scoring summary [240 $m]**). Use punto y coma para separar familias de instrumentos.

##### Examples

- S (Enrico), T (Vanoldo); vl 1, 2, b; [winds]
- S 2 solo; Coro; ob obl; strings, bc
