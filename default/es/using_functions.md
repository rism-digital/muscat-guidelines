### La barra de menú superior

**Administration** links to the MARC configuration, which lets you view all the MARC fields used in Muscat (sources plus authority files)

El botón de  **Idioma**  permite cambiar el lenguaje de Muscat.

El **Panel de actividad** muestra los registros que ha editado recientemente en Muscat.

El botón de  **Comentarios**  permite ver todos los comentarios agregados a los registros de Muscat. Cualquier usuario puede ver los comentarios de todos los demás y comentar en cualquier registro. Comments can be added to any kind of record throughout Muscat. You can only add comments through the full record view. Nombre a otros usuarios tipeando @ más su nombre para incluirlos en la conversación.

**Folders** allow you to see all folders created by Muscat users.

The **Sources** page is the main cataloging page in Muscat and contains the bibliographic records that describe all of the musical sources in Muscat.

El botón de  **Autoridades**  lo lleva a todos los archivos de autoridades, vocabulario controlado e índices en Muscat. See **General cataloging guidelines: Authorities** for more information.

El botón de  **Lineamientos**  permite consultar todos los lineamientos en una sola página. Es donde estamos ahora.

### Secciones y acciones en el modo de edición

Esta sección trata sobre las acciones que se pueden realizar cuando se edita el registro de una fuente.

La columna de navegación a la derecha permite saltar a secciones específicas del registro, guardar y ver su trabajo.

Use los  **enlaces**  en la parte superior para saltar a una sección del registro. When editing a single section, your work will be retained if you jump to a different section or if you click on **Show all sections**. (But remember to save your work before leaving the editing mode!)

El botón  **Mostrar todas las secciones**  permite ver todas las secciones del registro. This is useful for when you want to return to editing the full record after working on a specific section.

El botón  **Mostrar vista preliminar ** permite ver el registro sin guardar. Para volver al modo de edición, haga click en  **Esconder vista previa.**

**Cesto de basura** : Borre un campo haciendo click en el cesto de basura.

El botón  **Guardar y continuar editando**  permite guardar su trabajo y seguir en el modo de edición. Save frequently to prevent you from losing your work. After a record is first saved, the RISM ID number is assigned automatically.

El botón  **Cancelar**  lo lleva de nuevo a la pantalla anterior sin guardar.

El botón  **Guardar y cerrar**  lo lleva de regreso a la pantalla anterior después de guardar su trabajo.

El botón  **Mostrar historial de modificaciones**  permite ver, restaurar y borrar versiones previas del registro. Click **Show all sections** again to return to the editing mode and any unsaved changes.

**Attach a new image** lets you upload small images (usually watermarks, handwriting samples, or bindings) to attach to your records. Puede acceder a las imágenes cargadas en el menú  **Autoridades ** \>  **Imágenes.**

### Botones del modo de edición

**Magnifying glass**: Click here to search the authority file linked to the field. Se abrirá una ventana aparte. Después de encontrar lo que necesite, haga click en  **Seleccionar**  para hacer la transferencia de la selección a su registro.

**Move arrow**: Fields that can be repeated have an up-and-down arrow if you wish to change the order. Click the arrow and drag it to its new position.

**Question mark (?)**: Click ? to display the RISM guidelines for this field.

**Plus (+) and minus (-) signs**: Fields that may be repeated have a plus sign (+). Haga click en el + para crear un nuevo registro vacío. Fields may be reordered in this section by clicking and dragging them. Click the - to delete a field.

**Trash can**: Delete a field by clicking on the trash can.

**Show/hide arrow**: Click on the arrow to expand or collapse fields.

**Add a group**: This button is found at the bottom of the section **Material description**. With different groups, you can associate different dates, formats, watermarks, names, institutions, etc. with different types of sources (or however you choose to describe your material). Some of these fields, such as **Additional personal name (700)**,**Additional institution (710)**, and **General note (500)**are also found elsewhere in the Sources template. Use your best judgment to decide where to place such information: does it apply to the entire source, or just this group of material?

### Otras funciones en el modo de edición

#### Autocomplete

If you see a field that contains a key, the field is linked to the authority file or index. Begin typing and use the autocomplete to help you.

#### Adding new names, titles, subject headings, etc.

If you do not find what you need in the authority files, simply enter the name or term you need. Once you click to a different field, an orange border appears around the fields and you will see a checkbox that reads "Confirm the insertion of a new value." Haga click en esta casilla para confirmar. For personal names, a field called **Life dates** will appear. Fill this out if you can because it helps the Editorial Center create a new authority record. Al guardar, el nombre o título será añadido automáticamente al archivo de autoridades. See also **General Cataloging Guidelines** under **Personal names.**

News secondary literature must be entered directly in the **Secondary literature** database.

#### Required fields and validation

When you begin a new record, the most important fields will already be open and ready for you to fill in. Los campos en amarillo son campos requeridos. If you save without filling out one of these fields, a red border will appear around the fields that still need attention, and the sections in which the fields occur will be red in the sidebar on the right. In cases where no information can be filled out in a required field, the validation may be overridden by checking a box in the sidebar.

### Actions in the full record view

**Crear** : este botón lleva a la página de selección de plantillas desde la cual puede crear un nuevo registro.

**Regresar a la lista** : este botón lo lleva de regreso a la lista de todas las fuentes musicales.

**Editar:**  verá este botón en caso de que cuente con los permisos necesarios para editar el registro.

**Edit:** If you have permissions to edit the record, you will see this edit button.

**Duplicate**: In the full record view, a record may be copied by clicking on the Duplicate button.

### Merging records

Duplicate authority records can be merged by the Editorial Center. During the process of merging, any sources that are linked to the deprecated authority record are automatically transferred to the target record.

1. Pick out two records that you want to merge. One is the target, which will be kept. The other is deprecated and will be deleted.

2. In the editing mode of the deprecated record, set the Record Status to "Unpublished" at the bottom and save.

3. On the Institutions search page, perform a search so that the two records are on the same page of results.

4. Select the two you want to merge by clicking the checkbox to the left of the record.

5. Click "Merge" under Actions on the right.

6. A popup message will appear that says, "Should [the deprecated record] really be merged into [the target record]?" This is the action that takes links in the unpublished record and sends them to the target. Click OK.

7. Now a message appears that says, "Successfully merged Institution [deprecated record] into [target record]!"

8. You can confirm that this worked by viewing the unpublished, deprecated record, which will have 0 sources attached to it. The target record will have its previous records plus the new records attached to it from the merge. (It might take a moment for Muscat to reindex before this is displayed on the search page, but the full record views are correct.) Now you can delete the unpublished, deprecated record.

Note:
- In the Modification History for the linked sources, the change will be displayed like this: "Institution change id from 51000870 to 40009964"
- Only two records at a time can be merged.
- Only authority records can be merged, not Sources.
- As a protection against accidental deleting, autority records that are linked to other authority records cannot be deleted. Before merging, make sure that the target record has all of the information you need from the deprecated record. Delete any references to other authority records.  
