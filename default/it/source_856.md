#### Localizzazione e accesso elettronico** (856)**  

Utilizza questo campo per collegare una risorsa esterna che ha un legame diretto alla fonte descritta.   
  

**URL per l'accesso elettronico****  (856 $u)**

Inserisci lo URL della risorsa esterna. Utilizza sempre dei collegamenti permanenti (permalink).

 

**Nota sulla risorsa esterna****  (856 $z)**

Questo campo è obbligatorio se si inserisce un collegamento internet.

Inserisci una breve nota spiegando perché il collegamento è rilevante per la fonte descritta. Inserisci utilizzando la tua lingua di catalogazione.

_Esempi:_  
Copia digitale  
Filigrana a p. 4  
Homepage del progetto  
Dettaglio della rilegatura  
Scheda bibliografica  
Collegamento alla scheda in Bach Digital  
Collegamento alla composizione nel Frescobaldi Thematic Catalogue Online  
Voce nel registro parrocchiale  
Collegamento a RISM ID no. 806155758, GB-Lbl Add. 14209 f.23r-27v, lo stesso testo messo in musica da N. Porpora  
Fonte concordante in GB-Ob

**Tipo di collegamento (856 $x)**

Questo campo è obbligatorio se si inserisce un collegamento a una risorsa esterna. Seleziona tra i valori seguenti:

- **Musica digitalizzata** : il collegamento punta a un sito internet esterno che è la digitalizzazione di un esemplare della fonte descritta. Di preferenza, scegli un deposito istituzionale, ma se non ve ne è alcuno disponibile, sono accettabili collegamenti a depositi esterni come Internet Archive o IMSLP. Per raccolte, non è necessario replicare negli spogli un collegamento inserito nella notizia principale.  
_Esempio_ :[  
https://mirador.acdh.oeaw.ac.at/musikarchivspitz/A-SPD\_A15/](https://mirador.acdh.oeaw.ac.at/musikarchivspitz/A-SPD_A15/)
- **IIIF manifest** : l'oggetto collegato è un oggetto JSON elaborato da un visualizzatore di immagini interno come diva.js. Il documento è inserito direttamente nella pagina web. In molti casi, nel collegamento apparre "manifest", "iiif" o simili.  
_Esempio_ :[  
https://iiif.lib.harvard.edu/manifests/drs:2820650](https://iiif.lib.harvard.edu/manifests/drs:2820650)

> In caso siano disponibili tanto collegamenti a un visualizzatore esterno che un IIIF manifest, ripeti il campo ed elenca separatamente ciascun collegamento.

> _Esempio_:

  - **URL per l'accesso elettronico** : [http://nrs.harvard.edu/urn-3:FHCL.Loeb:537966](http://nrs.harvard.edu/urn-3:FHCL.Loeb:537966)  
**Nota sulla risorsa esterna** : versione digitalizzata  
**Tipo di collegamento** : musica digitalizzata
  - **URL per l'accesso elettronico** : [https://iiif.lib.harvard.edu/manifests/drs:2820650](https://iiif.lib.harvard.edu/manifests/drs:2820650)  
**Nota **  **sulla risorsa esterna** : IIIF manifest  
**Tipo di collegamento** : IIIF manifest
- **Altri** : Collegamento ad altre risorse che non sono la fonte descritta.

#### Tipi di risorse esterne

**Tipo di collegamento****  856 $x: Musica digitalizzata**  
Inserisci un collegamento unicamente alla fonte descritta nella scheda RISM. Usa solo collegamenti permanenti (permalinks). Se non sono disponibili dei collegamenti permanenti, istituisci un collegamento a una pagina dalla quale sia facile trovare il collegamento alla fonte digitalizzata (come una scheda bibliografica in un catalogo di biblioteca). Puoi inserire estratti da una fonte digitalizzata (ad esempio, alcune pagine) se una versione digitalizzata completa non è disponibile.

I collegamenti inseriti come musica digitalizzata appaiono nel filtro "Musica digitalizzata" nell'OPAC pubblico (opac.rism.info).

**Tipo di collegamento 856 $x: Altri**

Fra gli altri tipi di collegamenti esterni si possono trovare i seguenti. Assicurati che per l'utilizzatore sia sempre comprensibile il motivo per cui si indica un collegamento, ad esempio in una **Nota generale (500)**.

- **Dettagli delle fonti**  
Dettagli delle fonti che ne presentano un aspetto specifico, come una filigrana, una rilegatura, il titolo o la copertina.
- **Schede di cataloghi o banche dati**  
Ad esempio, schede bibliografiche in cataloghi esterni o voci in banche dati esterne. Si possono inserire banche dati scientifiche esterne che forniscono informazioni utili, ma rifletti se non sia meglio indicarli nei riferimenti bibliografici.
- **Cataloghi tematici elettronici, enciclopedie online, riferimenti digitalizzati**  
In genere, utilizza i campi **Catalogo delle opere (690)** o **Riferimenti bibliografici (691)** per indicare opere online come cataloghi o enciclopedie. Tuttavia, come servizio agli utilizzatori, può essere utile aggiungere nel campo 856 un collegamento diretto a un certo luogo all'interno della risorsa di riferimento. 
- **Fonti archivistiche o storiche**   
Ad esempio, registri municipali o documenti, corrispondenza, periodici storici. Assicurati che la pertinenza della fonte archivistica sia spiegata in una **Nota generale (500)**, poi inserisci il collegamento diretto qui. Nel caso di periodici storici, inserisci il nome del periodico nei riferimenti bibliografici ma poi inserire qui un collegamento alla pagina specifica che contiene l'articolo; assicurati di inserire informazioni sull'articolo, ad esempio titolo e data, in una nota.
- **Siti web**  
Ad esempio, siti web di progetti di ricerca, di istituzioni finanziatrici, o altri siti web pertinenti.
- **Altre schede RISM**  
Istituisci un collegamento con un'altra scheda RISM soltanto se la scheda ha una diretta relazione alla fonte descritta. Utilizza soltanto collegamenti permanenti (permalinks) dall'OPAC RISM ([https://opac.rism.info/)](https://opac.rism.info/)). Deve essere chiaro all'utilizzatore perché la scheda è rilevante per la fonte descritta. Menziona come minimo la biblioteca di possesso, la collocazione e il numero identificativo RISM in una nota. A volte, una relazione con una diversa fonte può essere spiegata più efficacemente in una **Nota generale (500)**.  
Se fai riferimento ad altre schede RISM altrove nella tua scheda, non è necessario istituire un collegamento in questo campo.  
Non è necessario collegare qui tutte le schede RISM di fonti per la stessa composizione; di fatto, è un lavoro inutile perché il numero di fonti in Muscat cresce giornalmente.
- **Riferimenti a fonti pertinenti in altre biblioteche ma non in RISM**  
Se vuoi inserire un collegamento a una fonte che non è ancora in RISM, rifletti se sia possibile per te o per il tuo gruppo di lavoro di inserire il manoscritto, trattato o libretto digitalizzato, oppure aggiungere esemplari di una certa edizione a stampa. La redazione centrale è lieta di aiutarti se credi che una certa fonte dovrebbe essere presente in RISM. È comprensibile se non hai la possibilità di creare previamente una nuova scheda per una fonte.
- **Altre fonti rilevanti**  
Ad esempio, fonti per la stessa composizione, altri esemplari della stessa edizione, arie o parti dell'opera, fonti che hanno servito come base per la catalogazione della fonte descritta. Collegamenti simili si possono istituire all'oggetto digitalizzato oppure a un catalogo esterno.