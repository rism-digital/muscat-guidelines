### Odpowiedzi na częste pytania

Ta część zawiera informacje o Muscacie, które nie są związane z wytycznymi dotyczącymi katalogowania.

#### 1. Gdzie mogę znaleźć tutoriale na temat programu Muscat?

Linki do wszystkich tutoriali znajdują się na stronie programu Muscat [RISM Editorial Center](https://rism.info/community/muscat.html):

#### 2. Jak mogę skontaktować się z innymi użytkownikami Muscat?

Wszelkie błędy, pytania, komentarze i sugestie można zgłaszać w dowolnym momencie na adres [muscat@rism.info](mailto:muscat@rism.info).

**[RISM Muscat](https://groups.google.com/forum/#!forum/rism-muscat)**, grupa Google, jest oficjalną grupą dyskusyjną Muscat, do której należy każdy użytkownik Muscat. Oficjalne komunikaty od Editorial Center i programistów Muscat rozpowszechnia się wyłącznie za pośrednictwem tej grupy. Ponadto, wszystkich użytkowników Muscat zachęca się do zadawania pytań lub podnoszenia tematów do dyskusji. Nie ma potrzeby posiadania konta Google.

Istnieje również kanał dyskusyjny na Slack:    
[https://rismcommunity.slack.com/](https://rismcommunity.slack.com/)

#### 3. Czy cała literatura pomocnicza w podawana w Muscat znajduje się w Biurze Editorial Center?

Nie, w naszym biurze znajduje się tylko literatura oznaczona jako „HB” lub „Handbibliothek” lub „RISM-ZR”, co w Muscat oznaczone jest w Polu uwag miejscowych (599 $a) jako pozycja dostępna na miejscu. Materiały te mają służyć wszystkim współpracownikom RISM, więc jeśli mamy publikację, która może być pomocna, daj nam znać, a my postaramy się zdobyć to, czego potrzebujesz. Nawet jeśli poszukujesz publikacji, której nie mamy w biurze, napisz do nas a my postaramy się pomóc uzyskać do stęp do niej.

#### 4. Co robić, gdy zapomnę hasła lub chcę je zmienić?

Skontaktuj się z nami, jeśli zapomnisz hasła. Możesz zmienić hasło klikając na swoją nazwę użytkownika (w prawym górnym rogu w Muscat).

#### 5. Czy mogę pokazać system Muscat moim kolegom? Czy mogę zademonstrować system Muskat na konferencjach lub warsztatach?

Tak, jak najbardziej! Wersja szkoleniowa Muscat jest dostępna dokładnie w tych celach na stronie [https://muscat-training.rism.info](https://muscat-training.rism.info/). Wszyscy użytkownicy Muscat mogą się tam zalogować za pomocą swoich danych osobowych. Istnieje również 99 kont szkoleniowych („training01@rism.info” do „training99@rism.info”) dostępnych dla użytkowników indywidualnych. Można korzystać z każdego z tych kont szkoleniowych. Prosimy o kontakt z RISM Editorial Center w celu uzyskania aktualnego hasła. W wersji szkoleniowej można wszystko dodawać, edytować lub usuwać. Muscat jest regularnie aktualizowany, oznacza to, że rekordy utworzone w wersji szkoleniowej zostaną usunięte po tych aktualizacjach. Nowe rekordy lub zmiany na serwerze szkoleniowym nie są przekazywane do głównego programu Muscat.

#### 6. Co to znaczy, że w historii modyfikacji, „[system]” został wymieniony jako autor?

To jest edycja systemu. Możesz zobaczyć przykład edycji systemowej, jeśli jedno z indeksowanych pól związanych z Twoim rekordem uległo zmianie. Zmiana w rekordzie hasła wzorcowego zarejestruje się również jako zmiana w Twoim rekordzie. Zmiany prowadzone przez skrypty utrzymujące program są również rejestrowane jako edycje systemowe.

#### 7. Gdzie są publikowane rekordy Muscata?

Rekordy w Muscat, które posiadają status **opublikowany** pojawią się w [katalogu RISM](https://opac.rism.info/), rozwijanego przez [Bayerische Staatsbibliothek](https://www.bsb-muenchen.de/) (Monachium, Niemcy) i w [RISM Online](https://rism.online/), rozwijanym przez [Digital Center](https://rism.info/digital-center.html) (Berno, Szwajcaria).

Poza Muscatem, rekordy opublikowane dostępne są przez [SRU downloader](https://github.com/rism-international/sru-downloader), w katalogu RISM przez link „Show MARCXML”, comiesięczny dump danych katalogu RISM oraz poprzez API RISM Online.

#### 8. Kiedy rekordy z Muscat pojawiają się w publicznych katalogach?

The [RISM Catalog](https://opac.rism.info/) is updated once a month after the first of each month. Rekordy są widoczne kilka dni później. [RISM Online](https://rism.online/) is updated once a day.

#### 9. Co zrobić, jeśli źródło w RISM nie jest już w rękach instytucji przechowującej, wskazanej w rekordzie RISM?

Używaj siglum **XX-NN** w sytuacjach, w których obecna lokalizacja źródła jest nieznana, np. gdy źródło było zdeponowane w instytucji, ale zostało odebrane i obecnie znajduje się w rękach prywatnych. Zdarza się to rzadko. Jeśli źródło potrzebuje tego siglum, prosimy o kontakt z Editorial Center.

#### 10. Jakie są wymagania techniczne programu Muscat?

- Muscat jest niezależny od platformy i działa zarówno na komputerach Mac, jak i PC.
- Dostęp odbywa się poprzez adres URL. W związku z tym do korzystania z dostępu niezbędne jest połączenie z Internetem.
- Muscat najlepiej sprawdza się na ekranach o wymiarach co najmniej 1366 x 768 pikseli.
- Muscat jest dostosowany do wyszukiwarki Firefox i Chrome. Nie należy używać Internet Explorera!

#### 11. Jakie są niektóre techniczne aspekty programu Muscat?

- Muscat działa na otwartym kodzie źródłowym. Kod źródłowy jest dostępny pod adresem repozytorium [GitHub](https://github.com/rism-ch/muscat).
- Muscat jest aplikacją Ruby on Rails.
- Do renderowania incipitów muzycznych za pośrednictwem MEI wykorzystuje się [Verovio](https://www.verovio.org/pae-editor.html).
- Jako wyszukiwarka służy Solr.
- Muscat posiada an [SRU service](https://github.com/rism-ch/muscat/wiki/SRU) oraz [SRU downloader](https://github.com/rism-international/sru-downloader) do odzyskiwania rekordów MARCXML.
- Muscat obsługuje Unicode (UTF-8).
- Wersjonowanie umożliwia katalogerom przeglądanie zmian wprowadzonych do rekordów.

Więcej informacji o rozwijaniu Muscatu odnaleźc można na [stronie RISM Digital Center](https://rism.digital/tools/muscat.html).
