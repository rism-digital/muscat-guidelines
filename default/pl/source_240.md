### Tytuł ujednolicony (240)

W polu **Tytuł ujednolicony** należy wpisać tytuł w ustandaryzowanej formie. Tytuł ujednolicony łączy razem pod tym samym tytułem kompozycje, które mimo posiadania różnych nazw, są kompozycją tą samą lub podobną. Zwany również „tytułem grupującym” lub „tytułem jednolitym”.

_Notatka eksportu MARC:_  
Wartość pola **Tytuł ujednolicony** eksportowana jest jako MARC 130, z tymi samymi podpolami co 240, gdy rekord nie zawiera nazwy w polu **Kompozytor/Autor (100)**.

#### Tytuł ujednolicony (240 $a)

**Pole wymagane.**

Wprowadź tytuł w znormalizowanej formie. Pole jest powiązane z kartoteką haseł wzorcowych **Tytuły/incipity tekstowe** poprzez podpole $0. Zaznaczyć wątpliwe informacje znakiem zapytania na końcu (np. **Die Zauberflöte?**). Nie używać nawiasów kwadratowych ani okrągłych. Alternatywne wersje tytuły należy dodać w polu **Tytuł dodatkowy (730)**.

Tytuł ujednolicony można wygenerować zgodnie z poniższą preferencją kolejności:

1. Tytuły charakterystyczne
2. Incipity tekstowe
3. Gatunki
4. Oznaczenia tempa

##### 1. Tytuły charakterystyczne

Tytuły charakterystyczne obejmują wszelkiego rodzaju dzieła sceniczne, oratoria, kantaty i pieśni, a także niektóre rodzaje muzyki instrumentalnej (takie jak charakterystyczne dzieła z XVIII wieku o specjalnym tytule indywidualnym).

