### Frequently asked questions

The section **Frequently asked questions** contains information about Muscat that is not related to the cataloging guidelines.

#### 1. Where can I find tutorials about Muscat?

All of the tutorials are linked on the RISM Editorial Center's Muscat page: [https://rism.info/community/muscat.html](https://rism.info/community/muscat.html)

#### 2. How can I contact other Muscat users?

To contact the Muscat developers: Report any errors, questions, comments, or suggestions to muscat@rism.info at any time.

**[RISM Muscat](https://groups.google.com/forum/#!forum/rism-muscat)**, a Google Group, is the official Muscat discussion list that each Muscat user should join. Official announcements from the Editorial Center and the Muscat developers will be disseminated solely through this group. In addition, all Muscat users are encouraged to ask questions or raise topics for discussion. No se requiere una cuenta de Google. An invitation to join the group will be sent to you when you receive your Muscat account information.

There is also a discussion channel for the RISM community on Slack at:   
[https://rismcommunity.slack.com/](https://rismcommunity.slack.com/)

#### 3. Is all secondary literature cited in Muscat at the Editorial Center?

No, only the literature labeled "HB" or "Handbibliothek" or "RISM-ZR" in an internal note (599) is actually in our office. These materials are for the benefit of all RISM contributors, so if we have a publication that you would like to consult, let us know and we will try to get you what you need. Even if you are interested in a publication we do not have in the office, there is a chance that we know someone who has it.

#### 4. What do I do if I forget my password or want to change it?

Passwords are managed by the Editorial Center. Contactenos si pierde su contraseña. You can change your password by clicking on your user name (in the upper right-hand corner of Muscat).

#### 5. Can I show Muscat to my colleagues? Can I show Muscat to my colleagues? Can I demonstrate Muscat at conferences or in workshops?

Yes, you are welcome to do so. A training version of Muscat is available for exactly these purposes at [https://muscat-training.rism.info](https://muscat-training.rism.info/). Todos los usuarios de Muscat pueden acceder a la misma con sus credenciales personales. There are also 99 training accounts ("training01@rism.info" to "training99@rism.info") available for individual users. Any of these training accounts can be used. Contact the RISM Editorial Center for the current password. Anything on the training version can be added or edited. It is synchronized with the current Muscat data on a regular basis, so practice records on the training server may be deleted. New records or changes on the training server are not transferred to the main Muscat program.

#### 6. In the modification history, what does it mean if "[system]" is listed as the author?

This is a system edit. You might see a system edit if one of the indexed fields linked to your record was changed. The change in the authority record will register as a change in your record.

#### 7. Where are Muscat records published?

Muscat records that have the publication status "published" appear in the [RISM Catalog](https://opac.rism.info/), developed by the [Bavarian State Library](https://www.bsb-muenchen.de/) (Munich), and [RISM Online](https://rism.online/), developed by the [RISM Digital Center](https://rism.info/digital-center.html) (Bern, Switzerland). In addition, RISM records are available as open data and linked open data and may be reused in other projects.

Outside of Muscat, published Muscat records are availble through RISM's [SRU downloader](https://github.com/rism-international/sru-downloader), the RISM Catalog's "Show MARCXML" link on any record, the RISM Catalog's monthly data dump, and RISM Online's API.

#### 8. When do Muscat records appear in the public catalogs?

Muscat records are sent for publication in the [RISM Catalog](https://opac.rism.info/) once a month, at around the 19th of each month. Unos días después, los registros son visibles. [RISM Online](https://rism.online/) is updated once a day with records from Muscat.

#### 9. What if a source in RISM is no longer in the hands of the holding institution indicated in the RISM record?

Use the siglum **XX-NN** for situations in which the current location of a source is unknown, such as if it was on deposit at an institution but the source was taken back and is now in private hands. Esto sucede sólo en raras ocasiones. Contacte con el Centro Editorial si una fuente necesita esta Sigla.

#### 10. ¿Cuáles son los requerimientos técnicos de Muscat?

- Muscat es independiente de las plataformas y funciona tanto en Mac como en PC.
- El acceso se realiza a través de una URL y requiere una conexión a Internet.
- Muscat funciona mejor en pantallas de al menos 1366 x 768 píxeles.
- Muscat está optimizado para Firefox y Chrome. ¡No utilice Internet Explorer!

#### 11. Algunos aspectos técnicos de Muscat

- Muscat es un software de código abierto. The source code is available in the [GitHub](https://github.com/rism-ch/muscat) repository.
- Muscat es una aplicación de Ruby on Rails.
- [Verovio](https://www.verovio.org/pae-editor.html) is used to render the music incipits through MEI.
- Solr se utiliza como motor de búsqueda.
- Muscat cuenta con [un servicio SRU](https://github.com/rism-ch/muscat/wiki/SRU) y un _[SRU downloader](https://github.com/rism-international/sru-downloader) _que permite recuperar registros MARCXML.
- Muscat supports Unicode (UTF-8).
- Versioning allows catalogers to view changes made to records.
- Personal names can be imported through the [Virtual International Authority File (VIAF)](https://viaf.org/).

More information about the development of Muscat can be found on [RISM Digital Center's website](https://rism.digital/tools/muscat.html).
