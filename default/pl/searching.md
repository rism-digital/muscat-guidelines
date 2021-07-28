**Searching** in Muscat is available through a **faceted search** and through **filters**.

#### Faceted search

####

The **Faceted search** (top menu in the middle) is available to search the data in a familiar OPAC setting. If you have editing rights for a particular source, an edit button will take you directly to the Muscat editing mode.

An **incipit search** is available through the faceted search's Advanced search. A keyboard permits the easy insertion of notation. Four search modes are available, with various degrees of fuzziness:
1. Exact pitch: Incipit matches the exact pitches.
2. Interval: Exact pitches are ignored, but intervals are searched. This permits the inclusion of **transpositions** of a given melody.
3. Refined pitch contour: Intervals are ignored but only the upward and downward movements of the melody are searched.
4. Gross pitch contour: This is the fuzziest of all. The approximate contour of the melody is searched.

At the bottom of the page, the field **Incipit** permits the user to enter raw Plaine & Easie code (it can be copied and pasted from a source record, for example). The musical staff preview is automatically updated as in the Source editor.

All the other fields present in the Advanced Search can be combined with the incipit search.

The RISM OPAC has a simplified incipit search under the [Advanced search](https://opac.rism.info/index.php?id=3&L=0). See the [help page](https://opac.rism.info/index.php?id=8&L=0#c38) for more information.

Don't forget to always search for the incipit before entering an anonymous source! [Incipit search first](https://youtu.be/kKc0zzc8cbo)!

#### Muscat filters

The Muscat **filters** offer simple yet powerful searching.

You can enter in each field:

- Single words
- Multiple words:   
  either without quotations mark: **lass noch**   
  or with quotation marks: **"lass noch"**
- Truncation with ? or \*  
  **?** : The question mark replaces exactly one letter. **B?cher** will find Bucher and Bacher.   
  **\*** : The asterisk can be used to truncate or replace any number of letters. **B\*cher** will find Bucher and Bacher but also Boucher and Bötticher.
- AND, OR, NOT, ( ): Take advantage of Boolean searching. Use parenthesis to group your search. Examples:

  - Composer contains: **(Bach AND Johann) NOT Sebastian**  
    To find Johann Michael Bach and Johann Christian Bach but not Johann Sebastian Bach
  - Siglum contains: **D-B AND (I-\* OR F-P\*)**   
    To find all prints in the library D-B where there are also copies in Italy or Paris



Please note the following for all sections:

- **Date**

  - **Searching by date:** Enter dates in the format YYYY-MM-DD. The day is set to midnight by default.
  - **Single date ("from"):** If you fill in only the left-hand field (the "from"), you will get all records modified or created **since** that date (including records created during the day on that date).   
    Example: Last modification   
    **2012-02-07** - [empty]  
    will retrieve all records edited from February 7, 2012 to today.
  - **Single date ("to")**: If you fill in only the right-hand field (the "to"), you will get all records modified or created **up to** that date at midnight.  
    Example: Last modification  
    [empty] -  **2012-02-07**  
    will retrieve all records edited from the beginning of time up to February 7, 2012 at midnight (meaning no records created during the work day on February 7 will be included).
  - **Date range** : Note that since the day is set at midnight, to search for all records created on February 7, 2012, for example, you must enter the start date 2012-02-07 (understood as midnight on February 7) and the end date 2012-02-08 (understood as midnight on February 8). This will include all sources created during the day. A search from 2012-02-07 to 2012-02-07 will be empty!



Please note the following for searching **Sources** :

- **Siglum contains** : Search by the letters in a siglum. This field is case-sensitive. For example:  
  **D-\*** = all sources in Germany  
  **D-B\*** =all sources in German cities that start with B  
  **D-B** = all sources at the Staatsbibliothek zu Berlin



#### Personal names

Please note the following for searching **Personal names** :

- **Name** : Searches the fields **Heading - Personal name (100 $a)** and **Name variant (400 $a)**.
- **Life dates** : Searches the field **Years of birth and death (100 $d)**, meaning years as well as the following abbreviations: sc  a  p  c \*  +  /
- **Places** : Searches the field **Geographic name (551)**. This includes places of birth, death, origin, or activity.