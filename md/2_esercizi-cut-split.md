# Esercizi sui comandi `cut` e `split`

Crea il file `studenti.txt` utilizzando l'editor di testo `nano` con il seguente contenuto:
```
Marco;Rossi;3A;7
Giulia;Bianchi;3B;8
Luca;Verdi;3A;6
Sara;Neri;3C;9
Francesco;Russo;3B;5
Elena;Gallo;3C;7
Andrea;Conti;3A;6
Martina;Costa;3B;8
Davide;Ferrari;3C;7
Chiara;Romano;3A;9
```
Ricorda di salvare il contenuto del file con `ctrl + O` e uscire dall'editor con `ctrl + X`.

Utilizza i comandi `cut` e `split` per risolvere le seguenti richieste:

1. Estrai **il primo carattere** di ogni riga.
2. Estrai **i primi 5 caratteri** da ogni riga.
3. Estrai solo il **cognome** (secondo campo).
4. Estrai **nome e voto** dal file (primo e quarto campo).
5. Dividi il file in parti da **2 righe** ciascuno.
6. Dividi il file in due parti da **5 righe**, usando il prefisso `parte_`.
7. Dividi il file in parti da **1 riga**, usando il prefisso `studente_`.
8. Estrai solo i **nomi** (primo campo) con `cut`, poi dividi il risultato in gruppi da 3 con `split`.