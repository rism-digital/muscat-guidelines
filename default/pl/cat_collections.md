## Katalogowanie specjalnych typów źródeł

W tej sekcji opisano sposób katalogowania szczególnych rodzajów źródeł: kolekcje, klocki introligatorskie, kontrafacta, kompilacje, tzw. wstawki, parodie, materiały mieszane (rękopisy i druki przechowywane razem), muzyka w czasopismach, muzyka w publikacjach niemuzycznych, libretta, traktaty i aranżacje fortepianowe.

### Kolekcje

W RISM, _Kolekcja_ jest zarówno intencjonalnie powstałym zbiorowym rękopisem lub antologią wielu dzieł, jak również pozycją, która zawiera dwie lub więcej oddzielnych części. To ostatnie oznacza, że jeśli na przykład rękopis do sonaty fortepianowej ma również szkic do fugi na samym końcu, RISM skataloguje go jako kolekcję z rekordem macierzystym dla całej pozycji oraz indywidualnymi wpisami dla sonaty i fugi.

Przy katalogowaniu kolekcji, należy zwrócić uwagę na następujące kwestie:

1. Wpis główny kolekcji (rekord macierzysty) powinien zawierać informacje dotyczące całej kolekcji.
2. Wszelkie informacje, które są istotne tylko dla niektórych elementów kolekcji, należy wpisać w indywidualnym wpisie.

Jeżeli utwory w kolekcji mają różnych kompozytorów, obsadę, rodzaje źródeł itp. nie należy ich wpisywać w rekordzie macierzystym.

W przypadku kolekcji, w których utwory są bardzo podobne, dobrą strategią jest stworzenie pełnego pierwszego wpisu i wykorzystanie do skopiowania rekordu funkcji „Duplikuj”. Następnie dla kolejnych rekordów wystarczy zmienić tylko pola, takie jak tytuł i numer strony.

Rekordy macierzyste kolekcji nie mogą zawierać rekordów macierzystych kolekcji rękopisów. Zamiast tego należy zastosować bardziej płaską hierarchię za pomocą indywidualnych rekordów i wyjaśnić strukturę, konstrukcję lub organizację danej pozycji w uwadze.

### Klocki introligatorskie

**Klocek introligatorski** składa się z obiektów powstałych niezależnie, które wtórnie zostały ze sobą połączone zazwyczaj przez właściciela czy instytucję. Istnieją różne określenia na tego typu obiekt: sammelband, adligat, źródło współoprawne. Klocek introligatorski może zawierać zarówno woluminy złączonych pojedynczych druków jak i woluminy połączonych druków z rękopisami.

Istnieją dwa sposoby na wskazanie istnienia klocka introligatorskiego. Pierwsza, ta prostsza zakłada nadanie jednej sygnatury wszystkim zawartym obiektom z informacją „współoprawne z”. Drugi sposób zakłada wybór szablonu dla klocka introligatorskiego.

Katalogowanie klocka introligatorskiego ma na celu połączenie wszystkich obiektów współoprawnych w jeden rekord, dostarczając tym samym użytkownikowi praktyczny zarys zawartości źródła.

Rekordy klocków introligatorskich powinny być proste. Zasadniczo, opisują element wiążący dla pozycji składowych. Nie mylić klocków introligatorskich z kolekcjami; „kolekcje” w RISM przeznaczone są wyłącznie do rękopisów. Ponadto nie mylić klocków introligatorskich z drukami: druk jest pojedynczą jednostką bibliograficzną, która została wydana przez wydawcę jako taka. Zarówno kolekcje, jak i druki mogą zawierać wiele pozycji. W przeciwieństwie do tego, klocki introligatorskie łączą różne jednostki, na przykład wydrukowana kolekcja madrygałów z 1604, rękopis motetu z 1620 r. oraz druk madrygałów z 1615 r.

Podobnie jak w przypadku rekordów macierzystych kolekcji, informacje podane w klocku introligatorskim powinny być prawdziwe dla wszystkich składowych. Należy pamiętać, że szczegółowe informacje dotyczące zawartości poszczególnych obiektów powinny znajdować się w odpowiednich rekordach bibliograficznych. Nie należy tworzyć oddzielnych rekordów dla wielu klocków introligatorskich, które należą do siebie, takich jak zbiór głosów; powinny one być opisane w tym samym rekordzie. W wielu przypadkach wiele pól będzie pustych.

