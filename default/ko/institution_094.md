### Siglum (094)

The field **Siglum** is for the unique, unalterable RISM library siglum. Sigla are assigned by the RISM Editorial Center in
consultation with the RISM national working groups.

RISM has been using library sigla since its foundation in 1952 in all of its publications and catalogs. They are also used in all of the standard international music encyclopedias and in musicological publications.

**Obsolete procedures and MARC export note**: Previously the siglum for an institution was stored in the 110 $g field. This was changed to a dedicated field in 2024 to
allow former sigla to be tracked within the same field. The siglum in 094 $a is copied to 110 $g upon saving.

#### Siglum (094 $a)

Enter the RISM siglum. Sigla are made up of three elements: a country abbreviation, a city abbreviation, and an institution
abbreviation. The abbreviations for the country and city are always capitalized and the abbreviation for the institution is always lowercase. The country code is separated from the other details by a hyphen. The code for the country is taken from the list of international vehicle registration
codes maintained by the United Nations. City and institution codes are assigned by the RISM Editorial Center.

If an institution has changed its name it keeps the same siglum.

In general, if a library collection is moved to a new host institution the sources are not assigned a new institution, and thus the siglum of
the now-subsumed library will remain. An entry is added to the institution record under the 580 "Now in" field pointing to the institution record
of the new host. This is evaluated on a case-by-case basis.

In the case of private collections, the last name of the owner is added to the city code in lowercase letters. Double last names are written together, without a space.

##### Examples

- GB-Cu = United Kingdom, Cambridge, University Library
- F-Pn = France, Paris, Bibliothèque nationale de France, Département de la Musique
- CZ-Bu = Czech Republic, Brno, Moravská zemská knihovna v Brně (formerly the Universitní knihovna)
- I-PEbattisti = Italy, Perugia, Biblioteca privata Renzo Battisti

**Obsolete procedures:** In some cases, the institution abbreviation was omitted (example: D-B), especially if the institution was prominent within the city. Today, an institution abbreviation is always included in a siglum.

#### Former siglum (094 $z)

Enter the former RISM siglum.  Occasionally, due to geopolitical events or the need for clarification, an institution will be assigned a new siglum. To facilitate cross-references
with the former siglum, the old sigla are added to this field. Sigla are only reassigned by the RISM Editorial Center.

##### Examples

- I-RVat = The former siglum for the Biblioteca Apostolica Vaticana, now V-CVbav.
- J-Tn = The former siglum for Nanki Ongaku Bunko, now J-WAn.

#### Qualifying information (094 $q)

The term **siglum** is automatically added to this field.

#### Source of number or code (094 $2)

The term **rism** is automatically added to this field.
