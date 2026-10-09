# Osservazioni — Esercitazione 0

Gruppo:

Componenti (Lavinia Micocci laviniamicocci, Anna Lucia Orecchini orecchini2260654):

URL del repository condiviso: https://github.com/laviniamicocci/esercitazione-0-template.git

Chi ha usato la tastiera nello step 1 e nello step 2: entrambe 

Compilate insieme le osservazioni e discutete le risposte: entrambi dovete
saper spiegare le prove svolte.

## Step 1 — Hello World: compilazione ed esecuzione

Comando di compilazione: gcc -std=c17 -Wall -Wextra -Wpedantic hello.c -o hello

Comando di esecuzione e risultato osservato:./hello. Il terminale stampa "hello computational physics!"

Che cosa ho capito su sorgente ed eseguibile: la sorgente è hello.c, file in c dove sc5riviamo il programma. quando lo compiliamo il terminale crea il file eseguibile hello che è tradotto in un linguaggio eseguibile dalla macchina.

Output richiesto e comportamento del programma prima della modifica: prima della modifica il programma non stampava nulla, poichè non era presente il comando printf. 

Esito dopo la modifica e spiegazione della correzione: dopo aver aggiunto il comando printf viene stampata la frase "hello computational physics!"

## Step 1 — Git

Quali file ho incluso nel commit e perché: hello.c e osservazionib.md perche sono gli unici file che abbiamo modificato

Come ho verificato che la versione provata sia presente su GitHub: guardando la cronologia dei commit

Che cosa ho osservato prima e dopo `git pull`, e perché non serve un nuovo clone: prima su github c'era la versione vecchia, non modificata da noi sul terminale, dopo il git pull le modifiche che abbiamo fatto da github ai file sono apparse anche nei file sul terminale.

## Step 2 — Eco: prima prova

Argomenti passati, comando e risultato: abbiamo provato dando al programma argomenti diversi e anche sbagliati (come lettere o numeri numeri misti a lettere al posto dell'intero e del reale, numeri al posto di lettere)  o di un numero diverso da quello giusto (più o meno di 4).

Che cosa posso concludere: se scrivo una stringa priva di numeri al posto di un intero o di un reale atof e atoi resistituiscono 0.0 o 0. 
se scrivo un numero invece che una parola al primo argomento, stampa il numero. per scrivere un testo con uno spazio, lo scrivo tra virgolette.

## Step 2 — Eco: seconda prova

Argomenti passati, comando e risultato:

Che cosa ho capito su testo, conversioni e stampa:

## Step 2 — Risultato ed errori

Previsioni per l'esecuzione con argomenti validi e per quella con `dodici`: quella con dodici avrà uno zero come secondo argomento

Contenuto di `eco.txt`, messaggi nel terminale e codici di uscita osservati: eco.txt contiene l'output del programma. se vengono inseriti argomenti sbagliati, echo$? restituisce un numero diverso da 0. se gli argomenti sono corretti, restituisce 0.

Come un controllo automatico può riconoscere un errore: con il numero restituito dalla funzione main

## Step 2 — Parametri e calcolo fisico

Quando serve ricompilare e quando basta cambiare gli argomenti: dipende da come è scritto il programma. se gli argomenti sono della variabili alle quali l'utente assegna il valore allora non serve ricompilare:infatti in questo caso non serve modificare il codice per cambiare gli argomenti. se invece il valore viene scritto direttamente nel file .c allora bisognerà ricompilare.

## Step 2 — Git

Come riconosco nella cronologia i commit dei due step:

Come ho verificato che la versione finale sia presente su GitHub:
