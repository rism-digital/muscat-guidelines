## Catalogare fonti di tipo particolare

Questa sezione descrive come catalogare tipi speciali di fonti: raccolte, volumi compositi, contrafacta, opere compilative, inserti di arie, parodie, materiali misti (manoscritti e fonti a stampa riunite insieme), musica in periodici, musica in pubblicazioni non musicali, libretti, trattati e riduzioni per pianoforte.

### Raccolte

In RISM, una _raccolta_ indica sia un manoscritto intenzionalmente miscellaneo o un’antologia con diverse composizioni, sia un oggetto che contiene due o più composizioni separate. Ciò significa che se un manoscritto di una sonata per pianoforte, ad esempio, contiene alla fine uno schizzo per una fuga, RISM lo cataloga come una raccolta con una scheda madre per l'oggetto intero e schede figlie per la sonata e per la fuga.

Catalogando delle raccolte, tieni conto di quanto segue:

1. La scheda principale (scheda madre) contiene informazioni valide per l’intera raccolta.
2. Ogni informazione che riguarda soltanto una parte della raccolta va inserita nella relativa scheda figlia.

Se le composizioni nella raccolta hanno compositori, organici, tipi di fonte ecc. diversi, non inserirli nella scheda principale.

Per raccolte che comprendono composizioni molto simili, è una buona strategia creare una prima notizia completa e utilizzare la funzione “Duplica” per copiare la scheda. Così, per le schede seguenti dovrai soltanto cambiare alcuni campi come il titolo e i numeri di pagina.

La scheda principale (scheda madre) di una raccolta non può contenere un'altra scheda madre di una raccolta di manoscritti. Scegli piuttosto una gerarchia orizzontale, usando schede individuali e spiegando la struttura, la conformazione o l'organizzazione dell'oggetto in una nota.

### Catalogare volumi compositi

Un **volume composito** consiste di oggetti creati separatamente e rilegati insieme più tardi, solitamente da un possessore o da un'istituzione. Volumi di questo tipo si possono anche chiamare "binders' collection", "binders' volume", "bound sheet music", "bound-with", "collectors' volume", "factitious volume", "nonce volume", "tract volume" (EN), "recueil factice" (FR) o "Sammelband" (DE). There are many other names for such volumes in English: binders' collection, binders' volume, bound sheet music, bound-with, collectors' volume, factitious volume, nonce volume, recueils factices, Sammelband, tract volume.

Vi sono due maniere di catalogare un volume composito. La prima, e la più semplice, è di catalogare separatamente le diverse fonti e indicare per tutte la stessa segnatura; una nota "rilegato con" è qui opportuna. La seconda è di usare il template della scheda per i volumi compositi.

La scheda di un volume composito serve per collegare tutti gli oggetti rilegati insieme in una scheda unica, fornendo all'utente un utile riassunto dell'intero contenuto del volume rilegato.

È opportuno mantenere semplici le schede di volumi compositi. In linea di principio, descrivono semplicemente la rilegatura. Non confondere i volumi compositi con le raccolte; in RISM le "raccolte" sono esclusivamente manoscritte. Inoltre, non confondere i volumi compositi con le edizioni a stampa: un'edizione a stampa è una singola unità bibliografica che è stata pubblicata dall'editore in quanto tale. Sia le raccolte che le edizioni a stampa possono contenere più pezzi. Al contrario, i volumi compositi riuniscono unità disparate: ad esempio, un'antologia di madrigali stampata nel 1604, un manoscritto di un motetto del 1620, e un'edizione a stampa di madrigali del 1615.

Come per le schede principali di una raccolta, l'informazione data nella scheda di un volume composito deve valere per ciascuno dei componenti del volume. Ricorda che ogni informazione dettagliata riguardo al contenuto musicale va inserita nelle relative schede bibliografiche. Non creare schede separate per volumi compositi che compongono a un'unità, ad esempio vari libri-parte rilegati per tipologia di voce; questi vanno descritti in una scheda unica. In molti casi, numerosi campi resteranno vuoti.

