Benvenuto! Questo progetto implementa un agente di Reinforcement Learning per il gioco Snake, utilizzando Deep Q-Learning e una rete neurale con PyTorch. Di seguito troverai le istruzioni per installare e testare il programma.

#Requisiti di sistema
- Python 3.7+
- Pip (per installare i pacchetti richiesti)
- Sistema operativo: Windows, macOS, o Linux
- GPU (opzionale, per migliorare le prestazioni durante il training)

#Librerie necessarie
Assicurati di avere le seguenti librerie installate:

- Pygame: Per il rendering del gioco Snake
- PyTorch: Per la creazione e il training della rete neurale
- Numpy: Per la gestione dei dati numerici
- Matplotlib (opzionale): Per visualizzare i grafici dei punteggi e del training

#Installazione

1. Estrazione dei file: 
   - Scarica e decomprimi il file ZIP che contiene tutti i file del progetto.

2. Installazione delle dipendenze:
   - Apri un terminale o prompt dei comandi nella cartella del progetto.
   - Esegui il comando seguente per installare tutte le librerie richieste:
     pip install pygame torch numpy matplotlib

3. Esecuzione del gioco:
   - Dopo aver installato le dipendenze, puoi eseguire il gioco Snake con Reinforcement Learning.
   - Nel terminale, esegui il comando:
     python agent.py
   - Questo comando avvierà il ciclo del gioco e visualizzerà il gioco Snake su schermo.

#Come Funziona

- L'agente inizierà a giocare a Snake e apprenderà attraverso il Deep Q-Learning.
- Potrai vedere in tempo reale come l'agente migliora progressivamente il suo comportamento, cercando di evitare la morte e guadagnare più punti possibile.

#Parametri di Training
Nel file `agent.py` sono definiti alcuni parametri chiave che puoi modificare per influenzare il comportamento dell'agente:

- learning_rate: Tasso di apprendimento della rete neurale.
- gamma: Tasso di sconto per l'Equazione di Bellman.
- epsilon: Controlla il compromesso tra esplorazione ed exploitazione.
- batch_size: Numero di esperienze che l'agente utilizza per l'aggiornamento del modello.

#Visualizzazione dei Risultati
- Il programma genera un grafico che mostra l'andamento dei punteggi nel tempo, per monitorare i progressi dell'agente.
- Il file `plot.py` è utilizzato per visualizzare questi risultati, verr' esegito automaticamente.

#Note Aggiuntive
- Il file `arial.ttf` incluso nella cartella serve per il rendering del testo all'interno del gioco.
- Il file `snake_game.py` incluso nella cartella è una versione giocabile del gioco Snake

#Problemi Comuni

1. Il gioco non si avvia: 
   - Verifica di aver installato correttamente tutte le librerie richieste.
   - Assicurati che Python sia correttamente configurato sul tuo sistema.

2. Errori di installazione di PyTorch:
   - Se utilizzi una GPU, assicurati di installare la versione di PyTorch compatibile con CUDA. Puoi trovare le istruzioni dettagliate sul sito ufficiale di PyTorch: [https://pytorch.org](https://pytorch.org).

3. Prestazioni lente durante il training:
   - Se noti che il training è lento, puoi ridurre il batch_size o eseguire il training su una macchina con GPU.

Buon divertimento e buon training!
