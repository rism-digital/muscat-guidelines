# RISM Best Practices

**1. Free text fields and indexed fields**  
If you name a person or institution in your record (such as in a notes field), make sure to also enter the name in the indexed fields **Additional personal name (700)** or **Additional institution (710)**.

The same applies for citing secondary literature: if you refer to a publication in a notes field, make sure to also enter it in the field **Bibliographic reference (691)**.

**2. Citing secondary literature**  
Information that is not found on the source may be included in the RISM record but a Bibliographic reference (691) should be added. For example, if the composer of a manuscript is known through a book, or if the publication year for an imprint is given in a catalog, the source of the information should be made clear through a note (500) and an indexed reference (691).

**3. URLs and links to external resources**  
Always use permalinks when linking to digitized music, in particular for the field **External resource (856)**.

If you want to link to a different website, do not enter the URL in a notes field. Rather, enter the resource as a bibliographic reference by entering it in the **Secondary literature** database. Then, link to it in the field **Bibliographic reference (691)** and refer to it by its short title in a notes field. This provides users with access to complete bibliographic information, and if the URL changes then we only have to change it once in the bibliographic record.

For books found on Google Books or other online repositories, always create a bibliographic record in the **Secondary literature** database for the book itself and not the repository; i.e. cite the book and not Google Books.

**4. Making identifications**   
Important information such as names of composers or titles of pieces is not always named on the source itself. It is sometimes possible to make identifications based on the secondary literature, reference sources, other RISM records, or even archival sources you have access to. If you draw upon such resources, always be clear in the record about what you used to make the identification: name the resource in a **General note (500)** and add a **Bibliographic reference (691)** if appropriate. Make sure it is clear for later RISM users how you came to your conclusions.