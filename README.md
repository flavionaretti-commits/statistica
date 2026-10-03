# STATISTICA!

Laboratorio didattico interattivo di statistica e probabilità.

## Modalità disponibili

### 🎲 Dadi da gioco
- da 1 a 6 dadi a sei facce
- lanci manuali cumulativi
- simulazioni fino a 1.000.000 di lanci
- istogramma della somma dei dadi
- distribuzione teorica esatta

### 🪙 Monete
- da 1 a 6 monete
- esiti TESTA / CROCE
- con più monete viene registrato il numero di teste
- distribuzione binomiale teorica con p = 0,5

### 🔴 Palline / Urna
- urna configurabile con 6 colori
- da 0 a 20 palline per colore
- estrazioni con o senza reintroduzione
- probabilità aggiornate quando non c'è reintroduzione
- simulazioni e istogramma per colore

### 🃏 Carte
- mazzo standard da 40 carte: A, 2–7, Fante, Donna, Re nei semi Cuori, Quadri, Fiori e Picche
- mazzo personalizzabile carta per carta
- selezione rapida di tutte le carte, nessuna, numerali, figure o assi
- selezione/deselezione di un intero seme o valore dalla griglia
- pescate con o senza reintroduzione
- simulazioni fino a 1.000.000 di pescate con reintroduzione
- simulazioni senza reintroduzione fino all'esaurimento del mazzo
- analisi della stessa serie per seme, valore, tipo o colore rosso/nero
- confronto teorico quando le pescate sono con reintroduzione
- esportazione CSV dell'analisi corrente

## Funzioni comuni
- frequenze assolute e relative
- confronto osservato / teorico quando appropriato
- statistiche riassuntive adattate al tipo di esperimento
- esportazione CSV
- modalità PROIEZIONE dell'istogramma per LIM e uso in classe
- modalità giorno/notte, fullscreen e suoni
- PWA installabile e utilizzabile offline

### 🎡 Roulette
- tavolo completo con numeri 0–36 e principali puntate esterne
- versione europea con 0 singolo oppure americana con 0 e 00
- giri manuali e simulazioni
- analisi per numero, colore, pari/dispari, 1–18/19–36, dozzine e colonne
- confronto con le probabilità teoriche
- modalità GIOCO con saldo e fiche esclusivamente virtuali
- puntate virtuali su numero pieno, rosso/nero, pari/dispari, basso/alto, dozzine e colonne
- quote virtuali standard: 35:1 sul pieno, 2:1 su dozzine/colonne, 1:1 sulle chance semplici
- modalità MARTINGALA come laboratorio matematico su puntate virtuali rosso/nero
- tre scenari: capitale + massimale, solo capitale, modello ideale con risorse illimitate
- raddoppio automatico dopo una perdita e ritorno alla puntata base dopo una vincita
- simulazione di un singolo giro, di N giri o fino al blocco della strategia
- cruscotto con saldo, puntata corrente, puntata massima, serie negativa massima e volume totale puntato
- grafico dell'andamento del capitale
- evidenza della perdita attesa legata al vantaggio del banco
- esportazione CSV e modalità PROIEZIONE

### 🎱 Tombola
- tabellone completo da 1 a 90
- estrazione manuale senza reintroduzione
- cartella 3×9 da 15 numeri generata automaticamente
- marcatura automatica dei numeri estratti
- riconoscimento di ambo, terno, quaterna, cinquina e tombola
- analisi delle estrazioni per decine, pari/dispari, 1–45/46–90 o numero
- simulazione di molte partite per studiare il tempo di attesa di ciascun premio
- esportazione CSV e modalità PROIEZIONE

### ⚙️ Macchina di Galton
- da 4 a 16 file di pioli, con n+1 canali finali
- caduta animata di una singola pallina per seguire ogni deviazione
- sinistra/destra equiprobabili, interpretabili come CROCE/TESTA
- accumulo visivo delle palline nei canali finali
- simulazioni rapide fino a 1.000.000 di palline
- istogramma della posizione finale
- confronto con la distribuzione binomiale teorica
- frequenze assolute/relative, statistiche, PROIEZIONE ed esportazione CSV

### 🔵 Eventi · fasi 1 e 2
**Fase 1 · SOMMA**
- spazio campionario di un dado equilibrato: Ω = {1,2,3,4,5,6}
- costruzione libera di due eventi A e B selezionando direttamente gli esiti
- diagramma di Venn dinamico con A, B, intersezione e risultati esterni
- previsione prima del verdetto su eventi compatibili/incompatibili
- due preset non-spoiler: pari / maggiore di 3 e pari / dispari
- calcolo di P(A), P(B), P(A∩B) e P(A∪B)
- costruzione della regola della somma e semplificazione automatica per eventi incompatibili
- lanci singoli e simulazioni da 10, 100 o 1.000 prove

**Fase 2 · PRODOTTO**
- urna configurabile con palline rosse e blu
- due estrazioni con o senza reintroduzione
- A = prima pallina rossa; B = seconda pallina rossa
- previsione non-spoiler su eventi dipendenti/indipendenti
- confronto tra P(B) e P(B|A)
- diagramma ad albero con i quattro percorsi RR, RB, BR e BB
- regola generale P(A∩B) = P(A) · P(B|A)
- semplificazione P(A∩B) = P(A) · P(B) nel caso indipendente
- estrazioni singole e simulazioni da 10, 100 o 1.000 coppie
- confronto tra frequenza sperimentale di RR e probabilità teorica

## Crediti
Ideazione e progettazione didattica: prof. Flavio Naretti.  
Sviluppo dell'app in collaborazione con ChatGPT · OpenAI.  
© 2026 prof. Flavio Naretti · uso didattico.

STATISTICA! comprende ora dadi, monete, urna, carte, roulette, tombola, macchina di Galton e un laboratorio sugli eventi probabilistici.

© prof. Flavio Naretti