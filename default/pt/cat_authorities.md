# Authorities

The **Authorities** section of Muscat collects all authority files, controlled vocabulary, and indexes, and ensures that terminology is consistent throughout Muscat. Each of these is described in brief below. Full guidelines are included within each authority file.

## Digital objects

The digital objects database collects all of the images (typically watermarks, handwriting samples, or bindings) and MEI incipits that are attached to records in Muscat. You can attach digital objects to sources, people, and institutions.

## Institutions

The authority file for institutions (corporate names) describes non-persons that appear in connection with a source or other authority record in Muscat. This authority file contains both modern institutions (such as a library with a RISM library siglum) and historical corporate bodies (such as a publisher or an orchestra). Institutions can be linked in the field **Additional institution (710 $a)** in Sources, **Related institution (710 $a)** in Institutions, **Associated institution (510 $a)** in Personal names, and **Additional institution (710 $a)** in Secondary literature.

## Liturgical festivals

The index of liturgical festivals collects religious holidays and feast days. Liturgical festivals can be linked in the field **Liturgical festival (657 $a)** in Sources.

## Personal names

The authority file for personal names describes all people that are connected to a source or other authority record in Muscat. Personal names can be linked in the fields **Composer/Author (100 $a)** and **Additional personal name (700 $a)** in Sources, **Person (700 $a)** in Institutions, **Related personal name (500 $a)** in Personal names, **Author (100 $a)** and **Additional personal name (700 $a)** in Secondary literature, and **Composer (100 $a)** in Work nodes. RISM is a contributor to [VIAF (Virtual International Authority File)](https://www.viaf.org/) so names contributed to RISM are sent to VIAF on a regular basis.

New names can be edited by the record owner for two months after creation. Catalogers are encouraged to fill out as much information in the authority record as they can, including links to VIAF, biographical information, and alternate spellings. After two months, control of the record goes to the Editorial Center. Additions are still welcome and can be communicated through the comment function or by sending an email to [Alexander Marxen](mailto:alexander.marxen@rism.info).

## Places

The index of places collects the names of locations, including historical geographic names. The index is built from places entered in the following fields: **Location of performance (651 $a)** in Sources, **Geographic name (551 $a)** in Personal names, **Related place (651 $a)** in Secondary Literature, and **Place (551 $a)** in Institutions.

## Secondary literature

The database of Secondary literature enables catalogs of works, thematic catalogs, books, articles, encyclopedias, online resources, critical editions, modern performing editions, etc. to be cited in Muscat records. Secondary literature is linked through the **Short tile (210 $a)** in the fields **Catalog of works (690 $a)** and **Bibliographic reference (691 $a)** in Sources, **Literature (670 $a)** in Institutions, and **Source data found (670 $a)** in Personal names.

## Subject headings

All subject headings, musical forms, and genres are collected here. Some records include translations or explanations as to the scope of the subject heading. Subject headings are linked through the field **Subject heading (650 $a)** in Sources and **Subject heading (650 $a)** in Secondary literature.

## Titles/Text incipits

The Title/Text incipits index collects the titles entered in Sources from the fields **Standardized title (240 $a)** and **Additional title (730 $a)**, as well as the text incipits entered in the field **Text incipit (031 $t)**.

## Work nodes

Work nodes collect all information that is true for a work as a whole, no matter what other forms a piece of music exists in, whether it be—for example—an arrangement, a translation, a full score, or a single manuscript. Work nodes can include the composer, title, title variants, key, instrumentation, and incipits, though it is not always an easy matter to decide what constitutes a separate "work."

Associating a musical source in Muscat with a work ensures that all instances of any given piece of music are linked together. This improves the searchability of the catalog and helps users find all relevant sources, regardless of whether, for example, one manuscript calls the famous Mozart opera "Die Zauberflöte" and another is labeled "The Magic Flute," or a small chamber music piece is called a "duet" on one manuscript but a "sonata" on another. Beyond Muscat, in the linked data environment, information on works—and the associated RISM records—can be integrated into web searches, online encyclopedias, and other external databases.

Links to work nodes are made through the field 930 in every bibliographic record for a musical source. Works not in the authority file must be created there first before a link can be made.

**Creating a new work node**

Contact the RISM Editorial Center if you wish to create work nodes.

When you open a template to create a new authority record for a work, use the **VIAF search** to look in VIAF to see if the work is already there, and click **select** to transfer the data to your authority record and make the link to VIAF. Note that only the field 100 is searched (i.e., composer name, scoring summary, opus/thematic catalog number, key, and title), so searching for variants is not possible. Keep in mind that different VIAF contributors have different ways of expressing works, so expect variations in the formulation of titles, instruments, and even thematic indexes. A good strategy is to search by composer name plus the number of the opus/thematic index.

After you import the data from VIAF, note that it may be necessary to clean up some fields in the field **Heading (100)** to conform to RISM standards. Do not delete or edit imported information in the field **Name variants (400)**.
