## Cataloging special types of sources

This section describes how to catalog special types of sources: collections, composite volumes, contrafacta, compilations, parodies, insertion arias, mixed materials (manuscripts and printed items stored together), music in periodicals, music in non-music publications, collected works (sometimes called "monuments"), librettos, treatises, keyboard arrangements, and sources from other RISM Series B publications.

### Collections

In RISM, the word _collection_ refers to any item (whether manuscript or printed) that contains two or more pieces. This includes both intentional collections or anthologies, as well as items that were not necessarily intended as collections by their creators (such as a piano sonata with a short march on the last page).

Collections in RISM have a parent/child hierarchy, meaning there is one main entry (parent record) that describes the collection as a whole, and individual entries (child or analytical records) that describe each piece therein separately.

Los registros madre de colección no pueden albergar registros madre de colección de manuscritos. There are no smaller collections within collections, even though the item itself may be structured this way. Instead, use a flatter hierarchy by means of child records and explain the structure, makeup, or organization of the item in a note. For example, if a collection consists of a single march followed by a set of six sonatas, you will create 1 parent record and 7 individual entries, one for each piece. Even if the six sonatas can be considered as a unit, they must be described separately. The parent record can explain the organization of the collection and notes in the child records can explain that each sonata is part of a set.

When cataloging collections, note that:

1. La entrada principal de la colección (registro madre) debe contener información que aplique a toda la colección.
2. Any information that is relevant only for some sections of the collection should be entered in the child record.

Si las obras de la colección son de distintos compositores o presentan diferente plantilla/orgánico, tipo de fuente, etc., no ingrese estos datos en el registro madre.


### Composite volumes

Un **Volumen compuesto** es un volumen integrado por documentos que fueron creados por separado y encuadernados juntos posteriormente, usualmente por un propietario o una institución. En este conjunto se incluyen tanto los volúmenes en los que una suma de ítems impresos fue encuadernada en conjunto, como también aquellos en los que piezas impresas aparecen encuadernadas junto a manuscritos. There are many other names for such volumes in English: binders' collection, binders' volume, bound sheet music, bound-with, collectors' volume, factitious volume, nonce volume, recueils factices, Sammelband, tract volume.

Hay dos maneras de señalar la presencia de volúmenes compuestos. La primera y más simple consiste en dar a los ítems la misma signatura; también resulta útil una nota de encuadernación. La segunda forma consiste en utilziar la plantilla para volúmenes compuestos.

El registro de volúmen compuesto sirve como medio para vincular los ítems en un único registro, proveyendo, de esa manera, al usuario un panorama conveniente de todos los contenidos de un volumen encuadernado.

Es conveniente que los registros de volúmenes compuestos sean simples. In principle, the record simply describes the binding and serves as a means to connect the individual items to each other.

Do not confuse composite volumes with collections; see "Collections," above, for the use in RISM. Además, no hay que confundir los volúmenes compuestos con las ediciones impresas: una edición impresa es una unidad bibliográfica única que fue publicada por el editor como tal. Tanto las colecciones como las ediciones impresas pueden contener varias piezas. In contrast to this, composite volumes bring together disparate units: for example, a printed collection of madrigals from 1604, a manuscript of a motet from 1620, and a printed edition of madrigals from 1614.

Tal como con los registros madre de colección, la información consignada en el registro de volumen compuesto debería aplicar a todos los componentes del volumen, teniendo en cuenta que la información detallada en relación con la música corresponde a los registros bibliográficos respectivos. No cree registros separados para múltiples volúmenes compuestos que van juntos, tales como un conjunto de libros de partes ecuadernados por tipo de voz; es mejor que se los describa en el mismo registro. En muchos casos, deberá dejar muchos campos en blanco.

When describing a composite volumes creating the links, observe the following. As an example of a composite volume, see RISM ID no. 1001077677, a bound collection of 10 piano pieces by Chopin that were published ca. 1846-1857.

