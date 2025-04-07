## Cataloging special types of sources

Esta sección describe cómo catalogar tipos especiales de fuentes: colecciones, volúmenes compuestos, <em x-id="4">contrafacta</em>, compilaciones, arias insertadas, parodias, materiales mixtos (ítems manuscritos e impresos que se almacenan juntos), música en periódicos, música en publicaciones no musicales, libretos, tratados y arreglos para piano.

### Collections

In RISM, a _collection_ is both an intentional collective manuscript or anthology of multiple works as well as an item that contains two or more separate pieces. Esto último implica que, en caso de que un manuscrito de una sonata para piano, por ejemplo, incluya un borrador de una fuga justo al final, RISM lo catalogará como una colección con un registro madre para el documento en general y entradas individuales para la sonata y la fuga.

Al catalogar colecciones, tenga en cuenta que:

1. La entrada principal de la colección (registro madre) debe contener información que aplique a toda la colección.
2. Cualquier información que sea relevante sólo para algunas secciones de la colección debe ser registrada en la entrada individual.

Si las obras de la colección son de distintos compositores o presentan diferente plantilla/orgánico, tipo de fuente, etc., no ingrese estos datos en el registro madre.

En el caso de colecciones compuestas por obras muy similares entre sí, es una buena estrategia crear una primera entrada con todos los datos correspondientes a una obra y usar la función “Duplicar” para copiar el registro. Luego, para los registros siguientes sólo restará cambiar campos tales como el título y el número de páginas.

Los registros madre de colección no pueden albergar registros madre de colección de manuscritos. En su lugar, trabaje con una estructura menos jerarquizada, con registros individuales y explique la conformación u organización del ítem en una nota.

### Composite volumes

Un **Volumen compuesto** es un volumen integrado por documentos que fueron creados por separado y encuadernados juntos posteriormente, usualmente por un propietario o una institución. Hay otros nombres para este tipo de volúmenes: _bound-with, Sammelband, _volumen de encuadernador, volumen de colector. There are many other names for such volumes in English: binders' collection, binders' volume, bound sheet music, bound-with, collectors' volume, factitious volume, nonce volume, recueils factices, Sammelband, tract volume.

Hay dos maneras de señalar la presencia de volúmenes compuestos. La primera y más simple consiste en dar a los ítems la misma signatura; también resulta útil una nota de encuadernación. La segunda forma consiste en utilziar la plantilla para volúmenes compuestos.

El registro de volúmen compuesto sirve como medio para vincular los ítems en un único registro, proveyendo, de esa manera, al usuario un panorama conveniente de todos los contenidos de un volumen encuadernado.

Es conveniente que los registros de volúmenes compuestos sean simples. En principio, los mismos simplemente describen la encuadernación. No hay que confundir los volúmenes compuestos con las colecciones; las "colecciones" en el RISM son sólo para manuscritos. Además, no hay que confundir los volúmenes compuestos con las ediciones impresas: una edición impresa es una unidad bibliográfica única que fue publicada por el editor como tal. Tanto las colecciones como las ediciones impresas pueden contener varias piezas. En cambio, los volúmenes compuestos reúnen unidades dispares: por ejemplo, una colección impresa de madrigales de 1604, un manuscrito de un motete de 1620 y una edición impresa de madrigales de 1615.

Tal como con los registros madre de colección, la información consignada en el registro de volumen compuesto debería aplicar a todos los componentes del volumen, teniendo en cuenta que la información detallada en relación con la música corresponde a los registros bibliográficos respectivos. No cree registros separados para múltiples volúmenes compuestos que van juntos, tales como un conjunto de libros de partes ecuadernados por tipo de voz; es mejor que se los describa en el mismo registro. En muchos casos, deberá dejar muchos campos en blanco.

Con este tipo de documentos, deberá vincular tanto ítems manuscritos como impresos al registro de volumen compuesto; en cada caso el procedimiento es diferente.

1. Primero, cree el registro para el volumen compuesto, guárdelo y anote el número de RISM.
2. Para los manuscritos: en el modo de edición del registro de su manuscrito, vaya al campo **Registro madre (773)**. Haga click en el segundo botón (lupa de la derecha) para buscar el volúmen compuesto.
3. Para la música impresa: en el registro de ejemplar correspondiente a la copia de su repositorio, busque el campo **Encuadernado con (973)** y haga click en la lupa. Encuentre el registro del volúmen compuesto y selecciónelo.

### Contrafacta

_Contrafactum</em>)_ _son piezas vocales en las cuales se reemplaza el texto sin realizar cambios significativos a la música, como en el caso de las obras seculares cuyo texto es reemplazado por uno sacro, o viceversa. La derivación es casi mecánica; hay poca creatividad en juego de parte del arreglador, aunque se plantea un cambio significativo en el propósito musical de la pieza (por ejemplo, el desplazamientpo de un contexto teatral a otro religioso).

