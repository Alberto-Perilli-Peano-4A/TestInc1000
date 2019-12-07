# TestInc1000

Il programma TestInc1000 incrementa di mille un contatore statico per ogni ogetto appartenente alla classe, e lo stampa.

## Parte 1:

Nella prima parte il programma non esegue correttamente il suo copito poichè essendo la classe Inc1000 è un trhead, essa lavora in modo indipendente dal main. Ciò comporta che il main potrebbe concludersi prima che il contatore abbia raggiunto il numero richiesto, mandando così in output un numero molto inferiore a quello che ci si aspetterebbe.

**NB : Il trhead contnua comunque a lavorare in background fino al raggiungimento del numero richiesto.**

