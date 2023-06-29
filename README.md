# uranxoScript
My own programming lenguage
# Specifiche del linguaggio di programmazione

## Features del linguaggio:
1. Dichiarazione e assegnazione delle variabili:
   - Sintassi: `var nomeVariabile = valore;`
   - Esempio: `var numeroMele = 5;`

2. Tipizzazione dinamica delle variabili:
   - Sintassi: `var tipo nomeVariabile;`
   - Esempio: `var int numeroMele;`

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
   - If-else if-else:
     ```
     if (condizione) {
         // codice da eseguire se la condizione è vera
     } else if (altraCondizione) {
         // codice da eseguire se la condizione è falsa e l'altra condizione è vera
     } else {
         // codice da eseguire se tutte le condizioni precedenti sono false
     }
     ```

8. Cicli di iterazione:
   - Ciclo for:
     ```
     for (inizializzazione; condizione; iterazione) {
         // corpo del ciclo
     }
     ```

   - Ciclo while:
     ```
     while (condizione) {
         // corpo del ciclo
     }
     ```

   - Ciclo do-while:
     ```
     do {
         // corpo del ciclo
     } while (condizione);
     ```

9. Array:
   - Dichiarazione: `var tipo[] nomeArray = [elemento1, elemento2, ...];`
   - Accesso agli elementi: `nomeArray[indice]`

10. Funzioni:
    - Dichiarazione e definizione:
      ```
      func nomeFunzione(parametri) {
          // corpo della funzione
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
    - Dichiarazione: `bool nomeVariabile;`
    - Assegnazione: `nomeVariabile = true;` o `nomeVariabile = false;`

16. Commenti:
    - Commento su una riga: `# Questo è un commento su una riga`
    - Commento su più righe:
      ```
      #
      # Questo è un commento
      # su più righe
      #
      ```

17. Funzioni matematiche:
    - Valore assoluto: `absolute(nomeVariabile)`
    - Trasformazione da decimale a intero: `int(nomeVariabile, round/up/down/none, cifreDecimaliDaLasciare)`

18. Numeri casuali:
    - Numero casuale: `random()`
    - Intervallo numerico: `random(min, max)`

Queste sono le principali caratteristiche del linguaggio di programmazione che hai definito. Puoi utilizzare questo documento come base per la creazione del tuo file .me da aggiungere su GitHub. Assicurati di fornire ulteriori dettagli e spiegazioni per ogni funzionalità, nonché esempi di codice per illustrare il loro utilizzo.

Buon lavoro nella creazione del tuo linguaggio di programmazione!
