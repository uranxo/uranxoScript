# uranxoScript (concept)
# Specifiche del linguaggio di programmazione

## Features del linguaggio:
1. Dichiarazione e assegnazione delle variabili:
   - Sintassi: `var nomeVariabile = valore`
   - Esempio: `var numeroMele = 5`

2. Tipizzazione dinamica delle variabili:
   - Sintassi: `var tipo nomeVariabile`
   - Esempio: `var int numeroMele`

3. Operatori aritmetici:
   - Addizione: `+`
   - Sottrazione: `-`
   - Moltiplicazione: `*`
   - Divisione: `/`

4. Operatori di uguaglianza:
   - Uguale a: `==`
   - Diverso da: `!=`

5. Operatori di confronto:
   - Maggiore di: `>`
   - Minore di: `<`
   - Maggiore o uguale a: `>=`
   - Minore o uguale a: `<=`

6. Operatori logici:
   - AND logico: `&&`
   - OR logico: `||`
   - NOT logico: `!`

7. Condizioni condizionali:
   - If, else if, else:
     ```
     if (condizione) {
         # codice da eseguire se la condizione è vera
     } else if (altraCondizione) {
         # codice da eseguire se la condizione è falsa e l'altra condizione è vera
     } else {
         # codice da eseguire se tutte le condizioni precedenti sono false
     }
     ```

8. Cicli di iterazione:
   - Ciclo for:
     ```
     for (inizializzazione, condizione, iterazione) {
         # corpo del ciclo
     }
     ```

   - Ciclo while:
     ```
     while (condizione) {
         # corpo del ciclo
     }
     ```

   - Ciclo do-while:
     ```
     do {
         # corpo del ciclo
     } while (condizione)
     ```

9. Array:
   - Dichiarazione: `var tipo[] nomeArray = {elemento1, elemento2, ...}`
   - Accesso agli elementi: `nomeArray[indice]`

10. Funzioni:
    - Dichiarazione e definizione:
      ```
      func nomeFunzione(parametri) {
          # corpo della funzione
          return valore;
      }
      ```

11. Overloading delle funzioni:
    - Possibilità di definire più funzioni con lo stesso nome ma con parametri diversi.

12. Manipolazione delle stringhe:
    - Concatenazione: `concatenation(stringa1, stringa2)`
    - Lunghezza: `length(stringa)`
    - Accesso ai caratteri: `char(stringa, indice)`
    - Ricerca e sostituzione: `search(stringa, sottostringa)` e `replace(stringa, sottostringaDaSostituire, sottostringaSostitutiva)`
    - Suddivisione: `subdivide(stringa, carattereDelimitatore)`
    - Conversione di case: `uppercase(stringa)` e `lowercase(stringa)`

13. Output:
    - Sintassi: `out: espressione1, espressione2, ... :`
    - Esempio: `out: "Il risultato è ", risultato, :`

14. Input:
    - Sintassi: `inp: nomeVariabile1, nomeVariabile2 :`
    - Esempio: `inp: numeroMele, prezzoUnitario :`

15. Variabili booleane:
    - Dichiarazione: `bool nomeVariabile`
    - Assegnazione: `nomeVariabile = true;` o `nomeVariabile = false`

16. Commenti:
    - Commento su una riga: `# Questo è un commento su una riga`
    - Commento su più righe:
      ```
      #
      Questo è un commento
      su più righe
      #
      ```

17. Funzioni matematiche:
    - Valore assoluto: `absolute(nomeVariabile)`
    - Trasformazione da decimale a intero: `int(nomeVariabile, round/up/down/none, cifreDecimaliDaLasciare)`

18. Numeri casuali:
    - Numero casuale: `random()`
    - Intervallo numerico: `random(min, max)`

# 
# Sintassi del Linguaggio di Programmazione

1. Dichiarazione delle variabili:
   - Dichiarazione con tipo esplicito: `var tipoVariabile nomeVariabile`
   - Tipi di variabili:
     - `int ` variabili intere
     - `dec` variabili decimali
     - `lect` variabili stringhe
   - Dichiarazione con assegnazione: `var tipoVariabile nomeVariabile = valore`

2. Operatori aritmetici:
   - Addizione: `+`
   - Sottrazione: `-`
   - Moltiplicazione: `*`
   - Divisione: `/`
   - Modulo: `%`
   - Incremento: `++`
   - Decremento: `--`

3. Operatori di uguaglianza:
   - Uguale a: `==`
   - Diverso da: `!=`
   - Maggiore di: `>`
   - Minore di: `<`
   - Maggiore o uguale a: `>=`
   - Minore o uguale a: `<=`

4. Operatori logici:
   - And logico: `&&`
   - Or logico: `||`
   - Not logico: `!`

5. Condizioni condizionali:
   - If-else: 
     ```
     if (condizione) {
         # blocco di codice se la condizione è vera
     } else {
         # blocco di codice se la condizione è falsa
     }
     ```
   - Else-if: 
     ```
     if (condizione1) {
         # blocco di codice se la condizione1 è vera
     } else if (condizione2) {
         # blocco di codice se la condizione2 è vera
     } else {
         # blocco di codice se nessuna delle condizioni è vera
     }
     ```

6. Cicli:
   - Ciclo for:
     ```
     for (inizializzazione, condizione, incremento/decremento) {
         # blocco di codice da eseguire
     }
     ```
   - Ciclo while:
     ```
     while (condizione) {
         # blocco di codice da eseguire
     }
     ```
   - Ciclo do-while:
     ```
     do {
         # blocco di codice da eseguire
     } while (condizione)
     ```

7. Array:
   - Dichiarazione: `tipoVariabile[] nomeArray = {valore1, valore2, ...}`
   - Accesso agli elementi: `nomeArray[indice]`

8. Manipolazione delle stringhe:
   - Concatenazione: `concatenation(stringa1, stringa2)`
   - Lunghezza: `length(stringa)`
   - Accesso ai caratteri: `char(stringa, indice)`
   - Ricerca e sostituzione: 
     - Ricerca: `search(stringa, sottostringa)`
     - Sostituzione: `replace(stringa, sottostringaDaSostituire, sottostringaSostitutiva)`
   - Suddivisione: `subdivide(stringa, carattereDelimitatore)`
   - Conversione di case: 
     - Maiuscolo: `uppercase(stringa)`
     - Minuscolo: `lowercase(stringa)`

9. Output:
   - Sintassi: `out : valore1, valore2, ... :`
   - Esempio: `out : "Oggi ho comprato ", numeroMele + 1, " mele al prezzo di ", 10 / 2, " euro" :`

10. Input:
    - Sintassi: `inp : nomeVariabile1, nomeVariabile2 :`
    - Esempio: `inp : nomeVariabile :`

11. Variabili booleane:
    - Dichiarazione: `bool nomeVariabile`
    - Assegnazione: `nomeVariabile = true/false`

12. Commenti:
    - Commento su una riga: `# commento su una riga`
    - Commento su più righe:
      ```
      #
      commento su
      più righe
      #
      ```

13. Operazioni matematiche aggiuntive:
    - Valore assoluto: `absolute(nomeVariabile)`
    - Conversione da decimale a intero:
      ```
      int(nomeVariabile, up/down/round/none, cifreDecimaliDaLasciare)
      ```

14. Numeri casuali:
    - Numero casuale: `random()`
    - Intervallo specifico: `random(min, max)`