Por favor, nótese que RISM diferencia a los _contrafacta _de la parodia y las misas de parodia, las cuales, por lo general, involucran una transformación más significativa del material musical.

Take note of the following fields when cataloging contrafacta. RISM ID no. 300234487, a sacred contrafactum of an aria from Josef Mysliveček's opera Il Bellerofonte, will be used as an example.

**Composer (100)**

Enter the composer of the original music.

- Mysliveček, Josef

**Título uniforme (240)**

Use the standardized title of the original piece. **pf** o **V, pf**. Do not use **Arr**.

- _Il Bellerofonte. Extractos

**Alternative title (730)**

If there is a new, distinct standardized title for the piece in hand, you can enter it here. No ingrese incipits literarios en este campo.

**Subject headings (650)**

Add at least 3 subject headings (more if appropriate), in this order:\
Contrafacta\
Current genre\
Original genre

- Contrafacta
- Sacred songs
- Operas

**Description summary (520)**

Add a short description in English that explains the situation as a benefit to other RISM users.

- <em x-id="4">Sacred contrafactum of an aria from Mysliveček's opera Il Bellerofonte.</em><br x-id="2" />
 [Contrafactum sacro de un aria de la ópera Il Bellerofont, de Mysliveček]

**Language of text (041)**

Fill out both of these fields:\
Language of text (041 $a): The current text of the source in hand\
Language of original text (041 $h): Language of the original piece

- Idioma del texto: Latín
- Idioma del texto original: Italiano

**Text incipit (031 $t)**

Enter the text of the source in hand.\
If the original text is known, enter it in square brackets.

- Alma redemptoris mater, quae pervia caeli
- [Giusti dei che ben vedete]

**Otros campos**

Todos los otros campos, tales como la festividad litúrgica y la plantilla/orgánico, deben referir a la fuente que se cataloga, esto es, al _contrafactum _mismo, y no a la obra original en el cual se basa.

### Compilations

Las compilaciones constituyen obras nuevas e independientes hechas a partir de partes de una o más obras que también pueden incluir material nuevo. Con frecuencia, la obra resultante es de un género diferente al de las partes que la componen, como cuando las arias o dúos de una ópera se convierten en una cantata, o los extractos de una ópera se convierten en una suite instrumental. Esto también incluye los pasticcios. Si bien la frontera entre una compilación y un pasticcio no siempre es clara, los pasticcios pueden ser caracterizados generalmente por uno de estos rasgos: 1) arias, duetos o partes más grandes de obras dramáticas que se adaptan a un nuevo libreto; 2) varias obras independientes que se combinan para crear una nueva obra; o 3) composiciones colaborativas concebidas como tales desde el principio.

Las compilaciones se pueden cargar en un solo registro, o bien como colecciones.

Al catalogar compilaciones, tenga en cuenta los siguientes campos:

**Compositor/Autor (100)**

The composer is always **Compilations**.

**Nombre personal adicional (700)**

The name of the compiler can be added with the function **Editor**.

**Related source (787)**: Indicate the the larger work into which this piece was inserted and select the relationship type **Insert in**. **Related source (787)**: Indicate the larger work into which this piece was inserted and select the relationship type **Insert in**.

En el caso de los pasticcios, no registre compositoras/es como Referencias cruzadas de compositor. Instead, enter all composers as **Co-composer**s.

**Título uniforme (240)**

Introduzca el título uniforme de la fuente en cuestión. Para los pasticcios, añada seleccione **Extractos** o **Arreglo** según corresponda.

**Código de idioma (041)**

For the field **Language of text**, enter the language of the source in hand. Si corresponde, se puede introducir el idioma de la obra original en **Idioma del texto original**.

**Subject heading (650)**

The first subject heading should be **Compilations** and/or **Pasticcios**. El segundo corresponde al género de la fuente en cuestión. En el caso de los extractos, se puede añadir el género del extracto. Otra opción es **Collaborative compositions** (Composiciones colaborativas).

**Description summary (520)**

Use this field to describe in general the nature of the source.

<figure>
  Act 1 by Amadei, act 2 by Bononcini, overture and act 3 by Händel
  <figcaption>Example</figcaption>
</figure>

**Alternate title (730)**

Enter the standardized title of the original piece(s), adding **Excerpts** or **Arrangement** as appropriate. También puede introducir títulos <em x-id="4">ossia</em>.

**Catálogo de obras (690)**

You can enter the catalog of works number for both the compilation and the original works.

**Text incipit (031)**

Introduzca el incipit literario de la fuente en cuestión. If the original text is known, enter it in square brackets.

**General note (500)**

Always use a note for clarification, especially if the works of separate composers are involved. Esto asegura que los compositores se correspondan con las obras utilizadas en la compilación.