Al volume composito si collegano unità manoscritte oppure edizioni a stampa. Il collegamento è fatto in modo diverso:

1. Crea prima la scheda per il volume composito, salvala e prendi nota del numero RISM.
2. Per i manoscritti: nella modalità di redazione della scheda del tuo manoscritto, vai al campo **Notizia principale (773)**. Fai clic sul secondo bottone per cercare il volume composito.
3. Per le edizioni a stampa: nelle informazioni di possesso dell'edizione a stampa, trova il campo **Rilegato con (973)** e fai clic sulla lente d'ingrandimento. Cerca la scheda del volume composito e selezionala.

### Contrafacta

Un contrafactum è un brano vocale il cui testo verbale è stato cambiato, senza significativi interventi sul testo musicale, sottoponendo un testo di carattere sacro a una composizione profana o vice versa. La derivazione è quasi meccanica; vi è poca creatività da parte dell'arrangiatore, ma vi è un cambiamento significativo nella destinazione della musica (ad esempio, da un contesto teatrale a uno religioso).

Nota che RISM considera i contrafacta distinti dalle parodie o dalle messe parodia, che tipicamente implicano una trasformazione più significativa del contenuto musicale.

Presta attenzione ai campi seguenti nella catalogazione di contrafacta. Useremo come esempio la scheda RISM ID no. 300234487, un contrafactum sacro di un'aria dall'opera Il Bellerofonte di Josef Mysliveček.

**Compositore/Autore (100)**

Inserisci il compositore della musica originale.

- Mysliveček, Josef

**Titolo uniforme (240)**

Utilizza il titolo uniforme della composizione originale. Puoi aggiungere **Estratti**. Non utilizzare **Arrangiamento**.

- Il Bellerofonte. Estratti

**Titolo uniforme alternativo (730)**

Se vi è un nuovo, diverso titolo uniforme per il brano in esame, puoi inserirlo qui. Non inserire qui un incipit testuale.

**Soggetto (650)**

Inserisci almeno tre soggetti (o più se necessario), in quest'ordine:\
Contrafacta\
Genere attuale\
Genere originale

- Contrafacta
- Sacred songs
- Operas

**Descrizione sommaria (520)**

Aggiungi una breve descrizione in inglese che spiega la situazione a beneficio degli utenti RISM.

- Sacred contrafactum of an aria from Mysliveček's opera Il Bellerofonte.

**Codice lingua (041)**

Riempi entrambi i sottocampi:\
Lingua del testo cantato (041 $a): Il testo attuale della fonte in esame\
Lingua del testo originale (041 $h): La lingua della composizione originale

- Lingua del testo cantato: Latino
- Lingua del testo originale: Italiano

**Incipit testuale (031 $t)**

Inserisci due incipit testuali (usa il segno + per aggiungere una nuova riga).\
L'incipit testuale del testo attuale\
L'incipit testuale del testo originale, se questo è noto, tra parentesi quadre.

- Alma redemptoris mater, quae pervia caeli
- [Giusti dei che ben vedete]

**Altri campi**

Ogni altro campo, come feste liturgiche e organico, fa riferimento alla fonte in fase di catalogazione, ossia al contrafactum e non alla composizione originale su cui questo è basato.

### Opere compilative

Una compilazione è un'opera nuova e indipendente creata a partire da estratti di una o più altre composizioni, che può anche includere materiale originale. Spesso l'opera risultante appartiene a un genere diverso dalle parti che la costituiscono, ad esempio quando arie o duetti di un'opera teatrale diventano una cantata, oppure estratti di un'opera diventano una suite strumentale. Anche i pasticci rientrano in questa categoria. Sebbene i confini tra compilazione e pasticcio siano a volte fluidi, un pasticcio mostra in genere una delle seguenti caratteristiche: (1) arie, duetti o parti più ampie di opere drammatiche adattate a un nuovo libretto; (2) varie composizioni singole combinate per creare un'opera nuova; o (3) composizioni collaborative concepite come tali fin dal principio.

