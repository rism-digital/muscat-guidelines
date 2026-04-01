### Incipit (031)

Pole **Incipt** służy dostarczenia informacji muzycznej za pośrednictwem kilku otwierajacych taktów kompozycji zarówno dla warstwy muzycznej jak i tekstowej. Incipity pomagają w identyfikacji kompozycji i ułatwiają porównywanie źródeł. Najlepszą praktyką dla muzyki instrumentalnej jest włączanie incipitów z partii wysokiej i niskiej, takich jak vl 1 i bas. W przypadku muzyki wokalnej należy uwzględnić incipity z najwyższego głosu i pierwszych skrzypiec lub najwyższej partii instrumentalnej.

Jeśli potrzebna notacja nie jest dostępna przy użyciu kodu Plaine & Easie, należy możliwie jak najlepiej przetranskrybować muzykę i dołączyć notatkę objaśniającą. W celu dalszego wyjaśnienia można załączyć obraz incipitu ze źródła.

Pamiętaj, że transkrypcja incipitów jest wykorzystywana przede wszystkim do wyszukiwania i identyfikacji, a nie do wizualnego odworowania partytury. Kod Plaine & Easie jest celowym uproszczeniem notacji zachodniej i w zwiazku z tym nie wszystkie szczegóły mogą (lub powinny) być kodowane.

