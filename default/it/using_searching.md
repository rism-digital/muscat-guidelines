## Searching

**Searching** in Muscat is available through **filters** on the main Source page. For more extensive searching, including a music incipit search, use the public catalogs, the [RISM Catalog](https://opac.rism.info/) and [RISM Online](https://rism.online/).

### Muscat filters

The Muscat **filters** offer simple yet powerful searching.

You can enter in each field:

- Single words
- Multiple words:  
  either without quotations mark: **lass noch**   
  or with quotation marks: **"lass noch"**
- Truncation with ? **B\*cher** will find Bucher and Bacher but also Boucher and Bötticher. or \*  
  **?**: The question mark replaces exactly one letter. **B?cher** will find Bucher and Bacher.   
  **\***: The asterisk can be used to truncate or replace any number of letters.
- AND, OR, NOT, ( ): Take advantage of Boolean searching. Use parenthesis to group your search. Examples:
    - Composer contains: **(Bach AND Johann) NOT Sebastian**  
      To find Johann Michael Bach and Johann Christian Bach but not Johann Sebastian Bach
    - Siglum contains: **D-B AND (I-\* OR F-P\*)**   
      To find all prints in the library D-B where there are also copies in Italy or Paris

Note the following for all sections:

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
    - **Date range**: Note that since the day is set at midnight, to search for all records created on February 7, 2012, for example, you must enter the start date 2012-02-07 (understood as midnight on February 7) and the end date 2012-02-08 (understood as midnight on February 8). This will include all sources created during the day. A search from 2012-02-07 to 2012-02-07 will be empty!

Note the following for searching **Sources**:

- **Siglum contains**: Search by the letters in a siglum. This field is case-sensitive. For example:  
  **D-*** = all sources in Germany  
  **D-B*** = all sources in German cities that start with B  
  **D-B** = all sources at the Staatsbibliothek zu Berlin

### Personal names

Note the following for searching **Personal names**:

- **Name**: Searches the fields **Heading - Personal name (100 $a)** and **Name variant (400 $a)**.
- **Life dates**: Searches the field **Years of birth and death (100 $d)**, meaning years as well as the following abbreviations: sc a p c \* + /
- **Places**: Searches the field **Geographic name (551)**. This includes places of birth, death, origin, or activity.
