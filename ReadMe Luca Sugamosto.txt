Progetto ML - Studente: Luca Sugamosto, matricola 0324613
Il progetto scelto è "Traccia A1 - Riconoscimento di immagini MNIST-like - Extended Mnist"
------------------------------------------------------------------------------------------
La cartella "Progetto ML - Luca Sugamosto" contiene al suo interno:

1) Il file "emnist-letters.csv", contenente tutti i dati da utilizzare come Data Set.
2) Il file "projectML_LucaSugamosto.ipynb" contenente il codice vero e proprio che si compone dei seguenti punti:

2.1) Nella 1° parte, in cui è presente un metodo per l'addestramento della rete neurale composto da funzioni
   statiche; per esempio la struttura della rete da addestrare è definito dall'utente sulla base di riscontri ottenuti
   durante lo studio dei dati ottenuti.
   Inoltre, sono stati considerati tre algoritmi di ottimizzazione dei parametri (w, b): SGD, RMSProp, Adam;
   tutti con un valore di learning rate pari a 0.001 (default).

2.2) Nella 2° parte, dove viene definita una funzione per la creazione della rete neurale e si usa la classe
   per generare modelli diversi tra loro, questo permette di addestrare modelli diversi, ognuno con specifici valori
   di iperparametri. Alla fine vengono restituiti gli iperparametri del modello che ha ottenuto risultati migliori ed 
   In questo caso l'utente può scegliere il range di valori ammissibili per gli iperparametri ed il numero di modelli
   diversi da generare e quindi analizzare.

2.3) Nella 3° parte, in cui viene inizializzata una Convolutional Neural Network (leNet-5).
   Questa ha una struttura fissa ben definita composta da determinati strati e numero di neuroni.
   Inoltre come algoritmo di ottimizzazione è usato l'Adam, con tasso di apprendimento di default pari a 0,001.
   In questo caso si è studiato il comportamento della stessa CNN al variare della funzione di attivazione negli
   strati nascosti (in un caso la "sigmoid" ed in un altro la "relu").