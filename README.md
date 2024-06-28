# MLDLM_progetto

I dati raccolti descrivono il gesto del braccio del ciclista per segnalare 6 situazioni differenti.

## Descrizione Dataset
La cartella Dataset contiene i file:
File csv:
- buche.csv: Segnalazione della presenza di buche sul percorso
- detriti.csv: Segnalaazione della presenza di detriti sul percorso
- ostacolo.csv: Segnalazione per aggirare un ostacolo
- pericolo.csv: Segnalazione di pericolo in avvicinamento
- stop.csv: Rallentamento o fermata del ciclista
- svolta.csv: Segnalazione di svolta a destra del ciclista

Ogni file contiene i dati di 40 ripetizioni del gesto rappresentato. 
L'accquisizione dei dati di una ripetizione ha la durata di 10s

I dati che descrivono ogni ripetizione con relativo tempo di campionamento:
- Accelerometro: 100 Sa/s
- Giroscopio: 100 Sa/s
- Segnale EMG: 1k Sa/s


Raccolta dati effettuata con il microcontrollore Arduino Nano 33 BLE Sense Rev 2 e la scheda Olimex Shield EKG-EMG.

## Descrizione Gesti Analizzati
I gesti vengo rappresentati nell'immagine "Codice_dei_Cisclisti.png"

- Svolta a Destra: Estendere il braccio destro a 90 gradi in linea con la spalla.
- Stop: Alzare il braccio piegato con il palmo della mano aperto.
- Pericolo: Battere la mano sul sedere e indicare l'ostacolo con l'indice.
- Buche: Stendere il braccio nella direzione del pericolo e indicarlo con il dito indice.
- Detriti: Abbassare il braccio e fare un movimento circolare con la mano tenendo il palmo rivolto verso il terreno.
- Aggirare un ostacolo: Sventolare il braccio davanti al sedere in direzione opposta al pericolo.

