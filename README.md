# Relazione progetto - Editoria Digitale - Lorenzo Bruno

## Oggetto del progetto

L'elaborato finale del progetto è uno  **showcase** riguardo l'utilizzo dell'intelligenza artificiale nell'editoria digitale. 

## Obiettivi

L'obiettivo è quello di illustrare in modo chiaro e coinvolgente come l'intelligenza artificiale sta trasformando l'editoria digitale, offrendo nuove opportunità di innovazione e migliorando l'esperienza di lettura per gli utenti. L'elaborato vuole mettere in luce le potenzialità delle intelligenze artificiali e stimolare la riflessione su come queste tecnologie possano essere integrate in modo responsabile e sostenibile nel settore dell'editoria digitale, ponendo anche un occhio di riguardo sui limiti attuali delle tecnologie presenti.

## Processo di produzione

Per creare il showcase, utilizzerò una combinazione di presentazioni visive, video esplicativi e demo interattive. La presentazione visiva sarà strutturata in modo da fornire una panoramica chiara e concisa dei principali ambiti in cui l'intelligenza artificiale viene impiegata nell'editoria digitale, come la scrittura assistita, la creazione e personalizzazione di contenuti multimediali come audio, immagini o video.

### Studio e analisi del tema

* Studio del mercato:



* Definizione del target:


* Obiettivi comunicativi:


* Definizione dei formati:



### Stesura della bozza

* Punti da trattare

* Sviluppo dei contenuti:

    contenuti indifferentemente se destinati al pdf, alla pagina web o alla parte video/audio

* Stesura requisiti di accessibilità

* Inserire modalità di ricezione feedback

### Revisione dei contenuti

* Rilettura dei contenuti e perfezionamento
* Differenziazione degli elementi destinati alle diverse tecnologie
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

### Verifica post produzione

* Verifica degli eventuali feedback e conseguente revisione del prodotto

**N.B.:** questo processo di produzione non ho voluto appositamente aggiornarlo in modo da far vedere l'evoluzione del progetto man mano che il prodotto prendesse forma. Non viene infatti in alcun momento citato il tool mdBook. La parte di gestione documentale invece è fedele all'effettiva evoluzione del lavoro.

### Gestione documentale


### Struttura effettiva del contenuto


La struttura del manuale sarà la seguente: 

* Indice analitico 
* Contenuto nella scatola
* Installazione base
* Installazione avanzata
* Utilizzo del software dedicato
* Reset allo stato di fabbrica
* Shortcut di default
* Indicazioni legali
* Copyright

L'indice sarà generato in maniera automatica tramite un tool.

## Regole di accessibilità

### WAI-ARIA: Web Accessibility Initiative - Accessible Rich Internet Applications

WAI-ARIA definisce un modo per rendere i contenuti e le applicazioni Web più **accessibili alle persone con disabilità**. È particolarmente utile per i contenuti dinamici e i controlli avanzati dell'interfaccia utente sviluppati con HTML, JavaScript e tecnologie correlate. Senza WAI-ARIA alcune funzionalità utilizzate nei siti Web non sono disponibili per alcuni utenti con disabilità, in particolare per coloro che si affidano a lettori di schermo e per coloro che non possono utilizzare il mouse.[^3]

#### WAI-ARIA Roles

I ruoli ARIA possono essere usati per descrivere elementi che non esistono nativamente nell'HTML o che esistono ma non hanno ancora il pieno supporto del browser.

####  DPUB-ARIA
Il modulo Digital Publishing WAI-ARIA (DPUB-ARIA) è un'estensione della specifica ARIA. Fornisce un insieme aggiuntivo di ruoli specifici per l'editoria da utilizzare con l'attributo role di ARIA. I ruoli editoriali hanno lo scopo di migliorare l'usabilità delle pubblicazioni, sia fornendo alle tecnologie assistive (AT - assistive technologies) informazioni aggiuntive su strutture importanti, sia garantendo l'accessibilità dei comuni idiomi di markup editoriale. I ruoli non sono intesi come un meccanismo per la semantica del flusso di lavoro e quindi non forniscono la stessa ampiezza di copertura, ad esempio, del vocabolario EPUB Structural Semantics. È necessario prestare attenzione sia al numero di ruoli utilizzati sia al modo in cui vengono utilizzati, poiché un uso scorretto può compromettere la capacità degli utenti di consumare in modo accessibile una pubblicazione. di consumare una pubblicazione in modo accessibile.[^2]

I ruoli utilizzati all'interno del documento sono i seguenti

##### doc-chapter

**doc-chapter** è un landmark role tipicamente utilizzato all'interno di una section per definire una sezione tematica importante del contenuto di un'opera.

[^2]: http://kb.daisy.org/publishing/docs/html/dpub-aria/index.html
[^3]: https://www.w3.org/WAI/standards-guidelines/aria/


## Tecnologie adottate per l'automatismo

### Pandoc: conversione dei documenti

> If you need to convert files from one markup format into another, pandoc is your swiss-army knife. [^4]

Pandoc è un software gratuito progettato per la **conversione di documenti** di destinazione presenti in un'ampia varietà di formati. Nato per essere uno strumento flessibile e facile da usare, grazie al suo utilizzo tramite linea di comando, permette un utilizzo facile, veloce ed automatico per convertire istantaneamente i tuoi documenti.

[^4]: https://pandoc.org/

#### GitHub: gestione del versioning

Git è un sistema di **controllo di versione distribuito, gratuito e open source**, progettato per gestire con velocità ed efficienza progetti di ogni tipo, dai più piccoli ai più grandi. [^5]
GitHub è un **servizio di hosting** su Internet per lo sviluppo di software e il controllo delle versioni tramite Git. Fornisce il controllo di versione distribuito di Git più il controllo degli accessi, il bug tracking, le richieste di funzionalità software, la gestione delle attività, l'integrazione continua e i wiki per ogni progetto. [^6]

[^5]: https://git-scm.com/
[^6]: https://docs.github.com


### Evoluzione

L'elaborato rappresenta, al momento della sua pubblicazione, una fotografia delle tecnologie gratutite attualmente presenti sul mercato ed accessibili a chiunque. Progressivamente con l'evoluzione di queste tecnologie, il prodotto finale potrà mutare ed evolvere insieme ad esse.

### Conclusioni



