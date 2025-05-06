# Esercizi Linux – comandi base

**Obiettivo:** esercitarsi con i comandi base visti a lezione:  
`pwd`, `ls`, `cd`, `mkdir`, `touch`, `mv`, `cp`, `echo`, `cat`, redirezione `>`, `>>`

---

## Esercizio 1 – Struttura di base
Crea questa struttura all'interno della cartella Desktop:
```
esercizioLinux/
├── documenti/
│   ├── appunti.txt
│   └── todo.txt
├── immagini/
│   └── foto1.jpg
└── backup/
```
**Comandi utili:** `mkdir`, `touch`

---

## Esercizio 2 – Scrivere e leggere file
1. Inserisci nel file `appunti.txt` la frase:  
   `Oggi ho imparato i comandi base di Linux.`
2. Aggiungi:  
   `Il comando ls serve per elencare i file.`
3. Visualizza il contenuto con:
   ```bash
   cat appunti.txt
   ```
   
**Comandi utili:** `echo`, `>`, `>>`, `cat`

---

## Esercizio 3 – Spostamenti e copie
1. Sposta `foto1.jpg` da `immagini` a `backup`
2. Copia `todo.txt` da `documenti` a `backup`
3. Rinomina `todo.txt` in `attività.txt` nella cartella `documenti`

**Comandi utili:** `mv`, `cp`

---

## Esercizio 4 – Creazione di file dinamici
Crea un file chiamato `contenutoBackup.txt` che contenga l’elenco dei file presenti nella cartella `backup`.

---

## Esercizio 5 – Percorsi
Scrivi in un file chiamato `percorso.txt` il percorso assoluto della cartella `esercizioLinux`

**Comandi utili:** `pwd`, `>`