Wprowadź tytuł charakterystyczny stosując standardową pisownię wedle (1) New Grove, (2) MGG, (3) katalogów utworów i/lub (4) innych książek referencyjnych. Nie należy pomijać początkowych przedimków (the, a, an, der, die, le, l' itp.).

Popularne nazwy lub pseudonimy (takie jak „Eroica” czy „Msza Nelsońska”) nie są uznawane jako tytuły ujednolicone. Takie nazwy wpisuje się w polu **Tytuł dodatkowy (730 $a)**.

W języku angielskim preferowany jest przypadek zdania. W języku francuskim preferowane są ([Règles simplifiées](https://fr.wikipedia.org/wiki/Usage_des_majuscules_en_fran%C3%A7ais#Titres_d%E2%80%99%C5%93uvres_ou_de_p%C3%A9riodiques)).

###### Przykłady

- Die Forelle
- Die Zauberflöte
- The beggar's opera
- L'italiana in Algeri

##### 2. Incipit tekstowy

Wprowadź incipit tekstowy jako tytuł ujednolicony dla utworów wokalnych, jeśli nie mają odrębnego tytułu.

Te same zasady stosuje się do recytatywu i cavatiny, sceny i ronda lub podobnych kombinacji. Jeśli źródło składa się z recytatywu i arii lub sceny i arii, jako tytułu ujednoliconego zawsze używa się incipitu tekstowego arii. W przypadku pojedynczej arii z opery, której tytuł nie jest znany, należy wpisać incipit tekstowy arii.

Natomiast w przypadku kantat, tekst pierwszego utworu wokalnego funkcjonuje jako tytuł ujednolicony, niezależnie od tego, czy jest to recytatyw, aria czy chór.

Jednakże, w przypadku mszy, requiem, kompozycji na uroczystości pogrzebowe, litanii i kompozycji liturgicznych, należy wprowadzić gatunek. To samo dotyczy kompletnych oper i oratoriów, których tytuły są nieznane.

Przy wprowadzaniu incipitów tekstowych, należy stosować zasady ortografii każdego z języków w zakresie użycia wielkich lub małych liter. Należy kapitalizować nazwy bóstwa (God, Herr, Dio, Dieu, Signore, Lord, etc.). Należy pomijać znaki interpunkcyjne i powtórzenia w obrębie incipitu. Dla tytułów, które są tłumaczeniami należy użyć incipitu tekstowego w języku oryginału.

Upewnij się, że incipit tekstowy użyty w tym polu jest tak sam jak w polu **Incipit tekstowy (031 $t)**. W przypadku tekstów łacińskich należy wybrać tekst poprzedzany przez przecinek (z listy w aneksie) jako tytuł ujednolicony w całej swojej postaci.

###### Przykłady

- Der Mond ist aufgegangen
- Gloria [z incipitem tekstowym: Gloria, in excelsis Deo et in terra pax]

##### 3. Gatunek

Wykorzystaj gatunek utworu jako tytuł ujednolicony, gdy brak tytułu charakterystycznego lub incipitu tekstowego. W większości przypadków należy wpisać gatunek w języku angielskim i w liczbie mnogiej (np. **Operas**). Należy przy tym pamiętać, że w przypadku niektórych gatunków wykorzystuje się odpowiadajace określenie pochodzące z kartoteki haseł wzorcowych dla pola **Hasło przedmiotowe (650)**. Zapoznaj się z listą **Tytuł ujednolicony — Hasło przedmiotwe** w **Wytycznych** aby uzyskać pomoc.

###### Przykłady

- Symphonies
- Allemandes

##### 4. Oznaczenia tempa

Należy wprowadzić oznaczenie tempa jeżeli nie można ustalić gatunku. Jeżeli żadna z tych opcji nie jest dostępna, należy użyć następujących terminów:

- Songs (vocal pieces)
- Pieces (utwór ogólny)
- Części (pojedyncza część utworu instrumentalnego bez oznaczenia tempa i o nieustalonym charakterze)

###### Przykłady

- Presto
- Lento

#### Zasady specjalne

##### Kolekcje

W takich przypadkach wprowadza się liczbę plus wprowadzony gatunek. Podać cyfrę arabską oznaczającą ile utworów przynależy do danej kolekcji, a następnie podać możliwie najszerszy odpowiadajacy gatunek.

###### Przykłady

- 25 Arias
- 3 Instrumental pieces

##### Klocki introligatorskie

W takich przypadkach wprowadza się liczbę odpowiadającą ilości obiektów w adligacie plus angielskie słowo „Items”.

###### Przykład

- 11 Items

##### Wariacje

Wprowadzić **Variations** jako tytuł ujednolicony. W polu **Tytuł dodatkowy (730)**wpisz dzieło na bazie którego powstały wariacje, jeśli jest znane, i wybierz **Wariacje** obok **Strefy Aranżacji**.

##### Wstawki

Należy wprowadzić incipit tekstowy wstawionego utworu jako tytuł ujednolicony. W polu **Tytuł dodatkowy (730)** należy wpisać nazwę opery lub większego utworu i wybrać **Wstawienia** w ramach podpola **Pod-nagłówek**.

##### Alfabety niełacińskie

Jeśli źródło ma tytuł, który używa liter lub znaków innych niż łacińskie (cyrylica/alfabet grecki/hebrajski/koreański itp. znaki chińskie itp.), należy wprowadzić **Tytuł ujednolicony** stosując oryginalny alfabet. Tłumaczenia lub transliteracje nie są obowiązkowe, można je dodać w polu **Tytuł dodatkowy (730)**.

#### Arrangement statement (240 $o)

Select **Arrangement** if the work is an arrangement of another work.

Note that retextings and transpositions are not considered arrangements. In such cases, enter the name of the responsible person, if known, under **Additional personal name (700)**. Although the works are not considered arrangements, the person is referred to there as "Arranger".

Arrangements should also be distinguished from independent works (free elaborations), such as variations, paraphrases, parodies, and fantasies on themes from the original work.

#### Subheading (240 $k)

This field is for special form aspects as applicable. Select from the following:

- **Excerpts**: if only one or several sections of the complete work are present
- **Fragments**: if only fragments of the work are present
- **Sketches:** if only sketches of the work are present

#### Key or mode (240 $r)

**Required if the key can be determined with certainty.**

Select the key of the entire work (even for excerpts).

In the case of arrangements, enter the key of the original work. If the original key cannot be determined, enter the key of the source in hand; in this case, though, enter a corresponding note in the field **General note (500)**.

If no key is indicated on the source, select a key only if it can be determined with certainty.

Do not enter a key for: operas, oratorios, and cantatas; recitatives without an ensuing aria; and works for which a key cannot be clearly established.

Do not translate modes into modern key names.

The following Western church modes are available:
- 1st tone (Dorian)
- 1st tone (Dorian), transposed
- 2nd tone (Hypodorian)
- 2nd tone (Hypodorian), transposed
- 3rd tone (Phrygian)
- 3rd tone (Phrygian), transposed
- 4th tone (Hypophrygian)
- 4th tone (Hypophrygian), transposed
- 5th tone (Lydian)
- 5th tone (Lydian), transposed
- 6th tone (Hypolydian)
- 6th tone (Hypolydian), transposed
- 7th tone (Mixolydian)
- 7th tone (Mixolydian), transposed
- 8th tone (Hypomixolydian)
- 8th tone (Hypomixolydian), transposed
- 9th tone (Aeolian)
- 9th tone (Aeolian), transposed
- 10th tone (Hypoaeolian)
- 10th tone (Hypoaeolian), transposed
- 11th tone (Ionian)
- 11th tone (Ionian), transposed
- 2th tone (Hypoionian)
- 12th tone (Hypoionian), transposed

The following Byzantine church modes are available:
- Ēchos prōtos (First mode of Byzantine music)
- Ēchos deuteros (Second mode of Byzantine music)
- Ēchos tritos (Third mode of Byzantine music)
- Ēchos tetartos (Fourth mode of Byzantine music)
- Ēchos plagios prōtos (First plagal mode of Byzantine music)
- Ēchos plagios deuteros (Second plagal mode of Byzantine music)
- Ēchos barys (Third plagal mode of Byzantine music)
- Ēchos plagios tetartos (Fourth plagal mode of Byzantine music)

**Obsolete procedures**: Older RISM cataloging guidelines allowed multiple key signatures to be entered in this field, separated by a semicolon. This practice was discontinued with the introduction of Muscat.

#### Scoring summary (240 $m)

**Required field except for the following: operas and oratorios with the standard instrumentation V (X), Coro, orch**

If you have sketches or collections, enter a scoring summary if it makes sense to do so.

Enter a brief scoring (instrumentation) summary of the overall medium of performance for the work here. Enter a maximum of four elements. Separate each element of the scoring summary with commas. A detailed description of the instrumentation is entered in the field **Total scoring (594)**. The entire scoring summary goes in one line; repeat the field only to indicate alternative instrumentations (see below).

Use terms from the **Abbreviations** list. Write out any terms that are not contained in this list in full and in English.

Enter groups of instruments in the following order:

- Solo voices
- Chorus
- Solo instruments
- Strings
- Woodwinds
- Brass
- Plucked instruments
- Percussion
- Keyboard instruments
- Basso continuo

Use **V** to indicate an unknown vocal part and **i** for an unknown instrument. Indicate an unknown number with **(X)**. When more than one of the same voice or instrument is indicated, place the number in parentheses after the part designation, such as **B (2)**. Also use **V** to group together several different vocal parts, such as **V (8)**.

Specify solo instruments only if they have a continuous solo function in relation to an orchestra, especially in a solo concerto. Do not list a part here if it only has occasional solo passages, such as an oboe solo in a section of a cantata.

In the case of arrangements, the scoring summary refers to the personnel required in the present source, not in the work on which an arrangement is based. If the instrumentation of the original work is known, specify it in the field **General note (500)**. In the case of a **Collection**, only use the field if the particular scoring is applicable to all the works contained in the collection.

This field may be repeated in cases where alternative instrumentation is suggested, such as a song that is for either soprano or tenor. In such cases, enter each possible instrumentation in a separate field: for example, **S, pf** on one line and **T, pf** on the next.

If you have a figured bass, enter the instrument as usual, such as **b**, **bc**, **org**, etc. (but see the tables in the section **Figured bass in scores and/or parts** for guidance with related fields).

Omit the scoring summary if the performing forces are unknown or uncertain.

##### Examples
- A, Coro, orch
- Bariton, pf
- V (3), strings, bc
- V (4), Coro, orch, org   _for a mass_
- cl, orch _for a clarinet concerto_

Use the following standard instrumentation when applicable.

String quartet
- vl (2), vla, vlc

String quintet (2 violas)
- vl (2), vla (2), vlc

String quintet (2 cellos)
- vl (2), vla, vlc (2)

String quintet (with double bass)
- vl (2), vla, vlc, cb

Piano trio
- vl, vlc, pf

Flute quartet (all flutes)
- fl (4)

Flute quartet (flute with strings)
- fl, vl, vla, vlc
