# Analisi e sperimentazione di attacchi Return Oriented Programming (ROP)
Summary: 
Nell’ultimo ventennio, la tecnica di attacco informatico denominata Return Oriented Programming
(ROP) si è distinta dalle altre grazie alle sue capacità di adattamento alle
moderne architetture dei processori e di elusione delle tradizionali strategie di difesa quali
la NX/DEP (No-execute/ Data Execution Prevention) e la ASLR (Address Space Layout
Randomization).
In questo lavoro di tesi, inizialmente, verranno illustrati i concetti su cui si basa la ROP,
quali ad esempio la sezione di memoria stack ed i principali registri del processore, necessari
a comprendere interamente le sue potenzialità.
Successivamente, verrà analizzato l’impiego e la sperimentazione di essa mediante dei test
effettuati su del codice in determinate condizioni, sfruttando alcune delle più conosciute e
critiche vulnerabilità. Ogni test realizzato avrà come obiettivo l’applicazione personalizzata
della tecnica in base alla situazione, per poter poi sviluppare efficaci attacchi anche in
presenza di diversi sistemi di difesa. In conclusione, verranno proposti dei metodi di difesa
per proteggere il codice da attacchi realizzati con questa potente ed efficace tecnica.
