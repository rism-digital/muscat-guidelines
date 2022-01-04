### Íncipits (031)

Los íncipits ayudan a identificar las obras y facilitan la comparación de las fuentes entre sí. Para la música instrumental se prefiere el registro de fragmentos de una parte aguda y de una parte grave, como vl 1 y bajo. En el caso de la música vocal-instrumental, incluya íncipits de la voz más aguda y el primer violín o la parte instrumental más aguda. En el caso de los instrumentos transpositores, transcriba los fragmentos en altura real.

En caso de que la notación del fragmento que necesita transcribir no pueda representarse con código _Plaine & Easie_, transcriba la música de la manera más fiel posible e incluya una nota aclaratoria al respecto. Puede adjuntar una imagen del íncipit en la fuente para mayor claridad.

#### Número de obra, número de movimiento, número de íncipit (031 $a, b, c)

**Campos requeridos en caso de que se utilice cualquier otro campo de esta sección.**

El número de íncipit se compone de tres dígitos que representan obra, movimiento e íncipit, respectivamente. El primer dígito es siempre 1. El Movimiento se refiere a secciones significativas de una obra, sean estas movimientos técnicamente (como en el caso de una sinfonía), o bien secciones diferenciadas de una obra a gran escala (como en el caso de un aria). Para indicar que dos íncipits suenan en simultáneo (por ejemplo, vl 1 y bajo), los primeros dos dígitos del número de íncipit deben ser iguales.

Numere los íncipits correlativamente incluso si faltan movimientos en la fuente. Por ejemplo, si la fuente corresponde a una sinfonía de tres movimientos pero falta el movimiento intermedio, numere los íncipits como 1.1.1 y 1.2.1 (no 1.3.1). (Nota: los puntos entre los dígitos son añadidos automáticamente por Muscat).

##### Ejemplos  
1.1.1 = 1ra obra, 1er movimiento, 1er íncipit  
1.1.2 = 1ra obra, 1er movimiento, 2do íncipit (suena en simultáneo con 1.1.1)  
1.1.2 = 1ra obra, 1er movimiento, la entrada de la parte vocal  
1.2.1 = 1ra obra, 2do movimiento, 1er íncipit

#### Título del movimiento, tempo (031 $d)

Registre el título del movimiento y el tempo –o indicaciones similares–, si aparecen especificados, tal como figuran en la fuente. Indique saltos de línea con | (barra vertical) y espacios simples antes y después de dicho signo. Use corchetes para indicar agregados al original; los agregados deben tener una ortografía consistente. Pueden añadirse múltiples títulos o marcas de tempo adicionales en campos separados. Si registra varios íncipits para los cuales el título y la indicación de tempo coinciden, ingrese el dato solo en el primer íncipit.

#### Voz/instrumento (031 $m)

Registre la parte vocal o instrumental correspondiente al íncipit siguiendo la lista de **abreviaturas de instrumentos de RISM**. Use **V** para una parte vocal desconocida e **i** para una parte instrumental desconocida. En el caso de los instrumentos transpositores, transcriba el fragmento en altura real. Indique la afinación del instrumento en el campo **Nota general**.

##### Ejemplos  
pf  
T coro  
org with text

#### Personaje (031 $e)

Registre el nombre estandarizado del personaje en este campo. Si utiliza este campo, asegúrese de completar también el campo **Nombres de personajes (595)**. Indique cualquier agregado editorial con corchetes. Señale cualquier información dudosa con un signo de interrogación.

#### Íncipit literario (031 $t)

El íncipit literario consiste en las primeras palabras de una pieza o sección y puede equivaler al primer verso, la primera frase u otro grupo de palabras del texto que tenga sentido lingüístico. Los íncipits literarios sirven para identificar el texto utilizado y no precisan corresponderse con la longitud del íncipit musical necesariamente. Los mismos pueden registrarse sin importar si se ingresa un íncipit musical o no. Por favor, tenga en cuenta que se siguen reglas particulares para los textos en latín (vea más abajo).

Los íncipits literarios se presentan de forma estandarizada. Registre el íncipit literario con ortografía moderna. Guíese por el índice de autoridades de **Títulos/íncipits literarios** para estandarizar su entrada. Registre íncipits nuevos en caso de el índice no los incluya.