1. First, create the record for the composite volume, save, and note the RISM ID number.
2. Para los manuscritos: en el modo de edición del registro de su manuscrito, vaya al campo **Registro madre (773)**. Haga click en el segundo botón (lupa de la derecha) para buscar el volúmen compuesto.
3. Para la música impresa: en el registro de ejemplar correspondiente a la copia de su repositorio, busque el campo **Encuadernado con (973)** y haga click en la lupa. Encuentre el registro del volúmen compuesto y selecciónelo.


### Contrafacta

**Contrafacta** are vocal pieces in which the text is changed without significant change to the music, such as retexting a secular work with sacred text, or the other way around. La derivación es casi mecánica; hay poca creatividad en juego de parte del arreglador, aunque se plantea un cambio significativo en el propósito musical de la pieza (por ejemplo, el desplazamientpo de un contexto teatral a otro religioso).

Note that RISM considers contrafacta to be separate from parody and parody masses, which typically involve a more significant transformation of the musical material.

Take note of the following fields when cataloging contrafacta. RISM ID no. 300234487, a sacred contrafactum of an aria from Josef Mysliveček's opera Il Bellerofonte, will be used as an example.

- **Composer (100)**  
  Enter the composer of the original music.
 - Mysliveček, Josef
- **Standardized title (240)**  
  Use the standardized title of the original piece. **pf** o **V, pf**. Do not use **Arr**.
 - _Il Bellerofonte. Extractos
- **Título alternativo (730)**  
  Si la pieza con _contrafactum_ presenta un título uniforme nuevo y distintivo, regístrelo en este campo. No ingrese incipits literarios en este campo.
- **Subject headings (650)**  
  Add at least 3 subject headings (more if appropriate), in this order: Contrafacta -- Current genre -- Original genre.
 - Contrafacta
 - Sacred songs
 - Operas
- **Descripción sumaria (520)**  
  Añada una descripción breve en inglés que explique la situación, como un servicio a otros usuarios de RISM.
 - _Sacred contrafactum of an aria from Mysliveček's opera Il Bellerofonte._  
   [Contrafactum sacro de un aria de la ópera Il Bellerofont, de Mysliveček]
- **Idioma del texto (041)**  
  Complete cada uno de estos dos campos:  
  Idioma del texto (041 $a): correspondiente al texto actual del _contrafactum_.  
  Idioma del texto original (041 $h): correspondiente a la pieza original.
 - Idioma del texto: Latín
 - Idioma del texto original: Italiano
- **Text incipit (031 $t)**  
  You will enter two text incipits (use the + to add a new line):   
  The text incipit of the current text  
  The text incipit of the original text, if known, in square brackets.
 - Alma redemptoris mater, quae pervia caeli
 - [Giusti dei che ben vedete]
- **Other fields**  
  All other fields, such as liturgical feasts and instrumentation, should refer to the source in hand, that is, the contrafactum itself, and not the original work on which it was based.

### Compilations

**Compilations** are new, independent works made from parts of one or more other works and can also include new material. Con frecuencia, la obra resultante es de un género diferente al de las partes que la componen, como cuando las arias o dúos de una ópera se convierten en una cantata, o los extractos de una ópera se convierten en una suite instrumental. Esto también incluye los pasticcios. Si bien la frontera entre una compilación y un pasticcio no siempre es clara, los pasticcios pueden ser caracterizados generalmente por uno de estos rasgos: 1) arias, duetos o partes más grandes de obras dramáticas que se adaptan a un nuevo libreto; 2) varias obras independientes que se combinan para crear una nueva obra; o 3) composiciones colaborativas concebidas como tales desde el principio.

Las compilaciones se pueden cargar en un solo registro, o bien como colecciones.

Al catalogar compilaciones, tenga en cuenta los siguientes campos:

- **Compositor/Autor (100)**  
  El compositor es, en todos los casos, **Compilations** (Compilaciones).
- **Additional personal name (700)**  
  The name of the compiler can be added with the function **Editor**.  
  If you have a compilation, enter the composer(s) of the original material and select the function **Composer cross-reference**. Enter the composer(s) of the new material and select the function **Co-composer**.   
  If you have a pasticcio, do not enter composers as a composer cross-references. Instead, enter all composers as a **Co-composer**.
