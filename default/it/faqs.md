### Utilizzare Muscat   

1. **Dove posso trovare dei tutorial per Muscat?**  
Tutti i tutorial si trovano collegati sulla pagina Muscat dell'Editorial Center RISM: [http://www.rism.info/en/community/muscat.html](http://www.rism.info/en/community/muscat.html)  
  
2. **Come posso prendere contatto con altri utenti Muscat?**  
Per prendere contatto con gli sviluppatori Muscat, riferisci qualsiasi errore, domanda, commento o suggerimento in qualsiasi momento a muscat@rism.info.   
  
**[RISM Muscat](https://groups.google.com/forum/#!forum/rism-muscat)**, un gruppo Google, è la lista di discussione ufficiale Muscat cui ogni utente Muscat deve partecipare. Ogni annuncio ufficiali da parte della Redazione centrale e degli sviluppatori Muscat sarà diffuso unicamente attraverso questo gruppo. Inoltre, ogni utente Muscat è incoraggiato a porre domande o sollevare questioni da discutere.   
  
Non è necessario possedere un conto Google. Un invito a partecipare al gruppo ti verrà mandato al momento di ricevere le informazioni sul tuo conto Muscat.  
  
Vi è anche un canale di discussione su Slack:   
[https://rismcommunity.slack.com/](https://rismcommunity.slack.com/)  
  
3. **Tutta la bibliografia citata in Muscat si trova presso l'Editorial Center?**  
No, soltanto la bibliografia segnata con "HB" o "Handbibliothek" o "RISM-ZR" si trova effettivamente nel nostro ufficio. I materiali sono a disposizione di tutti coloro che contribuiscono a RISM, dunque se abbiamo una pubblicazione che vuoi consultare, puoi farcelo sapere e cercheremo di farti avere ciò che ti serve. Anche se ti interessi di una pubblicazione che non è nel nostro ufficio, è possibile che conosciamo qualcuno che la possiede.  
  
4. **Cosa faccio se dimentico la mia password o desidero cambiarla?**  
Le password sono gestite dall'Editorial Center. Mettiti in contatto con noi se hai perduto la tua password. Non puoi cambiare da solo la tua password.  
  
5. **Posso mostrare Muscat ai miei colleghi? Posso realizzare una dimostrazione di Muscat a un congresso o un seminario?**  
Certamente! Esiste una versione di prova di Muscat esattamente per questi scopi all'indirizzo [http://muscat-training.rism.info](http://muscat-training.rism.info/).   
  
Ogni utente Muscat può effettuare il login con le proprie credenziali personali. Esistono anche 99 conti di prova (da "training01@rism.info" a "training99@rism.info") a disposizione di singoli utenti. Si può usare uno qualsiasi di questi conti di prova. Si prega di contattare l'Editorial Center RISM (contact@rism.info) per ottenere la password attuale.  
  
Ogni cosa nella versione di prova può essere aggiunta, modificata o cancellata. Viene sincronizzata una volta alla settimana (di domenica) con i dati attuali di Muscat. Questo significa che anche le schede più recenti sono disponibili, ma anche che quelle create nella versione di prova saranno cancellate.   
  
6. **Nello storico delle modifiche, cosa significa se l'autore è indicato come "[system]"?**  
Puoi osservare una modifica di sistema se viene modificato uno dei campi indicizzati collegato alla tua scheda. Il cambiamento nella voce d'autorità sarà segnalato come un cambiamento anche nella tua scheda.  
  
7. **Posso creare una scheda basandomi su una descrizione in un catalogo stampato?**  
Sì! A volte, per vari motivi, non è possibile avere accesso a una fonte ed è disponibile soltanto la sua descrizione in un catalogo stampato, in un catalogo tematico o in un catalogo di biblioteca online. Puoi usare una simile descrizione come base per la tua notizia. Se decidi di farlo:  
a. aggiungi una **Nota generale (500)** come "Scheda basata sulla descrizione in YouV"   
b. istituisci il relativo collegamento nel campo **Riferimenti bibliografici (691)** oppure **Localizzazione e accesso elettronico (856)**, a seconda dei casi  
c. nel campo **Origine della scheda (980)**, sottocampo **Materiale esaminato** , seleziona "Materiale non esaminato".  
  
8. **Posso inserire fonti che sono incluse in altre pubblicazioni RISM della serie B? **  
Anche se stiamo gradualmente aggiungendo le fonti della serie B a Muscat, questo è un progetto a lungo termine. I documenti di B/I sono in Muscat mentre B/II è in preparazione. Nel frattempo, sentiti libero di inserire fonti da altri volumi B. Includi una citazione del volume B originale nel campo **Riferimenti bibiografici (691)**.  
  
9. **Quando appaiono i record nel catalogo pubblico su opac.rism.info?**  
I record di Muscat sono inviati per la pubblicazione nel catalogo pubblico su opac.rism.info una volta al mese, intorno al 19 di ogni mese. I record sono quindi visibili pochi giorni dopo.  
 
10. **Cosa succede se una fonte in RISM non è più in possesso dell'istituzione detentrice indicata nel record RISM?**  
Usate la sigla **XX-NN** quando la collocazione attuale di una fonte è sconosciuta, come ad esempio se era in deposito presso un'istituzione ma la fonte è stata ritirata e ora è di proprietà privata. Questo accade solo raramente. Contattare l'Editorial Center se una fonte ha bisogno di questa sigla.

 

### Aspetti tecnici di Muscat
**1. Che requisiti tecnici esistono per Muscat?**  

- Muscat è indipendente dalla piattaforma e funziona su Macintosh e PC.
- Si accede attraverso un URL e si richiede una connessione Internet.
- Muscat funziona al meglio su schermi di almeno 1366 x 768 pixel.
- Muscat è ottimizzato per Firefox e Chrome. Si prega di non usare Internet Explorer!   

**2. Quali sono gli aspetti tecnici salienti di Muscat?**

- Muscat è open source. Il codice sorgente è disponibile presso il deposito [GitHub](https://github.com/rism-ch/muscat).
- Muscat è un’applicazione Ruby on Rails.
- [Verovio](http://www.verovio.org/pae-examples.xhtml) è utilizzato per visualizzare gli incipit musicali attraverso MEI. 
- Solr è utilizzato come motore di ricerca.
- Muscat ha un servizio [SRU](https://github.com/rism-ch/muscat/wiki/SRU) e uno strumento di [download SRU](https://github.com/rism-international/sru-downloader) per esportare schede MARCXML.
- Muscat supporta Unicode (UTF-8).
Puoi trovare ulteriori informazioni sullo sviluppo di Musicat sul sito del [RISM Digital Center](https://rism.digital/tools/muscat.html).   

**3. Quali sono gli aspetti tecnici della ricerca per incipit?**

- È basata sul motore di ricerca [Themefinder](http://www.themefinder.org/) sviluppato all'Università di Stanford. 
- Sfrutta il sistema di indicizzazione sottostante (Solr), utilizzato per tutte le ricerche in Muscat, che è stato adattato per permettere l'analisi della notazione PAE utilizzata nel compilare le schede. Il processo di indicizzazione è del tutto trasparente per utenti e catalogatori, ed è necessaria soltanto il normale inserimento della notazione codificata nel campo 031.

**4. Cosa caratterizza Muscat, ad esempio?**

- **Versionamento** : Chi cataloga può vedere i cambiamenti fatti alle schede.
- **VIAF** : I nomi di persona possono essere importati attraverso il [Virtual International Authority File (VIAF)](https://viaf.org/). 