Łączenie rękopisu, pojedynczego druku muzycznego w kolekcji z rekordem dla klocka introligatorskiego odbywa się w różny sposób.

1. Po pierwsze, stwórz rekord dla szablonu klocka introligatorskiego, zapisz i odnotuj ID RISM.
2. Dla rękopisów, w trybie edycji, znajdź pole **Rekord macierzysty (773)**. Kliknij w drugą ikonę „Search composite” w celu wyszukania klocka introligatorskiego.
3. Dla druków muzycznych: W egzemplarzach znajdź pole **Współoprawne z (973)** i kliknij na ikonę lupy. Znajdź rekord klocka introligatorskiego i wybierz.

### Contrafacta

Contrafacta are vocal pieces in which the text is changed without significant change to the music, such as retexting a secular work with sacred text, or the other way around. The derivation is almost mechanical; there is little creativity on the part of the arranger, but there is a significant change in the musical purpose (such as from a theatrical context to a religious one).

Please note that RISM considers contrafacta to be separate from parody and parody masses, which typically involve a more significant transformation of the musical material.

Take note of the following fields when cataloging contrafacta. RISM ID no. 300234487, a sacred contrafactum of an aria from Josef Mysliveček's opera Il Bellerofonte, will be used as an example.

**Composer (100)**

Enter the composer of the original music.

- Mysliveček, Josef

**Standardized title (240)**

Use the standardized title of the original piece. **Excerpts** may be added. Do not use **Arr**.

- Il Bellerofonte. Excerpts

**Alternative title (730)**

If there is a new, distinct standardized title for the piece in hand, you can enter it here. Do not enter text incipits here.

**Subject headings (650)**

Add at least 3 subject headings (more if appropriate), in this order:\
Contrafacta\
Current genre\
Original genre

- Contrafacta
- Sacred songs
- Operas

**Description summary (520)**

Add a short description in English that explains the situation as a benefit to other RISM users.

- Sacred contrafactum of an aria from Mysliveček's opera Il Bellerofonte.

**Language of text (041)**

Fill out both of these fields:\
Language of text (041 $a): The current text of the source in hand\
Language of original text (041 $h): Language of the original piece

- Language of text: Latin
- Language of original text: Italian

**Text incipit (031 $t)**

Enter the text incipit of the source in hand.\
If the original text is known, enter it in square brackets.

- Alma redemptoris mater, quae pervia caeli
- [Giusti dei che ben vedete]

**Other fields**

All other fields, such as liturgical feasts and instrumentation, should refer to the source in hand, that is, the contrafactum itself, and not the original work on which it was based.

### Compilations

Compilations are new, independent works made from parts of one or more other works and can also include new material. Frequently, the resulting work is of a different genre than the component parts, such as when arias or duets from an opera become a cantata, or excerpts from an opera become an instrumental suite. This also includes pasticcios. While the boundary between a compilation and a pasticcio is not always clear, pasticcios can be generally be characterized by one of these features: (1) arias, duets, or larger parts of dramatic works that are adapted to a new libretto; (2) several independent works combined to create a new work; or (3) collaborative compositions conceived as such from the beginning.

Compilations may be entered on a single record, or they may be entered as collections.

Take note of the following fields when cataloging compilations.

**Composer/Author (100)**

The composer is always **Compilations**.

**Additional personal name (700)**

The name of the compiler can be added with the function **Editor**.

If you have a compilation, enter the composer(s) of the original material and select the function **Composer cross-reference**. Enter the composer(s) of the new material and select the function **Co-composer**.

If you have a pasticcio, do not enter composers as a composer cross-references. Instead, enter all composers as **Co-composer**s.

**Standardized title (240)**

Enter the standardized title of the source in hand. For pasticcios, add **Excerpts** or **Arrangement** as appropriate.

**Language code (041)**

For the field **Language of text**, enter the language of the source in hand. If appropriate, the language of the original work can be entered in **Language of original text**.

**Subject heading (650)**

The first subject heading should be **Compilations** and/or **Pasticcios**. The second should be the genre of the source in hand. If you have excerpts, the genre of the excerpt can be added. **Collaborative compositions** is also an option.

