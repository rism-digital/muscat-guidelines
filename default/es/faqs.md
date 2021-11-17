## Frequently asked questions

### Usando Muscat

1. **¿Dónde puedo encontrar tutoriales sobre Muscat?**  
   Todos los tutoriales están enlazados en la página de Muscat del Centro Editorial del RISM: [http://www.rism.info/en/community/muscat.html](http://www.rism.info/en/community/muscat.html)

2. **How can I contact other Muscat users?**  
   To contact the Muscat developers: Report any errors, questions, comments, or suggestions to muscat@rism.info at any time.  
   **[RISM Muscat](https://groups.google.com/forum/#!forum/rism-muscat)**, a Google Group, is the official Muscat discussion list that each Muscat user must join. Los anuncios oficiales del Centro Editorial y de los desarrolladores de Muscat se difundirán únicamente a través de este grupo. In addition, all Muscat users are encouraged to ask questions or raise topics for discussion.  
   A Google account is not required. An invitation to join the group will be sent to you when you receive your Muscat account information.  
   There is also a discussion channel on Slack at:   
   [https://rismcommunity.slack.com/](https://rismcommunity.slack.com/)

3. **¿Toda la literatura secundaria citada en Muscat está en el Centro Editorial?**  
   No, sólo la literatura etiquetada en una nota interna (599) como "HB" o "Handbibliothek" o "RISM-ZR"  está realmente en nuestra oficina. Esos materiales están destinados a todos los colaboradores de RISM, así que si tenemos una publicación que le gustaría consultar, háganoslo saber e intentaremos conseguirle lo que necesita. Incluso en caso de que esté interesado en una publicación que no tengamos en la oficina, existe la posibilidad de que conozcamos a alguien que la tenga.

4. **¿Qué hago si olvido mi contraseña o quiero cambiarla?**  
   Las contraseñas son administradas por el Centro Editorial. Contactenos si pierde su contraseña. No puede cambiar su contraseña.

5. **¿Puedo mostrar Muscat a mis colegas? ¿Puedo mostrar Muscat en congresos o talleres?**  
   ¡Sí, por favor, hágalo! Can I demonstrate Muscat at conferences or in workshops?</strong>  
   Yes, please do! Existe una versión de entrenamiento de Muscat para estos fines en [https://muscat-training.rism.info](https://muscat-training.rism.info).  Todos los usuarios de Muscat pueden acceder a la misma con sus credenciales personales. There are also 99 training accounts ("training01@rism.info" to "training99@rism.info") available for individual users. Se puede utilizar cualquiera de estas cuentas de entrenamiento. Please contact the RISM Editorial Center (contact@rism.info) for the current password.  
   Anything on the training version can be added, edited or deleted. La misma se sincroniza una vez a la semana (el domingo) con los datos actuales de Muscat. Esto implica tanto que los nuevos registros estarán disponibles, como que los creados en la versión de entrenamiento serán borrados.

6. **En el historial de modificaciones, ¿qué significa el hecho de que "[sistema]" figure como autor?**  
   Puede que vea una edición por parte del sistema en los casos en que uno de los campos indexados vinculados a su registro ha sido modificado. El cambio en un registro de autoridad vinculado también se reflejará como un cambio en su registro.

7. **¿Puedo crear registros basados en descripciones de catálogos impresos o catálogos de bibliotecas en línea?**  
   ¡Sí! A veces, por diversas razones, no es posible acceder a la fuente en persona y la única descripción disponible se encuentra en un catálogo impreso, un catálogo de obras o un catálogo de la biblioteca en línea. Sometimes, for various reasons, it is not possible to access the source in person and the only description available is in a printed catalog, catalog of works, or online library catalog. Puede utilizar dichas descripciones como base para su registro.   
   Si lo hace:  
   a. Incluya una **Nota general (500)** del tipo "Registro basado en la descripción en YouV [=nombre del catálogo]".   
   b. Haga un enlace al catálogo correspondiente en el campo **Referencia bibliográfica (691)** o **Recurso externo (856),** según proceda.  
   c. In the field Record origin (980), subfield **Material examined**, select **Material not examined**

8. **¿Puedo registrar fuentes incluidas en otras publicaciones de la serie B de RISM?**  
   Aunque estamos añadiendo gradualmente las fuentes de la serie B a Muscat, se trata de un proyecto a largo plazo. Los registros de B/I están en Muscat mientras B/II está en preparación. Mientras tanto, por favor siéntase libre de introducir fuentes de los otros volúmenes B. Incluya una cita del volumen B original en el campo **Bibliografía secundaria (691).**

9. **When do records appear in the public catalog at opac.rism.info?**  
   Muscat records are sent for publication in the public catalog at opac.rism.info once a month, at around the 19th of each month. Unos días después, los registros son visibles.

10. **¿Qué pasa si una fuente que figura en RISM ya no está en manos de la institución de indicada en el registro de RISM?**  
    Utilice la sigla  **XX-NN ** para situaciones en las que se desconoce la ubicación actual de una fuente, como es el caso de que hubiera estado depositada en una institución pero fue retirada y ahora está en manos privadas. Esto sucede sólo en raras ocasiones. Contacte con el Centro Editorial si una fuente necesita esta Sigla.

### Aspectos técnicos de Muscat

**1. ¿Cuáles son los requerimientos técnicos de Muscat?**

- Muscat es independiente de las plataformas y funciona tanto en Mac como en PC.
- El acceso se realiza a través de una URL y requiere una conexión a Internet.
- Muscat funciona mejor en pantallas de al menos 1366 x 768 píxeles.
- Muscat está optimizado para Firefox y Chrome. ¡No utilice Internet Explorer!

**2. Algunos aspectos técnicos de Muscat**

- Muscat es un software de código abierto. El código fuente está disponible en el repositorio de [GitHub](https://github.com/rism-ch/muscat).
- Muscat es una aplicación de Ruby on Rails.
- [Verovio](http://www.verovio.org/pae-examples.xhtml)se utiliza para renderizar los incipits de música a través de MEI.
- Solr se utiliza como motor de búsqueda.
- Muscat cuenta con [un servicio SRU](https://github.com/rism-ch/muscat/wiki/SRU) y un _[SRU downloader](https://github.com/rism-international/sru-downloader) _que permite recuperar registros MARCXML.
- Muscat supports Unicode (UTF-8).  
  More information about the development of Muscat can be found on [RISM Digital Center's website](https://rism.digital/tools/muscat.html).

**3. Algunos aspectos técnicos de la búsqueda del incipit**

- La misma se basa en el motor [Themefinder](http://www.themefinder.org/) desarrollado en la Universidad de Stanford.
- It leverages the underlying indexing system (Solr), used for all the search queries in Muscat, which was customized to permit the analysis of the Plaine & Easie notation used in the editor. El proceso de indexación resulta completamente transparente para los usuarios y los catalogadores, y sólo se requiere la inserción normal de la notación codificada en el campo 031.

**4. Otras características de Muscat**

- **Versioning**: Catalogers can view changes made to records
- **VIAF**: Personal names can be imported through the [Virtual International Authority File (VIAF)](https://viaf.org/).
