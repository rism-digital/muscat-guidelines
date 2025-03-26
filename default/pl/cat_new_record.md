# Rekordy i typy rekordów

Nowy rekord można utworzyć w Muscat poprzez wybranie odpowiedniego szablonu lub przez skopiowanie istniejącego rekordu. Linki do obydwu znaleźć można na stronie dla Źródeł lub w pełnym widoku rekordu.

## Szablony

Muscat oferuje możliwość wyboru szablonu, w zależności od rodzaju katalogowanego źródła. Szablon zawiera tylko te pola, które są potrzebne do skatalogowania danego źródła.

Jeżeli zauważysz, że rekord skatalgoowany jest w nieodpowiednim szablonie, poinformuj RISM Editorial Center w celu zmiany szablonu.

### Dostępne szablony

Rekord dla **Kolekcji** (rekord macierzysty) jest stosowany, gdy źródło składa się z wielu pozycji. Każda pozycja kolekcji jest dodawana jako **Pozycja w tym źródle** (rekord dziecko) i połączona z rekordem kolekcji. Rękopisy i druki muzyczne mogą również funkcjonować jako **Samodzielne pozycje** i nie być częscią kolekcji.

**Klocek introligatorski** składa się z pozycji powstałych niezależnie, które wtórnie zostały ze sobą połączone zazwyczaj przez właściciela czy instytucję. Klocek introligatorski może zawierać zarówno woluminy złączonych pojedynczych druków jak ja woluminy połączonych druków z rękopisami.

Manuscripts are unique to a library and can only be owned by one institution. Materiały drukowane posiadają egzemplarze, co oznacza że wiele bibliotek jest właścicielem kopii (egzemplarzy) danego wydania.

Szablon dedykowany libretto/tekstowi muzycznemu wykorzystywany jest do źródeł, które zawierają tylko tekst, odnoszący się do śpiewanego wykonawstawa muzycznego. Najczęściej są to książki, które zawierają słowa opery lub innej kompozycji wokalnej, ale mogą to być również kolekcje źródeł tekstowych, takich jak śpiewniki hymnów czy piosenek Bożonarodzeniowych. Takie publikacje są czasami nazywane zbiorami tekstów pieśni, książkami kieszonkowymi (często oznaczanymi tak na źródle) lub śpiewnikami.

Szablon dedykowany traktatom jest wykorzystywany do źródeł, które podejmują teoretyczne aspekty muzyki, w tym aspekty kompozycji czy wykonawstwa.

Both librettos and treatises may contain notated music, and the line between a libretto or treatise and music might not always be a clear one.

The following templates are used in Muscat for Sources. Templates are encoded in the MARC record's Leader, positions 6-7.

Handwritten materials:
- Music manuscript
 - Collection (parent record) [LDR: dc]
   - Item in a collection (child record) [LDR: da]
 - Single music manuscript [LDR: dm]
- Libretto/Song text
 - Collection (parent record) [LDR: dc]
   - Item in a collection (child record) [LDR: ta]
  - Single libretto/song text [LDR: tm]
- Treatise
   - Collection (parent record) [LDR: dc]
    - Item in a collection (child record) [LDR: ta]
   - Single treatise [LDR: tm]

Printed materials:
- Music edition
 - Collection (parent record) [LDR: cc]
   - Item in a collection (child record) [LDR: ca]
 - Single music edition [LDR: cm]
- Libretto/Song text
 - Collection (parent record) [LDR: ac]
   - Item in a collection (child record) [LDR: aa]
  - Single libretto/song text [LDR: am]
- Treatise
   - Collection (parent record) [LDR: ac]
    - Item in a collection (child record) [LDR: aa]
   - Single treatise [LDR: am]

Composite volumes:
- Composite volume [LDR: pc]


## Copying existing records

There are two ways to copy a record.

From the template selection screen: Simply enter the RISM ID number in the field "Create from existing source." You will then see a copy of the record in the editing mode and from there you can make any changes to the record that you need. The copied record will automatically receive a new RISM ID number upon saving.

From the full record view: When viewing any record in Muscat, you can click the "Duplicate" button in the sidebar on the right and a copy of the record in the editing mode will be displayed.

Catalogers may duplicate any record in Muscat, including records that were created by a different library. Editing permissions still apply, so catalogers will not be able to save a record for institutions that they do not have permissions for. Duplicating records saves time when cataloging one's own collections (especially if the content is similar throughout), but catalogers can also take advantage of records created by other libraries, especially if a record has extensive music incipits, or in the case of cataloging reprints where the contents are the same or similar. Only one record at a time can be duplicated.

The Plaine & Easie code for any music incipit may be copied from the full record view of any record. Above the music incipit, simply click on the link **PAE Code** and you can copy and paste the music incipit code that is shown.
