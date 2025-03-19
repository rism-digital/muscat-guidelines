### External resource (856)

The field **External resource** is used to link to an external resource that bears a direct connection to the source being described.

#### External resource URL (856 $u)

Enter the URL. Only enter one URL per field. All URLs must begin with **http** or **https**. Always use permalinks.

#### Note about external resource (856 $z)

**This field is required when entering a link to an external resource.**

Enter a brief description that explains why the URL is relevant to the source being described. Enter using your cataloging language.

##### Examples

- Digital copy
- Watermark on p. 4
- Project homepage
- Detail of binding
- Bibliographic record
- Link to record in Bach Digital
- Link to work in the Frescobaldi Thematic Catalogue Online
- Entry in the church registry


#### Link type (856 $x)

**This field is required when entering a link to an external resource.**

Select from the following:

- The preference is to link to institutional repositories but if one is not available then links to external repositories such as the Internet Archive or IMSLP are allowed. **Digitized source**: The link is to an external website which is a digitized copy of the resource being described. If a link to a digitized source is included in a record for a collection, it is not necessary to duplicate the same link in the individual entries.
 - Example  
   [https://mirador.acdh.oeaw.ac.at/musikarchivspitz/A-SPD\_A15/](https://mirador.acdh.oeaw.ac.at/musikarchivspitz/A-SPD_A15/)
- **IIIF manifest (digitized source)** and **IIIF manifest (other)**: The linked object is a machine-readable JSON object. IIIF links should only be to the manifest, not to a digital surrogate. IIIF manifests do not display the image but rather consist of machine-readable text that must be processed by an internal document viewer such as diva.js before it displays a meaningful image. When viewing the manifest in a web browser, it will start with the curly bracket {. The document is embedded in the web page directly. In many cases, "manifest," "iiif," or similar appears in the link.   
  **IIIF manifest (digitized source)** should be used when the manifest represents a digital surrogate of the source being described.  **IIIF manifest (other)** should be used when the manifest represents an element other than the full source, such as a watermark.
 - Example [https://iiif.lib.harvard.edu/manifests/drs:2820650](https://iiif.lib.harvard.edu/manifests/drs:2820650)

 In cases where both links to an external viewer and an IIIF manifest are available, repeat the field and list both links separately.
 - Examples
   - External resource: [http://nrs.harvard.edu/urn-3:FHCL.Loeb:537966](http://nrs.harvard.edu/urn-3:FHCL.Loeb:537966)  
     Note: digitized version  
     Link type: digitized source
   - External resource: [https://iiif.lib.harvard.edu/manifests/drs:2820650](https://iiif.lib.harvard.edu/manifests/drs:2820650)  
     Note: IIIF manifest  
     Link type: IIIF manifest

- **Other**: Link to other resources that are not the resource being described.

#### Kinds of external resources

**Link type 856 $x: Digitized source**  
Link only to the source being described in the RISM record. Only use permalinks. If permalinks are unavailable, you may link to a page where the link to the digitized source can be easily found (such as a bibliographic record in a library catalog). You may include portions of the digitized source (such as a few pages) if a fully digitized version is not available.

**Link type 856 $x: Other**  
Other kinds of external resources can include the following. Make sure it is always clear to the user why a link is being included, such as in a **General note (500)**.

- **Details of sources**  
  Details of sources that only present certain aspects, such as a watermark, binding, title page, or cover.
- **Catalog records/Databases**  
  Includes bibliographic entries in external catalogs or entries in external databases. External scholarly databases that provide useful information might be included, but consider whether they might be better linked as secondary literature.
- **Electronic catalogs of works, online encyclopedias, digitized reference sources**  
  In general, use the fields **Secondary literature (691)** or **Catalog of works (690)** to refer to online reference works such as catalogs of works or encyclopedias. However, as a service to users, it might be helpful to additionally include a direct link to a certain place within the resource through the 856 field.
- **Archival sources, historical sources**  
  Includes digitized municipal registers or documents, digitized correspondence, historical newspapers. Ensure that the relevance of the archival source is first clear in a **General note (500)**, then include the direct link here. For historical newspapers, you should enter the name of the newspaper as secondary literature but you may link to the specific page where the article is found here; make sure information about the article, such as article title and date, is included in a note.
- **Websites**  
  Includes project websites, websites of external funding agencies, or other relevant websites.
- **Other RISM records**  
  Only link to another RISM record if the record has direct bearing to the source being described. Only use permalinks. It should be clear to the user why the record is relevant to the source. At a minimum, name the holding library, shelfmark, and RISM ID number in a note. Sometimes a connection to a different source might be better explained in a **General note (500)**.   
  If you refer to other RISM records elsewhere in you record, it is not required to link to them in this field.  
  It is not necessary to link to all concordant sources in RISM here; indeed, this is a futile pursuit because the number of sources grows in Muscat daily.
- **References to relevant sources in other libraries but not in RISM**  
  If you want to link to a source not yet in RISM, consider whether it is possible for your working group to first enter the digitized libretto, manuscript, or treatise, or add holdings to a particular print. The Editorial Center is happy to help you if you think a source should be in RISM. However, it is understandable if you are unable to create a new record for a source first.
- **Other relevant sources**  
  Includes concordant sources, concordant works, concordant arias or sections of works, sources that served as the basis for the source being described. Such links can be to the digitized objects or links to external catalogs.
