### Usando Muscat

1. **¿Dónde puedo encontrar tutoriales sobre Muscat?**  
   Todos los tutoriales están enlazados en la página de Muscat del Centro Editorial del RISM: [http://www.rism.info/en/community/muscat.html](http://www.rism.info/en/community/muscat.html)

2. **¿Cómo puedo contactar con otros usuarios de Muscat?**  
   Para contactar con los desarrolladores de Muscat: Informe cualquier error, pregunta, comentario o sugerencia a muscat@rism.info en cualquier momento.

El Grupo de Google [**RISM Muscat**](https://groups.google.com/forum/#!forum/rism-muscat) es la lista de discusión oficial de Muscat a la que debe unirse cada usuario de Muscat. Los anuncios oficiales del Centro Editorial y de los desarrolladores de Muscat se difundirán únicamente a través de este grupo. Además, invitamos a todos los usuarios de Muscat a que hagan preguntas o planteen temas de discusión.

No se requiere una cuenta de Google. Se le enviará una invitación para unirse al grupo cuando reciba la información de su cuenta de Muscat.

También hay un canal de discusión de Slack en: [https://rismcommunity.slack.com/](https://rismcommunity.slack.com/)

3. **¿Toda la literatura secundaria citada en Muscat está en el Centro Editorial?**  
   No, sólo la literatura etiquetada en una nota interna (599) como "HB" o "Handbibliothek" o "RISM-ZR"  está realmente en nuestra oficina. Esos materiales están destinados a todos los colaboradores de RISM, así que si tenemos una publicación que le gustaría consultar, háganoslo saber e intentaremos conseguirle lo que necesita. Incluso en caso de que esté interesado en una publicación que no tengamos en la oficina, existe la posibilidad de que conozcamos a alguien que la tenga.

4. **¿Qué hago si olvido mi contraseña o quiero cambiarla?**  
   Las contraseñas son administradas por el Centro Editorial. Contactenos si pierde su contraseña. No puede cambiar su contraseña.

5. **¿Puedo mostrar Muscat a mis colegas? ¿Puedo mostrar Muscat en congresos o talleres?**  
   ¡Sí, por favor, hágalo! Can I demonstrate Muscat at conferences or in workshops?</strong>  
   Yes, please do! Existe una versión de entrenamiento de Muscat para estos fines en [https://muscat-training.rism.info](https://muscat-training.rism.info).

Todos los usuarios de Muscat pueden acceder a la misma con sus credenciales personales. También hay 99 cuentas de entrenamiento ("training01@rism.info" a "training99@rism.info") disponibles para usuarios individuales. Se puede utilizar cualquiera de estas cuentas de entrenamiento. Por favor, póngase en contacto con el Centro Editorial de RISM (contact@rism.info) para obtener la contraseña actual.

En la versión de entrenamiento se puede añadir, editar o eliminar cualquier ítem. La misma se sincroniza una vez a la semana (el domingo) con los datos actuales de Muscat. Esto implica tanto que los nuevos registros estarán disponibles, como que los creados en la versión de entrenamiento serán borrados.

6. **En el historial de modificaciones, ¿qué significa el hecho de que "[sistema]" figure como autor?**  
   Puede que vea una edición por parte del sistema en los casos en que uno de los campos indexados vinculados a su registro ha sido modificado. El cambio en un registro de autoridad vinculado también se reflejará como un cambio en su registro.

7. **¿Puedo crear registros basados en descripciones de catálogos impresos o catálogos de bibliotecas en línea?**  
   ¡Sí! A veces, por diversas razones, no es posible acceder a la fuente en persona y la única descripción disponible se encuentra en un catálogo impreso, un catálogo de obras o un catálogo de la biblioteca en línea. Sometimes, for various reasons, it is not possible to access the source in person and the only description available is in a printed catalog, catalog of works, or online library catalog. Puede utilizar dichas descripciones como base para su registro.   
   Si lo hace:  
   a. Incluya una **Nota general (500)** del tipo "Registro basado en la descripción en YouV [=nombre del catálogo]".   
   b. Haga un enlace al catálogo correspondiente en el campo **Referencia bibliográfica (691)** o **Recurso externo (856),** según proceda.  
   c. En el campo Origen del registro (980), subcampo **Material examinado** , seleccione **Material no examinado **

8. **¿Puedo registrar fuentes incluidas en otras publicaciones de la serie B de RISM?**  
   Aunque estamos añadiendo gradualmente las fuentes de la serie B a Muscat, se trata de un proyecto a largo plazo. Los registros de B/I están en Muscat mientras B/II está en preparación. Mientras tanto, por favor siéntase libre de introducir fuentes de los otros volúmenes B. Incluya una cita del volumen B original en el campo **Bibliografía secundaria (691).**

9. **¿Cuándo aparecen los registros en el catálogo público de opac.rism.info?**  
   Los registros de Muscat se envían para su publicación en el catálogo público en opac.rism.info una vez al mes, alrededor del día 19. Unos días después, los registros son visibles.

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
- Se puede encontrar más información sobre el desarrollo de Muscat en el [sitio web del](https://rism.digital/tools/muscat.html)_[RISM Digital Center](https://rism.digital/tools/muscat.html)

**3. Algunos aspectos técnicos de la búsqueda del incipit**

- La misma se basa en el motor [Themefinder](http://www.themefinder.org/) desarrollado en la Universidad de Stanford.
- Éste aprovecha el sistema de indexación subyacente (Solr), utilizado para todas las consultas de búsqueda en Muscat, que se ha personalizado para permitir el análisis de la notación PAE utilizada en el editor. El proceso de indexación resulta completamente transparente para los usuarios y los catalogadores, y sólo se requiere la inserción normal de la notación codificada en el campo 031.

**4. Otras características de Muscat**

- Versiones: Los catalogadores pueden ver los cambios realizados en los registros
- VIAF: Los nombres personales pueden ser importados a través del [Fichero de Autoridades Virtual Internacional (VIAF).](https://viaf.org/)
