### Buenas prácticas en RISM

This section outlines best practices when cataloging for RISM; that is, conventions that are not codified in the guidelines but nevertheless contribute to sound, reliable, and transparent records.

#### 1. Free text fields and indexed fields

If you name a person or institution in your record (such as in a notes field), make sure to also enter the name in the indexed fields **Additional personal name (700)** or **Additional institution (710)**.

Si nombra a una persona o institución en su registro (por ejemplo, en un campo de notas), asegúrese de introducir también el nombre en los campos indexados de **Nombre personal adicional (700)** o **Institución adicional (710).**

#### 2. Citing secondary literature

Information that is not found on the source may be included in the RISM record but the secondary literature should be cited. For example, if the composer of a manuscript is known through a journal article, or if the publication year for a printed edition is given in a published study on the publisher, the source of the information should be made clear through a **General note (500)** and indexed in the field **Bibliographic reference (691)**.

#### 3. URLs and links to external resources

Always use permalinks, in particular when linking to digitized music in the field **External resource (856)**.

If you want to link to a website, do not enter the URL in a notes field. Rather, enter the resource as a bibliographic reference. This is done by entering it in the **Secondary literature** database. Then, link to it in the field **Bibliographic reference (691)** and refer to it by its short title in a notes field. This provides users with access to complete bibliographic information, and if the URL changes then an update is only needed once through the Secondary literature database.

For books found on Google Books or other online repositories, always create a bibliographic record in the **Secondary literature** database for the book itself and not the repository; that is, cite the book and not Google Books.

If you wish to refer to a musical source that is digitized but not in RISM, please contact the RISM Editorial Center to discuss having the source added.

#### 4. Making identifications

Frequently, important information such as names of composers or titles of pieces is not always named on the source itself. It is sometimes possible to make identifications based on the secondary literature, reference sources, other RISM records, or even archival sources. If you draw upon such resources, always be clear in the record about what you used to make the identification: name the resource or RISM ID number in a **General note (500)** and add a **Bibliographic reference (691)** if appropriate. Asegúrese de que resulte claro, para usuarios posteriores del RISM, cómo llegó usted a sus conclusiones. More detailed, explanatory information not relevant for the public can be included in an **Internal note (599)** if needed.

#### 5. Creating records based on descriptions from printed catalogs or online library catalogs

Sometimes it is not possible to access the source in person and the only description available is in a printed catalog, catalog of works, or online library catalog. Such descriptions may be used as the basis of a RISM record. When doing so:

- Include a **General note (500)** that identifies the source of information, such as "Record based on description in YouV"
- Link to the source of information in the field **Bibliographic reference (691)** or **External resource** (856) as appropriate
- In the field **Record origin (980)**, subfield **Material examined**, select **Material not examined**
