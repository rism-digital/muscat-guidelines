### Frequently asked questions

#### Usando Muscat

##### 1. Where can I find tutorials about Muscat?

All of the tutorials are linked on the RISM Editorial Center's Muscat page: [https://rism.info/community/muscat.html](https://rism.info/community/muscat.html)

##### 2. How can I contact other Muscat users?

To contact the Muscat developers: Report any errors, questions, comments, or suggestions to muscat@rism.info at any time.

**[RISM Muscat](https://groups.google.com/forum/#!forum/rism-muscat)**, a Google Group, is the official Muscat discussion list that each Muscat user must join. Los anuncios oficiales del Centro Editorial y de los desarrolladores de Muscat se difundirán únicamente a través de este grupo. Además, invitamos a todos los usuarios de Muscat a que hagan preguntas o planteen temas de discusión. No se requiere una cuenta de Google. An invitation to join the group will be sent to you when you receive your Muscat account information.

También hay un canal de discusión de Slack en: [https://rismcommunity.slack.com/](https://rismcommunity.slack.com/)

##### 3. Is all secondary literature cited in Muscat at the Editorial Center?

No, only the literature labeled "HB" or "Handbibliothek" or "RISM-ZR" in an internal note (599) is actually in our office. Those materials are for the benefit of all RISM contributors, so if we have a publication that you would like to consult, let us know and we will try to get you what you need. Even if you are interested in a publication we do not have in the office, there's a chance that we know someone who has it.

##### 4. What do I do if I forget my password or want to change it?

Passwords are managed by the Editorial Center. Contactenos si pierde su contraseña. No puede cambiar su contraseña.

##### 5. Can I show Muscat to my colleagues? Can I demonstrate Muscat at conferences or in workshops?

Yes, please do! A training version of Muscat is available for exactly these purposes at [https://muscat-training.rism.info](https://muscat-training.rism.info/). Todos los usuarios de Muscat pueden acceder a la misma con sus credenciales personales. There are also 99 training accounts ("training01@rism.info" to "training99@rism.info") available for individual users. Any of these training accounts can be used. Por favor, póngase en contacto con el Centro Editorial de RISM (contact@rism.info) para obtener la contraseña actual. En la versión de entrenamiento se puede añadir, editar o eliminar cualquier ítem. It is synchronized once a week (on Sunday) with the current Muscat data. This means that the new records will then be available but also that the ones created on the training version will be erased.

##### 6. In the modification history, what does it mean if "[system]" is listed as the author?

You might see a system edit if one of the indexed fields linked to your record was changed. The change in the authority record will also register as a change in your record.

##### 7. Can I create records based on descriptions from printed catalogs or online library catalogs?

Yes! Sometimes, for various reasons, it is not possible to access the source in person and the only description  available is in a printed catalog, catalog of works, or online library catalog. You may use such descriptions as the  basis for your record. When doing so:

- Include a **General note (500)** such as "Record based on description in YouV"
- Link to the catalog in the field **Bibliographic reference (691)** or **External resource** (856) as appropriate
- In the field Record origin (980), subfield **Material examined**, select **Material not examined**

##### 8. Can I enter sources that are included in other RISM publications from the B series?

Though we are gradually adding sources from the B series to Muscat, this is a long-term project. Records from B/I are in Muscat while B/II is in preparation. Mientras tanto, por favor siéntase libre de introducir fuentes de los otros volúmenes B. Incluya una cita del volumen B original en el campo **Bibliografía secundaria (691).**

##### 9. When do records appear in the public catalog at opac.rism.info?

Muscat records are sent for publication in the public catalog at opac.rism.info once a month, at around the 19th of each month. Unos días después, los registros son visibles.

##### 10. What if a source in RISM is no longer in the hands of the holding institution indicated in the RISM record?

Use the siglum **XX-NN** for situations in which the current location of a source is unknown, such as if it was on  deposit at an institution but the source was taken back and is now in private hands. Esto sucede sólo en raras ocasiones. Contacte con el Centro Editorial si una fuente necesita esta Sigla.

#### Aspectos técnicos de Muscat

##### 1. ¿Cuáles son los requerimientos técnicos de Muscat?

- Muscat es independiente de las plataformas y funciona tanto en Mac como en PC.
- El acceso se realiza a través de una URL y requiere una conexión a Internet.
- Muscat funciona mejor en pantallas de al menos 1366 x 768 píxeles.
- Muscat está optimizado para Firefox y Chrome. ¡No utilice Internet Explorer!

##### 2. Algunos aspectos técnicos de Muscat

- Muscat es un software de código abierto. El código fuente está disponible en el repositorio de [GitHub](https://github.com/rism-ch/muscat).
- Muscat es una aplicación de Ruby on Rails.
- [Verovio](http://www.verovio.org/pae-examples.xhtml)se utiliza para renderizar los incipits de música a través de MEI.
- Solr se utiliza como motor de búsqueda.
- Muscat cuenta con [un servicio SRU](https://github.com/rism-ch/muscat/wiki/SRU) y un _[SRU downloader](https://github.com/rism-international/sru-downloader) _que permite recuperar registros MARCXML.
- Muscat supports Unicode (UTF-8).  
  More information about the development of Muscat can be found on [RISM Digital Center's website](https://rism.digital/tools/muscat.html).

##### 3. Algunos aspectos técnicos de la búsqueda del incipit

- La misma se basa en el motor [Themefinder](http://www.themefinder.org/) desarrollado en la Universidad de Stanford.
- It leverages the underlying indexing system (Solr), used for all the search queries in Muscat, which was customized to permit the analysis of the Plaine & Easie notation used in the editor. El proceso de indexación resulta completamente transparente para los usuarios y los catalogadores, y sólo se requiere la inserción normal de la notación codificada en el campo 031.

##### 4. Otras características de Muscat

- **Versioning**: Catalogers can view changes made to records
- **VIAF**: Personal names can be imported through the [Virtual International Authority File (VIAF)](https://viaf.org/).