Un'opera compilativa può essere catalogata in una singola scheda, oppure come una raccolta.

Presta attenzione ai campi seguenti per catalogare opere compilative.

**Compositore/Autore (100)**

Il compositore è sempre **Compilations**.

**Nome aggiuntivo di persona (700)**

Il nome del compilatore può essere aggiunto con la funzione **Curatore**.

Catalogando un'opera compilativa, inserisci il compositore o i compositori del materiale originale e seleziona la funzione **Rimando ad altro compositore**. Inserisci il compositore o i compositori di materiale originale aggiunto e seleziona la funzione **Compositore secondario**.

Catalogando un pasticcio, non inserire compositori come rimandi ad altri compositori. Inserisci piuttosto tutti i compositori come **Compositori secondari**.

**Titolo uniforme (240)**

Inserisci il titolo uniforme della fonte in esame. Per i pasticci, inserisci **Estratti** o **Arrangiamento** se necessario.

**Codice lingua (041)**

Nel campo **Codice lingua** inserisci la lingua della fonte in esame. Se necessario, la lingua dell'opera originale può essere inserita nel sottocampo **Lingua del testo originale**.

**Soggetto (650)**

Il primo soggetto dev'essere **Compilations** e/o **Pasticcios**. Il secondo dev'essere il genere della fonte esaminata. Se si tratta di estratti, puoi aggiungere il genere dell'estratto. **Collaborative compositions** è un'altra possibilità.

**Descrizione sommaria (520)**

Usa questo campo per descrivere in generale la natura della fonte.

<figure>
  Atto I di Amadei, atto II di Bononcini, ouverture e atto III di Händel
  <figcaption>Esempio</figcaption>
</figure>

**Titolo uniforme alternativo (730)**

Inserisci il titolo uniforme della composizione o delle composizioni originali, aggiungendo **Estratti** or **Arrangiamenti** se necessario. Puoi anche inserire altri titoli alternativi.

**Catalogo delle opere (690)**

Puoi inserire il numero di catalogo tanto della compilazione che delle opere originali.

**Incipit testuale (031)**

Inserisci il testo della fonte in esame. Se è noto, inserisci tra parentesi quadre il testo originale.

**Nota generale (500)**

Aggiungi sempre una nota esplicativa, specialmente se sono coinvolte opere di più compositori. Questo permette all'utente di stabilire il collegamento corretto tra i compositori e le varie composizioni utilizzate per creare l'opera compilativa.

**Nota sull'esecuzione (518)**

Aggiungi una nota soltanto se relativa ad esecuzioni dell'opera compilativa in quanto tale.

**Esempi di opere compilative**:

230001408: Una cantata creata a partire da arie d'opera con recitativi di nuova composizione

702000623: Una suite realizzata da estratti di un'opera

700007222: Diverse opere dello stesso compositore usate per creare una nuova cantata

702000642, 702000643: Varie opere di vari compositori usate per creare una nuova suite

452505748: Un'opera-pasticcio consistente di tre atti di tre diversi compositori

### Parodies

Una parodia è una composizione basata su materiale preesistente che risulta in una opera nuova. Nel XIX secolo, il termine acquisisce una connotazione satirica.

Useremo la scheda 150205470 come esempio.

**Compositore/Autore (100)**

Inserisci il compositore della musica nella fonte in esame.

- Weyse, Christoph Ernst Friedrich

**Nome aggiuntivo di persona (700)**

Inserisci il compositore del materiale preesistente e seleziona la funzione Rimando ad altro compositore.

- Rossini, Gioachino

**Titolo uniforme (240)**

Inserisci il titolo uniforme della fonte in esame.

- Dannemark hellige lyd

**Titolo uniforme alternativo (730)**

Inserisci il titolo del materiale preesistente. Aggiungi Estratti se necessario. Non usare Arrangiamento o Variazioni.

- Tancredi. Estratti

**Soggetto (650)**