- **Título estandarizado (240)**  
  Introduzca el título estandarizado de la fuente en cuestión. Para los pasticcios, añada seleccione **Extractos** o **Arreglo** según corresponda.
- **Language code (041)**  
  For the field **Language of text**, enter the language of the source in hand. Si corresponde, se puede introducir el idioma de la obra original en **Idioma del texto original**.
- **Descriptor (650)**  
  El primer descriptor debe ser **Compilations** (Compilaciones) y/o **Pasticcios**. El segundo corresponde al género de la fuente en cuestión. En el caso de los extractos, se puede añadir el género del extracto. Otra opción es **Collaborative compositions** (Composiciones colaborativas).
- **Description summary (520)**  
  Use this field to describe in general the nature of the source.
 - Act 1 by Amadei, act 2 by Bononcini, overture and act 3 by Händel
- **Título alternativo (730)**  
  Escriba el título uniforme de la(s) pieza(s) original(es), seleccionando **Extractos** o **Arreglo** según corresponda. También puede introducir títulos _ossia_.
- **Catálogo de obras (690)**  
  Puede introducir el número de catálogo de obras tanto para la compilación como para las obras originales.
- **Text incipits (031)**  
  Enter the text incipit of the source in hand. If the original text is known, enter it in square brackets.
- **Nota general (500)**  
  Utilice siempre una nota para aclaraciones, especialmente si se trata de obras de compositores distintos. Esto asegura que los compositores se correspondan con las obras utilizadas en la compilación.
- **Nota sobre ocasión de interpetación (518)**  
  Las interpretaciones deben ser señaladas sólo en la medida en que se relacionen con la compilación misma.

#### Examples of compilations

- 230001408: Cantata hecha de arias de ópera con recitativos de nueva composición
- 702000623: Suite hecha de partes de una ópera
- 700007222: Varias obras de un mismo compositor utilizadas para crear una nueva cantata
- 702000642, 702000643: Varias obras de varios compositores utilizadas para crear una nueva suite
- 452505748: Un ópera pasticcio que consiste en 3 actos de 3 compositores diferentes

### Parodias

A **parody** is a composition based on pre-existing material that results in a new work. En el siglo XIX, el término adquiere un sesgo satírico.

El registro 150205470 será usado como ejemplo.

- **Composer (100)**  
  Enter the composer of the music for the source in hand.
 - Weyse, Christoph Ernst Friedrich
- **Additional personal name (700)**  
  Enter the composer of the pre-existing material and select the function Composer cross-reference.
 - Rossini, Gioachino
- **Título estandarizado (240)**  
  Introduzca el título estandarizado de la fuente en cuestión.
 - Dannemark hellige lyd
- **Additional title (730)**  
  Enter the title of the pre-existing material. Seleccion Extractos según corresponda. No utilice Arreglos o Variaciones.
 - Tancredi. Extractos
- Introduzca **Parodies** (Parodias) como primer Descriptor. Registre el género de la fuente en cuestión como segundo descriptor, y el género del material preexistente como tercer descriptor.
 - Parodias
 - Himnos nacionales
 - Operas
- **Language code (041)**  
  Enter the language for the source in hand in the field Language of text. Introduzca el idioma del material preexistente en el campo Idioma del texto original.
 - Danés
 - Italiano
- **Incipit literario (031)**  
  Introduzca el texto de la fuente en cuestión. If known, enter the original text in square brackets.
 - Dannemark hellige lyd
 - [Di tanti palpiti]
- **Other fields**  
  All other fields, such as performance information, should relate only to the source in hand.

### Insertion arias

Operas that include **insertion arias** (also called suitcase arias or interpolated arias) should be cataloged with at least three records: a parent record (collection main record) for the opera as a whole, a record for the original movements of the opera (which will contain most of the incipits), and a record for each of the inserts.

Las inserciones que aparecen separadas de una obra mayor deben catalogarse por separado. Se puede indicar un enlace a la obra en la que eran interpoladas en el campo **Fuente relacionada (787).**

A la hora de crear el registro madre y el registro de la ópera principal, se siguen las reglas usuales. Observe the following when cataloging the insert. Considere lo siguiente al catalogar la inserción: tenga en cuenta que todos los campos (tales como como la fecha de la composición y la plantilla/orgánico) corresponden únicamente a la inserción.

