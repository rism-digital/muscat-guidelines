### Dobre praktyki RISM

Ta sekcja omawia dobre praktyki katalogowania do RISM; tj. praktyki, które nie zostały omówione w wskazówkach, ale mimo to przyczyniają się do ....

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

Frequently, important information—such as names of composers or titles of pieces—is not always named on the source itself. It is sometimes possible to make identifications based on the secondary literature, reference sources, other RISM records, or archival sources. If you draw upon such resources, always be clear in the record about what you used to make the identification: name the resource or source in RISM (with siglum, shelfmark, and RISM ID number) in a **General note (500)** and add a **Bibliographic reference (691)** if appropriate. Make sure it is clear for later RISM users how you came to your conclusions. More detailed, explanatory information not relevant for the public can be included in an **Internal note (599)** if needed.

#### 5. Creating records based on descriptions from printed catalogs or online library catalogs

Sometimes it is not possible to access the source in person and the only description available is in a printed catalog, catalog of works, or online library catalog. Such descriptions may be used as the basis of a RISM record. When doing so:

- Include a **General note (500)** that identifies the source of information, such as "Record based on description in YouV"
- Link to the source of information in the field **Catalog of works (690)**, **Bibliographic reference (691)**, or **External resource** (856) as appropriate
- In the field **Record origin (980)**, subfield **Material examined**, select **Material not examined**

#### 6. The shared cataloging environment of printed music

Bibliographic records for printed editions exist in a shared cataloging environment where multiple libraries have editing rights to the same record. This differs from manuscripts, which are unique to the holding library. Due to the shared environment, care must be taken so that the implications of adding or deleting information from core bibliographic records is thought through.

Catalogers should not remove information from the core record if it is correct. Administrative information is stored in the records that can explain decisions made by the Editorial Center and the relationship to other records. Never delete a note that indicates that a record was merged with another record. Do not delete or edit data in the fields **Initial entry in A/I (775)**, **Local number (035)**, or **RISM series (510)**.

If a record has already been revised by another working group (evident by the presence of a library's siglum and shelfmark in the field **Source of description note (588)**), use cataloger's judgement as to whether further revision is necessary. If you make further changes, make it clear in the note what revisions you contributed.

If your copy is incomplete, revisions might still be possible, but make it clear in the **Source of description note (588)** that your copy is incomplete.

If you wish to edit a record that was previously described using an incomplete copy, it must first be ensured that the accurate material information is preserved in the holdings record of the library with the incomplete copy. The Editorial Center can assist with transferring data to holdings records.
