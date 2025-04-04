# Rekordy i typy rekordów

Nowy rekord można utworzyć w Muscat poprzez wybranie odpowiedniego szablonu lub przez skopiowanie istniejącego rekordu. Linki do obydwu znaleźć można na stronie dla Źródeł lub w pełnym widoku rekordu.

## Szablony

Muscat oferuje możliwość wyboru szablonu, w zależności od rodzaju katalogowanego źródła. Szablon zawiera tylko te pola, które są potrzebne do skatalogowania danego źródła.

Jeżeli zauważysz, że rekord skatalgoowany jest w nieodpowiednim szablonie, poinformuj RISM Editorial Center w celu zmiany szablonu.

### Dostępne szablony

Rekord dla **Kolekcji** (rekord macierzysty) jest stosowany, gdy źródło składa się z wielu pozycji. Każda pozycja kolekcji jest dodawana jako **Pozycja w tym źródle** (rekord dziecko) i połączona z rekordem kolekcji. Rękopisy i druki muzyczne mogą również funkcjonować jako **Samodzielne pozycje** i nie być częscią kolekcji.

**Klocek introligatorski** składa się z pozycji powstałych niezależnie, które wtórnie zostały ze sobą połączone zazwyczaj przez właściciela czy instytucję. Klocek introligatorski może zawierać zarówno woluminy złączonych pojedynczych druków jak ja woluminy połączonych druków z rękopisami.

Manuscripts are unique to a library and can only be owned by one institution. Druki muzyczne posiadają egzemplarze, co oznacza że wiele bibliotek jest właścicielem kopii (egzemplarzy) danego wydania.

Takie publikacje są czasami nazywane zbiorami tekstów pieśni, książkami kieszonkowymi (często oznaczanymi tak na źródle) lub śpiewnikami. Najczęściej są to książki, które zawierają słowa opery lub innej kompozycji wokalnej, ale mogą to być również kolekcje źródeł tekstowych, takich jak śpiewniki hymnów czy piosenek Bożonarodzeniowych. Szablon dedykowany libretto/tekstowi muzycznemu wykorzystywany jest do źródeł, które zawierają tylko tekst, odnoszący się do śpiewanego wykonawstawa muzycznego.

Szablon dedykowany traktatom jest wykorzystywany do źródeł, które podejmują teoretyczne aspekty muzyki, w tym aspekty kompozycji czy wykonawstwa.

Zarówno szablony dedykowane librettom jak i traktatom mogą zawierać zapis nutowy, a proporcje między zawartością nut do tekstu nie zawsze jest wyraźny.

Następujące szablony są używane w Muscat dla Źródeł. Szablony są kodowane w pozycji 6-7 Lider rekordu MARC.

Materiały rękopiśmienne:
- Rękopisy muzyczne
 - Rekord kolekcji (rekord macierzysty) [LDR: dc]
   - Indywidualny wpis pozycji w kolekcji (rekord dziecka) [LDR: da]
 - Pojedynczy rękopis muzyczny [LDR: dm]
- Libretta/Teksty pieśni
 - Rekord kolekcji (rekord macierzysty) [LDR: dc]
   - Indywidualny wpis pozycji w kolekcji (rekord dziecka) [LDR: ta]
  - Pojedynczy rękopis libretta/Tekstu pieśni [LDR: tm]
- Traktaty
   - Rekord kolekcji (rekord macierzysty) [LDR: dc]
    - Indywidualny wpis pozycji w kolekcji (rekord dziecka) [LDR: ta]
   - Pojedynczy rękopis traktatu [LDR: tm]

Materiały drukowane:
- Druki muzyczne
 - Rekord kolekcji (rekord macierzysty) [LDR: cc]
   - Indywidualny wpis pozycji w kolekcji (rekord dziecka) [LDR: ca]
 - Pojedynczy druk muzyczny [LDR: cm]
- Libretta/Teksty pieśni
 - Rekord kolekcji (rekord macierzysty) [LDR: ac]
   - Indywidualny wpis pozycji w kolekcji (rekord dziecka) [LDR: aa]
  - Pojedynczy druk libretta/Tekstu pieśni [LDR: am]
- Traktaty
   - Rekord kolekcji (rekord macierzysty) [LDR: ac]
    - Indywidualny wpis pozycji w kolekcji (rekord dziecka) [LDR: aa]
   - Pojedynczy druk traktatu [LDR: am]

Klocki introligatorskie:
- Klocek introligatorski [LDR: pc]


## Kopiowanie istniejących rekordów

Istnieją dwa sposoby na skopiowanie rekordu.

Można to zrobić na ekranie szablonu: wystarczy wpisać numer RISM w polu „Utwórz z istniejącego źródła”. Wówczas na ekranie ukaże się kopia rekordu w trybie edycji, gdzie można dokonać dowolnych zmian. Przy zapisywaniu skopiowany rekord automatycznie otrzyma nowy numer identyfikacyjny RISM.

Alternatywnie, można skopiować rekord w trybie przeglądania z widoku pełnego rekordu, klikając przycisk „Duplikuj” na pasku bocznym po prawej stronie. Wówczas na ekranie ukaże się kopia rekordu w trybie edycji.

Katalogorze mogą duplikować każdy rekord w Muscat, w tym rekordy, które zostały utworzone przez inną bibliotekę. Jednocześnie, obowiazują zasady uprawnień do trybu edycji rekordów, tzn. jeśli kataloger nie posiada uprawnień do siglum danej instytucji, to nie może zapisać rekordu z danym siglum. Duplikowanie rekordów oszczędza czas podczas katalogowania własnych kolekcji (szczególnie jeśli zawartość jest podobna), ale katalogerzy mogą również korzystać z rekordów utworzonych przez inne biblioteki, w szczególności jeżeli rekordy posiadają liczne incipity muzyczne lub w przypadku katalogowania reprintów, których zawartość jest taka sama lub podobna. Tylko jeden rekord na raz może być powielony.

Kod Plaine & Easie może zostać skopiowany z widoku pełnego rekordu dla każdego rekordu. Powyżej incipitu muzycznego należy kliknąć w link **Kod PAE**, skopiować i wkleić kodowanie incipitu muzycznego, który jest wyświetlany.
