### **Incipit (031)**

Gli incipit aiutano l’identificazione delle composizioni e facilitano la comparazione delle fonti. Miglior pratica per la musica strumentale è di includere incipit per una parte acuta e una parte grave, ad esempio vl 1 e basso. Per la musica vocale, includi incipit per una parte vocale e una parte strumentale. Scrivi gli strumenti traspositori alle altezze d’effetto.

Se la notazione di cui hai bisogno non è disponibile nel codice Plain & Easie, trascrivi la musica nel miglior modo possibile e aggiungi una nota esplicativa. Puoi allegare un’immagine dell’incipit dalla fonte come ulteriore chiarificazione. 

Per un aiuto nella trascrizione di notazione mensurale, For assistance with transcribing mensural notation, please see "Basic Mensural Notation Reference" by Ted Dumitrescu ([http://cmme.org/misc/refsheet.pdf](http://cmme.org/misc/refsheet.pdf))).

#### Numero dell'opera, N.o del movimento, N.o dell'incipit (031 $a, b, c) 

**Campi obbligatori se un sottocampo qualsiasi di questa parte è utilizzato.**

Il numero d’incipit consiste di tre cifre che rappresentano la composizione, il movimento e l’incipit. La prima cifra è sempre 1. Un movimento si riferisce a sezioni significative di una composizione, che si tratti sia tecnicamente di movimenti (come in una sinfonia) che di diverse sezioni (come in un’aria o l’entrata di una parte vocale). Per indicare che gli incipit risuonano contemporaneamente, il numero d’incipit deve essere lo stesso.

Numera gli incipit consecutivamente anche se nella fonte mancano alcuni movimenti. Ad esempio, se la fonte contiene una sinfonia in tre movimenti ma il movimento centrale manca, gli incipit verranno numerati 1.1.1 e 1.2.1 (non 1.3.1). (Nota bene: i punti fra le cifre sono aggiunti automaticamente da Muscat.)

_Esempi_:  
1.1.1 = 1a composizione, 1o movimento, 1o incipit  
1.1.2 = 1a composizione, 1o movimento, 2o incipit (risuona contemporaneamente a 1.1.1)  
1.1.2 = 1a composizione, 1o movimento, entrata della parte vocale  
1.2.1 = 1a composizione, 2o movimento,1o incipit

 

**Intestazione, tempo (031 $d)**

Inserisci l’intitolazione e il tempo del movimento o simili indicazioni, se specificate, come appaiono nella fonte. Utilizza **|** (la barra verticale) con uno spazio singolo prima e dopo il segno per mostrare un a capo. Utilizza parentesi quadre per indicare delle aggiunte all’originale; tali aggiunte devono essere formulate in maniera coerente. Più intestazioni o indicazioni di tempo aggiuntive possono essere indicate in campi separati. Se stai inserendo più incipit per i quali vale la stessa intestazione o indicazione di tempo, inseriscila solo per il primo incipit musicale.

 

**Voce/strumento****  (031 $m)**

Inserisci la parte vocale o lo strumento usando la lista di **abbreviazioni RISM per gli strumenti**. Inserisci **V** per una parte vocale sconosciuta. Inserisci **i** per una parte strumentale sconosciuta. Utilizza la notazione d’effetto per gli strumenti traspositori. Indica l’accordatura dello strumento nel campo  **Commento all'incipit musicale**.

_Esempi_:  
pf  
T coro  
org with text

#### Personaggio (031 $e)

Inserisci qui il ruolo teatrale. Se riempi questo campo, assicurati di riempire anche il campo ** **** Personaggi menzionati**** (595)**. Utilizza parentesi quadre per indicare delle aggiunte editoriali. Indica ogni informazione dubbia con un punto interrogativo.

 

#### Incipit testuale (031 $t)

Un incipit testuale consiste delle prime parole di una composizione o di una sezione e possono essere il primo verso, la prima frase, o un altro gruppo di parole che abbia senso linguisticamente. Gli incipit testuali servono ad identificare il testo utilizzato e non corrispondono necessariamente alla lunghezza della musica riportata nell’incipit musicale. Nota che per i testi in latino vi sono regole particolari (vedi sotto). 

Gli incipit testuali sono indicati in forma standardizzata. Inserisci l’incipit testuale modernizzando l’ortografia. Fai riferimento all’indice **Titolo/incipit testuale** per aiutarti a standardizzare la tua immissione. Inserisci nuovi incipit se non sono presenti nell’indice.

Non mettere parti del testo tra parentesi e non aggiungere parole mancanti. Ometti l’interpunzione e le ripetizioni testuali. Gli accenti dovrebbero essere usati solo come appaiono nel dizionario o se sono grammaticalmente corretti. Trascrivi in parole delle cifre presenti all’inizio del testo. L’uso delle maiuscole e minuscole segue le regole della relativa lingua, eccettuati i nomi di Dio (Herr, Dio, Dieu, Signore, Lord ecc.) che hanno sempre l’iniziale maiuscola. Se l’incipit testuale è usato come titolo uniforme (240), assicurati che la lunghezza e l’ortografia corrispondano esattamente.

Ometti il testo interamente se non riesci a leggerlo e aggiungi in una nota "Text illegible" o simili.

Nelle lingue romanze, il testo segue un apostrofo direttamente e senza uno spazio. Un’eccezione si ha quando la prima lettera di una parola è sostituita da un apostrofo (ad esempio: Fra l'amante e 'l genitor).

Testi accertati o desunti che non appaiono nella fonte possono essere riportati qui. In questi casi, inserisci l’intero testo tra parentesi quadre. Tra questi vi sono:

·        Testi aggiunti se manca la parte vocale

·        Incipit testuali nella lingua originale della composizione quando la fonte contiene una versione tradotta

·        Testi di composizioni vocali usati come tema di una variazione o come base di un arrangiamento strumentale

**Alfabeti non latini**: Se la fonte ha un incipit testuale che utilizza caratteri o lettere non latine (alfabeto cirillico/greco/ebraico/coreano ecc., ideogrammi cinesi ecc.) inserisci l’ **Incipit testuale** utilizzando l’alfabeto originale. Traduzioni e traslitterazioni non sono obbligatorie e possono essere aggiunte nel campo note. Traduzioni aggiunte (non presenti nella fonte) vanno messe tra parentesi quadre. Puoi tradurre in una qualsiasi delle lingue RISM.

**Regole speciali per testi latini**: Inserisci testi latini, sia sacri che profani. Il campo è collegato all’indice **Titolo/incipit testuale**. All’interno dell’indice **Titolo/incipit testuale**, un termine preceduto dall’indicazione **t** significa che puoi ottenere informazioni sul preciso contesto liturgico, versioni alternative e altre questioni. Se l’incipit testuale è usato come titolo uniforme, assicurati che l’ortografia è identica, ma ricordati che i testi latini nei titoli uniformi sono inseriti solo fino alla virgola. Utilizza le parentesi quadre per inserire testi latini non presenti sulla fonte ma ottenuti attraverso una ricerca.

Testi latini standardizzati solitamente corrispondono ai testi nel _Liber usualis_. In RISM, questi testi contengono una virgola. Ad esempio, cercando il testo "Et in terra pax", compariranno una dozzina di opzioni, ma una sola ha una virgola e questa è utilizzata 4'800 volte nella banca-dati. Dunque è questa che cerchiamo – posto che corrisponda alla nostra fonte. Se il tuo incipit testuale è soltanto "Et in terra pax", ciò significa (1) che la tua fonte contiene solo queste parole oppure (2) che il testo nella fonte prosegue in maniera diversa che nel _Liber usualis_. Questo ovviamente è possibile, ma nella maggioranza dei casi vorrai usare la versione con la virgola.  

**Tonalità, modo****  (031 $r)**

Seleziona la tonalità o il modo dalla lista.

**Armatura di chiave****  (031 $n)**

Inserisci **x** per tonalità diesizzate o **b** per tonalità bemollizzate. Inserisci poi i nomi delle note che sono influenzate dall’armatura di chiave. Aggiungi diesis o bemolli palesemente mancanti tra parentesi quadre. Se manca l’armatura di chiave, lascia il campo vuoto.

_Esempi:_  
xF = il fa è diesizzato = sol maggiore o re minore  
bBE = il si e il mi sono bemollizzati = si bemolle maggiore o sol minore  
xFC[G] = il fa e il do sono diesizzati ma il brano è palesemente in la maggiore, dunque l'ultimo diesis è aggiunto tra parentesi quadre

**Misura (031 $o)**

Inserisci la misura dell’incipit musicale come frazione. Sono consentite anche le seguenti misure: 

**c ** = tempo comune or tempus imperfectum cum prolatione imperfecta  
**c/ ** = tempo tagliato, alla breve  
**3 ** = proportio tripla; anche  **1**,  **2**  ecc.  
**c3 ** = proportio tripla  
**c3/2  
c. ** = tempus imperfectum cum prolatione perfecta  
**o ** = tempus perfectum cum prolatione imperfecta  
**o/ ** = tempus perfectum cum prolatione minore diminutum  
**o. **  = tempus perfectum cum prolatione perfecta

Se la misura è alternata regolarmente, puoi inserire la prima misura seguita dalla seconda, separate da uno spazio. Se l’incipit è privo di misura, lascia vuoto questo campo.

_Esempi_:  
4/4  
6/8

3/4 4/4

Se la misura nella fonte è chiaramente sbagliata, correggila per farla corrispondere con l’incipit indicato. Aggiungi una nota esplicativa nel campo  **Commento all'incipit musicale**.

 

**Chiave (031 $g)**

Seleziona una chiave dalla lista. La lettera indica il tipo di chiave. Il numero si riferisce alla posizione sul rigo. Un trattino significa notazione moderna. Un segno più significa notazione mensurale.

 

**Validità (031 $s)**

Non inserire nulla in questo campo! (È usato solo per dati vecchi.)   
  

**Incipit musicale (031 $p)**

Inserisci l’incipit musicale in forma codificata utilizzando il codice Plaine & Easie (vedi anche [http://www.iaml.info/plaine-easie-code](http://www.iaml.info/plaine-easie-code)). L’incipit dovrebbe avere una lunghezza di almeno due battute oppure sei note.

**1. Ottave**  
' = nella 1a ottava sopra al do centrale  
'' = nella 2a ottava sopra al do centrale  
''' = nella 3a ottava sopra al do centrale  
, = nella 1a ottava sotto al do centrale  
,, = nella 2a ottava sotto al do centrale  
,,, = nella 3a ottava sotto al do centrale

**2. Valori ritmici**  
0 = longa  
9 = breve  
1 = semibreve  
2 = minima  
4 = quarto / semiminima  
8 = ottavo / croma  
6 = sedicesimo / semicroma   
3 = trentaduesimo / biscroma  
5 = sessaquattresimo / semibiscroma  
7 = centoventottesimo / fusa  
4. = quarto col punto / seminima col punto  
8.. = ottavo col doppio punto / croma col doppio punto   
7. = notazione neumatica

**3. Alterazioni**  
x = diesis  
xx = doppio diesis  
b = bemolle  
bb = doppio bemolle  
n = bequadro

**4. Nomi delle note**  
C, D, E, F, G, A, B 

**5. Notine e abbellimenti**  
g = acciaccatura (senza valore ritmico, precede il nome della nota)  
q = appoggiatura (con valore ritmico, precede il nome della nota)  
qq...r = più appoggiature o notine d’abbellimento unite (con valore ritmico)

**6. Pause**  
8- = pausa di ottavo / croma  
2- = pausa di minima, ecc.  
= oppure =1 = pausa di una battuta  
=35 = pausa di 35 battute (non dimenticare le stanghette di battuta!)

**7. Stanghette di battuta**  
/ = stanghetta di battuta  
// = stanghette doppie  
//: = stanghette doppie con segno di ripetizione  
:// = stanghette doppie con segno di ripetizione  
://: = stanghette doppie con segno di ripetizione

**8. Altri simboli**  
t = trillo (segue immediatamente la nota)  
+ = legatura di valore (segue immediatamente la nota, da non confondersi con la legatura di fraseggio.)   
() = fermata (si può mettere tra parentesi solo una singola nota o una singola pausa; alterazioni ecc. devono essere fuori dalla parentesi; vedi anche oltre **10. Ritmi speciali**)

Non inserire legature di fraseggio.

**9. Travature**  
{ = inizio della travatura  
} = fine della travatura

Esempio:  
{qq6'CDEDr}

**10. Ritmi speciali**  
( = inizio del ritmo speciale  
) = fine del ritmo speciale  
   
La durata totale del gruppo deve essere scritta prima della **(**. Il valore ritmico della prima nota deve essere indicata dopo la **(**, anche se è identica alla nota immediatamente precedente la sezione nel ritmo speciale. Il numero di note nel gruppo deve essere indicato prima di **)**. È separato dall’ultima nota da **;**.

_Esempi:_  
8(3ABCDE;5) = quintina, cinque trentaduesimi/biscrome nello spazio di un ottavo/una croma.  
8({3ABCDE};5) = quintina, cinque trentaduesimi/biscrome nello spazio di un ottavo/una croma, con travatura  

La terzina è un caso speciale. In effetti, dovrebbe essere codificata come segue:  
8(6ABC;3) oppure 8({6ABC};3).  
Invece è permessa la seguente abbreviazione:  
(6ABC)  
({6ABC})

Si prega di non dimenticare il valore ritmico all’interno della parentesi!

**11. Scorciatoie notazionali  
Nota:** Attualmente, la ricerca OPAC ignora gli elementi ripetuti descritti in 11.1 e 11.2. Questo significa che se utilizzi queste abbreviazioni, i tuoi incipit non saranno pienamente ricercabili nell’OPAC. Finché questo problema non è risolto, si prega di scrivere l’incipit per esteso. (L’abbreviazione 11.3 può essere usata come descritto più oltre.)

11.1. Ripetizione di figurazioni  
! = inizio e fine del passo  
f = indicazione della ripetizione   
La figurazione sarà ripetuta tante volte quanto si ripete **f** dopo il secondo **!**. Questo è solo possibile all’interno di una battuta.

_Esempio:_  
 !{'8ABAG}!ff = questa figurazione sarà ripetuta due volte

11.2. Ripetizione di battute  
i = ripete l’ultima battuta  
‘i’ va sempre posta tra due stanghette di battuta.

_Esempio:_  
'4ABAG/i/i/ = la battuta sarà ripetuta due volte

  

11.3. Moduli ritmici

Se si ripete più volte una stessa sequenza ritmica, il modulo ritmico si può indicare prima dei nomi delle rispettive note.

_Esempio:_  
Invece di **8.A6B8C8.D6E8F** si può usare il codice **8.68ABCDEF**  
La sequenza ritmica si interrompe non appena compare un nuovo valore ritmico.

   
**12. Cambio di chiave, tonalità o misura**

Utilizza % per cambiare la chiave, $ per cambiare la tonalità e @ per cambiare la misura. Fai seguire questi segni con la nuova indicazione generale (chiave, tonalità o misura) seguita da uno spazio.

_Esempi:_  
%C-1 '2A  
%C-1 $xFC '8B  
@3/2 '1C  
$nBE $xFC

 

**13. Abbreviazioni**   
Forme di notazione abbreviata che si trovano nella musica, come tremoli o segni analoghi di ripetizione, devono essere scritti per esteso usando l’effettiva notazione.

_Esempio:_  
{'8DDDD} = una minima di tremolo sul re

 

**14. Accordi**

Inserisci accordi dalla nota più acuta alla più grave, separate da **^**.

_Esempio:_  
4’’C^’G^E^C

####  

**Commento all'incipit mus.****  (031 $q)**

Aggiungi commenti come l’accordatura degli strumenti traspositori, errori nell’incipit, l’incipit testuale con l’ortografia e/o l’interpunzione originali, e ogni intervento che hai dovuto fare. Inserisci i dati usando la tua lingua di catalogazione.

**Organico del movimento (031 $z)**

In questo campo puoi indicare l’organico specifico del movimento in questione (come un movimento all’interno di una complessa composizione vocale). Elenca l’organico su una linea utilizzando le abbreviazioni RISM per gli strumenti e l’ordine standardizzato (descritto in **Organico sintetico** **[240 $m]**). Usa un punto e virgola per separare famiglie di strumenti. 

_Esempi:_   
S (Enrico), T (Vanoldo); vl 1, 2, b; [winds]  
S 2 solo; Coro; ob obl; strings, bc