# Esercizio 6: Recuperi in Git

1. **Togliere un file dall'indice senza perdere le modifiche:**
   - Comando: `git restore --staged <file>`
   - Effetto: Rimuove il file dall'indice (staging area) ma lascia intatte le modifiche nell'area di lavoro; la storia non cambia.

2. **Scartare le modifiche nell'area di lavoro tornando all'ultimo commit:**
   - Comando: `git restore <file>`
   - Effetto: Elimina le modifiche locali non salvate nell'area di lavoro, riportando il file allo stato esatto dell'ultimo commit; indice e storia restano inalterati.

3. **Correggere l'ultimo messaggio di commit senza creare un nuovo commit:**
   - Comando: `git commit --amend -m "Messaggio corretto"`
   - Effetto: Modifica e sostituisce il messaggio dell'ultimo commit registrato senza generare commit spuri o aggiuntivi nella storia.