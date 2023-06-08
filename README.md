# L'IA tra le Righe: L'Editoria Digitale alla Sfida dell'Intelligenza Artificiale

Repository non allineata con il progetto e quindi ancora **IN FASE DI AGGIORNAMENTO**

## 🗃 Indice dei contenuti
* [Oggetto del progetto](#oggetto-del-progetto)
* [Obiettivi](#-obiettivi)
* [Processo di produzione](#processo-di-produzione)
     * [Studio e analisi del tema](#studio-e-analisi-del-tema)
     * [Stesura della bozza](#stesura-della-bozza)
     * [Definizione dello stile grafico](#definizione-dello-stile-grafico)
* [Tecnologie](#tecnologie)
    * [Tecnologie per l'automatismo](#tecnologie-per-lautomatismo)
* [Conclusioni](#conclusioni)

## Oggetto del progetto

Questo progetto rappresenta uno **showcase** sull'applicazione delle tecnologie basate su intelligenza artificiale (IA) nell'ambito dell'editoria digitale. 

## 🎯 Obiettivi

L'obiettivo è quello di illustrare in modo chiaro e coinvolgente come l'intelligenza artificiale sta trasformando l'editoria digitale, offrendo nuove opportunità di innovazione e migliorando l'esperienza di lettura per gli utenti. L'elaborato vuole mettere in luce le potenzialità delle intelligenze artificiali e stimolare la riflessione su come queste tecnologie possano essere integrate in modo responsabile e sostenibile nel settore dell'editoria digitale, ponendo anche un occhio di riguardo sui limiti attuali delle tecnologie presenti.

## Processo di produzione

Per creare il showcase, è stata utilizzata una combinazione di presentazioni audiovisive. La presentazione sarà strutturata in modo da fornire una panoramica chiara e concisa dei principali ambiti in cui l'intelligenza artificiale viene impiegata nell'editoria digitale, come la scrittura assistita, la creazione e personalizzazione di contenuti multimediali come audio, immagini o video.

### Studio e analisi del tema

* Studio del mercato:
Negli ultimi anni, l'utilizzo delle nuove tecnologie basate sull'intelligenza artificiale (IA) ha registrato un incremento esponenziale in vari settori. Questo rapido sviluppo è stato alimentato  da diversi fattori, tra cui l'aumento della disponibilità di dati, i  progressi nella capacità di calcolo e l'avanzamento degli algoritmi  di apprendimento automatico. Anche nel campo dell'editoria digitale, l'utilizzo dell'IA ha registrato una crescita significativa. Le intelligenze artificiali vengono 
utilizzate per automatizzare compiti editoriali come la scrittura assistita e la personalizzazione dei contenuti per gli utenti. Inoltre, l'IA è impiegata nella gestione dei flussi di lavoro editoriali, ottimizzando la produzione e la distribuzione dei contenuti digitali.

* Obiettivi comunicativi: Mostrare le potenzialità e i limiti di un impiego delle nuove tecnologi basate du IA, discutendo infine i nuovi rapporti opera/autore, il diritto d'autore e le potenzialità/rischi derivati dal loro impiego in ambito editoriale.

* Definizione dei formati: Il formato finale del progetto è quello dell'ePub, standard aperto specifico per la pubblicazione di libri digitali (eBook)

### Stesura della bozza

* Punti da trattare
* Sviluppo dei contenuti
* Stesura requisiti di accessibilità


### Revisione dei contenuti

* Rilettura dei contenuti e perfezionamento
* Differenziazione degli elementi
* Inclusione nuovi contenuti
* Revisione requisiti di accessibilità

### Definizione dello stile grafico

* Regole di impaginazione 
* Revisione requisiti di accessibilità

### Creazione del formato

* Compilazione del documento
* Revisione dell'impaginazione e dell'accessibilità
* Definizione dei metadati descrittivi
* Dichiarazione delle licenze

### Struttura effettiva del contenuto

Lo showcase è organizzato nel seguente modo:

* Introduzione
* Testo
* Immagini
* Audio
* Video
* Conclusioni
* Copyright

L'indice (TOC) sarà generato in maniera automatica tramite tool.

## 🔠 Regole di accessibilità 

L'attributo epub:type facilita solamente i comportamenti dell'interprete, come le note a comparsa. AL momento della sua introduzione, si sperava che potesse colmare l'esigenza di semantica del flusso di lavoro dell'editore con l'accessibilità, ma non ci si è riusciti. Da solo non migliora l'accessibilità delle pubblicazioni.

L'attributo può ancora essere utile per i flussi di lavoro interni come mezzo per generare ruoli ARIA, ma in questi casi è necessario seguire attentamente i requisiti della specifica ARIA. L'uso dei ruoli è molto più restrittivo di epub:type.

È anche possibile utilizzare sia l'attributo epub:type che role quando si sovrappongono i comportamenti dell'accessibilità e dell'interprete avanzato.[^1]


### WAI-ARIA: Web Accessibility Initiative - Accessible Rich Internet Applications

WAI-ARIA definisce un modo per rendere i contenuti e le applicazioni Web più **accessibili alle persone con disabilità**. È particolarmente utile per i contenuti dinamici e i controlli avanzati dell'interfaccia utente sviluppati con HTML, JavaScript e tecnologie correlate. Senza WAI-ARIA alcune funzionalità utilizzate nei siti Web non sono disponibili per alcuni utenti con disabilità, in particolare per coloro che si affidano a lettori di schermo e per coloro che non possono utilizzare il mouse.[^3]

#### WAI-ARIA Roles

I ruoli ARIA possono essere usati per descrivere elementi che non esistono nativamente nell'HTML o che esistono ma non hanno ancora il pieno supporto del browser.

####  DPUB-ARIA
Il modulo Digital Publishing WAI-ARIA (DPUB-ARIA) è un'estensione della specifica ARIA. Fornisce un insieme aggiuntivo di ruoli specifici per l'editoria da utilizzare con l'attributo role di ARIA. I ruoli editoriali hanno lo scopo di migliorare l'usabilità delle pubblicazioni, sia fornendo alle tecnologie assistive (AT - assistive technologies) informazioni aggiuntive su strutture importanti, sia garantendo l'accessibilità dei comuni idiomi di markup editoriale. I ruoli non sono intesi come un meccanismo per la semantica del flusso di lavoro e quindi non forniscono la stessa ampiezza di copertura, ad esempio, del vocabolario EPUB Structural Semantics. È necessario prestare attenzione sia al numero di ruoli utilizzati sia al modo in cui vengono utilizzati, poiché un uso scorretto può compromettere la capacità degli utenti di consumare in modo accessibile una pubblicazione. di consumare una pubblicazione in modo accessibile.[^2]

##### Roles utilizzati

I ruoli utilizzati all'interno del documento sono i seguenti

* **doc-chapter**: landmark role utilizzato all'interno di una section per definire una sezione tematica importante del contenuto di un'opera.
* **doc-introduction**: landmark role utilizzato per indicare una sezione preliminare che di solito introduce l'ambito o la natura del lavoro.
* **doc-conclusion**: landmark role utilizzato per indicare una sezione o una dichiarazione conclusiva che riassume il lavoro o conclude la narrazione.

[^1]: http://kb.daisy.org/publishing/docs/html/epub-type.html
[^2]: http://kb.daisy.org/publishing/docs/html/dpub-aria/index.html
[^3]: https://www.w3.org/WAI/standards-guidelines/aria/


## Tecnologie

#### ChatGPT

ChatGPT è un modello di intelligenza artificiale sviluppato da OpenAI. È stato addestrato su una vasta quantità di testi provenienti da internet, consentendogli di generare testo coerente e rilevante in risposta a input in linguaggio naturale. ChatGPT è in grado di eseguire diverse attività linguistiche come rispondere a domande, fornire informazioni, generare testo creativo, dare consigli, svolgere compiti di traduzione e molto altro. Può essere utilizzato per una vasta gamma di scopi, tra cui assistenza virtuale, tutoraggio online, creazione di contenuti e supporto nella ricerca di informazioni.

#### DALL-E 2
DALL-E è un modello di intelligenza artificiale sviluppato da OpenAI. Può generare immagini originali e creative basate su input testuali. Tuttavia, è importante sottolineare che DALL-E è un modello generativo e non possiede una comprensione semantica completa delle immagini. Pertanto, potrebbe produrre immagini che sembrano corrispondere alla descrizione fornita, ma che contengono dettagli o interpretazioni errate. DALL-E non ha la capacità di comprendere il contesto o il significato delle immagini al di là delle associazioni apprese durante l'addestramento. Inoltre, DALL-E richiede specifiche dettagliate per generare un'immagine e può essere sensibile alla formulazione delle descrizioni. Piccole variazioni nelle istruzioni possono portare a risultati completamente diversi. Quindi, è importante essere precisi nella descrizione dell'immagine desiderata.

#### Fliki.ai
> Fliki è una soluzione text-to-speech e text-to-video che consente di creare contenuti audio e video utilizzando voci simili a quelle umane in meno di un minuto

Fliki è un software gratuito che permette la creazione di contenuti audio e video a partire da semplice testo. È basato sui i migliori motori di sintesi vocale basati sull'intelligenza artificiale sviluppati da leader del settore come Google, Microsoft e Amazon per fornire voci curate tra cui scegliere. I diritti di pubblicazione sono di proprietà dell'utente del contenuto. Le immagini/clip utilizzate sono esenti da diritti d'autore e la musica è priva di copyright, conferendo all'utente i diritti commerciali di qualsiasi piano a pagamento.

### Tecnologie per l'automatismo 

#### Pandoc: conversione dei documenti

> If you need to convert files from one markup format into another, pandoc is your swiss-army knife. [^4]

Pandoc è un software gratuito progettato per la **conversione di documenti** di destinazione presenti in un'ampia varietà di formati. Nato per essere uno strumento flessibile e facile da usare, grazie al suo utilizzo tramite linea di comando, permette un utilizzo facile, veloce ed automatico per convertire istantaneamente i tuoi documenti.

[^4]: https://pandoc.org/

#### GitHub: gestione del versioning

Git è un sistema di **controllo di versione distribuito, gratuito e open source**, progettato per gestire con velocità ed efficienza progetti di ogni tipo, dai più piccoli ai più grandi. [^5]
GitHub è un **servizio di hosting** su Internet per lo sviluppo di software e il controllo delle versioni tramite Git. Fornisce il controllo di versione distribuito di Git più il controllo degli accessi, il bug tracking, le richieste di funzionalità software, la gestione delle attività, l'integrazione continua e i wiki per ogni progetto. [^6]

[^5]: https://git-scm.com/
[^6]: https://docs.github.com


## Conclusioni



### 🔜 Sviluppi futuri

L'elaborato rappresenta, al momento della sua pubblicazione, una fotografia delle tecnologie gratutite attualmente presenti sul mercato ed accessibili a chiunque. Progressivamente con l'evoluzione di queste tecnologie, il prodotto finale potrà mutare ed evolvere insieme ad esse.



