# Records and record types

A new record can be created in Muscat by either selecting the appropritate template or by copying an existing record. Links to both are on the Source page or the full record view.

## Copia de registros existentes

Muscat offers templates for different sources. La plantilla ofrecerá sólo los campos que se requieren para la fuente en cuestión.

If you see that a record is in the wrong template, notify the Editorial Center to have the template changed.

### Available templates

A **Collection** record (parent record) is used when the item contains multiple works. Each work in the collection is then entered as an **item in the collection** (child record) and linked to the collection record. Manuscripts and prints can also exist as **single items alone** that are not part of collections.

A **Composite volume** is a volume that consists of items that were created separately but later bound together, typically by an owner or institution. This includes volumes in which individual printed items are bound together, as well as volumes in which printed items and manuscripts are bound together.

Manuscripts are unique to a library and can only be owned by one institution. Printed materials have holdings, meaning that multiple libraries can own copies (exemplars) of an edition.

The libretto template is used for documents that contain texts that clearly represent a sung musical performance. Most commonly, these are books that contain the words of an opera or other long vocal work, but they can also be collections of text-only  books such as hymnals or Christmas songs. Such publications are sometimes known as songsters, pocket books (frequently labeled as such on the source), or tunebooks.

The treatise template is used for documents that explore theoretical aspects of music, including points of composition or performance.

Both libretti and treatises may contain notated music, and the line between a libretto or treatise and music might not always be a clear one.

The following templates are used in Muscat for Sources. Templates are encoded in the MARC record's Leader, positions 5-7.

Manuscripts:
- Music manuscripts
 - Collection record (parent record) [LDR: ndc]
   - Item in collection (child record) [LDR: ndd]
 - Music manuscript alone [LDR: ndm]
- Libretti
 - Collection record (parent record) [LDR: ndc]
   - Item in collection (child record) [LDR: ntm]
  - Libretto alone
- Treatises
   - Collection record (parent record) [LDR: ndc]
    - Item in collection (child record)
   - Treatise alone

Printed materials:
- Printed music editions
 - Collection record (parent record) [LDR: ncc]
   - Item in collection (child record) [LDR: ncd]
 - Music manuscript alone
- Libretti
 - Collection record (parent record)
   - Item in collection (child record)
  - Libretto alone
- Treatises
   - Collection record (parent record)
    - Item in collection (child record)
   - Treatise alone


Composite volumes:
- Composite volume [LDR: npc]


## Copying existing records

There are two ways to copy a record.

From the template selection screen: Simply enter the RISM ID number in the field "Create from existing source." Le aparecerá una copia del registro en modo de edición y desde allí podrá hacer cualquier cambio que sea necesario. El registro copiado recibirá automáticamente un número ID de RISM nuevo después de ser guardado.

From the full record view: When viewing any record in Muscat, you can click the "Duplicate" button in the sidebar on the right and a copy of the record in the editing mode will be displayed.

Catalogers may duplicate any record in Muscat, including records that were created by a different library. Editing permissions still apply, so catalogers will not be able to save a record for institutions that they do not have permissions for. Duplicating records saves time when cataloging one's own collections (especially if the content is similar throughout), but catalogers can also take advantage of records created by other libraries, especially if a record has extensive music incipits, or in the case of cataloging reprints where the contents are the same or similar. Only one record at a time can be duplicated.

The Plaine & Easie code for any music incipit may be copied from the full record view of any record. Above the music incipit, simply click on the link **PAE Code** and you can copy and paste the music incipit code that is shown.
