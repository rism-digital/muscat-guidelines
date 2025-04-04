### RISM Best Practices

This section outlines best practices when cataloging for RISM; that is, conventions that are not codified in the guidelines but nevertheless contribute to sound, reliable, and transparent records.

#### 1. Free text fields and indexed fields

If you name a person or institution in your record (such as in a notes field), make sure to also enter the name in the indexed fields **Additional personal name (700)** or **Additional institution (710)**.

The same applies for citing secondary literature: if you refer to a publication in a notes field, make sure to also enter it in the field **Bibliographic reference (691)**.

Conversely, make sure that the relevance of an indexed name or institution is clear, such as through an explanation in a notes field.

#### 2. Citing secondary literature

Information that is not found on the source may be included in the RISM record, but the secondary literature should be cited. For example, if the composer of a manuscript is known through a journal article, or if the publication year for a printed edition is given in a published study on the publisher, the source of the information should be made clear through a **General note (500)** and indexed in the field **Bibliographic reference (691)**.

#### 3. URLs and links to external resources

Always use permalinks, in particular when linking to digitized music in the field **External resource (856)**.

If you want to link to a website, do not enter the URL in a notes field. Rather, enter the resource as a bibliographic reference. Then, link to it in the field **Bibliographic reference (691)** and refer to it by its short title in a notes field. This is done by entering it in the **Secondary literature** authority. This provides users with access to complete bibliographic information, and if the URL changes then an update is only needed once through the **Secondary literature** database.

For books found on Google Books or other online repositories, always create a bibliographic record in the **Secondary literature** authority for the book itself and not the repository; that is, cite the book and not Google Books.

For databases cited as secondary literature, as a convenience for our users you may cite the database in the **Bibliographic reference (691)** field and then provide a direct link to the entry in the database through the **External resource (856)** field.

If you wish to refer to a musical source that is digitized but not in RISM, contact the RISM Editorial Center to discuss having the source added.

#### 4. Making identifications

Frequently, important information—such as names of composers or titles of pieces—is not always named on the source itself. It is sometimes possible to make identifications based on the secondary literature, reference sources, other RISM records, or archival sources. If you draw upon such resources, always be clear in the record about what you used to make the identification: name the resource or source in RISM (with siglum, shelfmark, and RISM ID number) in a **General note (500)** and add a **Bibliographic reference (691)** if appropriate. Make sure it is clear for later RISM users how you came to your conclusions. More detailed, explanatory information not relevant for the public can be included in an **Internal note (599)** if needed.

#### 5. Creating records based on descriptions from printed catalogs or online library catalogs

Sometimes it is not possible to access the source in person and the only description available is in a printed catalog, catalog of works, or online library catalog. Such descriptions may be used as the basis of a RISM record. When doing so:

- Include a **General note (500)** that identifies the source of information, such as "Record based on description in YouV"
- Link to the source of information in the field **Catalog of works (690)**, **Bibliographic reference (691)**, or **External resource** (856) as appropriate
- In the field **Record origin (980)**, subfield **Material examined**, select **Material not examined**

#### 6. The shared cataloging environment of printed music

Bibliographic records for printed editions exist in a shared cataloging environment where multiple libraries have editing rights to the same record. This differs from manuscripts, which are unique to the holding library. Due to the shared environment, care must be taken so that the implications of adding or deleting information from core bibliographic records is thought through.

Catalogers should not remove information from the core record if it is correct. Administrative information is stored in the records that can explain decisions made by the Editorial Center and the relationship to other records. Never delete a note that indicates that a record was merged with another record. Do not delete or edit data in the fields **Initial entry in A/I (775)**, **Local number (035)**, or **RISM series (510)**.

If a record has already been revised by another working group (evident by the presence of a library's siglum and shelfmark in the field **Source of description note (588)**), use cataloger's judgement as to whether further revision is necessary. If you make further changes, make it clear in the note what revisions you contributed.

If your copy is incomplete, revisions might still be possible, but make it clear in the **Source of description note (588)** that your copy is incomplete.

If you wish to edit a record that was previously described using an incomplete copy, it must first be ensured that the accurate material information is preserved in the holdings record of the library with the incomplete copy. The Editorial Center can assist with transferring data to holdings records.