**Note on performance (518)**

Performances should be noted only as they relate to the compilation itself.

**Examples of compilations**:

230001408: Cantata hecha de arias de ópera con recitativos de nueva composición

702000623: Suite hecha de partes de una ópera

700007222: Varias obras de un mismo compositor utilizadas para crear una nueva cantata

702000642, 702000643: Varias obras de varios compositores utilizadas para crear una nueva suite

452505748: Un ópera pasticcio que consiste en 3 actos de 3 compositores diferentes

### Parodias

Una parodia es una composición basada en material preexistente que da lugar a una nueva obra. En el siglo XIX, el término adquiere un sesgo satírico.

El registro 150205470 será usado como ejemplo.

**Composer (100)**

Introduzca el compositor del material preexistente y seleccione la función Referencia cruzada de compositor.

- Weyse, Christoph Ernst Friedrich

**Nombre personal adicional (700)**

Enter the composer of the pre-existing material and select the function Composer cross-reference.

- Rossini, Gioachino

**Título uniforme (240)**

Introduzca el título uniforme de la fuente en cuestión.

- Dannemark hellige lyd

**Título adicional (730)**

Introduzca el título del material preexistente. Seleccion Extractos según corresponda. No utilice Arreglos o Variaciones.

- Tancredi. Extractos

**Subject heading (650)**

Enter Parodies as the first subject heading. Registre el género de la fuente en cuestión como segundo descriptor, y el género del material preexistente como tercer descriptor.

- Parodias
- Himnos nacionales
- Operas

**Código de idioma (041)**

Introduzca el idioma de la fuente en cuestión en el campo Idioma del texto. Introduzca el idioma del material preexistente en el campo Idioma del texto original.

- Danés
- Italiano

**Incipits literarios (031)**

Introduzca el incipit literario de la fuente en cuestión. If known, enter the original text in square brackets.

- Dannemark hellige lyd
- [Di tanti palpiti]

**Otros campos**

<strong x-id="1">Título adicional (730):</strong> Título de la obra mayor, más el subencabezado <strong x-id="1">Inserciones.</strong>

### Insertion arias

<strong x-id="1">Descriptor (650):</strong> Introduzca tres: <em x-id="4">Insertions</em>, el género de la inserción y el género de la obra mayor.

Las inserciones que aparecen separadas de una obra mayor deben catalogarse por separado. Se puede indicar un enlace a la obra en la que eran interpoladas en el campo **Fuente relacionada (787).**

A la hora de crear el registro madre y el registro de la ópera principal, se siguen las reglas usuales. Please observe the following when cataloging the insert. Considere lo siguiente al catalogar la inserción: tenga en cuenta que todos los campos (tales como como la fecha de la composición y la plantilla/orgánico) corresponden únicamente a la inserción.

**Compositor (100):** Compositor de la inserción.

**Nombre personal adicional (700):** Compositor de la obra mayor, como la Ópera

**Título uniforme (240):** Título de la inserción, o el nombre de la ópera seguido de Extractos.

**Título adicional (730):** Si el libreto se basa en un libro o una obra de teatro, puede introducirse aquí el título de la obra original.

**Descriptor (650):** Introduzca tres: _Insertions_, el género de la inserción y el género de la obra mayor.

**Fuente relacionada (787):** Indique la obra mayor en la que se interpolaba esta pieza y seleccione el tipo de relación **Inserción en**. Añada una breve observación en el campo **Nota** para explicar la naturaleza de la inserción como, por ejemplo, el punto de la obra mayor en el que se interpola.

**Nota general (500):** Se puede añadir cualquier información adicional que se conozca y aclare la relación de la inserción dentro de la obra mayor.

### Mixed materials (manuscripts and printed items stored together)

No resulta extraño encontrar manuscritos e ítems impresos reunidos en la misma carpeta o bajo la misma signatura: por ejemplo, una partitura impresa con particellas manuscritas, o un grupo de particellas impresas junto con otras manuscritas.

Procure siempre catalogar el material impreso en un registro separado, dado que es posible que otras bibliotecas tengan ejemplares de la misma edición. Cree un registro para el material impreso, añada sus registros de ejemplar y cree otro registro para los materiales manuscritos. Utilice el campo **Fuente relacionada (787)** para señalar la relación de un registro al otro.

If it is not feasible to create an adequate record for the printed material, proceed as follows: Catalog your material using a manuscript template. In the material description section, describe the manuscript materials. Add an additional material group, and describe the printed materials.

### Music in periodicals

Existen dos maneras de catalogar periódicos que contienen música: como colección o como obra individual. En cada caso, el título del periódico, con el número de edición y el año, se registran en el campo **Título adicional (730).**

**Collections** can be appropriate when the periodical consists of all or mostly music and the item was collected and preserved as a whole. Los registros de ejemplar se añaden al nivel de la colección. Individual entries are created for each piece in the issue.

