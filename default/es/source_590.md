### Particellas conservadas y extensión de las mismas (590)

**Requerido si la fuente contiene particellas.**

The field **Parts held and extent** indicates which parts are held and their foliation/pagination.

#### Particellas conservadas (590 $a)

Registre las particellas conservadas siguiendo la lista de abreviaturas de instrumentos de RISM y su cantidad. If you wish, you may use the designations that appear on the source if they vary from the standardized RISM abbreviation.

La primera letra de las abreviaturas de partes instrumentales se coloca en minúscula y la de las partes vocales, en mayúsculas. El orden en que deben nombrarse las particellas se consigna a continuación.

- Partes vocales solistas. Inicie el campo con **Solo:**
- Partes vocales corales. Inicie el campo con **Coro:**
- Instrumentos solistas
- Cuerdas
- Bajo continuo
- Vientos-madera
- Vientos-metal
- Otros instrumentos

If no further details of the part designations are available, write the English phrase: **no further indication**

Casos especiales:

- Figured bass: If you have a figured bass, enter the instrument followed by **.fig**, such as **b.fig**, **bc.fig**, **org.fig**, etc. (but see the tables in the section **Figured bass in scores and/or parts** for guidance with related fields).
- Instrumento que no aparece en la lista de abreviaturas de RISM: escriba el instrumento en su totalidad.
- Unusual instruments, designations, or tunings (such as **cor in D\|x**) may be written out in full; however, in the field **Total scoring (594)**, try to standardize the instrument to RISM's instrument abbreviation list if possible (such as **cor in E\|b**).
- Keyboard part with text: Enter using English **pf with text** (or **org with text**, **keyb with text**, etc.). Lo mismo se registra en el campo de **Voz/instrumento** **(031 $m)** correspondiente al íncipit.
- In partbooks of the 15th and 16th centuries, it is sometimes the case that a part appears in a partbook that differs from the partbook’s label, such as a Tenor 2 part that is printed in a Quinta vox (V 5) partbook. In this field, you can indicate where each part is found by using an equals sign.  
  Example:  
  Partbooks are S, A, T, B, V 5. V 5 contains a T 2 part.  
  S, A, T, B, V 5 (= T 2)  
  See also the field **Total scoring (594)** on how to enter the total instrumentation.


#### Extensión (partes) (590 $b)

Registre el número de folios, páginas, hojas o pliegues de cada particella. Utilice un solo método de enumeración. Elija entre las siguientes abreviaturas:

- **f** para folio
- **p** para página
- **lvs** para hojas
- **fds** para pliegos

Indicate other units (such as the conversion from folios to pages) in the field **General note (500)**.

También se pueden indicar páginas o folios particulares de una pieza dentro de una colección manuscrita, por ejemplo, **p. 5-6** o **f. 4r-4v**.

##### Examples
There are two different ways list the parts.

*Ejemplo 1*: Una familia instrumental por línea e instrumentos separados por coma. Se repite el campo para cada familia.

**(= bc)**: la particella es de bajo continuo

**Particellas conservadas (590 $a)**: Coro: S, A, T B  
**Extensión (particellas) (590 $b)**: 4, 4, 4, 4 p.

**Parts held (590 $a)**: vl 1, 2, vla, vlc, b (= bc)  
**Extent (parts) (590 $b)**: 4, 4, 3, 4, 2 p.

**Parts held (590 $a)**: ob 1, 2, cl 1, 2 in B\|b  
**Extent (parts) (590 $b)**: 2, 2, 2, 2 p.

**Parts held (590 $a)**: tr 1 and 2 in B\|b   
**Extent (parts) (590 $b)**: 2 p.

**Particellas conservadas (590 $a)**: org (incpl)  
**Extensión (particellas) (590 $b)**: 8 p.

*Example 2*: Everything on one line with a comma separating the instruments and a semicolon separating the instrument families (but this can be hard to follow if many parts are present)

**Particellas conservadas (590 $a)**: Solo: S (2x), A, T, Bariton, B; Coro: S; vl 1, 2, vla, vlc, cb (incpl); fl 1, 2, ob; cor 1 and 2  
**Extensión (particellas) (590 $b)**: 2, 2, 2, 3, 3, 3; 3; 5, 5, 3, 2, 1; 4, 3, 4; 2 f.

#### Información adicional

Se puede añadir información adicional (breves comentarios) sobre aspectos tales como el número o lo incompleto de las partes entre paréntesis, inmediatamente después de la designación de parte. Siga las siguientes convenciones:

- Si tiene múltiples copias de la misma parte, indique la cantidad de copias con un número seguido de una x en el subcampo **Particellas conservadas**. Example: **S (2x)**
- **Particellas conservadas (590 $a)**: Solo:
- **(incpl)**: la particella está incompleta
- Use una barra inclinada (/) para unir dos elementos: **bc (2x/incpl)**
- Si una particella contiene la música de varios instrumentos, use el conector **and** (y). Ejemplo: **tr 1 and 2**
- You can include the tuning: **cl 1, 2 in B\|b**  