**Description summary (520)**

Use this field to describe in general the nature of the source.

<figure>
  Act 1 by Amadei, act 2 by Bononcini, overture and act 3 by Händel
  <figcaption>Example</figcaption>
</figure>

**Alternate title (730)**

Enter the standardized title of the original piece(s), adding **Excerpts** or **Arrangement** as appropriate. You can also enter ossia titles.

**Catalog of works (690)**

You can enter the catalog of works number for both the compilation and the original works.

**Text incipit (031)**

Enter the text of the source in hand. If known, enter the original text in square brackets.

**General note (500)**

Always use a note for clarification, especially if the works of separate composers are involved. This ensures that the composers are matched to the works used in the compilation.

**Note on performance (518)**

Performances should be noted only as they relate to the compilation itself.

**Examples of compilations**:

230001408: Cantata made from opera arias with newly composed recitatives

702000623: Suite made from parts of an opera

700007222: Several works by a single composer used to create a new cantata

702000642, 702000643: Several works by several composers used to create a new suite

452505748: An opera pasticcio consisting of 3 acts by 3 different composers

### Parodies

A parody is a composition based on pre-existing material that results in a new work. In the 19th century, the term gains a satirical flavor.

The record 150205470 will be used as an example.

**Composer (100)**

Enter the composer of the music for the source in hand.

- Weyse, Christoph Ernst Friedrich

**Additional personal name (700)**

Enter the composer of the pre-existing material and select the function Composer cross-reference.

- Rossini, Gioachino

**Standardized title (240)**

Enter the standardized title of the source in hand.

- Dannemark hellige lyd

**Additional title (730)**

Enter the title of the pre-existing material. Add Excerpts as appropriate. Do not use Arrangement or Variations.

- Tancredi. Excerpts

**Subject heading (650)**

Enter Parodies as the first subject heading. Enter the genre of the source in hand for the second, and the genre of the pre-existing material as the third.

- Parodies
- National anthems
- Operas

**Language code (041)**

Enter the language for the source in hand in the field Language of text. Enter the language of the pre-existing material in the field Language of original text.

- Danish
- Italian

**Text incipits (031)**

Enter the text incipit of the source in hand. If the original text is known, enter it in square brackets.

- Dannemark hellige lyd
- [Di tanti palpiti]

**Other fields**

All other fields, such as performance information, should relate only to the source in hand.

### Insertion arias

Operas that include insertion arias (also called suitcase arias or interpolated arias) should be cataloged with at least three records: a parent record (collection record) for the opera as a whole, a record for the original movements of the opera (which will contain most of the incipits), and a record for each of the inserts.

Inserts that are separated from a larger work should be cataloged separately. A link to the work into which it was inserted can be indicated in the field **Related source (787**).

The usual rules apply when creating the parent record and the record for the main opera. Please observe the following when cataloging the insert. Note that all fields (such as date of composition and scoring) pertain to the insertion only.

**Composer (100)**: Composer of the insertion

**Additional name (700)**: Composer of the larger work, such as an opera

**Standardized title (240)**: Title of the insertion, or the name of the opera followed by Excerpts

**Additional title (730)**: Title of the larger work, plus the subheading **Inserts**

**Subject heading (650)**: Enter three: Insertions, the genre of the insertion, and the genre of the larger work

**Related source (787)**: Indicate the the larger work into which this piece was inserted and select the relationship type **Insert in**. Add a brief remark in the field **Note** to explain the nature of the insert, such as where it is located within the larger work.

**General note (500)**: Any additional information can be added to make the relationship of the insert within the larger work (if known) clear.

### Mixed materials (manuscripts and printed items stored together)

It is not uncommon for manuscript and printed items to be found together in the same folder or with the same shelfmark: for example, a printed score with handwritten parts, or a group of printed parts together with some handwritten ones.

Always strive to catalog the printed material in a separate record, because it is possible that other libraries have copies of the same edition. Create one record for the printed item, add your holdings, and create another record for the manuscript materials. Use the field **Related source (787)** to point from one record to the other.

If it is not feasible to create an adequate record for the printed material, proceed as follows: Catalog your material using a manuscript template. In the material description section, describe the manuscript materials. Add an additional material group, and describe the printed materials.

