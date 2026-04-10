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

Wprowadzić **Variations** jako tytuł ujednolicony. W polu **Tytuł dodatkowy (730)** wpisz dzieło na bazie którego powstały wariacje, jeśli jest znane, i wybierz **Wariacje** w ramach podpola **Uwaga do aranżacji**.

##### Wstawki

Należy wprowadzić incipit tekstowy wstawionego utworu jako tytuł ujednolicony. W polu **Tytuł dodatkowy (730)** należy wpisać nazwę opery lub większego utworu i wybrać **Wstawienia** w ramach podpola **Pod-nagłówek**.

##### Alfabety niełacińskie

Jeśli źródło ma tytuł, który używa liter lub znaków innych niż łacińskie (cyrylica/alfabet grecki/hebrajski/koreański itp. znaki chińskie itp.), należy wprowadzić **Tytuł ujednolicony** stosując oryginalny alfabet. Tłumaczenia lub transliteracje nie są obowiązkowe, można je dodać w polu **Tytuł dodatkowy (730)**.

#### Strefa aranżacji (240 $o)

Wybrać **Aranżacja**, jeśli utwór jest aranżacją innego utworu.

Należy pamiętać, że przetekstowań i transpozycji nie traktuje się jako aranżacji. W takich przypadkach należy w polu **Dodatkowa osoba (700)** wpisać imię i nazwisko osoby odpowiedzialnej (jeśli jest znane). Mimio iż w przypadku tych utworów, nie mamy do czynienia z aranżacjami, wybieramy w funkcji dla tych osób „Aranżera”.

Należy również odróżnić aranżacje od utworów niezależnych (swobodnych opracowań), takich jak wariacje, parafrazy, parodie i fantazje na tematy z utworu oryginalnego.

#### Podhasło (240 $k)

Pole to dotyczy szczególnych aspektów formularza, w stosownych przypadkach. Wybrać spośród poniższych:

- **Wyjątki**: dostępna jest tylko jedna lub kilka sekcji całego utworu
- **Fragmenty**: dostępne są tylko fragmenty utworu
- **Szkice**: dostępne są tylko szkice utworu

#### Tonacja lub modus (240 $r)

**Wymagane, jeśli tonację można ustalić z pewnością.**

Wybrać tonację całego utworu (nawet w przypadku wyjątków).

W przypadku aranżacji, wpisać tonację oryginalnego utworu. Jeśli nie można ustalić oryginalnej tonacji, należy wprowadzić tonację posiadanego źródła. W tym przypadku należy jednak wprowadzić odpowiednią uwagę w polu **Uwaga ogólna (500)**.

Jeśli w źródle nie jest wskazano żadnej tonacji, należy wybrać tonację tylko wtedy, gdy można ją ustalić z pewnością.

Nie należy wprowadzać tonacji w przypadku oper, oratoriów i kantat, recytatywów bez następujących po nich arii oraz utworów, w przypadku których tonacji nie da się jednoznacznie ustalić.

Nie tłumaczyć modusów na współczesne nazwy tonacji.

Dostępne są poniższe skale kościelne:
- 1. ton (dorycki)
- 1. ton (dorycki), transponowany
- 2. ton (hypodorycki)
- 2. ton (hypodorycki), transponowany
- 3. ton (frygijski)
- 3. ton (frygijski), transponowany
- 4. ton (hypofrygijski)
- 4. ton (hypofrygijski), transponowany
- 5. ton (lidyjski)
- 5. ton (lidyjski), transponowany
- 6. ton (hypolidyjski)
- 6. ton (hypolidyjski), transponowany
- 7. ton (miksolidyjski)
- 7. ton (miksolidyjski), transponowany
- 8. ton (hypomiksolidyjski)
- 8. ton (hypomiksolidyjski), transponowany
- 9. ton (eolski)
- 9. ton (eolski), transponowany
- 10. ton (hypoeolski)
- 10. ton (hypoeolski), transponowany
- 11. ton (joński)
- 11. ton (joński), transponowany
- 12. ton (hypojoński)
- 12. ton (hypojoński), transponowany

Dostępne poniżej modusy bizantyjskie:
- Ēchos prōtos (pierwszy modus muzyki bizantyskiej)
- Ēchos deuteros (drugi modus muzyki bizantyskiej)
- Ēchos deuteros (trzeci modus muzyki bizantyskiej)
- Ēchos tetartos (czwarty modus muzyki bizantyskiej)
- Ēchos plagios prōtos (pierwszy plagalny modus muzyki bizantyskiej)
- Ēchos plagios deuteros (drugi plagalny modus muzyki bizantyskiej)
- Ēchos barys (trzeci plagalny modus muzyki bizantyskiej)
- Ēchos plagios tetartos (czwarty plagalny modus muzyki bizantyskiej)

