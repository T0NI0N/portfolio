---
layout: default
---

## Riassunto ed estratto tesi

### Capitolo 1: Introduzione

Con l'avvento dell'informatica quantistica, la sicurezza degli attuali sistemi crittografici che si basano sulla difficoltà di alcuni problemi matematici risulta potenzialmente compromessa. Le potenti capacità di calcolo dei computer quantistici possono potenzialmente attaccare e violare questi sistemi crittografici e compromettere la riservatezza, l'integrità e l'autenticità delle comunicazioni.  
La crittografia post-quantistica è una branca della crittografia che mira a sviluppare sistemi crittografici in grado di resistere agli attacchi dei computer quantistici. Questi sistemi sono progettati sulla base di problemi matematici ritenuti difficili anche per i computer quantistici. Sono stati proposti molti schemi crittografici post-quantistici, tra cui la crittografia basata su reticoli.  

La crittografia basata sugli attributi (_Attribute Based Encryption_ - ABE) è un tipo di crittografia che consente al proprietario dei dati di specificare le politiche di accesso in base agli attributi degli utenti. Ciò significa che solo gli utenti in possesso degli attributi richiesti possono accedere ai dati cifrati. ABE ha diverse applicazioni, come la condivisione sicura dei dati e il controllo degli accessi.  
La combinazione di crittografia post-quantistica e crittografia basata sugli attributi può fornire una maggiore sicurezza e privacy per diverse applicazioni, dove la prima garantisce sicurezza dal punto di vista di attacchi a forza bruta, mentre la seconda permette di non fidarsi di chi memorizza i dati, essendo cifrati, e di chi decide chi è autorizzato ad accedervi, essendo deciso da complesse operazioni matematiche.  

In questo lavoro di tesi verrà analizzata la progettazione e l'implementazione di schemi di crittografia post quantistica basati su attributi. L'obiettivo è fornire uno studio completo degli schemi ABE post-quantistici esistenti, delle loro proprietà di sicurezza e delle loro prestazioni. Per raggiungere tali obiettivi, viene innanzitutto fornita una panoramica completa della letteratura sulla crittografia post-quantistica e sulla crittografia basata sugli attributi, esaminando i problemi matematici e le ipotesi di base, nonchè i pro e i contro di tale tecnologia. In conclusione, viene mostrata una possibile implementazione di ABE in un determinato scenario applicativo, includendo anche l'analisi della performance in accordo con il livello di sicurezza richiesto.  

Struttura:
- Capitolo 2 - Background sulle tecnologie coinvolte: panoramica sulle attuali tecnologie coinvolte, a partire dai computer quantistici, spiegandone le proprietà più significative, illustrando poi come l'applicazione di tali proprietà risulti nello sviluppo di nuovi e più potenti algoritmi, le cui applicazioni risulteranno fondamentali nei problemi di ricerca e calcolo, destando allo stesso tempo preoccupazione per quanto riguarda la sicurezza. In seguito verrà analizzato l'impatto sulla crittografia di tali scoperte, valutando gli attuali studi di varie soluzioni post quantistiche, con particolare attenzione alle direttive del NIST, un'agenzia del governo degli Stati Uniti d'America che si occupa della gestione delle tecnologie;
- Capitolo 3 - _Attribute-Based Encryption_: presentazione dello schema di cifratura basato su attributi, delle sue caratteristiche principali, modalità di utilizzo, operazioni fondamentali, gestione delle chiavi e dei pro e contro di tale approccio. Inoltre, in una sezione dedicata, viene discusso il sottostrato matematico che rende lo schema sicuro contro dei possibili attacchi da parte di un computer quantistico, ovvero la crittografia basata su reticoli;
- Capitolo 4 - Stato dell'arte: confronto sulle tecnologie già presenti e studiate in letteratura con approcci più moderni e ancora in fase di sviluppo, riguardante sia la crittografia post quantistica, sia le implementazioni vere e proprie di algoritmi e schemi proposti nel corso degli anni;
- Capitolo 5 - Soluzione proposta: definizione e descrizione di una possibile implementazione dello schema ABE in ambito industriale, al fine di rendere sicuri i dati sensibili di utenti e segreti industriali, includendo delle possibili politiche di accesso e insiemi di attributi per gli utenti, simulandone il comportamento attraverso l'utilizzo di codice scritto ad-hoc a tale scopo;
- Capitolo 6 - Analisi performance: valutazione del tempo di esecuzione delle operazioni primitive dello schema CP-ABE, al variare dei parametri di sicurezza e al numero degli attributi utilizzati, confrontando anche le diverse modalità di generazione delle chiavi, includendo anche la valutazione della soluzione proposta simulando su un calcolatore l'uso contemporaneo dello schema da parte di più utenti;
- Capitolo 7 - Conclusioni: include il riassunto del lavoro svolto, il riepilogo dei risultati ottenuti e proposte per ulteriori sviluppi futuri.


[Indietro](./README.md)
