### Título uniforme (240)

The field **Standardized title** is for the title in a standardized form. The standardized title brings compositions together under the same title which, despite having a variety of names, are the same or similar. También se lo conoce como título estandarizado.

_MARC export note:_  
The field **Standardized title** is exported as MARC 130, with the same subfields as 240, when the record does not include a name in the field **Composer/Author (100)**.

#### Título uniforme (240 $a)

**Campo requerido.**

Enter the title in a standardized form. The field is linked to the **Title/Text incipit** index through $0. Indicate questionable information with a question mark at the end (for example, **Die Zauberflöte?**). Do not use square brackets or parentheses. Registre versiones alternativas en el campo **Título adicional (730)**.

Un título uniforme puede generarse a partir de:

1. Títulos distintivos
2. Íncipits literarios
3. Géneros
4. Indicaciones de tempo

##### 1. Títulos distintivos

Distinctive titles include all kinds of stage works, oratorios, cantatas, and songs, and also certain kinds of instrumental music (such as character pieces from the 18th century with a distinctive, individual title).

Enter the distinctive title in standard spelling as in (1) New Grove, (2) MGG, (3) catalogs of works, and/or (4) other reference books. No omita artículos iniciales (el, la, un, una, the, a, an, der, die, le, l’, etc.).

Los nombres o apodos por los cuales se conoce popularmente una obra (tales como “Eroica” o “Misa Nelson”) no cuentan como títulos uniformes. Such names are entered in the field **Additional titles (730 $a)**.