Aby uzyskać pomoc w transkrypcji notacji menzuralnej, zobacz [„Podstawowy notacji menzuralnej” autorstwa Teda Dumitrescu](http://www.cmme.org/misc/refsheet.pdf).

<!-- Note to translators: If you know of a standard reference document or website for transcribing mensural notation in your language, please use that instead. If not, feel free to link to this English document. -->  

_Notatka eksport MARC:_  
Rekordy, które zawierają inicpit (cokolwiek w polu 031) otrzymają przy zapisywaniu adnotację marc $2pe, wskazując, że incipit został utworzony przy użyciu kodu Plaine & Easie.

#### Numer utworu, numer części, numer incipitu (031 $a, b, c)

**Pole wymagane w przypadku korzystania z dowolnego pola w tej sekcji.**

Numer incipitu składa się z trzech cyfr, które oznaczają utwór, część i incipit.

Pierwszą cyfrą jest zawsze 1. Numer utworu odnosi się do pozycji incipitu w danym rekordzie, a nie do pozycji w całym źródle. Utwory w RISM katalogowane są jako osobne rekordy przy użyciu hierarchii rodziców/dzieci, w związku z czym kaązdy rekord ma jeden utwór.

Części odnoszą się zarówno do utworów jak i do istotnych części utworu, niezależnie od tego, czy są to części w sensie technicznym (np. symfonii), czy też różne sekcje utworu (np. aria). Numery części mogą być identyczne, jeżeli istnieje wiele incipitów dla części.

Numer incipitu jest osadzony w hierarchii części uwtoru. Takie same numery części, ale różne numery incipitów oznaczają, że incipity brzmią jednocześnie np. vl 1 i bas.

##### Przykłady

- 1.1.1 = 1. utwór, 1. część, 1. incipit
- 1.1.2 = 1. utwór, 1. część, 2. incipit (brzmi jednocześnie tak jak 1.1.1)
- 1.2.1 = 1. utwór, 2. część, 1. incipit
- 1.2.1 = 1. utwór, 3. część, 1. incipit

Kropki pomiędzy numerami są automatycznie dodawane przez Muscat.

Trzycyfrowy numer incipitu musi być unikalny w ramach rekordu. Numeracja incipitów powinna odzwierciedlać porządek w rekordzie. Incipit nie może sugerować swojej pozycji w kolekcji w źródle. Numeracja w ramach źródła powinna być ujęta opisie tytułu, a wszelkie cechy szczególne powinny zostać wyrażone w uwadze. Oznacza to, że numeracja incipitu czwartej pieśni w kolekcji będzie oznaczona jako 1.1.1 jak każda z pieśni kolekcji.

 Incipity należy numerować kolejno, nawet jeśli w źródło jest wybrakowane. Na przykład, jeśli brakuje jednej pieśni w kolekcji 6 pieśni, numer utworu każdego incipitu zawsze będzie się zaczynał od wartości 1. Jeżeli źródłem jest symfonia trzyczęściowa, ale brakuje części środkowej, incipity będą ponumerowane 1.1.1 i 1.2.1 (nie 1.3.1).


#### Tytuł części, tempo (031 $d)

Należy wpisać tytuł części i tempo lub podobne wskaźniki, jeśli takowe zostały określone, w sposób, w jaki pojawiają się one w źródle. Należy użyć **|** (pionowa kreska) z pojedynczą spacją przed i po znaku, aby pokazać koniec linii. Należy użyć nawiasów kwadratowych, aby wskazać dodatki do oryginału; pisownia wszelkich takich dodatków powinna być spójna. Wiele tytułów lub dodatkowe oznaczenia tempa można dodać w osobnych polach. Przy wpisywaniu wielu incipitów, dla których tytuł lub oznaczenie tempa jest takie samo, należy je wpisać tylko dla pierwszego incipitu muzycznego.

##### Przykłady
- All|o
- [vol. 1 p. 17:] N. 1: Recit. et Aria

**Przestarzałe procedury**: Starsze wytyczne RISM umożliwiały korzystanie ze sformułowania „Without tempo” na wskazanie, że część ma kilka oznaczeń tempa, z czego jeden lub kilka nie jest znanych. Wielokrotne oznaczenia tempa były wprowadzone po sobie, oddzielone średnikami.


#### Głos/instrument (031 $m)

Partię wokalną lub instrumentalną należy wpisać korzystając z listy **skrótów instrumentów RISM**. W przypadku nieustalonego głosu należy wpisać **V**. W przypadku nieustalonej partii instrumentalnej należy wpisać **i**. Strój instrumentu należy podać w polu **Uwaga ogólna**. Jeżeli instrument transponuje, jego incipit należy zapisać tak jak jhest zanotowany lub jak brzmi. W polu **Uwaga ogólna (031 $q)**, wskaż jaka metoda została zastosowana.

##### Przykłady

- pf
- Coro T
- org with text

**Przestarzałe procedury**: Starsze wytyczne RISM wymagały zapisywania incipitów muzycznych dla transponujących instrumentów, w sposób jaki brzmią.

#### Rola (031 $e)

Tutaj należy wprowadzić ujednoliconą nazwę roli dramatycznej. Jeśli wypełnisz to pole, upewnij się, że wypełnisz również pole **Postaci (595)**. Wskazać uzupełnienia za pomocą nawiasów kwadratowych. Wszelkie wątpliwe informacje należy odnotować znakiem zapytania.

#### Incipit tekstowy (031 $t)

Incipit tekstowy składa się z kilku pierwszych słów utworu lub części i może być pierwszą linijką, pierwszą frazą lub inną grupą słów, które mają sens językowy. Incipity tekstowe służą do identyfikacji użytego tekstu i niekoniecznie muszą pasować do długości muzyki podanej w incipicie muzycznym. Incipit tekstowy można uwzględnić niezależnie od tego, czy jest podany na źródle. Należy pamiętać, że do tekstów sporządzonych w języku łacińskim mają zastosowanie odrębne zasady (patrz poniżej).

Incipity tekstowe podaje się w formie ujednoliconej. Incipity tekstowe należy wprowadzać przy użyciu współczesnej pisowni. W celu znormalizowania wpisu należy odwołać się do kartoteki haseł wzorcowych **Tytuły/incipity tekstowe**. Jeśli nie ma ich w kartotece, należy wpisać dodać nowe incipity.

Nie należy umieszczać fragmentów tekstu w nawiasach lub podawać brakujących słów. W tekście nie należy umieszczać znaków interpunkcyjnych i powtórzeń.

Akcentów należy używać tylko w takiej formie, w jakiej pojawiają się w słowniku lub jeśli są poprawne gramatycznie. Numery należy wypisać na początku tekstu jako słowa. Wielkie i małe litery mają być zgodne z zasadami obowiązującymi w danym języku, z tym, że oznaczenia dla Boga (Herr, Dio, Dieu, Signore, Lord, etc.) należy zawsze pisać wielką literą. W przypadku stosowania incipitu tekstowego jako tytułu ujednoliconego (240), należy upewnić się, że długość i pisownia dokładnie się zgadzają.

Należy całkowicie pominąć tekst, jeśli nie można go przeczytać i należy dodać adnotację „Tekst nieczytelny” lub podobną.

W językach romańskich, kontynuuj wpisywanie tekstu bezpośrednio po apostrofie i bez spacji. Wyjątkiem od tej reguły jest sytuacja, gdy pierwszą literę słowa zastępuje apostrof (na przykład: Fra l'amante e 'l genitor).

Można tu podać sprawdzone lub pochodne teksty, które nie pojawiają się w źródle. W takich przypadkach należy umieścić cały tekst w nawiasach kwadratowych. Są to między innymi:

- Teksty, jeśli brakuje części wokalnej
- Incipity tekstowe w oryginalnym języku utworu, gdy źródło zawiera przetłumaczoną wersję
- Teksty kompozycji wokalnych, które stały się tematem wariacji lub podstawą aranżacji instrumentalnej

**Alfabety niełacińskie::** Jeśli w źródle znajduje się incipit tekstowy, który zawiera litery lub znaki niełacińskie (cyrylica/alfabet grecki, hebrajski/koreański itd., znaki chińskie itp.), tenże **Incipit tekstowy** należy wprowadzić przy użyciu oryginalnego alfabetu. Tłumaczenia lub transliteracje są opcjonalne i można je dodawać w dodatkowych polach incipitu tekstowego. Tłumaczenia nie znajdujące się w źródle należy dodawać w nawiasach. Można tłumaczyć na dowolny język RISM.

**Specjalne zasady dla tekstów w języku łacińskim:** Należy wprowadzić teksty łacińskie, zarówno sakralne, jak i świeckie. Jeżeli insipit tekstowy jest wykorzystwyany jako tytuł ujednolicony, dopilnuj aby pisownia była identyczna, ale pamiętaj że teksty łacińskie w tytułach ujetnoliconych wprowadza się tylko do pojawienia sę przecinka. Należy użyć nawiasów kwadratowych, aby wprowadzić teksty łacińskie, których nie podano w źródle, ale które ustalono w wyniku badań.

Standardowe teksty łacińskie zazwyczaj pasują do tekstów wystąpującyh w _Liber usualis_. W RISM teksty te zazwyczaj zawierają przecinek. Na przykład, w przypadku szukania tekstu „Et in terra pax”, wyświetla się około tuzina opcji, ale tylko jedna ma przecinek i tego źródła używa się w bazie danych 4 800 razy. Dlatego jest to ten poszukiwany tekst – zakładając, że pasuje on do danego źródła. Jeśli incipit tekstowy zawiera tylko „Et in terra pax”, oznacza to, że źródło (1) zawiera tylko te słowa lub (2) jego ciąg dalszy jest inny niż w _Liber usualis_. Jest to oczywiście możliwe, ale w większości przypadków pożądana jest wersja z przecinkiem.


#### Tonacja lub modus (031 $r)

Należy wybrać tonację lub modus z listy.

**Przestarzałe procedury**: Starsze wytyczne katalogowania RISM pozwolalały na wprowadzenie wielu tonacji w tym polu, oddzielonych średnikiem. Praktyka ta została przerwana wraz z wprowadzeniem programu Muscat.

#### Tonacja/Znaki przykluczowe (031 $n)

Wprowadzić **x** dla tonacji durowych lub **b** dla tonacji molowych, podając następnie wielkie litery dźwięków, które mają być podniesione lub obniżone. Jeżeli dany utwór jest wyraźnie napisany w danej tonacji, lecz w znakach przykluczowych nie podano krzyżyka lub bemolu, brakujące krzyżyki i bemole można dodać w nawiasach.

W przypadku braku znaków przykluczowych, należy pozostawić puste miejsce.

##### Przykłady

- xF = F jest z krzyżykiem = G-dur lub e-moll
- bBE = B i E są z bemolami = B-dur lub g-moll
- xFC[G] = F i C mają krzyżyki w źródle dur, ale utwór jest wyraźnie napisany w tonacji A-dur, więc ostatni krzyżyk dodano w nawiasie

#### Metrum/Znak metrum (031 $o)

Wpisywać znaki metrum jako ułamki. Dozwolone są następujące oznaczenia:

- **c** = tempus imperfectum cum prolatione imperfecta
- **c/** = alla breve
- **3** = proportio tripla; także **1**, **2**, itd.
- **c3** = proportio tripla
- **c3/2 = proportio sesquialtera**
- **c** = tempus imperfectum cum prolatione perfecta
- **o** = tempus perfectum cum prolatione imperfecta
- **o/** = tempus perfectum cum prolatione minore diminutum
- **o.** = tempus perfectum cum prolatione perfecta

Jeżeli metrum stale się zmienia, można wpisać pierwszy znak metrum, a po nim drugi, przedzielony spacją.

Jeżeli incipit jest pozbawiony znaku metrum, dodaj je oraz podaj wyjaśnienie w polu **Uwaga ogólna (031 $q)** takie jak „Dodano oznaczenie metrum”. Nie należy podawać wywnioskowanego metrum w nawiasie kwadratowym.

**Przestarzałe procedury**: Starsze wytyczne pozwalały na pozostawienie pola pustego jeśli incipit pozbawiony był metrum.

##### Przykłady

- 4/4
- 6/8
- 3/4 4/4

Jeżeli znak metrum podane w źródle jest ewidentnie nieprawidłowe, należy je poprawić tak, aby odpowiadało podanemu incipitowi. W polu **Uwaga ogólna** należy dodać objaśnienie.

#### Klucz (031 $g)

Należy wybrać klucz z listy. Litera wskazuje rodzaj klucza. Myślnik oznacza notację współczesną. Znak plus oznacza notację menzuralną. Cyfra odnosi się do pozycji na linii pięciolinii.

Jeżeli na źródle nie ma podanego klucza, wybierz jeden z listy i dodaj uwagę wyjaśniającą w polu **Uwaga ogólna (031 $q)**.

#### Ważność (031 $s)

W tym polu nie należy niczego wpisywać! (Stosuje się je tylko dla starych danych.)

#### Incipit muzyczny (031 $p)

Incipit muzyczny należy wpisywać w formie zakodowanej korzystając z kodu Plaine & Easie (patrz także [https://www.iaml.info/plaine-easie-code](https://www.iaml.info/plaine-easie-code)). Incipit powinien być długości co najmniej dwóch taktów (miar) lub sześciu nut.

##### 1. Oktawy
' = w pierwszej oktawie powyżej środkowego C '' = w drugiej oktawie powyżej środkowego C ''' = w trzeciej oktawie powyżej środkowego C , = w pierwszej oktawie poniżej środkowego C ,, = w drugiej oktawie poniżej środkowego C ,,,,, = w trzeciej oktawie poniżej środkowego C

##### 2. Wartości rytmiczne

0 = longa  
9 = brevis  
1 = cała nuta / semibrevis  
2 = półnuta / minima  
4 = ćwierćnuta / semiminima  
8 = ósemka / fusa  
6 = szesnastka / semi fusa   
3 = trzydziestodwójka 5 = sześćdziesięcioczwórka  
7 = stodwudziestoósemka   
7\. = notacja neumatyczna

Kropki stosuje się do oznaczenia nut z kropką. Do nuty można dodać wiele kropek.

4\. = ćwierćnuta z kropką</0> 8.. = ósemka z podwójną kropką

##### 3. Znaki chromatyczne

x = krzyżyk  
xx = podwójny krzyżyk  
b = bemol  
bb = podwójny bemol  
n = kasownik

##### 4. Nazwy nut

C, D, E, F, G, A, H

##### 5. Ozdobniki

g = acciaccatura (bez wartości rytmicznej, poprzedza nazwę nuty)  
q = appoggiatura/przednutka długa (posiada wartość rytmiczną, poprzedza nazwę nuty)  
qq...r = kilka appoggiatur lub ozdobników, które stanowią jedną całość (posiadają wartość rytmiczną)

##### 6. Pauzy

'-' czyli (znak minus) oznacza pauzę jednonutową. Dla oznaczenia taktu pustego należy stosować „=” (znak równości). Dla wielu pustych taktów, po znaku równości, należy podać ilość i oznaczenie kreski taktowej.
- Przykład dla pauzy ósemkowej
 - 8-/
- Przykłady dla jednego taktu pustego
 - -/
 - =1/
- Przykłady dla wielu taktów pustych
 - =35/

##### 7. Kreski taktowe

/ = kreska taktowa  
// = podwójna kreska taktowa  
//: = podwójna kreska taktowa z powtórzeniem  
:// = podwójna kreska taktowa z powtórzeniem  
://: = podwójna kreska taktowa z powtórzeniem

##### 8. Inne symbole

t = tryl (znajduje się natychmiast po nucie)

+ + = łuk (znajduje się natychmiast po nucie; nie mylić z legato)  
  () = fermata/trzymanie/pauza (w nawiasy można ująć jedynie nazwę literową jednej nuty lub jedną pauzę; znaki chromatyczne, oznaczenia wysokości dźwięku itp. muszą być po za nawiasami; patrz także ** 10. Rytmy specjalne**, poniżej)

Nie wpisywać łuków.

##### 9. Belkowanie

{ = początek belkowania  
} = koniec belkowania

###### Przykład

{qq6'CDEDr}

##### 10. Rytmy specjalne

( = początek rytmu specjalnego  
) = koniec rytmu specjalnego

Ogólną wartość trwania grupy należy podać przed **(**. Wartość rytmiczna pierwszej nuty należy podać po **(**, nawet jeśli jest identyczna jak wartość nuty znajdującej tuż przed sekcją specjalnego rytmu. Liczbę nut w grupie należy wskazać przed **)**. Należy ją oddzielić od ostatniej nuty za pomocą **;**.

###### Przykłady

- 8(3ABCDE;5)  = grupa pięciu trzydziestodwójek w miejsce jednej ósemki.
- 8({3ABCDE};5) = grupa pięciu trzydziestodwójek w miejsce jednej ósemki, belkowana.

Triola stanowi przypadek szczególny. Zasadniczo, należy ją kodować w sposób następujący:  
8(6ABC;3) lub 8({6ABC};3).  
Zamiast tego, dozwolony jest następujący skrót:  
(6ABC)  
({6ABC})

Nie należy zapominać o wartości rytmicznej w obrębie nawiasu kwadratowego!

##### 11. Skróty

###### 11.1. Figury powtarzane

! ! = początek i koniec pasażu  
f = oznaczenie powtórzenia   
Powtórzeń tej figury jest tyle, ile jest powtórzeń **f** po drugim **!**. Jest to możliwe jedynie w obrębie taktu.

###### Przykład

- !{'8ABAG}!ff = ta figura powtarza się dwukrotnie.

###### 11.2. Powtarzane takty

i = powtórzenie ostatniego taktu  
'i' umieszcza się zawsze między dwoma kreskami taktowymi.

###### Przykład

- '4ABAG/i/i/ = takt zostanie powtórzony dwukrotnie.

###### 11.3. Wzory rytmiczne

Gdy dana sekwencja rytmiczna powtarza się kilka razy, wzór rytmiczny można podać przed nazwami literowymi odpowiednich nut.

Sekwencja rytmu kończy się z chwilą pojawienia się innej wartości rytmicznej. Upewnij się, że wszystkie nuty oznaczone jako wzór są widoczne co najmniej raz.

###### Przykład

- Zamiast zapisu **8.A6B8C8.D6E8F** korzystając z kodowania można zapisać **8.68ABCDEF**


##### 12. Zmiana klucza

Jeżeli klucz zmienia się w obrębie incipitu, użyj znaku **%** w celu zmiany klucza. Następnie podaj nowy klucz i spację.

###### Przykłady

- %C-1 '2A
- %C-1 $xFC '8B

##### 13. Zmiana tonacji

Jeżeli tonacja, zmienia się w obrębnie incipitu, użyj znaku **$** w celu zmiany tonacji. Następnie podaj nową toncję za pomocą oznaczeń znaków przykluczowych i spację. Zmiana tonacji może być wprowadzona tylko raz w ramach taktu. Możesz anulować poprzednią zmianą tonacji używając znaku $n lub wprowadzić nową nową tonację poprzez oznaczenia znaków przykluczowych.

###### Przykłady

- $nBE $xFC
- $xFC

##### 14. Zmiana metrum

Jeżeli metrum zmienia się w obrębie incipitu, użyj znaku **@** w celu zmiany metrum. Następnie podaj nowe oznaczenie metrum i spację.

###### Przykład

- @3/2 '1C

##### 15. Skróty

Skrócone formy notacji występujące w nutach, takie jak tremola lub znaki simile, należy wpisać w całości stosując występującą w źródle notację.

###### Przykład

- {'8DDDD} = półnuta/minima/półtremolo na D

##### 16. Akordy

Wprowadzić akordy od najwyższej do najniższej nuty, oddzielone znakiem **^**.

###### Przykład

- 4’’C^’G^E^C

**Przestarzałe procedury**: We wcześniejszych programach do katalogowania, pole do zakodowanych zapisów rozpoczynało się od znaku $, następnie występowały znaki przykluczowe ($xFC DLA $bBE), a następnie znak a ³ (3 w indeksie górnym), ale wyświetlane jako an _ (podkreślenie). Incipity bez oznaczenia tonacji, zaczynały się od znaku an _.

#### Uwaga ogólna (031 $q)

Tu należy wprowadzić wszelkie inne uwagi, takie jak wysokość dźwięku transponowanych instrumentów, błędy w incipicie, incipit tekstowy w oryginalnej pisowni i/lub z oryginalną interpunkcją, lub wszelkie inne dokonane adiustacje. Wprowadzać stosując używany przez Państwa język katalogowania.

**Przestarzałe procedury**: Starsze wytyczne katalogowania RISM pozwolalały na użycie symboli **?**, **+**i **t** odzwierciedlając znormalizowane uwagi. Praktyka ta została przerwana wraz z wprowadzeniem programu Muscat i zamiast tego informacje wyjaśniające w są umieszczane w polu **Uwaga ogólna (031 $q)**. Były następujące symbole:
- **?** = Błąd w incipicie nie mógł zostać skorygowany.
- **+** = Błąd w incipicie został poprawiony
- **t** = Incipity został przetranskrybowany do współczesnej notacji


#### Scoring in movement (031 $z)

In this field, you can indicate the specific scoring for the particular movement in question (such as a movement within a complex vocal piece). List the scoring on one line using RISM instrument abbreviations and in the standard order (described in **Scoring summary [240 $m]**). Use a semicolon to separate instrument families.

##### Przykłady

- S (Enrico), T (Vanoldo); vl 1, 2, b; [winds]
- S 2 solo; Coro; ob obl; strings, bc
