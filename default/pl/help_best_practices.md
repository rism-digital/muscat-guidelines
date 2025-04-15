### Dobre praktyki RISM

Ta sekcja omawia dobre praktyki katalogowania do RISM; tj. praktyki, które nie zostały omówione w wskazówkach, ale mimo to przyczyniają się do dokładnego, rzetelnego i zrozumiałego opracowania rekordów.

#### 1. Pola tekstowe i pola indeksowane

W przypadku podawania w swoim wpisie nazwiska osoby lub instytucji (np. w polu uwag), należy to nazwisko wpisać również w indeksowane pola **Dodatkowa osoba (700)** lub **Dodatkowa instytucja (710)**.

To samo dotyczy cytowania literatury pomocniczej: w przypadku powoływania się na publikację w polu uwag, należy wpisać ją również w polu **Odniesienie bibliograficzne (691)**.

Z drugiej strony należy upewnić się, że znaczenie zaindeksowanej nazwy lub instytucji jest jasne, na przykład poprzez wyjaśnienie w polu uwag.

#### 2. Przytaczanie literatury pomocniczej

Informacje, których brakuje w źródle, mogą zostać dodane w rekordzie RISM, ale należy podać literaturę pomocniczą. Na przykład, jeśli kompozytor rękopisu jest znany poprzez artykuł lub jeśli rok wydania druku muzycznego podano w opracowaniu poświęconemu wydawcy, źródło informacji powinno być jasno określone w polu **Uwaga ogólna (500)** i **Odniesienie bibliograficzne (691)**.

#### 3. Adresy URL i linki do zasobów zewnętrznych

Zawsze należy używać permalinków przy linkowaniu do zdigitalizowanych źródeł muzycznych, w szczególności w polu **Zasoby zewnętrzne (856)**.

W celu wprowadzenia odniesienia do strony www, nie należy wpisywać adresu URL w polu uwag. Zasób należy wprowadzić jako odniesienie bibliograficzne. Co należy wprowadzić w hasłach wzorcowych ** Literatura pomocnicza**. Następnie dodać rekord w polu **Odniesienie bibliograficzne (691)** i podając tytuł skrócony w polu uwag. Zapewnia to użytkownikom dostęp do pełnych informacji bibliograficznych, i jeśli URL zmieni się, aktualizacja jest potrzebna tylko w bazie haseł wzorcowych **literatury pomocniczaj**.

Dla książek znalezionych w Google Books lub innych repozytoriach cyfrowych, zawsze stwórz rekord bibliograficzny w bazie haseł wzorcowych **Literatura pomocnicza** dla samej książki, a nie dla cyfrowego zasobu. To znaczy, cytujemy książkę, a nie Google Books.

Dla baz danych wymienionych jako literatura pomocnicza, jako wygoda dla naszych użytkowników, możesz przytoczyć bazę danych w polu **Odniesienie Bibliograficzne (691)**, a następnie podać bezpośredni link do wpisu w bazie danych za pośrednictwem pola **Zasób zewnętrzny (856)**.

Jeśli chcesz odnieść się do źródła muzycznego, które jest zdigitalizowane, ale nie znajduje się w RISM, skontaktuj się z Editorial Center RISM w celu omówienia kwestii dodania źródła.

#### 4. Dokonywanie identyfikacji

Często ważne informacje takie jak kompozytor czy tytuły kompozycji nie zawsze są podane na źródle. Czasami identyfikacji można dokonać na podstawie literatury pomocniczej, źródeł referencyjnych, innych rekordów RISM, a nawet źródeł archiwalnych, do których użytkownik systemu ma dostęp. W przypadku korzystania z takich zasobów, zawsze należy jasno określić w rekordzie, czego użyto do identyfikacji: należy podać nazwę zasobu w polu **Uwaga ogólna (500)** i w razie potrzeby dodać informację w polu **Odniesienie bibliograficzne (691)**. Dla kolejnych użytkowników RISM musi być jasne, w jaki sposób osoba wprowadzająca dane do systemu doszła do swoich wniosków. W razie potrzeby bardziej szczegółowe, wyjaśnienia, które nie są istotne dla zewnętrznych użytkowników, mogą być zawarte w adnotacji **Pole uwag miejscowych (599 $a)**.

#### 5. Tworzenie rekordów na podstawie opisów z drukowanych katalogów lub katalogów bibliotek online

Czasamie nie jest możliwe dotarcie do źródła osobiście i jedyny dostępny opis znajduje się w katalogach drukowanych, monograficznych katalogach dzieł lub katalogach online. Takie opisy mogą być wykorzystywane jako podstawa rekordu RISM. Czyniąc to:

- Dodaj w polu ** Uwaga ogólna (500)** informację o identyfikującym źródle, takie jak „Zapis oparty na YouV”.
- Źródło, na podstawie którego stworzono rekord dodaj w polach: **Katalog utworów**, **Odniesienie Bibliograficzne (691)** lub w **Zasób zewnętrzny (856)** stosownie do przypadku.
- In the field **Record origin (980)**, subfield **Material examined**, select **Material not examined**

#### 6. The shared cataloging environment of printed music

Bibliographic records for printed editions exist in a shared cataloging environment where multiple libraries have editing rights to the same record. This differs from manuscripts, which are unique to the holding library. Due to the shared environment, care must be taken so that the implications of adding or deleting information from core bibliographic records is thought through.

Catalogers should not remove information from the core record if it is correct. Administrative information is stored in the records that can explain decisions made by the Editorial Center and the relationship to other records. Never delete a note that indicates that a record was merged with another record. Do not delete or edit data in the fields **Initial entry in A/I (775)**, **Local number (035)**, or **RISM series (510)**.

If a record has already been revised by another working group (evident by the presence of a library's siglum and shelfmark in the field **Source of description note (588)**), use cataloger's judgement as to whether further revision is necessary. If you make further changes, make it clear in the note what revisions you contributed.

If your copy is incomplete, revisions might still be possible, but make it clear in the **Source of description note (588)** that your copy is incomplete.

If you wish to edit a record that was previously described using an incomplete copy, it must first be ensured that the accurate material information is preserved in the holdings record of the library with the incomplete copy. The Editorial Center can assist with transferring data to holdings records.
