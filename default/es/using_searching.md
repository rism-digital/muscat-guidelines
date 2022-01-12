En Muscat es posible realizar **búsquedas** mediante la **búsqueda por facetas** y los **filtros**.

### Filtros de Muscat

La **búsqueda por facetas** (menú superior, en el medio) su usa para buscar los datos en un contexto de tipo OPAC. If you have editing rights for a particular source, an edit button will take you directly to the Muscat editing mode.

Una de las posibilidades de la [búsqueda avanzada](http://muscat.rism.info/advanced) es la  **búsqueda por íncipit. A keyboard permits the easy insertion of notation. Hay cuatro modos de búsqueda disponibles, con diversos grados de flexibilidad:

1. Altura exacta: el íncipit concuerda con las alturas exactas.
2. Intervalo: se ignoran las alturas, pero se buscan los intervalos. Esto permite la inclusión de **transposiciones** de una melodía dada.
3. Contorno refinado de alturas: se ignoran los intervalos y se buscan sólo los movimientos ascendentes y descendentes de la melodía.
4. Contorno grueso de alturas: es el más flexible de todos. Se busca el contorno aproximado de la melodía.

At the bottom of the page, the field **Incipit** permits the user to enter raw Plaine & Easie code (it can be copied and pasted from a source record, for example). La previsualización del pentagrama se actualiza automáticamente como sucede en el editor de Fuentes.

Todos los otros campos presentes en la Búsqueda Avanzada pueden ser combinados con la búsqueda por íncipit.

La plataforma OPAC de RISM ofrece una búsqueda simplificada por íncipit en el motor de [Búsqueda Avanzada](https://opac.rism.info/index.php?id=3&L=0). [En este enlace](https://opac.rism.info/index.php?id=8&L=0#c38) encontrará instrucciones detalladas en [video](https://youtu.be/HgXFyiXZq5M).

Don't forget to always search for the incipit before entering an anonymous source! [Incipit search first](https://youtu.be/kKc0zzc8cbo)!

### Nombres personales

¡No olvide siempre buscar el íncipit antes de ingresar una fuente anónima! ¡[Primero busque por íncipit](https://youtu.be/kKc0zzc8cbo)!

Los **filtros** de Muscat permiten hacer búsquedas simples pero poderosas.

- Palabras sueltas
- Multiple words:  
  either without quotations mark: **lass noch**   
  or with quotation marks: **"lass noch"**
- Truncation with ? or \*  
  **?**: The question mark replaces exactly one letter. **B?cher** will find Bucher and Bacher.   
  **\***: The asterisk can be used to truncate or replace any number of letters. **B\*cher** encontrará Bucher y Bacher pero también Boucher y Bötticher.
- AND, OR, NOT, (): Aproveche las ventajas de la búsqueda booleana. Use paréntesis para agrupar su búsqueda. _Ejemplos_:
    - Compositor contiene: **(Bach AND Johann) NOT Sebastian**  
      Encontrará a Johann Michael Bach y Johann Christian Bach pero no a Johann Sebastian Bach.
    - Sigla contiene: **D-B AND (I-\* OR F-P\*)**  
      Encontrará todos los casos de impresos conservados en el repositorio D-B de los cuales también haya copias en Italia o París.

En cada campo puede ingresar:

- **Fecha**

    - **Búsqueda por fecha** : Ingrese fechas en el formato AAAA-MM-DD. El día se fija a medianoche por defecto.
    - **Fechas de vida** : busca en el campo **Años de nacimiento y muerte (100 $d)**, entendiendo por fechas tanto los años como también las siguientes abreviaturas: sc a p c \* + /
    - **Nombre:** busca en los campos **Encabezado – Nombre personal (100 $a)** y **Variante de nombre (400 $a).**
    - **Date range**: Note that since the day is set at midnight, to search for all records created on February 7, 2012, for example, you must enter the start date 2012-02-07 (understood as midnight on February 7) and the end date 2012-02-08 (understood as midnight on February 8). Esto incluirá todas las fuentes creadas durante el día. ¡Una búsqueda de 2012-02-7 a 2012-02-7 no mostrará ningún resultado!  
      Por favor, tenga en cuenta lo siguiente para buscar **Fuentes** :

Please note the following for searching **Sources**:

- **Siglum contains**: Search by the letters in a siglum. Este campo registra mayúsculas y minúsculas. For example:  
  **D-&#42;** = all sources in Germany  
  **D-B&#42;** = all sources in German cities that start with B  
  **D-B** = all sources at the Staatsbibliothek zu Berlin

### Nombres personales

Please note the following for searching **Personal names**:

- **Name**: Searches the fields **Heading - Personal name (100 $a)** and **Name variant (400 $a)**.
- **Life dates**: Searches the field **Years of birth and death (100 $d)**, meaning years as well as the following abbreviations: sc a p c \* + /
- **Places**: Searches the field **Geographic name (551)**. Incluye lugares de nacimiento, muerte, origen o actividad.
