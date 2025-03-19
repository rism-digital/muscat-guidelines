# Hasła wzorcowe

Sekcja **Hasła wzorcowe** w programie Muscat gromadzi wszystkie pliki autorytatywne, kontrolowane słownictwo i indeksy, w celu zachowania spójności stosowanej terminologii w Muscat. Każde z nich opisano w skrócie poniżej. Pełne wytyczne dla wskazanych rodzajów haseł wzorcowych zawarte są w dokuemntacji każdego hasła.

## Obiekty cyfrowe

Baza danych obiektów cyfrowych gromadzi wszystkie obrazy (zazwyczaj znaki wodne, próbki pisma ręcznego lub oprawy) oraz incipity MEI, które są dołączone do rekordów w Muscat. Obiekty cyfrowe można dołączać do źródeł, osób i instytucji.

## Instytucje

Pliki autorytatywne dla Instytucji (nazwy korporatywne) opisują ciała zbiorowe niebędących osobami, które pojawiają się w związku ze źródłem lub innym rekordem autorytatywnym w Muscat. Ten autorytatywny plik zawiera zarówno współczesną nazwę instytucji (biblioteka z siglum biblioteki RISM) i historyczne oddziały instytucji (takie jak wydawca lub orkiestra). Instytucje można dodawać w polu **Dodatkowa instytucja (710 $a)** w Źródłach, **Dodatkowa instytucja (710 $a)** w Instytucjach, ** Powiązana instytucja (510 $a)** w Osobach i **Dodatkowa instytucja (710 $a)** w Literaturze pomocniczej.

## Święta liturgiczne

W indeksie świąt liturgicznych gromadzi się święta religijne i dni świąteczne. Święta liturgiczne można dodawać w polu **Święto liturgiczne (657 $a)** w Źródłach.

## Osoby

Plik autorytatywny nazw osobowych opisuje wszelkie osoby powiązane ze źródłem, lub innym rekordem autorytatywnym w Muscat. Nazwy osobowe można dodawać w polach **Nazwa kompozytora/autora (100 $a)** i **Dodatkowa osoba (700 $a)** w Źródłach, **Imię i nazwisko (700 $a)** w Instytucjach, **Powiązana osoba (500 $a)**  w Nazwach osobowych, **Autor (100 $a)** i **Dodatkowa osoba (700 $a)** w Literaturze pomocniczej oraz Kompozytor (100 $a)</strong> w....... RISM jest współtwórcą [VIAF (Virtual International Authority File)](https://www.viaf.org/), więc nazwy wnoszone do RISM są regularnie wysyłane do VIAF.

Nowe rekordy nazw osobowych mogą być edytowane przez właściciela rekordu przez dwa miesiące po utworzeniu. Zachęca się, aby katalogerzy wypełniali w rekordzie autorytatywnym możliwie jak najwięcej informacji, w tym odwołania do VIAF, informacje biograficzne i inne pisownie. Po dwóch miesiącach tryb edycji rekordu przechodzi do Biura Centralnego. Additions are still welcome and can be communicated through the comment function or by sending an email to [Alexander Marxen](mailto:alexander.marxen@rism.info).

## Places

The index of places collects the names of locations, including historical geographic names. The index is built from places entered in the following fields: **Location of performance (651 $a)** in Sources, **Geographic name (551 $a)** in Personal names, **Related place (651 $a)** in Secondary Literature, and **Place (551 $a)** in Institutions.

## Secondary literature

The database of Secondary literature enables catalogs of works, thematic catalogs, books, articles, encyclopedias, online resources, critical editions, modern performing editions, etc. to be cited in Muscat records. Secondary literature is linked through the **Short tile (210 $a)** in the fields **Catalog of works (690 $a)** and **Bibliographic reference (691 $a)** in Sources, **Literature (670 $a)** in Institutions, and **Source data found (670 $a)** in Personal names.

## Subject headings

All subject headings, musical forms, and genres are collected here. Some records include translations or explanations as to the scope of the subject heading. Subject headings are linked through the field **Subject heading (650 $a)** in Sources and **Subject heading (650 $a)** in Secondary literature.

## Titles/Text incipits

The Title/Text incipits index collects the titles entered in Sources from the fields **Standardized title (240 $a)** and **Additional title (730 $a)**, as well as the text incipits entered in the field **Text incipit (031 $t)**.

## Work nodes

Work nodes collect all information that is true for a work as a whole, no matter what other forms a piece of music exists in, whether it be—for example—an arrangement, a translation, a full score, or a single manuscript. Work nodes can include the composer, title, title variants, key, instrumentation, and incipits, though it is not always an easy matter to decide what constitutes a separate "work."

Associating a musical source in Muscat with a work ensures that all instances of any given piece of music are linked together. This improves the searchability of the catalog and helps users find all relevant sources, regardless of whether, for example, one manuscript calls the famous Mozart opera "Die Zauberflöte" and another is labeled "The Magic Flute," or a small chamber music piece is called a "duet" on one manuscript but a "sonata" on another. Beyond Muscat, in the linked data environment, information on works—and the associated RISM records—can be integrated into web searches, online encyclopedias, and other external databases.

Links to work nodes are made through the field 930 in every bibliographic record for a musical source. Works not in the authority file must be created there first before a link can be made.

**Creating a new work node**

Contact the RISM Editorial Center if you wish to create work nodes.

When you open a template to create a new authority record for a work, use the **VIAF search** to look in VIAF to see if the work is already there, and click **select** to transfer the data to your authority record and make the link to VIAF. Note that only the field 100 is searched (i.e., composer name, scoring summary, opus/thematic catalog number, key, and title), so searching for variants is not possible. Keep in mind that different VIAF contributors have different ways of expressing works, so expect variations in the formulation of titles, instruments, and even thematic indexes. A good strategy is to search by composer name plus the number of the opus/thematic index.

After you import the data from VIAF, note that it may be necessary to clean up some fields in the field **Heading (100)** to conform to RISM standards. Do not delete or edit imported information in the field **Name variants (400)**.
