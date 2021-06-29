.. _problematiche-da-indirizzare-4:

Problematiche da indirizzare
============================

Elenchiamo di seguito le principali problematiche da indirizzare.

Condivisione per la gestione dei dati aggregati e anonimizzati 
---------------------------------------------------------------

La norma, a differenza dell’interoperabilità applicativa, non fornisce
dettagli circa il modello da perseguire ma si limita a definire
**l'obiettivo di condivisione dei dati aggregati e anonimizzati a fini
analitici**, per innescare il processo decisionale della Presidenza del
Consiglio e delle stesse PA con i dati provenienti da più PA.

Nel processo di elaborazione di una politica si possono prevedere due
scenari distinti:

-  **un’analisi ex-ante** per l’individuazione della platea, la scelta
   dello strumento e il fine-tuning degli obiettivi del provvedimento;

-  **una verifica ex-post** dei risultati del provvedimento, anche in
   ottica così detta anti-frode ovvero comportamenti dei fruitori non
   coerenti con gli obiettivi perseguiti.

La norma prescrive che i dati a scopo di policy data-driven siano
aggregati e anonimizzati. Mentre l’anonimizzazione o
pseudo-anonimizzazione non inficerebbero la significatività dei dati e
delle loro analisi sia descrittive che predittive, **l’aggregazione
comporterebbe invece una forte limitazione non definibile a priori del
contenuto informativo**. [1]_

Sarà necessario **definire tutti gli aspetti del ciclo di vita del
dato**, con diversi scenari implementativi per la gestione della
sicurezza e più in generale come già trattato nel capitolo 3 sulla *data
governance*.

Interoperabilità applicativa per lo scambio di dati e servizi
-------------------------------------------------------------

I maggiori ostacoli alla valorizzazione dei dati sono di tipo
**organizzativo, tecnico, semantico e legale**. Gli articoli 50 e 50-ter
del CAD cercano di risolvere alcuni di questi ostacoli - come quelli
legati alla stipula degli accordi d'interoperabilità - ed in particolare
il 50-ter descrive l’approccio da seguire per realizzare la componente
di interoperabilità della Piattaforma Digitale Nazionale Dati (PDND).
Tale piattaforma fornirà un **catalogo di API e dei meccanismi di
autenticazione**, **autorizzazione e auditing degli accessi**. Viene
specificato, inoltre, che la piattaforma dovrà supportare il processo di
accordo tra un erogatore di API ed un fruitore della stessa (accordo di
interoperabilità). A oggi ogni amministrazione che vuole automatizzare
la stipula di accordi di interoperabilità deve costruire una piattaforma
specifica ed accreditare ed identificare separatamente ogni fruitore. Ad
esempio l'ANPR permette ai comuni, dopo essersi accreditati sulla
piattaforma, di fruire dei dati anagrafici per dare servizi ai
cittadini: laddove gli accordi di interoperabilità sono in genere
personalizzati in base agli enti sottoscrittori, quello di ANPR è stato
standardizzato in modo da applicarlo a tutti i comuni. La PDND dovrā
quindi generalizzare il modello di accordo descritto sopra adattandolo a
una modalità “molti a molti”.

Le principali problematiche da affrontare sono:

-  l’\ **automatizzazione degli “accordi di interoperabilità”** in
   ottica “molti a molti” che ha un elevato livello di complessità;

-  l’\ **autenticazione ed autorizzazione** che deriva dagli accordi in
   interoperabilità;

-  il **controllo degli accessi**;

-  l’\ **accesso all'ecosistema delle API pubbliche** **da parte di
   attori terzi** in una logica di integrazione dei dati
   pubblici-privati per una valorizzazione del sistema-dati paese.

L'implementazione di soluzioni tecnologiche utili a semplificare
problemi organizzativi [2]_ richiede un impegno sistematico nella
creazione e **manutenzione di standard di comunicazione e sicurezza
riconosciuti a livello globale**, che non soffrano della frammentazione
tipica delle regole tecniche stabilite in autonomia dai vari stati.
Questo affinché la complessità crescente delle minacce digitali e i
rischi di obsolescenza non limitino il consolidamento di queste
piattaforme. Da un punto di vista semantico è necessario un lavoro
intersettoriale per stabilire e **consolidare una semantica condivisa
dei dati**, senza la quale anche banche dati organizzate in maniera
efficiente hanno bisogno di un grosso lavoro di adattamento manuale per
poter interoperare. [3]_

.. [1]
   Un dato già aggregato vanificherebbe la possibilità di esplorare
   differenti tipologie di aggregazione e di incrocio con altri dati.
   Come ribadito da alcuni partecipanti, l’analisi con un approccio Big
   Data richiede che la granularità del dato sia massima al fine di
   poter estrarre tutto il potenziale informativo. Ciò richiede enfasi
   sulla pseudo-anonimizzazione/anonimizzazione e particolare attenzione
   nel garantire il massimo livello di privacy. Questo approccio è
   esplicitamente previsto nel `Data Governance
   Act <https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX:52020PC0767>`__
   dove non si parla di obbligo di aggregazione dei dati ai fini della
   protezione della *privacy.*

.. [2]
   Previsti per esempio dall’art. 50 ter del CAD, da Regolamenti e
   direttive europee come il Single Digital Gateway Regulation (EU)
   2018/1724 of the European Parliament) o la Payment Service Directive
   2 Directive (EU) 2015/2366.

.. [3]
   Si pensi ad esempio al concetto di famiglia - che nella PA ha una
   declinazione *anagrafica* ed una fiscale: il *nucleo familiare.*
