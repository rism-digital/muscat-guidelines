### Recurso externo (856)  

Use este campo para realizar un vínculo hacia una fuente externa que tenga una conexión directa con la fuente descripta.

#### URL del recurso externo (856 $u)

Registre la URL completa del recurso externo. Siempre use permalinks.

#### Nota sobre recurso externo (856 $z)
**Campo requerido cuando se registra un vínculo a un recurso externo.**  
Realice un breve comentario que explique por qué la URL es relevante para la fuente descripta. Hágalo en su propio idioma de catalogación.

_Ejemplos_:  
Copia digital  
Filigrana en p. 4  
Página principal del proyecto  
Detalle de la encuadernación  
Registro bibliográfico  
Enlace al registro en Bach Digital  
Enlace a la obra en el Catálogo Temático Online de Frescobaldi  
Entrada en el registro de la iglesia  
Enlace al RISM ID no. 806155758, GB-Lbl Add. 14209 f.23r-27v, una versión de N. Porpora sobre este texto  
Fuente concordante en GB-Ob

#### Tipo de enlace (856 $x)

**Campo requerido cuando se registra un vínculo a un recurso externo. ** Seleccione entre las siguientes opciones:

- **Fuente digitalizada** : el enlace pertenece a un sitio web externo que alberga una copia digitalizada del recurso descripto. Se privilegian los enlaces a repositorios institucionales; no obstante, si no hay repositorios institucionales disponibles, se aceptan enlaces a repositorios externos tales como_Internet_ _Archive_ o IMSLP. En el caso de las colecciones, no es necesario duplicar el mismo enlace en la entrada principal de la colección y las entradas individuales.  
_Ejemplo:  
[https://mirador.acdh.oeaw.ac.at/musikarchivspitz/A-SPD\_A15/](https://mirador.acdh.oeaw.ac.at/musikarchivspitz/A-SPD_A15/)_  

- **Manifiesto IIIF** : el objeto vinculado es un objeto JSON legible por máquina, procesado con un visor de documentos interno como diva.js. El documento aparece incrustado directamente en la página web. En muchos casos, el link mismo incluye partículas como "manifest," "iiif" u otras similares.  
_Ejemplo_:   
*[https://iiif.lib.harvard.edu/manifests/drs:2820650](https://iiif.lib.harvard.edu/manifests/drs:2820650)*  
  
En casos en los que haya enlaces disponibles tanto a un visor externo como a un manifiesto IIIF, repita el campo y consigne ambos enlaces por separado.  
_Ejemplo:_

  - Fuente externa: [http://nrs.harvard.edu/urn-3:FHCL.Loeb:537966](http://nrs.harvard.edu/urn-3:FHCL.Loeb:537966)   
Nota: versión digitalizada  
Tipo de enlace: recurso digitalizado
  - Fuente externa: [https://iiif.lib.harvard.edu/manifests/drs:2820650](https://iiif.lib.harvard.edu/manifests/drs:2820650)  
Nota: manifiesto IIIF  
Tipo de enlace: manifiesto IIIF
- **Otro** : vínculo a un recurso diferente de la fuente descripta.

####   

#### Tipos de enlaces externos

**Tipo de enlace 856 $x: Fuente digitalizada**   
Enlace solo a la fuente correspondiente al registro RISM. Use solamente permalinks. Si no hay permalinks disponibles, puede realizar un vínculo a una página en la cual sea fácil hallar el enlace al documento digitalizado (por ejemplo, un registro bibliográfico en un catálogo de biblioteca). Se pueden incluir fragmentos digitalizados de la fuente digitalizada (unas pocas páginas, por ejemplo) si no hay disponible una versión digitalizada por completo.

Los vínculos identificados como música digitalizada se muestran en el filtro “Música digitalizada” del OPAC público de RISM (opac.rism.info).

**Tipo de enlace 856 $x: Otro**

A continuación se presentan otros tipos de recursos externos. Asegúrese de que siempre resulte claro para el usuario por qué se incluye el link, tal como se señala en **Nota general (500):**

- **Detalles de las fuentes**  
Detalles de las fuentes que muestran aspectos específicos, como filigranas, encuadernaciones, portadas o tapas.
- **Registros catalográficos / Bases de datos**  
Incluye entradas bibliográficas en catálogos externos o entradas en bases de datos externas. Las bases externas de datos para investigación que proveen información útil pueden incluirse; no obstante, considere si no es más conveniente enlazarlas como bibliografía secundaria.
- **Catálogos electrónicos de obras, enciclopedias en línea, fuentes digitalizadas de referencia**  
En general, use los campos **Bibliografía secundaria (691)** o **Catálogo de obras (690)** para referirse a obras de referencia online tales como catálogos de obras o enciclopedias. Sin embargo, como un servicio a los usuarios, puede resultar útil incluir adicionalmente un enlace directo a un lugar preciso dentro del recurso mediante el campo 856.
- **Fuentes de archivo, fuentes históricas**  
Incluye registros o documentos municipales digitalizados, correspondencia digital, diarios históricos. En este caso, primero asegúrese de que la relevancia de la fuente de archivo quede clara en una **Nota general (500)** y luego incluya el enlace directo en este campo. En el caso de los diarios históricos, será necesario ingresar el nombre del diario como bibliografía secundaria; este campo puede ser utilizado para realizar un vínculo la página específica donde se encuentre el artículo. Asegúrese de incluir en una nota información sobre el artículo, como título y fecha.
- **Sitios web**  
Incluye sitios de proyectos, sitios de agencias de financiación externas u otros sitios relevantes.
- **Otros registros RISM**  
Solo incluya enlaces a otros registros RISM si los mismos guardan relación directa con la fuente que está siendo descripta. Utilice sólo permalinks del OPAC de RISM ([https://opac.rism.info/](https://opac.rism.info/)). Es necesario que resulte claro para el usuario por qué dicho registro es relevante para la fuente. Indique, al menos, la biblioteca, la signatura topográfica y el número ID de RISM del registro en una nota. En ocasiones puede ser mejor explicar la relación con una fuente diferente en una **Nota general (500)**. En caso de que refiera a otros registros RISM en algún otro lugar de su registro, no es necesario que los enlace en este campo. No es necesario víncular aquí todas las fuentes concordantes en RISM; de hecho, es un esfuerzo en vano, ya que el número de fuentes crece diariamente en Muscat.
- **Referencias a fuentes relevantes que aparezcan en otras bibliotecas pero no en RISM**  
En caso de que desee realizar un vínculo a una fuente que aún no esté en RISM, considere primero si resulta posible para su equipo de trabajo registrar primero el libreto, tratado o manuscrito en cuestión, o añadir registros de ejemplares a un impreso en particular. La Oficina Central le ayudará con gusto si considera que cierta fuente debería estar en RISM. Sin embargo, resultará entendible si no puede crear un nuevo registro para la fuente en tal caso.
- **Otras fuentes relevantes**  
Incluye concordancias de fuentes, obras, arias o secciones de obras, o fuentes que sirvieron de base a la fuente que está siendo descripta. Puede tratarse tanto de vínculos a los objetos digitalizados como de enlaces a catálogos externos.