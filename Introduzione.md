# Benvenuti in Swift
***

## Un po' su Swift
Swift è un modo fantastico per scrivere codice, sia per cellulari, desktop, server o qualsiasi altra cosa che esegue codice. È un linguaggio di programmazione sicuro, veloce e interattivo che combina il meglio del pensiero del linguaggio moderno con la saggezza della più ampia cultura ingegneristica di Apple e i diversi contributi della sua comunità open source. Il compilatore è ottimizato per le prestazioni e il linguaggio è ottimizzato per lo sviluppo, senza scendere a compromessi su entrambi.

Swift è facile da capire per i nuovi. È un linguaggio di programmazione di qualità industriale che è espressivo e divertente come un linguaggio di scripting. Scrivere codice Swift in un playground ti permette di sperimentare con il codice e vedere i risultati immediatamente, senza il sovracarico della compilazione e dell'esecuzione di un app.

Swift definisce le grandi classi di comuni errori di programmazione adottando dei moderni patter di programmazione:

*   Le variabili sono sempre inizializzate prima dell'uso.
*   Gli indici degli array sono verificati per gli errori out-of-bounds.
*   Gli Integer sono verificati per l'overflow.
***
*   Gli optional aasicurano che i valori nil siano gestiti esplicitamente.
*   La memoria è gestita automaticamente.
*   La gestione degli errori permette un recupero controllato da fallimenti inaspettati.

Il codice Swift è compilato e ottimizzato per ottenere il meglio dall'hardware moderno. La sintassi e la libreria standard sono state progettate basandosi sul principio guida secondo cui il modo ovvio per scrivere codice dovrebbe anche dare il meglio. La sua combinazione di sicurezza e velocità rende Swift un'eccellente scelta per ogni cosa dal "Hello, world!" a un intero sistema operativo.

Swift combina pontenti inferenze di tipo e corrispondenza di modelli con una sintassi moderna e leggera, permettendo che idee complesse vengano esspresse in un modo chiaro e conciso. Come risultato, il codice non è soltanto più facile da scrivere, ma anche più chiaro da leggere da mantenere.

Swift è stato anni in creazione, ed esso continua ad evolversi con nuove caratteristiche e capacità. Le nostre mete per Swift sono ambiziose. Non vediamo l'ora di vedere cosa creerai con esso.
***
# Compatibilità di versione

Questo libro descrive Swift 4.2, la versione di default di Swift che è inclusa in Xcode 10.0. Puoi usare Xcode 10.0 per compilare target che sono scritti nei precedenti Swift 4 o Swift 3.

> NOTA
>
> Quando il compilatore di Swift 4.2 esegue codice di Swift 3, identifica > la sua versione di linguaggio a 3.4. Di conseguenza, puoi usare blocchi > di compilazione condizionale come #if swift(>= 3.4) per scrivere codice > che è compatibile con versioni multiple di compilatori di Swift.

Quando usi Xcode 9.2 per compilare codice Swift 3, molte delle funzionalità del nuovo Swift 4 sono disponibili. Detto ciò, le seguenti caratteristiche sono disponibili solo con con codice Swift 4:

* Le operazioni di substring ritornano un'istanza del tipo Substring invece di String.
* L'attributo @objc è aggiunto implicitamente in meno posti.
* Le estensioni di un tipo nello stesso file possono accedere ai membri privati di quel tipo.
***

Un target scritto in Swift 4 può dipendere su un target che è scritto in Swift 3, e vice versa. Questo significa, che se hai un progetto grosso che è diviso in più frameworks, puoi migrare il tuo codice da Swift 3 a Swift 4 un framework alla volta.