**Przestarzałe procedury**: Starsze wytyczne katalogowania RISM pozwolalały na wprowadzenie wielu tonacji w tym polu, oddzielonych średnikiem. Praktyka ta została przerwana wraz z wprowadzeniem programu Muscat.

#### Podsumowanie obsady (240 $m)

**Pole wymagane, z wyjątkiem: oper i oratoriów ze standardową instrumentacją V (X), Coro, orch.**

W przypadku szkiców lub kolekcji, jeśli ma to sens, należy wprowadzić podsumowanie obsady.

Wprowadzić tutaj krótkie podsumowanie całkowitej obsady (instrumentacji) jako narzędzia wykonawczego. Każdy element streszczenia obsady należy oddzielić przecinkami. Wprowadzić maksymalnie cztery elementy. Dokładny opis obsady wprowadza się w polu **Szczegółowy opis obsady (594)**. Całe podsumowanie obsady znajduje się w jednej linii; pole należy powtórzyć tylko w celu podania alternatywnych instrumentacji (patrz poniżej).

Używać wyrażeń z listy **Skróty**. Jeżli jakiejś nazwy brakuje na liście, należy ją podać w pełnym brzmieniu i w języku angielskim.

Grupy instrumentów wprowadzić w następującej kolejności:

- Głosy solowe
- Chóry
- Instrumenty solowe
- Smyczki
- Dęte drewniane
- Blaszane
- Szarpane
- Perkusja
- Klawiszowe
- Basso continuo

W przypadku podania więcej niż jednego tego samego głosu lub instrumentu należy umieścić ich liczbę w nawiasach po desygnacji partii, np. **B(2)**. Wprowadzić **V**, aby oznaczyć nieznaną partię głosową oraz **i**, aby oznaczyć nieznany instrument. Należy podać **V** także do zgrupowania kilku różnych partii wokalnych, takich jak **V (8)**. W przypadku nieznanej liczby, należy podać **(X)**.

Instrumenty solowe należy podawać tylko wtedy, gdy pełnią one ciągłą funkcję solową w stosunku do orkiestry, zwłaszcza w koncercie solowym. Nie wymieniać tutaj partii, jeśli ma ona jedynie okazjonalne pasaże solowe, takie jak obój solo w sekcji kantaty.

W przypadku aranżacji, podsumowanie obsady odnosi opisywanego źródła, a nie do źródła oryginalnego na podstawie, którego aranżacja się opiera. Jeżeli znana jest instrumentacja utworu oryginalnego, należy ją podać w polu **Uwaga ogólna (500)**. W przypadku **Kolekcji** należy korzystać z pola tylko wtedy, gdy dana obsada ma zastosowanie do wszystkich utworów zawartych w kolekcji.

Pole to można powtórzyć w przypadkach, gdy w źródle sugeruje się alternatywną instrumentację, np. pieśń na sopran lub na tenor. W takich przypadkach należy wpisać każdą możliwą instrumentację w osobnym polu: na przykład: **S, pf** w jednej linii i **T, pf** w następnej.

W przypadku basso continuo, należy wpisać instrument jak zwykle, np. **b**, **bc**, **org**, itp. (ale zobacz tabele w sekcji **Basso continuo w partyturach i/lub partiach** w celu uzyskania wskazówek dotyczących powiązanych pól).

Ominąć podsumowanie obsady, jeżeli instrumentacja nie jest znana lub wiedza na jej temat jest niepewna.

##### Przykłady
- A, Coro, orch
- Bariton, pf
- V (3), strings, bc
- V (4), Coro, orch, org   _na mszę_
- cl, orch _na koncert klarnetowy_

Wykorzystuj następującej standardowej instrumentacji, jeśli ma zastosowanie.

Kwartet smyczkowy
- vl (2), vla, vlc

Kwartet smyczkowy (2 altówki)
- vl (2), vla (2), vlc

Kwartet smyczkowy (2 wiolonczele)
- vl (2), vla, vlc (2)

Kwartet smyczkowy (z kontrabasem)
- vl (2), vla, vlc, cb

Trio pianistyczne
- vl, vlc, pf

Kwartet fletowy (same flety)
- fl (4)

Kwartet fletowy (flety ze smyczkami)
- fl, vl, vla, vlc
