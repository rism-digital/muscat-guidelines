#### **Zasób zewnętrzny (856)**   

Z pola należy korzystać, aby podać link do zewnętrznego zasobu, który bezpośrednio dotyczy opisywanego źródła. 

**Adres URL zasobu zewnętrznego (856 $u)**    
Wprowadzić adres URL zasobu zewnętrznego. Zawsze stosować permalinki. 

**Uwaga o zasobie zewnętrznym (856 $z)**    
Pole wymagane przy wprowadzaniu linku do zasobu zewnętrznego.   
Wprowadzić krótki opis, który wyjaśnia, dlaczego dany adres URL jest istotny w odniesieniu do opisywanego źródła. Należy stosować własny język katalogowania. 

_Przykłady:_  
Egzemplarz zdigitalizowany  
Znak wodny na str. 4  
Strona główna projektu  
Szczegół oprawy  
Rekord bibliograficzny  
Link do rekordu w Bach Digital  
Link do dzieła w Frescobaldi Thematic Catalogue Online  
Wpis/Hasło w rejestrze kościelnym  
Link do numeru identyfikacyjnego RISM Nr 806155758, GB-Lbl Add. 14209 f.23r-27v, skład tego tekstu przez N. Porpora/ a setting by N. Porpora of this text ?   
Zgodne źródło w GB-Ob

**Typ linku (856 $x)**    
Pole to należy wypełnić przy wprowadzaniu linku do zasobu zewnętrznego. Należy wybrać jedno z następujacych:

- **źródło zdigitalizowane** Link jest odsyłaczem do zewnętrznej strony internetowej, która jest zdigitalizowaną kopią opisywanego zasobu. Preferuje się zamieszczanie linku do zasobów instytucjonalnych, ale jeżeli takowy nie jest dostępny wtedy dopuszcza się linki do zasobów zewnętrznych, takich jak Internet Archive czy IMSLP.    
  
