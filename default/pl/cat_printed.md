## Druki muzyczne w RISM

Sekcja **Druki muzyczne w RISM** przedstawia pewne przemyślenia odnośnie druków muzycznych, w szczegónosci zakresu edycji muzycznych, rekordów bibliograficznych wobec informacji dla egzemplarza, kiedy tworzyć nowy rekord, wprowadzać tytuły standaryzowane, rekrody dla wielu nakładów, koniecznoś podziału rekordów i ich łączenia, a także wydań druków muzycznych z Serii B.

### Zakres druków muzycznych w RISM

RISM dąży do dokumentowania druków muzycznych od początku historii drukowania nut do około 1945 roku.

W XX wieku i do dziś obserwujemy gwałtowny rozwój komercyjnych wydawnictw muzycznych i dystrybucji publikacji. Ilość muzyki uważanej za „rzadką” lub nieudokumentowaną, w porównaniu z poprzednimi wiekami, jest teraz znacznie mniejsza. Druki muzyczne wydawane przez współczesnych wydawców, są szeroko dostępne i ukazują się w dużych ilościach, przeznaczone są do aktywnego wykorzystania przez użytkowników bibliotek, w związku z tym są lepiej udokumentowane w bazach danych, takich jak [WorldCat](http://www.worldcat.org/).

RISM bierze pod lupę każdy druk muzyczny, która wymyka się swoim ramom jako indywidalny przypadek. Chodzi tu o przypadki nieistniejących już wydawców, lub wydane przez mniejszych, regionalnych wydawców o znaczeniu historycznym czy współczesne wydania, będące częścią kolekcji o wartosci historycznej, jak prywatne biblioteczki osób prywatnych.

### Rekord bibliograficzny wobec danych dla rekordu egzemplarza

Muscat posiada dwustopniową strukturę dla wydań druków muzycznych: poziom danych bibliograficznych i poziom danych egzemplarzy. Informacje prawdziwe dla całego wydania wprowadza się do rekordu bibliograficznego, natomiast dane specyficzne dla egzemplarza, znajdującego się w kolekcji biblioteki wprowadza się do rekordu egzemplarza.

Informacje odnoszące się do poziomu bibliograficznego zawierają: kompozytora, tytuł wydawcy, obsadę, numer wydawniczy oraz format. Informacje typowe dla poziomu egzemplarza zawierają: siglum właściciela, syganturę lub numer inwentarzowy, naniesienia rękopiśmienne, informacje dotyczące poprzednich właścicieli, opraw i pieczęci własnościowych lub proweniencyjnych. Pola MARC w rekordzie egzemplarzy są połączone przez $3.

### Kiedy wprowadzić nowy rekord (dla druków muzycznych)

RISM traktuje każdy rękopis jako pozycję unikalną i dlatego też każdy rękopis posiada swój własny rekord RISM. Należy zwrócić uwagę na to, że w Muscat jest ponad 125 000 rekordów druków muzycznych, zatem istnieje duża szana, że rekord dla źródła wydanego przez 1800 rokiem już istnieje, dzięki czemu katalogerzy mogą zauważyć znaczące różnice między katalogowanym źródłem a istniejącym rekordem, co przekłada się na konieczność stworzenia nowego rekordu. Natomiast materiały drukowane różnią się od rękopisów tym, że wiele egzemplarzy tego samego wydania można opisać za pomocą jednego rekordu (poprzez dodanie rekordu egzemplarza i informacji typowych rozróżniajacych dla danego egzemplarza).

Poniżej zamieszczono wskazówki, które pomogą w ustaleniu, które warianty uzasadniają tworzenie nowego rekordu. (W tej części korzystano obszernie z dokumentu [Katalogowanie opisowe zbiorów specjalnych (zbiory muzyczne)](http://rbms.info/dcrm/))

**Nowy rekord jest konieczny**, jeżeli opisywana pozycja wykazuje jedną lub więcej z następujących różnic w stosunku do rekordu RISM:

- **Inna treść**: Różnice w tytule lub autorach/współautorach. Strefa wydania, która wykazuje korekty, rewizje, rozszerzenia, uproszczenia, lub włączenie materiałów uzupełniających.
- **Inny wydawca.**
- **Inny układ druku**: Zmiany w numerach wydawniczych (z wyjątkiem numerów zastępczych). Zmiany w objętości. Zmiana w zakresie bibliograficznym lub muzycznym. Różnice w zakończeniach pięciolinii i w kustoszach (wykazane w wyniku porównania wielu egzemplarzy).
- **Inny status wydania**: Usunięto lub wymieniono oryginalną stronę tytułową. Oryginalne wydanie nut wydano w okładce nowego wydawcy zawierającej więcej informacji niż podano na stronie tytułowej. Strona tytułowa serii jest nowa. Na oryginalnej strefie wydania, dystrybucji, produkcji itd. znajduje się informacja o nowym wydawcy.
- **Inny numer wydawniczy lub numer wydawcy**.

**Nie należy tworzyć nowego rekordu**, jeżeli opisywana pozycja wykazuje jedną z poniższych różnic. Jeżeli opisywana pozycja posiada _więcej niż jedną_ z poniższych różnic, należy zdecydować, czy nowy rekord jest konieczny.

- Inna strefa oznaczenie druku: na przykład, „Piąty wydruk”
- Inna drukarnia lub wytwórca, lecz ten sam wydawca
- Inna data druku, lecz ta sama data wydania
- Inna obwoluta wydawcy, która nie zawiera dowodów istnienia odrębnej jednostki wydawniczej (np. zmiana koloru materiału)
- Inna oprawa wydawcy
- Inne reklamy lub katalogi wydawcy (chyba, że stanowią integralną część wydania)
- Poprawki dokonane w trakcie druku nakładu (poprawki dokonane w trakcie druku)
- Obecność lub brak erraty

Powyższe wytyczne oznaczają, że pojedynczy rekord może opisywać wiele nakładów, korekt, wariantów opraw odnosząc się do jednego wydania lub nakładu. W danych dla egzemplarza, można wprowadzić szczegóły na temat wariantów i informacji identyfikujących dany egzemplarz.

#### Przykłady

Druk o numerze RISM 1001031016: Beethoven, „Adelaide” op. 46, niedatowany, Bonn, N. Simrock, tekst w języku niemieckim i francuskim. Błąd w pisowni na stronie tytułowej: „à une vois [!] Seule”.

1. Egzemplarz 1: Ta sama informacja o wydaniu, lecz błąd w pisowni poprawiono. Sama ta okoliczność nie uzasadnia tworzenia nowego rekordu, lecz pojawia się dodatkowy tekst w języku włoskim. **Nowy rekord jest wymagany** (inna treść/rozszerzenie). Wynik: 1001031017

2. Egzemplarz 2: Sytuacja podobna jak w przypadku egz. 1, lecz na stronie tytułowej odbito cenę. **Nie należy tworzyć nowego rekordu** (brak dowodu istnienia odrębnego wydawnictwa/odrębnej jednostki wydawniczej). Dodaj egzemplarz i podaj informację o cenie w danych o egzemplarzu.

3. Egzemplarz 3: Taki jak numer RISM 1001031016 (lecz poprawiono błąd w pisowni), ale podany jest dodatkowy wydawca: „chez L. PLATTNER à ROTTERDAM." **Nowy rekord jest wymagany** (inny status wydania). Wynik: 1001031022

Druk o numerze RISM 990044663: Mozart, Quartets, Bonn, Köln, N. Simrock.

1. Egzemplarz 1: Ten sam tytuł, ale nalepka została naniesiona na strefę wydania: Köln, P.J. Simrock. Możesz zobaczyć, że etykieta przykrywa informacje o Bonn/Köln. **Nowy rekord jest wymagany** (inny status wydania: na oryginalnej strefie wydania, znajduje się informacja o nowym wydawcy). Wynik: 1001141767

Druk o numerze RISM 990024126: Gyrowetz, Symphonies, op. 9. Rekord RISM prezentuje zbiór wielu symfonii. Każda symfonia jest dostępna jako oddzielne wydanie z samodzielnymi numerami wydawniczymi, jako _livres_ 1, 2 i 3.

1. Opcja 1: szybkie rozwiązanie: jeżeli Twoja biblioteka posiada jedną z symfonii zbioru, możesz wybrać **Dodaj egzemplarz** i w polu „Posiadany materiał”, wskazać którą symfonię (livre) posiadasz.
2. Opcja 2: lepsze rozwiązanie, które zajmie jednak więcej czasu: **Powiadomić Editorial Center** o tym rekordzie, a my podzielimy rekord na trzy rekordy, po jednym dla każdej symfonii. Następnie należy dodać rekord egzemplarza do rekordu symfonii, którą biblioteka posiada.

### Znormalizowane tytuły dla druków muzycznych

#### Tytuły charakterystyczne

Druki muzyczne zawierają inne tytuły znacznie częściej niż rękopisy muzyczne. Przy katalogowaniu druków muzycznych w polu **Tytuł ujednolicony (240)** należy przestrzegać następujących zasad:

1. **Pisownia**

Tytuły ujednolicone należy wprowadzać stosując współczesną ortografię, lecz nie należy nadmiernie korygować uzusu archaicznego lub dialektu/regionalizmów. Częste zmiany to zmiana _v_ na _u_, _i_ na _j_, Dodatkowe warianty można wprowadzić w polu **Tytuł dodatkowy (730)**.

##### Przykłady:

- na
 - : Tytul widniejący na źródle: Musicalische Grab=schrifft. Tytuł ujednolicony: Musikalische Grabschrift
 - Rekord bibliograficzny wobec danych dla rekordu egzemplarza


2. **Uzyskiwanie tytułu ujednoliconego z tytuły charakterystycznego**

Tytuły ujednolicone winny składać się tytułu druku aż do miejsca naturalnej przerwy, często przecinka, kropki lub oznaczenia autora, instrumentacji, numeru lub stopki wydawniczej. Czasami charakterystyczny tytuł znajduje się na innej stronie niż strona tytułowa.

##### Przykłady

- ID RISM nr 990003743
   - Tytuł widniejący na źródle: Vezzo di perle musicali modernamente conteste alla regia sposa effigiata nella sacra cantica; opera ventesima terza
   - Tytuł ujednolicony: Vezzo di perle musicali

- ID RISM nr 990006458
   - Tytuł widniejący na źródle: Novo giardino de concerti a quattro voci, per cantare a due chori con due voci, e due tromboni, o altri stromenti, o voci, secondo la comodità de cantori ... nel quale li contengono alquante antifone del cantico della Beata Virgine, di alcune solennità principali del anno, & altri motetti, con il basso principale per l'organo, opera undecima
   - Tytuł ujednolicony: Novo giardino de concerti

#### Tytuły generyczne

Standardowe wytyczne RISM dla tytułów generycznych mają zastosowanie (patrz **Tytuł ujednolicony (240)**), ale pamiętaj, że w starszych stopkach wydawniczych są często cytowane w literaturze jak by były tytułami charakterystycznymi. Do wprowadzania takich tytułów w ujednoliconej formie służy pole **Tytuł dodatkowy (730)**. Wskazówki można znaleźć w takich opracowaniach jak Grove i MGG, oraz hasłach wzorcowych [Library of Congress](http://id.loc.gov/authorities/names.html) lub Jeżeli tytuł wskazuje, że opisywana pozycja posiada afiliację z inną, poprzez oznaczenie takie, jak libro/Buch/livre lub Teil/part/tomus, należy wprowadzić komponent w języku oryginalnym (stosując standardową pisownię) oraz numer arabski występujący po tytule.

##### Przykłady

  - ID RISM nr 990048285
    - Tytuł widniejący na źródle: CANTVS \| IOANNIS PETRALOYSII \| PRAENESTINI \| Missarum cum quatuor, quinque, & sex vocibus. \| LIBER DVODECIMVS. \| Nunc primum in lucem editus. \| VENETIIS, Apud Haeredem Hieronymi Scoti. MDCI
    - Tytuł ujednolicony: Missarum, liber 12
    - Tytuł dodatkowy: 6 Masses

  - ID RISM nr 993000147
    - Tytuł widniejący na źródle: Ander Theil \| Der Preussischen \| Fest-Lieder/ \| Von Ostern an biß Advent \| Mit 5/ 6/ 7/ 8. Tytuł widniejący na źródle: Ander Theil \| Der Preussischen \| Fest-Lieder/ \| Von Ostern an biß Advent \| Mit 5/ 6/ 7/ 8. \| JOHANNIS ECCARDI MULHUSINI THURINGI, \| vnd \| JOHANNIS STOBAEI GRUDENTINI BORUSSI. \| Beyder Chur: vnd Fürstlicher Brandeb. Capell= \| meistern in Preussen. \| DISCANTVS. \| Gedruckt zu Königsberg durch Johann Reusnern An: 1644.
    - Tytuł ujednolicony: Preussische Festlieder, Teil 2


### Wiele kopii/egzemplarzy w jednej instytucji

Jeżeli Państwa instytucja posiada wiele egzemplarzy tego samego drukowanego wydania, należy stworzyć osobny rekord dla każdego egzemplarza.

### Kopie mikrofilmowe

Kopie mikrofilmów druków muzycznych nie są dodawane jako oddzielne rekordy egzemplarzy, ale są opisywane wraz z informacjami o egzemplarzach, które stanowią oryginał druku, na podstawie którego stworzono mikrofilm. Powiadom Editorial Center jeżeli chcesz dodać swoją kopię mikrofilmową, ale nie możesz edytować rekordu egzemplarza. Linki opisujące mikrofilm w lokalnym katalogu instytucji mogą zostać dodane jeśli są dostępne. Jesli mikrofilm jest dostępny cyfrowo, link można dodać do pola Zasób zewnętrzny (856).

#### Przykłady
- ID RISM nr 990052954, egzemplarz w B-Bc:  
  Mikrofilm dostępny w Niemieckim Archiwum Historii Muzyki (D-Kdma)
- ID RISM nr 1000000576, egzemplarz w D-B:  
  Cyfrowa kopia mikrofilmu dostępna w zasobach cyfrowych i katalogu Chorwackiej Akademii Nauk i Sztuk DiZbi.HAZU


### Podział i łączenie rekordów

#### Kontekst
Pierwsze projekty RISM w latach 1950-1970 dotyczyły druków muzycznych. Podjęto wiele uproszczeń związanych z wyzwaniem zestawienia danych z kart katalogowych z międzynarodowej sieci instytucji współpracujących z RISM i ograniczeniami przestrzeni w drukowanych katalogach RISM. Woluminy publikowane w ramach serii RISM A/I, B/I, and B/II ujmowały w jednym rekordzie często wiele wydań, wskazując właściwości różnicujące, ale bez ich dalszego opracowania. Jednocześnie zdarzało się, że współpraca z wieloma katalogerami generowała nieświadomie wiele opisów tego samego wydania, znajdującyego się w różnych lokalizacjach.

Dzisiejsze środowisko online daje elastyczność opisu jednego wydania za pomocą jednego rekordu. Oznacza to, że wspólne rekordy opisujące wiele edycji powinny zostać rozdzielone, a wielokrotne opisy tego samego wydania połączone.

##### Podział rekordów

Rekord musi być podzielony, jeżeli istnieją dowody, że w jednym rekordzie opisano wiele odrębnych edycji. Zamysłem samodzielengo wydania jest to, że wydawca opracował je intencjonalnie jako wydanie i w takiej postaci było dostępne na rynku. W rezultacie konsumenci (i późniejsze biblioteki) mogli samodzielnie nabyć wydanie, z lub bez innych edycji w serii lub zestawie.

Możesz rozpoznać obecność odrębnych edycji za pomocą wskazanych poniżej właściwości, jakie zauważysz w rekordach.

W polu **Tytuł w źródle (245)** często wspomniane jest wiele części lub kluczy:
- Concerto [A (B, Es)] à flûte principale ... N\|o 1 (2, 3)
- Sinfonie [C, F, A] à grand orchestre
- Concert pour la flûte traversière ... libro I(-VI)
- Divine harmony. Six select anthems … (Divine harmony. The 2\|d collection being select anthems ...)

W polu **Numer wydawniczy (028)** wylistowane będzie wiele numerów wydawniczych z kolejnymi numerami w nawiasach:
- 1192
- (1198)
- (1199)
- (1217)
- (1218)

W polu **Uwaga ogólna (500)** lub w informacji **egzemplarza** podana będzie informacja o wielu wydaniach, zazwyczaj w języku niemieckim lub angielskim:

- Wiele wydań
- GB-Lbl (2 verschiedene Ausgaben)

W rekordzie **egzemplarza** są podane zazwyczaj informacje o przechowywaniu określonej części lub woluminu, a język tej adnotacji będzie zgodny z językiem tytuły wydania.

- F-Pc K-733 [libro II]
- D-F Mus. pr. Q 55/349 [livre 1]
- CH-Bu [2., 3. Buch]

W przypadku podziału rekordów, numer serii A/I lub B/I RISM jest przenoszony do wszystkich nowych rekrodów.

##### Łączenie rekordów

Katalogerzy powinny być świadomi, że w bazie czasami można znaleźć duplikaty. Niektóre duplikaty swoje początki mają w drukowanych seriach RISM A/I lub B: pasticcia lub inne dzieła wydane przez kilku autorów wpisywano pod wieloma kompozytorami, podczas gdy wydanie zaklasyfikowane w serii B/I również było publikowane w serii A/I, więc było po prostu dwukrotnie dodane w ramach długiej listy. Ponadto niekiedy katalogerzy nieumyślnie tworzą duplikaty już istniejących rekordów.

Zduplikowane rekordy nie są dozwolone i muszą być scalone po zidentyfikowaniu. Podczas łączenia rekordów obowiązują kryteria dotyczące tego, jaki rekord będzie ostateczny i jaki rekord zostanie połączony. Pierwszeństwo nadaje się rekordowi z serii A/I lub B/I (zazwyczaj możliwe do zidentyfikowania za pomocą numeru identyfikacyjnego RISM, który zaczyna się od 990 lub 993) oraz starszy rekord jest preferowany wobec nowszego (można zweryfikować przez datę utworzenia rekordu). Egzemplarze są przenoszone do finalnego rekordu bibliograficznego i jeśli na podstawie tego źródła stworzono rekord bibliograficzny, egzemplarz wykorzystywany jest jako egzemplarz kontrolny. Notatka taka jak „Ten rekord został scalony z ID RISM nr Notatka taka jak „Ten rekord został scalony z ID RISM nr XXX” jest zawsze uwzględniany w celu śledzenia historii starych numerów RISM.


##### Procedura

Podziały i łączenie rekordów może być przeprowadzane wyłącznie przez Editorial Center w trybie ad hoc. Jeśli zauważysz przypadek, kiedy rekordy powinny zostać podzielone lub połączone, skontaktuj się z Editorial Center.

#### Wydania z serii B

Editorial Center zaimportowało automatycznie rekordy z serii A/I i B/I. Podczas gdy dalszy autmatyczny import jest planowany dla innych woluminów z serii B, jest mile widziane i pożądane, aby współpracujący z RISM dodawali ręcznie wydania z serii B. Podczas gdy dalszy autmatyczny import jest planowany dla innych woluminów z serii B, jest mile widziane i pożądane, aby współpracujący z RISM dodawali ręcznie wydania z serii B. Robiąc to, uzupełnij pole **Seria RISM (510)** w celu wskazania, w której serii znajduje się dane wydanie. Powiadom Editorial Center o takich uzupełnieniach, abyśmy mogli dodać inne egzemplarze instytucji zgodnie z opisami w woluminach serii B.     
