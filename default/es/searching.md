En Muscat es posible realizar **búsquedas** mediante la **búsqueda por facetas** y los **filtros**.

### Filtros de Muscat

La **búsqueda por facetas** (menú superior, en el medio) su usa para buscar los datos en un contexto de tipo OPAC. Si Ud. cuenta con derechos de edición sobre una fuente en particular, un botón de edición lo llevará directamente al modo de edición del registro respectivo Muscat.

Una de las posibilidades de la [búsqueda avanzada](http://muscat.rism.info/advanced) es la  **búsqueda por íncipit. ** Un teclado facilita el ingreso de la notación musical. Hay cuatro modos de búsqueda disponibles, con diversos grados de flexibilidad:

1. Altura exacta: el íncipit concuerda con las alturas exactas.
2. Intervalo: se ignoran las alturas, pero se buscan los intervalos. Esto permite la inclusión de **transposiciones** de una melodía dada.
3. Contorno refinado de alturas: se ignoran los intervalos y se buscan sólo los movimientos ascendentes y descendentes de la melodía.
4. Contorno grueso de alturas: es el más flexible de todos. Se busca el contorno aproximado de la melodía.

Al final de la página, el campo **Íncipit** permite al usuario ingresar un fragmento de código Plaine & Easie (el mismo puede ser copiado y pegado desde una Fuente, por ejemplo). La previsualización del pentagrama se actualiza automáticamente como sucede en el editor de Fuentes.

Todos los otros campos presentes en la Búsqueda Avanzada pueden ser combinados con la búsqueda por íncipit.

La plataforma OPAC de RISM ofrece una búsqueda simplificada por íncipit en el motor de [Búsqueda Avanzada](https://opac.rism.info/index.php?id=3&L=0). [En este enlace](https://opac.rism.info/index.php?id=8&L=0#c38) encontrará instrucciones detalladas en [video](https://youtu.be/HgXFyiXZq5M).

Don't forget to always search for the incipit before entering an anonymous source! [Incipit search first](https://youtu.be/kKc0zzc8cbo)!

### Nombres personales

¡No olvide siempre buscar el íncipit antes de ingresar una fuente anónima! ¡[Primero busque por íncipit](https://youtu.be/kKc0zzc8cbo)!

Los **filtros** de Muscat permiten hacer búsquedas simples pero poderosas.

- Palabras sueltas
- Múltiples palabras:  
  tanto sin comillas: **lass noch**    
  como con comillas: **“lass noch”**
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

- **Siglum contains**: Search by the letters in a siglum. Este campo registra mayúsculas y minúsculas. Por ejemplo:  
  **D-\*** = todas las fuentes en Alemania  
  **D-B\*** = todas las fuentes en ciudades alemanas que empiezan con B  
  **D-B** = todas las fuentes en la _Staatsbibliothek zu Berlin_

### Nombres personales

Please note the following for searching **Personal names**:

- **Name**: Searches the fields **Heading - Personal name (100 $a)** and **Name variant (400 $a)**.
- **Life dates**: Searches the field **Years of birth and death (100 $d)**, meaning years as well as the following abbreviations: sc a p c \* + /
- **Places**: Searches the field **Geographic name (551)**. Incluye lugares de nacimiento, muerte, origen o actividad.