_Przykład_  
  :*[  
https://mirador.acdh.oeaw.ac.at/musikarchivspitz/A-SPD\_A15/  
  
](https://mirador.acdh.oeaw.ac.at/musikarchivspitz/A-SPD_A15/)*
- ** Manifest IIIF**: Podlinkowany obiekt jest czytelny dla formatu JSON i obsługiwany przez viewer np. diva.js. Dokument jest osadzony bezpośrednio na stronie internetowej. W wielu przypadkach w linku pojawia się określenie „manifest”, „iiif” lub podobne.  
  
_Przykład_  
  :*[  
https://iiif.lib.harvard.edu/manifests/drs:2820650](https://iiif.lib.harvard.edu/manifests/drs:2820650)*  
  
W przypadku, gdy oba linki są dostępne, zarówno do zewnętrznego viewera, jak i do manifestu IIIF, należy powtórzyć pole i podać oba linki osobno.  
  
_Przykład_  
  :  

  - źródło zewnętrzne: [http://nrs.harvard.edu/urn-3:FHCL.Loeb:537966](http://nrs.harvard.edu/urn-3:FHCL.Loeb:537966)  
Uwaga: wersja zdigitalizowana  
Typ linku: źródło zdigitalizowane  
  - źródło zewnętrzne:[https://iiif.lib.harvard.edu/manifests/drs:2820650](https://iiif.lib.harvard.edu/manifests/drs:2820650)  
Uwaga: manifest IIIF  
Typ linku: manifest IIIF  
  
  
- **Inne: ** Link do innych zasobów, które nie są zasobem opisywanym.  

 

 

#### Rodzaje źródeł zewnętrznych  

**Typ linku 856 $x: źródło zdigitalizowane**  
Należy linkować jedynie do źródła opisanego w rekordzie RISM. Należy stosować jedynie permalinki. W przypadku braku permalinków należy linkować do strony, na której można łatwo znaleźć link do zdigitalizowanego źródła  (takiego jak rekord bibliograficzny w katalogu bibliotecznym). Można dołączyć fragmenty zdigitalizowanego źródła (np. kilka stron), jeżeli w pełni zdigitalizowana wersja nie jest dostępna.

Linki wprowadzone jako nuty zdigitalizowane nuty pojawiają się w filtrze "Muzyka zdigitalizowana" w katalogu OPAC 

(opac.rism.info).

**Typ linku 856 $x: Inne**

Innymi rodzajami źródeł zewnętrznych mogą być źródła wymienione poniżej. Zawsze należy zadbać o to, aby powód dołączenia danego linku był dla użytkownika czytelny, na przykład w **Uwadze ogólnej (500)**.

- **Informacje szczegółowe o źródłach**  
Informacje szczegółowe o źródłach, które prezentują jedynie pewne aspekty formy fizycznej, takie jak znak wodny, oprawa, strona tytułowa lub okładka.   
- **Rekordy katalogowe/bazy danych**  
Obejmują hasła bibliograficzne w katalogach zewnętrznych lub hasła w zewnętrznych bazach danych. Można włączać zewnętrzne, naukowe bazy danych, które zawierają przydatne informacje, lecz należy rozważyć, czy nie lepiej je linkować jako literaturę pomocniczą.
- **Elektroniczne katalogi dzieł, encyklopedie dostępne w trybie online, literatura zdigitalizowana** Na ogół, dla dostępnej w sieci literatury podręcznej, takiej jak katalogi dzieł lub encyklopedie należy używać pól **Literatura pomocnicza (691)** lub **Katalog dzieł (690).** Jednak, jako ułatwienie dla użytkowników, można dodać bezpośredni link do określonego miejsca w zasobie poprzez pole 856.
- **Źródła archiwalne, źródła historyczne**   
Obejmuje zdigitalizowane rejestry lub dokumenty municypalne, zdigitalizowaną korespondencję, zdigitalizowane gazety. Należy upewnić się, czy istotność źródła archiwalnego jest przede wszystkim czytelna w **Uwadze ogólnej (500)**, a dopiero potem podać tutaj bezpośredni link. Dla gazet historycznych, należy wprowadzić nazwę gazety jako literatury pomocniczej, lecz można też wprowadzić link do określonej strony, gdzie artykuł można znaleźć; informację o artykule, np. tytuł i datę artykułu, należy umieścić w uwadze.  
- **Strony internetowe**  
Obejmuje strony internetowe projektu, strony agencji odpowiadających za finansowanie zewnętrzne lub inne istotne strony internetowe.   
- **Inne rekordy RISM**   
Należy podawać link do innego rekordu RISM jedynie wtedy, gdy ten rekord jest bezpośrednio związany z opisywanym źródłem. Należy stosować jedynie permalinki z OPAC-u RISM ([https://opac.rism.info/)](https://opac.rism.info/)). Użytkownik musi wiedzieć, dlaczego rekord jest istotny dla danego źródła. Minimalnym wymogiem jest podanie w uwadze biblioteki przechowującej, sygnatury i numeru identyfikacyjnego RISM. Czasami powiązanie z innym źródłem lepiej jest wyjaśnić w **Uwadze ogólnej (500)**.  
W przypadku podania linków do innych rekordów RISM w innym miejscu w rekordzie, nie ma potrzeby podawać linków do nich w tym polu.   
Nie ma potrzeby w tym miejscu podawać linku do wszystkich konkordancji w RISM; jest to niepotrzebne, ponieważ liczba źródeł w systemie Muscat codziennie rośnie.   
- **Odniesienia do istotnych źródeł znajdujących się w innych bibliotekach (poza RISM).**  
W przypadku, gdy chcemy podać link do źródła, które jeszcze nie znajduje się w RISM, należy rozważyć, czy Państwa grupa robocza może najpierw wprowadzić zdigitalizowane libretto, rękopis lub traktat, czy też najpierw dodać posiadane zbiory do konkretnego druku.  Biuro Centralne RISM bardzo chętnie udzieli pomocy,  jeżeli uznają Państwo, że dane źródło powinno się znaleźć w RISM. Jednak zaleca się korzystać z tej możliwości, jeżeli nie będą Państwo w stanie sami dla tego źródła stworzyć nowego rekordu.  
- **Inne istotne źródła**  
Obejmuje konkordancje, zgodne arie lub części dzieł, źródła, które służyły jako podstawa do stworzenia opisu źródła. Mogą to być linki do obiektów zdigitalizowanych lub linki do katalogów zewnętrznych.