- **Compositor (100):** Compositor de la inserción.
- **Nombre personal adicional (700):** Compositor de la obra mayor, como la Ópera
- **Título uniforme (240):** Título de la inserción, o el nombre de la ópera seguido de Extractos.
- **Título adicional (730):** Si el libreto se basa en un libro o una obra de teatro, puede introducirse aquí el título de la obra original.
- **Nota general (500):** Se puede añadir cualquier información adicional que se conozca y aclare la relación de la inserción dentro de la obra mayor.
- Add a brief remark in the field **Note** to explain the nature of the insert, such as where it is located within the larger work. **Related source (787)**: Indicate the larger work into which this piece was inserted and select the relationship type **Insert in**.
- **Nota general (500):** Se puede añadir cualquier información adicional que se conozca y aclare la relación de la inserción dentro de la obra mayor.

### Mixed materials (manuscripts and printed items stored together)

No resulta extraño encontrar manuscritos e ítems impresos reunidos en la misma carpeta o bajo la misma signatura: por ejemplo, una partitura impresa con particellas manuscritas, o un grupo de particellas impresas junto con otras manuscritas.

Procure siempre catalogar el material impreso en un registro separado, dado que es posible que otras bibliotecas tengan ejemplares de la misma edición. Cree un registro para el material impreso, añada sus registros de ejemplar y cree otro registro para los materiales manuscritos. Utilice el campo **Fuente relacionada (787)** para señalar la relación de un registro al otro.

If it is not feasible to create an adequate record for the printed material, proceed as follows: Catalog your material using a manuscript template. In the material description section, describe the manuscript materials. Add an additional material group, and describe the printed materials.

### Music in periodicals

Existen dos maneras de catalogar periódicos que contienen música: como colección o como obra individual. En cada caso, el título del periódico, con el número de edición y el año, se registran en el campo **Título adicional (730).**

#### Collections
**Collections** can be appropriate when the periodical consists of all or mostly music and the item was collected and preserved as a whole. Los registros de ejemplar se añaden al nivel de la colección. Individual entries are created for each piece in the issue.

##### Example

1001097294: January issue (precise year unknown) of the _Kleine Pianoforte-Bibliothek_, containing 5 pieces. Hay un registro madre para la colección y cinco entradas individuales, una para cada pieza.

#### Single works
**Single works** can be appropriate when works were included as insertions or additions to periodicals without a notated music focus. Frequently, such items are preserved outside of their original publication context (for example, a song was torn out of the periodical).

#### Examples

- 991018149: "The Pantheon" published in _The Lady's Magazine_, August 1784
- 990042111: "L'amour folâtrant l'autre jour" published in _Nouveau Mercure galant_, May 1679

### Music in non-music publications

RISM también incluye música presente en publicaciones impresas que fueron concebidas como documentos fundamentalmente no musicales. El foco de RISM, no obstante, se ubica sobre la música

As an example we will use RISM ID no. 990026614, three songs by John Isaac Hawkins that were published in Charles Willson Peale's _Discourse introductory to a course of lectures on the science of nature_ (1800).
- **Composer/Author (100)**: The composer of the music
- **Additional Personal Name (700)**: The author of the book, with the function **other**
- **Title on source (245)**: The title of the book
- **Standardized title (240)**: A standardized title according to RISM rules, such as **3 Songs**
- **Physical description (300)**: A description of the music, such as **1 score: 5 p.**

**Institución adicional (710):** No olvide indexar el nombre del editor (en el caso de los libretos impresos). A **General note (500)** is useful to give more information such as the context of the music within the book or the total pagination of the book.

### Collected works and monuments

Volumes that are part of collected works editions or monuments of music are treated like separate publications and are cataloged as one record per volume. Such volumes will usually consist of a parent record for the edition and individual entries for each piece contained therein. The name of the series is entered in the field **Additional title (730)**.

Observe the following fields in particular when cataloging volumes in collected works. We will use RISM ID no. 1001200051 as an example, a volume of masses in the series _Wolfgang Amadeus Mozart's Werke._