##### _Ejemplo: _

1001097294: January issue (precise year unknown) of the _Kleine Pianoforte-Bibliothek_, containing 5 pieces. Hay un registro madre para la colección y cinco entradas individuales, una para cada pieza.

**Single works** can be appropriate when works were included as insertions or additions to periodicals without a notated music focus. Frequently, such items are preserved outside of their original publication context.

##### Examples

991018149: "The Pantheon" published in _The Lady's Magazine_, August 1784\
990042111: "L'amour folâtrant l'autre jour" published in _Nouveau Mercure galant_, May 1679

### Music in non-music publications

RISM también incluye música presente en publicaciones impresas que fueron concebidas como documentos fundamentalmente no musicales. El foco de RISM, no obstante, se ubica sobre la música

##### _Ejemplo: _

990026614: 3 songs by John Isaac Hawkins that were published in Charles Willson Peale's _Discourse introductory to a course of lectures on the science of nature_ (1800).\
**Composer/Author (100)**: The composer of the music\
**Additional Personal Name (700)**: The author of the book, with the indicator **other**\
**Title on source (245)**: The title of the book\
**Standardized title (240)**: A standardized title according to RISM rules, such as **3 Songs**\
**Physical description (300)**: A description of the music, such as **1 score: 5 p.**\
**Composer/Author (100)**: The composer of the music\
**Additional Personal Name (700)**: The author of the book, with the indicator **other**\
**Title on source (245)**: The title of the book\
**Standardized title (240)**: A standardized title according to RISM rules, such as **3 Songs**\
**Physical description (300)**: A description of the music, such as **1 score: 5 p.**

<strong x-id="1">Institución adicional (710):</strong> No olvide indexar el nombre del editor (en el caso de los libretos impresos).

### Libretti

Por favor, tenga en cuenta lo siguiente al catalogar libretos.

**Compositor/Autor (100):** Introduzca el autor del libreto. No utilice este campo para el compositor de la música.

**Nombre personal adicional (700):**"Autor del concepto" es una función útil, por ejemplo, para registrar al autor de una obra de teatro en la que se basa el libreto. Introduzca el nombre de un compositor como referencia cruzada sólo si se lo nombra en la fuente.

**Institución adicional (710):** No olvide indexar el nombre del editor (en el caso de los libretos impresos).

**Título uniforme (240):** Los campos "Declaración de arreglo" y "Tonalidad o modo" no resultan relevantes en este caso. En caso de que el libreto incluya música anotada, indique la tonalidad sólo en el Incipit musical (031).

**Título adicional (730):** Título de la obra mayor, más el subencabezado **Inserciones.**

**Descriptor (650):** Introduzca el nombre del género para el que se escribió el libreto, si se lo conoce (como "Operas" o "Cantatas"). "Librettos" no es necesario.

**Código de idioma (041):** Utilice el campo "Idioma del texto" sólo si el libreto contiene música anotada con letra.

**Tipo de fuente (593):** Seleccione "Libreto, manuscrito" o "Libreto, impreso".

**Descripción física:** **Formato, extensión (300):** Utilice la frase "text document" [documento de texto] para describir el formato del libreto. Un ejemplo sería: 1 text document: viii, 27. Para un capítulo dentro de una colección de ensayos, introduzca los números de página del capítulo:<br x-id="2" /> <em x-id="4">Ejemplo:</em><br x-id="2" />
p.

### Treatises

Cuanto se catalogan tratados, el campo **Formato, extensión (300 $a)** debe incluir, por lo general, **_text document_** (documento de texto) como formato.

Appropriate subject headings for treatises include the following:

- **Treatises**
- **Writings**
- \*\***Music theory \*\* [Teoría musical]**
- \*\***Theory of harmony \*\* [Teoría de la armonía]**
- **Tutors (inst.)**: Includes methods and schools
- **Tutors (voc.)**: Includes methods and schools
- \*\***Contrapuntal studies (inst./voc.).**
- \*\*\*\*Solfeggios (voc.)
- \*\*\*\*Solfeggios (inst.)
- \*\*\*\*Scales (inst./voc.)

Additional subject headings may be added.

### Piano arrangements

Especifique los arreglos para piano del siguiente modo:

- **uniforme (240)**:
 - Seleccione **Arreglo** en el subcampo **Mención de arreglo.**
 - Under **Scoring summary**, enter the scoring of the arrangement, such as **pf** or **V, pf**. No ingrese la plantilla/orgánico de la obra original.
- In the field **Total scoring (594)**, enter the total scoring of the arrangement. No ingrese la plantilla/orgánico de la obra original.
- In the field **Physical description (300)**, use **keyboard score** if the work has been reduced for piano. Use **vocal** score if the work has been reduced for voice and piano.
