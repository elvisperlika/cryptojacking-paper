<h1 align="center">Cryptojacking: quando il tuo personal computer lavora per qaualcun altro.</h1>

<h2 align="center">Abstract</h2>
Il Cryptojacking, in Italiano "Dirottamento di risorse", è una forma di attacco informatico che sfrutta la 
potenza di calcolo di un utente, senza che esso ne sia consapevole, per minare criptovalute. [1]

L'obiettivo degli hacker è quello di prendere il controllo del maggior numero possibile di sistemi al 
fine di minare quante più criptovalute. Questo sistema di hacking non punta unicamente la classica 
utenza di Personal Computer ma cerca di sfruttare anche le risorse di Server, infrastrutture Cloud 
e in generale ogni tipologia di macchina computazionale con un accesso alla rete Internet.

La caratteristica fondamentale di questo malware è far sì che la vittima sia ignara dei processi 
in background, i quali effettuano il mining, e permettergli di usare la propria macchina normalmente. 
Ovviamente, il tutto, a discapito di un sovraccarico della macchina e conseguente surriscaldamento, 
presenza di lag, maggior consumo elettrico (che nel caso di servizi Server o Cloud porta ad avere 
fatture particolarmente elevate) e riduzione delle performance generali. È nelle skills del cyber-criminale 
riuscire a mantenere questi effetti collaterali il più nascosti possibile se vuole mantenere 
il controllo della macchina per il maggior tempo possibile.

Questo paper si propone di analizzare il fenomeno del cryptojacking, i metodi di attacco, le tecnologie 
coinvolte e i relativi aspetti tecnici per poi esporre le contromisure per prevenire e individuare 
questi malware all'interno delle proprie macchine. In particolare, nella sezione "Aspetti Tecnici" 
si andrà ad analizzare nel dettaglio il mining di Monero, una delle criptovalute più utilizzate per 
il cryptojacking e l'algoritmo RandomX (che ha sostituito CryptoNight), utilizzato per minare Monero.
