### Odpowiedzi na częste pytania

Ta część zawiera informacje o Muscacie, które nie są związane z wytycznymi dotyczącymi katalogowania.

#### 1. Gdzie mogę znaleźć tutoriale na temat programu Muscat?

Linki do wszystkich tutoriali znajdują się na stronie programu Muscat [RISM Editorial Center](https://rism.info/community/muscat.html):

#### 2. Jak mogę skontaktować się z innymi użytkownikami Muscat?

Wszelkie błędy, pytania, komentarze i sugestie można zgłaszać w dowolnym momencie na adres [muscat@rism.info](mailto:muscat@rism.info).

**[RISM Muscat](https://groups.google.com/forum/#!forum/rism-muscat)**, grupa Google, jest oficjalną grupą dyskusyjną Muscat, do której należy każdy użytkownik Muscat. Official announcements from the Editorial Center and the Muscat developers are disseminated solely through this group. In addition, all Muscat users are encouraged to ask questions or raise topics for discussion. A Google account is not required.

There is also a discussion channel for the RISM community on Slack at:   
[https://rismcommunity.slack.com/](https://rismcommunity.slack.com/)

#### 3. Is all secondary literature cited in Muscat at the Editorial Center?

No, only the literature labeled "HB" or "Handbibliothek" or "RISM-ZR" in an internal note (599 $a) is actually in the Editorial Center office. These materials are for the benefit of all RISM contributors, so if we have a publication that you would like to consult, let us know and we will try to get you what you need. Even if you are interested in a publication we do not have in the office, let us know and we can try to help you gain access to it.

#### 4. What do I do if I forget my password or want to change it?

Contact the Editorial Center if you lose your password. You can change your password by clicking on your user name (in the upper right-hand corner of Muscat).

#### 5. Can I show Muscat to my colleagues? Can I demonstrate Muscat at conferences or in workshops?

Yes, you are welcome to do so. A training version of Muscat is available for exactly these purposes at [https://muscat-training.rism.info](https://muscat-training.rism.info/). All Muscat users can login there with their personal credentials. There are also 99 training accounts ("training01@rism.info" to "training99@rism.info") available for individual users. Any of these training accounts can be used. Contact the RISM Editorial Center for the current password. Anything on the training version can be added or edited. It is updated with the current Muscat data on a regular basis, so practice records on the training server are be deleted after these updates. New records or changes on the training server are not transferred to the main Muscat program.

#### 6. In the modification history, what does it mean if "[system]" is listed as the author?

This is a system edit. You might see a system edit if one of the indexed fields linked to your record was changed. The change in the authority record will register as a change in your record. Changes undertaken by maintenance scripts are also registered as system edits.

#### 7. Where are Muscat records published?

Muscat records that have the publication status **published** appear in the [RISM Catalog](https://opac.rism.info/), developed by the [Bavarian State Library](https://www.bsb-muenchen.de/) (Munich, Germany), and [RISM Online](https://rism.online/), developed by the [RISM Digital Center](https://rism.info/digital-center.html) (Bern, Switzerland).

Outside of Muscat, published Muscat records are available through RISM's [SRU downloader](https://github.com/rism-international/sru-downloader), the RISM Catalog's "Show MARCXML" link on any record, the RISM Catalog's monthly data dump, and RISM Online's API.

#### 8. When do Muscat records appear in the public catalogs?

Muscat records are sent for publication in the [RISM Catalog](https://opac.rism.info/) once a month, at around the 19th of each month. Records are then visible a few days later. [RISM Online](https://rism.online/) is updated once a day with records from Muscat.

#### 9. What if a source in RISM is no longer in the hands of the holding institution indicated in the RISM record?

Use the siglum **XX-NN** for situations in which the current location of a source is unknown, such as if it was on deposit at an institution but the source was taken back and is now in private hands. This happens only rarely. Contact the Editorial Center if a source needs this siglum.

#### 10. What are the technical requirements for Muscat?

- Muscat is platform independent and works on both Macs and PCs.
- Access is through a URL and requires an Internet connection.
- Muscat works best on screens that are at least 1366 x 768 pixels.
- Muscat is optimized for Firefox and Chrome. Do not use Internet Explorer!

#### 11. What are some technical aspects about Muscat?

- Muscat is open source. The source code is available in the [GitHub](https://github.com/rism-ch/muscat) repository.
- Muscat is a Ruby on Rails application.
- [Verovio](https://www.verovio.org/pae-editor.html) is used to render the music incipits through MEI.
- Solr is used as a search engine.
- Muscat has [an SRU service](https://github.com/rism-ch/muscat/wiki/SRU) and an [SRU downloader](https://github.com/rism-international/sru-downloader) to retrieve MARCXML records.
- Muscat supports Unicode (UTF-8).
- Versioning allows catalogers to view changes made to records.

More information about the development of Muscat can be found on [RISM Digital Center's website](https://rism.digital/tools/muscat.html).
