Creazione di un Applicazione Oracle Apex SQL che permetta di accedere a dati contenuti in un Database Oracle creato seguendo questa traccia:

Un’agenzia spaziale internazionale sta sviluppando un sistema informatico per consentire la 
gestione e l’analisi avanzata dei dati raccolti durante le missioni di esplorazione lunare. 
Ciascuna missione prevede l’utilizzo di sensori avanzati posizionati in diverse regioni della 
superficie lunare e di robot autonomi che supportano le operazioni sul campo, insieme a un 
team di specialisti in orbita. Il sistema ha l’obiettivo di coordinare in tempo reale le attività dei 
membri della missione, gestire i dati provenienti dai sensori e consentire un monitoraggio 
completo e dettagliato delle operazioni in corso.

Si suppone che ogni MISSIONE sia identificata da un codice e caratterizzata da un obiettivo 
specifico, come la mappatura geologica o il rilevamento di risorse. Per ogni missione è 
necessario memorizzare la data di inizio, la data di fine e lo stato attuale che indica se la 
missione è pianificata, in corso, completata o annullata. Inoltre, per ogni missione si vogliono 
memorizzare tutte le informazioni relative ai MEMBRI DELL’EQUIPAGGIO assegnati e le 
risorse impiegate, ossia i SENSORI e i ROBOT coinvolti. 

Ogni membro dell’equipaggio, identificato da un codice e caratterizzato da nome, cognome e ruolo, è responsabile della 
gestione delle operazioni di manutenzione e riparazione dei sensori. Si suppone che ogni 
sensore installato sulla superficie lunare sia identificato da un ID univoco e che venga 
registrato in base alla posizione geografica tramite coordinate tridimensionali (latitudine, 
longitudine ed altitudine). Ogni sensore è caratterizzato da una tipologia specifica (come 
temperatura, pressione, gas, radiazioni o geologia) e sono memorizzate la data di 
installazione e la data dell’ultimo controllo. Per ciascun sensore, si tiene traccia dello stato 
operativo, che può essere attivo, in standby, in manutenzione o malfunzionante, e tale stato 
può essere verificato anche dai membri dell’equipaggio. Si suppone che i robot autonomi 
siano utilizzati come supporto tecnico e siano identificati da un ID univoco e caratterizzati dalla 
tipologia (ad esempio, “esplorazione”, “manutenzione”, “raccolta risorse”, etc.).

Si suppone che il sistema debba memorizzare ogni RILEVAZIONE effettuata da un sensore, registrando 
la data e l’ora della misurazione ed il valore rilevato. Inoltre, un sensore può entrare in uno 
stato di ANOMALIA ed in tal caso devono essere memorizzati data e ora, livello di priorità (da 
bassa a critica), causa dell’anomalia (ad esempio, “sovraccarico energetico”, “tempesta di 
polveri”, etc.). Per risolvere un’anomalia, è possibile avviare un INTERVENTO che può 
coinvolgere uno o più membri dell’equipaggio. Ogni intervento, identificato da un codice 
univoco e da una descrizione (ad esempio, “riparazione”, “calibrazione” o “sostituzione”). Ogni 
intervento a valle di un’anomalia è caratterizzato da una data prefissata di esecuzione 
dell’intervento ed esito dell’intervento. 
Infine, si prevede che ogni membro dell’equipaggio possa compilare REPORT sullo stato di una missione.

(Le parole in MAIUSCOLO sono entità)
