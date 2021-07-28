### Verwendung Muscat

1. **Where can I find tutorials about Muscat?**  
All of the tutorials are linked on the RISM Editorial Center's Muscat page: [http://www.rism.info/en/community/muscat.html  
  
](http://www.rism.info/en/community/muscat.html)
2. **How can I contact other Muscat users?**  
To contact the Muscat developers: Report any errors, questions, comments, or suggestions to muscat@rism.info at any time.   
  
**[RISM Muscat](https://groups.google.com/forum/#!forum/rism-muscat)**, a Google Group, is the official Muscat discussion list that each Muscat user must join. Official announcements from the Editorial Center and the Muscat developers will be disseminated solely through this group. In addition, all Muscat users are encouraged to ask questions or raise topics for discussion.   
  
A Google account is not required. An invitation to join the group will be sent to you when you receive your Muscat account information.  
  
There is also a discussion channel on Slack at:   
[https://rismcommunity.slack.com/](https://rismcommunity.slack.com/)  
  
3. **Is all secondary literature cited in Muscat at the Editorial Center?**  
No, only the literature labeled "HB" or "Handbibliothek" or "RISM-ZR" in an internal note (599) is actually in our office. Those materials are for the benefit of all RISM contributors, so if we have a publication that you would like to consult, let us know and we will try to get you what you need. Even if you are interested in a publication we do not have in the office, there's a chance that we know someone who has it.  
  
4. **What do I do if I forget my password or want to change it?**  
Passwords are managed by the Editorial Center. Contact us if you lose your password. You cannot change your password.  
  
5. **Can I show Muscat to my colleagues? Can I demonstrate Muscat at conferences or in workshops?**  
Yes, please do! A training version of Muscat is available for exactly these purposes at [https://muscat-training.rism.info](https://muscat-training.rism.info/).   
  
All Muscat users can login there with their personal credentials. There are also 99 training accounts ("training01@rism.info" to "training99@rism.info") available for individual users. Any of these training accounts can be used. Please contact the RISM Editorial Center (contact@rism.info) for the current password.  
  
Anything on the training version can be added, edited or deleted. It is synchronized once a week (on Sunday) with the current Muscat data. This means that the new records will then be available but also that the ones created on the training version will be erased.   
  
6. **In the modification history, what does it mean if "[system]" is listed as the author?**  
You might see a system edit if one of the indexed fields linked to your record was changed. The change in the authority record will also register as a change in your record.  
  
7. **Can I create records based on descriptions from printed catalogs or online library catalogs?**  
Yes! Sometimes, for various reasons, it is not possible to access the source in person and the only description available is in a printed catalog, catalog of works, or online library catalog. You may use such descriptions as the basis for your record.   
When doing so:  
a. Include a **General note (500)** such as "Record based on description in YouV"   
b. Link to the catalog in the field **Bibliographic reference (691)** or **External resource** (856) as appropriate   
c. In the field Record origin (980), subfield **Material examined** , select **Material not examined**   
  
8. **Can I enter sources that are included in other RISM publications from the B series?**  
Though we are gradually adding sources from the B series to Muscat, this is a long-term project. Records from B/I are in Muscat while B/II is in preparation. In the meantime, please feel free to enter sources from other B volumes. Include a citation to the original B volume in the field **Secondary literature (691)**.  
  
9. **When do records appear in the public catalog at opac.**** rism.info?**  
Muscat records are sent for publication in the public catalog at opac.rism.info once a month, at around the 19th of each month. Records are then visible a few days later.  
  
10. **What if a source in RISM is no longer in the hands of the holding institution indicated in the RISM record?**  
Use the siglum **N. N.** for situations in which the current location of a source is unknown, such as if it was on deposit at an institution but the source was taken back and is now in private hands. This happens only rarely. Contact the Editorial Center if a source needs this siglum.

###   

### Technische Aspekte von Muscat
**1. What are the technical requirements for Muscat?**  

- Muscat is platform independent and works on both Macs and PCs.
- Access is through a URL and requires an Internet connection.
- Muscat works best on screens that are at least 1366 x 768 pixels.
- Muscat is optimized for Firefox and Chrome. Do not use Internet Explorer!   

**2. What are some technical aspects about Muscat?**

- Muscat is open source. The source code is available at the [GitHub](https://github.com/rism-ch/muscat) repository.
- Muscat is a Ruby on Rails application.
- [Verovio](http://www.verovio.org/pae-examples.xhtml) is used to render the music incipits through MEI. 
- Solr is used as a search engine.
- Muscat has [an SRU service](https://github.com/rism-ch/muscat/wiki/SRU) and an [SRU downloader](https://github.com/rism-international/sru-downloader) to retrieve MARCXML records.
- Muscat supports Unicode (UTF-8).  
More information about the development of Muscat can be found on [RISM Switzerland's website](http://rism-ch.org/infrastructure/muscat.html?locale=en).   
  

**3. What are some technical aspects of the incipit search?**

- It is based on the [Themefinder](http://www.themefinder.org/) engine developed at the University of Stanford. 
- It leverages the underlying indexing system (Solr), used for all the search queries in Muscat, which was customized to permit the analysis of the PAE notation used in the editor. The indexing process is completely transparent to the users and catalogers, and only the normal insertion of the coded notation is required in the 031 field.  

**4. What are some of the features of Muscat?**

- **Versioning** : Catalogers can view changes made to records
- **VIAF** : Personal names can be imported through the [Virtual International Authority File (VIAF)](https://viaf.org/).