Inserisci Parodies come primo soggetto. Come secondo soggetto, inserisci il genere della fonte in esame, e come terzo il genere del materiale preesistente.

- Parodies
- National anthems
- Operas

**Codice lingua (041)**

Inserisci la lingua della fonte in esame nel sottocampo Lingua del testo cantato. Inserisci la lingua del materiale preesistente nel campo Lingua del testo originale.

- Danese
- Italiano

**Incipit testuale (031)**

Inserisci l'incipit testuale della fonte in esame. Se il testo originale è noto, inseriscilo tra parentesi quadre.

- Dannemark hellige lyd
- [Di tanti palpiti]

**Altri campi**

Ogni altro campo, ad esempio una nota su un'esecuzione, si riferisce soltanto alla fonte in esame.

### Inserti di arie

Opere che comprendono inserti di arie (anche chiamate arie di baule o arie interpolate) vanno catalogate con tre schede: una scheda madre (collezione) per l'opera intera, una scheda per i movimenti originali dell'opera (che conterrà la maggior parte degli incipit), e una scheda per ciascuno degli inserti.

Inserti non compresi in un'opera più vasta vanno catalogati separatamente. Un collegamento alla composizione in cui erano inseriti può essere indicato nel campo **Fonte correlata (787)**.

Creando la scheda madre e la scheda per la composizione principale si seguono le regole consuete. Catalogando l'inserto si prega di osservare quanto segue. Nota che tutti i campi (come la data di composizione e l'organico) si riferiscono soltanto all'inserto.

**Compositore/autore (100)**: Compositore dell'inserto

**Nome aggiuntivo di persona (700)**: Compositore dell'opera più vasta, ad esempio un'opera teatrale

**Titolo uniforme (240)**: Titolo dell'inserto, o nome dell'opera seguito da Estratti

**Titolo uniforme alternativo (730)**: Titolo dell'opera più vasta, seguito dal sottocampo **Inserti**

**Soggetto (650)**: Inserisci tre soggetti: Insertions, il genere dell'inserto e il genere dell'opera più vasta

**Fonte correlata (787)**: Indica l'opera più vasta all'interno della quale questo brano è stato inserito e seleziona il tipo di relazione **Insert in**. Aggiungi un breve commento nel campo **Note** per spiegare la natura dell'inserto, ad esempio dove è collocato all'interno dell'opera più vasta.

**Nota generale (500)**: Puoi aggiungere informazioni supplementari per chiarificare la relazione tra l'inserto e l'opera più vasta (se conosciuta).

### Materiale misto (manoscritti e fonti a stampa conservate insieme)

It is not uncommon for manuscript and printed items to be found together in the same folder or with the same shelfmark: for example, a printed score with handwritten parts, or a group of printed parts together with some handwritten ones.

Cerca sempre di catalogare il materiale stampato in una scheda differente, perché è possibile che altre biblioteche abbiano copie della stessa edizione. Crea una notizia per l'oggetto a stampa, aggiungi le tue informazioni di possesso, e crea un'altra notizia per il materiale manoscritto. Usa il campo **Fonte correlata (787)** per rimandare da una scheda all'altra.

Se non è possibile creare una notizia per il materiale stampato, procedi come segue: Cataloga il materiale utilizzando il modello per i manoscritti. Nella sezione descrizione del materiale, descrivi i materiali manoscritti. Aggiungi un ulteriore gruppo di materiali e descrivi i materiali stampati.

### Musica in periodici

Ci sono due modi per catalogare periodici che contengono musica: come una collezione o come una singola composizione. In entrambi i casi, il titolo del periodico, con il numero dell'annata e l'anno, è inserito nel campo **Titolo aggiuntivo (730)**.

Una **raccolta** può essere appropriata quando il periodico è costituito del tutto o per lo più da musica e l'oggetto è stato raccolto e conservato integralmente. Le informazioni di possesso vanno collegate alla notizia per la collezione. Per ogni brano contenuto in ciascun numero della rivista, crea una nuova scheda individuale.