In English, sentence case is preferred. In French, the simplified French rules ([Règles simplifiées](https://fr.wikipedia.org/wiki/Usage_des_majuscules_en_fran%C3%A7ais#Titres_d%E2%80%99%C5%93uvres_ou_de_p%C3%A9riodiques)) are preferred.

###### Examples

- _Songs_ (para piezas vocales)
- _Pieces_ (para piezas genéricas)
- _Movements_(un único movimiento de una pieza instrumental sin indicación de tempo ni de carácter)
- L'italiana in Algeri

##### 2. Text incipit

Enter the text incipit as the standardized title for vocal pieces if there is no distinctive title.

Aplique los mismos principios a casos de recitativo y cavatina, _scena</em> y rondó, o combinaciones similares. If a source consists of a recitative and aria or a scena and aria, the text incipit of the aria is always used as the standardized title. If you have a single opera aria from an opera whose title is unknown, enter the text incipit of the aria.

With cantatas, on the other hand, the text of the first vocal piece functions as the standardized title, regardless of whether it is a recitative, aria, or chorus.

Sin embargo, utilice el género en el caso de las misas, los réquiem, las obsequias, letanías y composiciones para el Oficio Divino. The same is true for complete operas and oratorios whose titles are unknown.

Utilice mayúscula inicial para los nombres de la deidad (Dios, God, Herr, Dio, Dieu, Signore, Lord, etc.). When entering text incipits, use the orthographic rules of each respective language to dictate use of upper or lower case letters. Omit punctuation marks and repetitions within the incipit. If the item is clearly a translation, enter the standardized title in the original language.

Asegúrese de que el íncipit literario que registra en este campo sea idéntico al ingresado en el campo **Íncipit literario (031 $t)**. With Latin texts, use the text that precedes the comma (from the list in the appendix) as a standardized title but use the text incipit in its entirety for the text incipit.

###### Examples

- Der Mond ist aufgegangen
- Gloria, in excelsis Deo et in terra pax]

##### 3. Genre

Use the genre of the piece as the standardized title if you have neither a distinctive title nor a text incipit. In most cases, enter the genre in English and in the plural (such as **Operas**). Note that for some genres, a corresponding **Subject heading (650)** is used. Consult the appendix **Standardized title – Subject heading** in the **Guidelines** for assistance.

###### Examples

- **Extractos** : en casos en los que sólo se cuente con una o varias partes de la obra completa.
- **Fragmentos** : en casos en los que sólo se cuente con fragmentos de la obra completa.

##### 4. Tempo indications

Enter the tempo indication if the genre cannot be determined. If none of these options are available, use the following terms:

- Songs (vocal pieces)
- Pieces (a generic piece)
- Movements (a single movement of an instrumental piece without a tempo indication and of indeterminate character)

###### Examples

- Voces solistas
- Cuerdas

#### Special rules

##### Collections

En este caso, el título se formula con un número más el género (en inglés y en plural, a la manera de los descriptores). Enter an Arabic numeral indicating how many works belong to the collection, followed by a genre that is as comprehensive as possible.

###### Examples

- 25 Arias
- 3 Instrumental pieces

##### Composite volumes

Enter a number corresponding to the number of items involved plus the English word "Items."

###### Example

- 11 Items

##### Variations

Enter **Variations** as the standardized title here. In the field **Additional title (730)**, enter the piece the work is based on, when known, and select **Variations** next to **Arrangement statement**.

##### Insertions

Enter the text incipit of the inserted piece as the standardized title here. In the field **Additional title (730)**, enter the name of the opera or larger work and select **Inserts** next to **Subheading.**

##### Non-Latin scripts

If your source has a standardized title that uses non-Latin letters or characters (Cyrillic/Greek/Hebrew/Korean etc. alphabet, Chinese characters, etc.) enter the **Standardized title** using the original script. Translations or transliterations are optional and may be added in the field **Additional title (730)**.

#### Tonalidad o modo (240 $r)

Seleccione el calificador **Arreglo** si la pieza es un arreglo de otra obra.

Tenga en cuenta que los reemplazos de texto y las transposiciones no se consideran arreglos. In such cases, enter the name of the responsible person, if known, under **Additional personal name (700)**. Although the works are not considered arrangements, the person is referred to there as "Arranger".

También es necesario distinguir los arreglos respecto de las obras independientes (elaboraciones libres) tales como variaciones, paráfrasis, parodias y fantasías sobre temas de la obra original.

#### Declaración de arreglo (240 $o)

Este campo registra aspectos formales especiales del documento que resulten relevantes. Seleccione una opción entre las siguientes:

- **Excerpts**: if only one or several sections of the complete work are present
- **Fragments**: if only fragments of the work are present
- **Variaciones**.

#### Tonalidad o modo (240 $r)

**Required if the key can be determined with certainty.**

Seleccione la tonalidad de toda la obra (incluso en el caso de los extractos).

En el caso de los arreglos, ingrese la tonalidad de la obra original. If the original key cannot be determined, enter the key of the source in hand; in this case, though, enter a corresponding note in the field **General note (500)**.

No ingrese ninguna tonalidad los siguientes casos: óperas, oratorios y cantatas, recitativos sin su aria respectiva y obras para las cuales no puede establecerse una tonalidad claramente.

Do not enter a key for: operas, oratorios, and cantatas; recitatives without an ensuing aria; and works for which a key cannot be clearly established.

Consulte los apartados “Modos eclesiásticos” –para los modos griegos occidentales y bizantinos– y “Tonalidades” –para lista de tonalidades– en la sección **Abreviaturas y términos generales**.

The following Western church modes are available:
- 1st tone (Dorian)
- 1st tone (Dorian), transposed
- 2nd tone (Hypodorian)
- 2nd tone (Hypodorian), transposed
- 3rd tone (Phrygian)
- 3rd tone (Phrygian), transposed
- 4th tone (Hypophrygian)
- 4th tone (Hypophrygian), transposed
- 5th tone (Lydian)
- 5th tone (Lydian), transposed
- 6th tone (Hypolydian)
- 6th tone (Hypolydian), transposed
- 7th tone (Mixolydian)
- 7th tone (Mixolydian), transposed
- 8th tone (Hypomixolydian)
- 8th tone (Hypomixolydian), transposed
- 9th tone (Aeolian)
- 9th tone (Aeolian), transposed
- 10th tone (Hypoaeolian)
- 10th tone (Hypoaeolian), transposed
- 11th tone (Ionian)
- 11th tone (Ionian), transposed
- 2th tone (Hypoionian)
- 12th tone (Hypoionian), transposed

The following Byzantine church modes are available:
- Ēchos prōtos (First mode of Byzantine music)
- Ēchos deuteros (Second mode of Byzantine music)
- Ēchos tritos (Third mode of Byzantine music)
- Ēchos tetartos (Fourth mode of Byzantine music)
- Ēchos plagios prōtos (First plagal mode of Byzantine music)
- Ēchos plagios deuteros (Second plagal mode of Byzantine music)
- Ēchos barys (Third plagal mode of Byzantine music)
- Ēchos plagios tetartos (Fourth plagal mode of Byzantine music)

**Obsolete procedures**: Older RISM cataloging guidelines allowed multiple key signatures to be entered in this field, separated by a semicolon. This practice was discontinued with the introduction of Muscat.

#### Tonalidad o modo (240 $r)

**Required field except for the following: operas and oratorios with the standard instrumentation V (X), Coro, orch**

If you have sketches or collections, enter a scoring summary if it makes sense to do so.

Enter a brief scoring (instrumentation) summary of the overall medium of performance for the work here. Ingrese un máximo de cuatro elementos. Separate each element of the scoring summary with commas. A detailed description of the instrumentation is entered in the field **Total scoring (594)**. The entire scoring summary goes in one line; repeat the field only to indicate alternative instrumentations (see below).

Use los términos de la lista de **Abreviaturas**. Write out any terms that are not contained in this list in full and in English.

Ingrese los grupos de instrumentos en el siguiente orden:

- Voces solistas
- Coro
- Instrumento solista
- Cuerdas
- Vientos-madera
- Vientos-metal
- Instrumentos de cuerda pulsada
- Percusión
- Instrumentos de cuerda pulsada
- Bajo continuo

Utilice **V** para indicar una parte vocal desconocida e **i** para remitirse a un instrumento desconocido. Indique un número desconocido de partes con **(X)**. When more than one of the same voice or instrument is indicated, place the number in parentheses after the part designation, such as **B (2)**. Also use **V** to group together several different vocal parts, such as **V (8)**.

Specify solo instruments only if they have a continuous solo function in relation to an orchestra, especially in a solo concerto. Do not list a part here if it only has occasional solo passages, such as an oboe solo in a section of a cantata.

In the case of arrangements, the scoring summary refers to the personnel required in the present source, not in the work on which an arrangement is based. If the instrumentation of the original work is known, specify it in the field **General note (500)**. In the case of a **Collection**, only use the field if the particular scoring is applicable to all the works contained in the collection.

This field may be repeated in cases where alternative instrumentation is suggested, such as a song that is for either soprano or tenor. In such cases, enter each possible instrumentation in a separate field: for example, **S, pf** on one line and **T, pf** on the next.

If you have a figured bass, enter the instrument as usual, such as **b**, **bc**, **org**, etc. (but see the tables in the section **Figured bass in scores and/or parts** for guidance with related fields).

Omita el resumen de plantilla/orgánico si los medios interpretativos se desconocen o resultan inciertos.

##### Examples
- A, Coro, orch
- Bariton, pf
- V (3), strings, bc
- V (4), Coro, orch, org   _for a mass_
- cl, orch _for a clarinet concerto_

Use the following standard instrumentation when applicable.

String quartet
- vl (2), vla, vlc

String quintet (2 violas)
- vl (2), vla (2), vlc

String quintet (2 cellos)
- vl (2), vla, vlc (2)

String quintet (with double bass)
- vl (2), vla, vlc, cb

Piano trio
- vl, vlc, pf

Wind quintet
- fl, ob, cl, cor, fag

Flute quartet (all flutes)
- fl (4)

Flute quartet (flute with strings)
- fl, vl, vla, vlc