### Music in periodicals

There are two ways to catalog periodicals that contain music: as a collection or as a single work. In either case, the title of the periodical, with the issue number and year, is entered in the field **Additional title (730)**.

**Collections** can be appropriate when the periodical consists of all or mostly music and the item was collected and preserved as a whole. Holdings are attached to the collection level. Individual entries are created for each piece in the issue.

##### Example:

1001097294: January issue (precise year unknown) of the _Kleine Pianoforte-Bibliothek_, containing 5 pieces. There is one record for the collection parent record, and five individual entries for each piece.

**Single works** can be appropriate when works were included as insertions or additions to periodicals without a notated music focus. Frequently, such items are preserved outside of their original publication context.

##### Przykłady

991018149: "The Pantheon" published in _The Lady's Magazine_, August 1784\
990042111: "L'amour folâtrant l'autre jour" published in _Nouveau Mercure galant_, May 1679

### Music in non-music publications

RISM includes music found in printed publications that are not primarily music documents. The focus of the RISM record is nevertheless the music.

##### Example:

990026614: 3 songs by John Isaac Hawkins that were published in Charles Willson Peale's _Discourse introductory to a course of lectures on the science of nature_ (1800).\
**Composer/Author (100)**: The composer of the music\
**Additional Personal Name (700)**: The author of the book, with the indicator **other**\
**Title on source (245)**: The title of the book\
**Standardized title (240)**: A standardized title according to RISM rules, such as **3 Songs**\
**Physical description (300)**: A description of the music, such as **1 score: 5 p.**\
**Composer/Author (100)**: The composer of the music\
**Additional Personal Name (700)**: The author of the book, with the indicator **other**\
**Title on source (245)**: The title of the book\
**Standardized title (240)**: A standardized title according to RISM rules, such as **3 Songs**\
**Physical description (300)**: A description of the music, such as **1 score: 5 p.**

Individual entries are then created for each piece, following normal RISM rules.

### Libretti

Please observe the following when cataloging libretti.

**Composer/Author (100):** Enter the author of the libretto. Do not use this field for the composer of the music.

**Additional personal name (700):** A useful function is "conceptor," such as the author of a play that a libretto was based on. Only enter a composer's name as a cross-reference if named on the source.

**Additional institution (710):** Do not forget to index the name of the publisher (for printed libretti).

**Standardized title (240):** The fields "Arrangement statement" and "Key or mode" are not relevant here. If the libretto includes notated music, indicate the key in the music incipit (031) only.

**Additional title (730):** If the libretto was based on a book or play, the title of the original work can be entered here.

**Subject heading (650):** Enter the name of the genre for which the libretto was written, if known (such as “Operas” or “Cantatas”). "Librettos" is not necessary.

**Language code (041):** Use the field "Language of text" only if the libretto contains notated music with words.

**Source type (593):** Select either "Libretto, handwritten" or "Libretto, printed."

**Physical description: Format, extent (300):** Use the phrase "text document" to describe the format of the libretto. An example would be: 1 text document: viii, 27. p. p. p.

### Treatises

When cataloging treatises, the field **Format, extent (300 $a)** should generally include "text document" as the format.

Appropriate subject headings for treatises include the following:

- **Treatises**
- **Writings**
- **Music theory**
- **Theory of harmony**
- **Tutors (inst.)**: Includes methods and schools
- **Tutors (voc.)**: Includes methods and schools
- **Contrapuntal studies (inst./voc.)**
- **Solfeggios (voc.)**
- **Solfeggios (inst.)**
- **Scales (inst./voc.)**

Additional subject headings may be added.

### Piano arrangements

Specify piano arrangements as follows.

- In the field **Standardized title (240):**
 - Select **Arrangement** next to **Arrangement statement**.
 - Under **Scoring summary**, enter the scoring of the arrangement, such as **pf** or **V, pf**. Do not enter the scoring of the original work.
- In the field **Total scoring (594)**, enter the total scoring of the arrangement. Do not enter the scoring of the original work.
- In the field **Physical description (300)**, use **keyboard score** if the work has been reduced for piano. Use **vocal** score if the work has been reduced for voice and piano.