- **Title on source (245)**: Multiple title pages and half titles are frequently present. Choose one as the chief source of information and enter it as the **Title on source.** Make sure to indicate at the beginning of the field what page is being transcribed, for example [title page] or [p. iii]. Enter all other titles in the field **Variant title on source (246)**.
- **Variant title on source (246)**: Due to the prevelance of reprints and variant editions of collected works, it is best practice to include all other title pages or title indications in this field. This will ease identification by other users if they have in hand a copy with varying front matter.
- **Additional title (730)**: Enter the name of the series, following the conventions of the series, including the volume number.

### Librettos

Observe the following when cataloging librettos.

- **Compositor/Autor (100):** Introduzca el autor del libreto. No utilice este campo para el compositor de la música.
- **Nombre personal adicional (700):**"Autor del concepto" es una función útil, por ejemplo, para registrar al autor de una obra de teatro en la que se basa el libreto. Introduzca el nombre de un compositor como referencia cruzada sólo si se lo nombra en la fuente.
- **Additional institution (710):** Do not forget to index the name of the publisher (for printed librettos).
- **Título uniforme (240):** Los campos "Declaración de arreglo" y "Tonalidad o modo" no resultan relevantes en este caso. En caso de que el libreto incluya música anotada, indique la tonalidad sólo en el Incipit musical (031).
- **Título uniforme (240):** Título de la inserción, o el nombre de la ópera seguido de Extractos.
- **Subject heading (650):** If known, enter the name of the genre for which the libretto was written, such as “Operas” or “Cantatas”. "Librettos" no es necesario.
- Entre los descriptores apropiados para tratados aparecen los siguientes casos:
- **Source type (593):** Select the source type. For the content type, select "Libretto."
- **Descripción física:** **Formato, extensión (300):** Utilice la frase "text document" [documento de texto] para describir el formato del libreto. Un ejemplo sería: 1 text document: viii, 27. Para un capítulo dentro de una colección de ensayos, introduzca los números de página del capítulo:  
  _Ejemplo:_  
  p.

### Treatises

Cuanto se catalogan tratados, el campo **Formato, extensión (300 $a)** debe incluir, por lo general, **_text document_** (documento de texto) como formato.

Appropriate subject headings for treatises include the following:

- **Treatises**
- **Writings**
- ********Music theory ** [Teoría musical]******
- ****Theory of harmony ** [Teoría de la armonía]**
- En el campo **Título**
- **uniforme (240)**:
- ********Contrapuntal studies (inst./voc.).******
- ****Solfeggios (voc.) **[Solfeos (vocales)]**
- ****Solfeggios (inst.) **[Solfeos (instrumentales)]**
- ****Scales (inst./voc.) **[Escalas (instrumentales/vocales)]**

Additional subject headings may be added.

The boundry between treatises and method books can sometimes be a thin one, and it is up to the cataloger to decide whether to catalog methods as treatises or music editions.

### Keyboard arrangements

Specify keyboard arrangements as follows.

- Seleccione **Arreglo** en el subcampo **Mención de arreglo.**
  - ****Solfeggios (inst.) **[Solfeos (instrumentales)]**
  - Under **Scoring summary**, enter the scoring of the arrangement, such as **pf** or **V, pf**. No ingrese la plantilla/orgánico de la obra original.
- In the field **Total scoring (594)**, enter the total scoring of the arrangement. No ingrese la plantilla/orgánico de la obra original.
- **Título uniforme (240)**  
  Utilice el título uniforme de la pieza original. Puede seleccionar el calificador  **Extractos.**  No use el calificador  **Arreglo**.

### Sources described in RISM Series B publications not yet in Muscat

There are currently no projects underway by the Editorial Center to systematically add sources described in [RISM's Series B publications](https://rism.info/publications.html#series-b-bibliographies-organized-by-topic). Nevertheles, RISM contributors are welcome to create new records for such sources. If you add items to Muscat that are described in a B volume, fill out the field **RISM Series (510)** in the Administration section and indicate what book the description was found in. The Editorial Center will see the new record and ensure all information from the book (including other holding libraries) is in the new record.