No agregue fragmentos de texto entre corchetes ni reponga palabras faltantes. Omita los signos de puntuación y las repeticiones del texto. Las tildes deben usarse sólo si aparecen en el diccionario o si son gramaticalmente correctas. Escriba los números de principio del texto como palabras. El uso de mayúsculas y minúsculas debe seguir las reglas del idioma respectivo, salvo en el caso de las designaciones de Dios (Herr, Dio, Dieu, Signore, Lord, etc.) que se colocan siempre con mayúscula inicial. Si el íncipit literario se usa como Título Uniforme (240), asegúrese de que el largo y la ortografía se correspondan de modo exacto.

Omita el texto por completo si no puede leerlo y añada una nota que diga “Texto ilegible” o algo similar.

En lenguas romances, los apóstrofos van seguidos inmediatamente por el texto, sin que medien espacios. La excepción a esta regla se da cuando la primera letra de una palabra es remplazada por un apóstrofo (por ejemplo: Fra l’amante e ‘l genitor).

En este campo también pueden registrarse textos relacionados que no aparezcan en la fuente, pero igualmente puedan vincularse a ella por verificación o derivación. En este caso, ponga todo el texto entre corchetes. Esta situación puede darse con:

- Texto de una parte vocal faltante
- Íncipits literarios en el idioma original de la obra, cuando la fuente presenta una versión traducida
- Textos de una composición vocal usada como tema de una variación o base de un arreglo instrumental

**Escritura no latina**: si su fuente presenta un íncipit literario escrito con letras o caracteres no latinos (alfabeto cirílico/griego/hebreo/coreano, caracteres chinos, etc.) ingrese el **Íncipit literario** en su idioma original. Las traducciones o transliteraciones son opcionales y pueden añadirse en campos de íncipit literario adicionales. Si desea añadir traducciones que no están en la fuente, hágalo entre corchetes. Se puede traducir a cualquiera de los idiomas RISM.

**Reglas especiales para textos en latín**: ingrese los textos en latín, tanto sacros como seculares. Este campo está vinculado al archivo de autoridades de **Títulos/íncipits literarios**. Dentro del archivo de autoridades de **Títulos/íncipits literarios**, los términos precedidos por el indicador **t**  presentan información sobre el contexto litúrgico exacto, versiones variantes y otros aspectos vinculados al íncipit literario. Si el íncipit literario se usa además como Título Uniforme, asegúrese de que la ortografía sea idéntica; no obstante, recuerde que en los títulos uniformes el texto en latín se ingresa sólo hasta la coma. Use corchetes para registrar textos en latín que no aparecen en la fuente pero han sido determinados por vía de la investigación.

Los textos normalizados en latín suelen corresponderse con las versiones del _Liber usualis_. En RISM, estos textos incluyen generalmente una coma. Por ejemplo, si busca el texto “Et in terra pax”, encontrará alrededor de una docena de resultados, pero sólo uno incluye una coma, y verá que esta fuente ha sido usada 4800 veces en la base de datos. Se trata del registro que deseamos usar como íncipit –asumiendo que el mismo se corresponda con su fuente–. Si su íncipit literario es sólo “Et in terra pax” se da a entender que, o bien (1) sólo contiene esas palabras, o bien (2) continúa de un modo diferente al del _Liber usualis_. Por supuesto, cabe la posibilidad de que esto suceda. Sin embargo, en la mayoría de los casos se optará por la versión con la coma.

#### Tonalidad o modo (031 $r)

Seleccione la tonalidad o modo entre las opciones de la lista desplegable.

#### Armadura de clave (031 $n)

Ingrese **x** para armaduras con sostenidos o **b** para armaduras con bemoles, seguido de las letras mayúsculas correspondientes a las alturas alteradas por la armadura. Si la pieza está claramente en una cierta tonalidad pero falta un sostenido o un bemol en la armadura, puede agregarlo entre corchetes. Si no hay armadura de clave, deje el campo en blanco.

##### Ejemplos  
xF = F (Fa) es sostenido = Sol mayor o Mi menor  
bBE = B (Si) y E (Mi) son bemoles = Si bemol mayor o Sol menor  
xFC[G] = F (Fa) y C (Do) son sostenidos en la fuente pero la pieza está claramente en La mayor, por lo cual se agrega el último sostenido entre corchetes.

#### Indicación de compás (031 $o)

Registre la indicación de compás como una fracción. También se permiten las siguientes opciones:

**c** = compasillo, _common time_ o _tempus imperfectum cum prolatione imperfecta_  
**c/** = compás mayor, _alla breve_  
**3** = _proportio tripla_; también **1**, **2**, etc.  
**c3** = _proportio tripla_  
**c3/2** [añadido a la traducción: _proportio sesquialtera,_ «proporción menor»_]_  
**c.** = _tempus imperfectum cum prolatione perfecta_  
**o** = _tempus perfectum cum prolatione imperfecta_  
**o/** = _tempus perfectum cum prolatione minore, diminutum_  
**o.** = _tempus perfectum cum prolatione perfecta_

Si la métrica cambia constantemente, puede escribir la primera indicación de compás seguida de la segunda, separadas por un espacio. Si el íncipit no lleva indicaicón de compás, deje el campo en blanco.

##### Ejemplos  
4/4  
6/8  
3/4 4/4

En caso de que el compás indicado sea obviamente erróneo, por favor corríjalo para que se corresponda con el íncipit dado. Incluya una nota aclaratoria al respecto en el campo **Nota general**.

#### Clave (031 $g)

Seleccione una clave de la lista. La letra indica el tipo de clave. El guión (-) indica notación moderna. El signo más (+) indica notación mensural. El número se refiere a la posición de la clave en el pentagrama.

#### Validez (031 $s)

¡No ingrese nada en este campo! (Solo se usa para datos antiguos).

#### Íncipit musical (031 $p)

Registre el íncipit musical de forma codificada, haciendo uso del código _Plaine & Easie_ (véase también [https://www.iaml.info/plaine-easie-code](https://www.iaml.info/plaine-easie-code)). Es necesario que el íncipit tenga por lo menos dos compases o seis notas de longitud.

**1. Octavas**  
‘ = notas de la 1ª octava sobre el Do central  
‘‘ = 2ª octava sobre el Do central  
‘’’ = 3ª octava sobre el Do central  
, = notas de la 1ª octava debajo del Do central  
,, = 2ª octava debajo del Do central  
,,, = 3ª octava debajo del Do central

**2. Valores rítmicos / figuras**  
0 = longa  
9 = breve  
1 = redonda / semibreve  
2 = blanca / mínima  
4 = negra / semimínima  
8 = corchea / fusa  
6 = semicorchea / semifusa  
3 = fusa  
5 = semifusa  
7 = garrapatea  
7. = notación neumática

Se usan puntos para las notas apuntilladas. Se pueden agregar varios puntos a una nota.  
4. = negra con puntillo  
8.. = corchea con doble puntillo

**3. Alteraciones**  
x = sostenido  
xx = doble sostenido  
b = bemol  
bb = doble bemol  
n = becuadro o natural

**4. Nombre de las notas**  
_C, D, E, F, G, A, B_ (= Do, Re, Mi, Fa, Sol, La, Si)

**5. Ornamentos**  
g = _acciaccatura_ (sin valor rítmico, precede al nombre de la nota)  
q = _appoggiatura_ (con valor rítmico, precede al nombre de la nota)  
qq…r = varias _appoggiaturas_ u ornamentos agrupados (con valor rítmico)

**6. Silencios**  
El “-“ (signo menos) se utiliza para silencios individuales (una sola figura). Utilice “=” (signo igual) para indicar un silencio de compás. En caso de múltiples compases de silencio, indique el número de compases tras el signo =. Debe añadir una barra de compás para visualizarlo.

_Ejemplo de un silencio de corchea:_  
8-  
_Ejemplos de un compás de silencio:_  
=  
=1  
_Ejemplo de múltiples compases de silencio:_  
=35

**7. Barras de compás**  
/ = barra de compás  
// = doble barra de compás  
//: = doble barra de compás con repetición del fragmento posterior  
:// = doble barra de compás con repetición del fragmento anterior  
://: = doble barra de compás con doble repetición

**8. Otros símbolos**  
t = trino (se coloca inmediatamente después de la nota)  
+ = ligadura de prolongación (se coloca inmediatamente después de la nota; no confundir con ligadura de expresión)  
() = calderón/fermata/pausa (solo puede usarse con una sola nota o silencio; las alteraciones, etc. deben quedar afuera del paréntesis; consulte también el punto **10. Ritmos especiales**, más abajo).

No escriba ligaduras de expresión.

**9. Barrado en corcheas y figuras menores (i.e. unión de las plicas)**  
{ = comienzo del barrado  
} = fin del barrado

##### Ejemplo  
{qq6’CDEDr}

**10. Figuras irregulares**  
( = inicio del grupo de figuras irregulares  
) = fin del grupo irregular

La duración total del grupo debe escribirse antes de **(**. El valor rítmico de la primera nota debe escribirse después de **(**, aunque sea idéntico al de la nota inmediatamente antes de la sección con figuras irregulares. El número de notas del grupo debe indicarse antes de **)**, separado de la última nota por **;**.

_Ejemplos_  
8(3ABCDE;5) = quintillo (5) de fusas (3), en el tiempo de una corchea (8)  
8({3ABCDE};5) = quintillo de fusas, en el tiempo de una corchea con las plicas unidas.

El tresillo constituye un caso especial. En sentido estricto, debería codificarse como:  
8(6ABC;3) o 8({6ABC};3)

Sin embargo, puede usarse el siguiente atajo:  
(6ABC) = tresillo de semicorcheas (6)  
({6ABC}) = tresillo de semicorcheas con barrado

Por favor, ¡no olvide el valor rítmico dentro de los paréntesis!

**11. Métodos abreviados**  
**Nota**: Actualmente, la búsqueda de OPAC ignora los elementos repetidos descritos en 11.1 y 11.2. Esto significa que si utiliza estos métodos abreviados, sus íncipits no podrán ser buscados por completo en el OPAC. Hasta que esto se solucione, por favor escriba el íncipit en su totalidad. (El método 11.3 puede ser utilizado).

**11.1. Figuras repetidas**  
! = inicio y fin de un pasaje  
f = repetir la indicación  
El pasaje será repetido cada vez que aparezca  **f**  después del segundo **!**. Esto sólo es posible dentro de un mismo compás.

##### Ejemplo  
!{‘8ABAG}!ff = el pasaje se repetirá dos veces

**11.2 Compases repetidos**  
i = repetir el último compás.  
La “i” siempre va entre dos barras de compás

##### Ejemplo  
‘4ABAG /i/i = el compás será repetido dos veces

**11.3 Patrones rítmicos**  
Cuando cierta secuencia rítmica se repite varias veces, el patrón rítmico puede consignarse antes de los respectivos nombres de nota.

##### Ejemplo  
**8.A6B8C 8.D6E8F** puede reemplazarse por **8.68ABCDEF**  
La secuencia rítmica se termina apenas se presenta un valor rítmico distinto.

**12. Cambio de clave, armadura o compás**  
Use **%** para cambiar la clave, **$** para cambiar la armadura y **@** para cambiar la indicación de compás. Tras el carácter respectivo, escriba la nueva indicación (clave, armadura o compás) seguida de un espacio.

##### Ejemplos

%C-1 '2A  
%C-1 $xFC '8B  
@3/2 '1C  
$nBE $xFC

**13. Formas de escritura abreviada**  
Las formas abreviadas de notación que se encuentran en la música, como trémolos o signos similares de repetición, deben escribirse en su totalidad utilizando el equivalente en notación real.  
##### Ejemplo  
{‘8DDDD} = trémolo de corchea sobre Re

**14. Acordes**  
Registre acordes desde la nota más aguda a la más grave, separando los componentes con el signo **^**.

##### Ejemplo  
4’’C^G^E^C

#### Nota general (031 $q)

Utilice este campo para registrar cualquier otro comentario, como la afinación de los instrumentos transpositores, la presencia de errores en el íncipit, el texto del íncipit con la ortografía y/o puntuación original, o cualquier otro ajuste que desee hacer. Hágalo usando su propio idioma de catalogación.

#### Plantilla/orgánico del movimiento (031 $z)

En este campo puede indicar la plantilla/orgánico específica para el movimiento en cuestión (por ejemplo, el caso de un movimiento dentro de una pieza vocal compleja). Consigne la plantilla/orgánico en una línea siguiendo las abreviaturas de instrumentos de RISM y el orden estándar (descriptas en **Resumen de plantilla/orgánico [240 $m]**). Use punto y coma para separar familias de instrumentos.

##### Ejemplos  
S (Enrico), T (Vanoldo); vl 1, 2, b; [winds]  
S 2 solo; Coro; ob obl; strings, bc