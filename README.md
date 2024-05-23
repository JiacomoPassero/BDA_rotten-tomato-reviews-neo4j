Per scaricare il dataset sono necessaria chiavi Kaggle da integrare nel progetto.

Deve essere creato database neo4j e avviato prima dell'esecuzione della parte denominata "Creazione database Neo4j", le credenziali di base di accesso sono:

username: neo4j

password: pomodoro

ma possono essere cambiate a piacimento.


Durante l'esecuzione del notebook sarà necessario di aggiungere dei file generati alla directory import del progetto neo4j creato.

Due query di creazione pur essendo sintatticamente corrette vanno in errore se lanciate da driver in python, purtroppo non ho trovato la causa del problema e le stesse query lanciate da terminale cypher funzionano
senza problemi quindi per la parte di popolamento del dataset, in particolare dei nodi Movie e dei link REVIEWS sarà necessario un ulteriore step manuale lanciando le query di creazione di nodi, link e indici da terminale.

Tutte le altre operazioni compreso quelle di download del dataset da kaggle sono svolte eseguendo il notebook il codice.

Il notebook contiene assieme al codice le riflessioni sul dataset e sui risultati ottenuti dalla data analysis.