##### Esempio:

1001097294: numero di gennaio (l'anno è sconosciuto) della _Kleine Pianoforte-Bibliothek_, contenente 5 pezzi. C'è una scheda per la notizia-madre (la collezione) e cinque singole voci per ciascun brano.

Un'**opera singola** può essere appropriata se la composizione è compresa come un inserto o un'aggiunta a un periodico il cui contenuto prevalente è privo di notazione musicale. Di frequente, simili oggetti si conservano al di fuori del contesto originario della loro pubblicazione.

##### Esempi:

991018149: "The Pantheon" pubblicato su _The Lady's Magazine_, Agosto 1784\
990042111: "L'amour folâtrant l'autre jour" pubblicato in _Nouveau Mercure galant_, maggio 1679

### Musica in pubblicazioni non musicali

RISM includes music found in printed publications that are not primarily music documents. L'oggetto della catalogazione RISM tuttavia è la musica.

##### Esempio:

990026614: 3 canzoni di John Isaac Hawkins pubblicate nel _Discourse introductory to a course of lectures on the science of nature_ di Charles Willson Peale (1800).\
**Compositore/Autore (100)**: Il compositore della musica\
**Nome aggiuntivo di persona (700)**: L'autore del libro, con l'indicatore **Altra funzione**\
**Titolo diplomatico (245)**: Il titolo del libro\
**Titolo uniforme (240)**: Un titolo uniforme secondo le regole RISM, ad esempio **3 Songs**\
**Descrizione fisica (300)**: Descrizione della musica, ad esempio **1 score: 5 p.**

Individual entries are then created for each piece, following normal RISM rules.

### Libretti

Please observe the following when cataloging libretti.

**Compositore/Autore (100):** Inserisci l'autore del libretto. Non usare questo campo per il compositore della musica.

\*\* Nome aggiuntivo di persona (700):\*\* Una funzione utile è "Autore della fonte letteraria", ad esempio l'autore di un'opera di teatro di prosa su cui si basa il libretto. Only enter a composer's name as a cross-reference if named on the source.

**Nome di ente aggiuntivo (710):** Non dimenticare di indicizzare il nome dell'editore (per libretti stampati).

**Standardized title (240):** The fields "Arrangement statement" and "Key or mode" are not relevant here. If the libretto includes notated music, indicate the key in the music incipit (031) only.

**Additional title (730):** If the libretto was based on a book or play, the title of the original work can be entered here.

**Subject heading (650):** Enter the name of the genre for which the libretto was written, if known (such as “Operas” or “Cantatas”). "Librettos" is not necessary.

**Language code (041):** Use the field "Language of text" only if the libretto contains notated music with words.

**Source type (593):** Select either "Libretto, handwritten" or "Libretto, printed."

**Physical description: Format, extent (300):** Use the phrase "text document" to describe the format of the libretto. An example would be: 1 text document: viii, 27. p.

### Treatises

When cataloging treatises, the field **Format, extent (300 $a)** should generally include "text document" as the format.

Appropriate subject headings for treatises include the following:

- **Treatises**
- **Writings**
- **Music theory**
- **Theory of harmony**
- **Tutors (inst.)**: Includes methods and schools
- **Tutors (voc.)**: Includes methods and schools
- **Contrapuntal studies (inst./voc.)**
- **Solfeggios (voc.)**
- **Solfeggios (inst.)**
- **Scales (inst./voc.)**

Additional subject headings may be added.

### Piano arrangements

Specify piano arrangements as follows.

- In the field **Standardized title (240):**
 - Select **Arrangement** next to **Arrangement statement**.
 - Under **Scoring summary**, enter the scoring of the arrangement, such as **pf** or **V, pf**. Do not enter the scoring of the original work.
- In the field **Total scoring (594)**, enter the total scoring of the arrangement. Do not enter the scoring of the original work.
- In the field **Physical description (300)**, use **keyboard score** if the work has been reduced for piano. Use **vocal** score if the work has been reduced for voice and piano.
