# Progetto GIS

Il progetto consiste in uno sviluppo di un'applicazione con interfaccia grafica interattiva basata sulla mappa del campus di Fisciano.
Il sistema permette di calcolare il percorso ottimale tra due punti dell'università, lasciando scegliere all'utente l'itinerario più ombreggiato o più soleggiato.

## Tecnologie utilizzate

- **Python**: utilizzato per lo sviluppo del backend e per la gestione della logica del sistema di calcolo dei percorsi.
- **HTML, CSS e JavaScript**: utilizzati per la realizzazione dell’interfaccia grafica e della parte frontend dell’applicazione.
- **QGIS**: utilizzato per la gestione e la visualizzazione dei dati geografici relativi alla mappa del campus universitario.
- **GRASS GIS**: utilizzato per l’analisi spaziale avanzata, in particolare per il calcolo dell’esposizione al sole e delle aree d’ombra lungo i percorsi.


## Installazione dell'ambiente Python

   
1. Installare le dipendenze Python
  ```bash
pip install -r requirements.txt
```

2. Avvio del backend

Apri il terminale e spostati nella cartella backend attiva l'ambiente virtuale (se non già attivo):
```bash
venv\Scripts\activate   
```

Avvia il server backend:
```bash
python percorsi.py
```

3. Avvio del frontend

Apri un altro terminale e spostati nella cartella frontend e avvia il server frontend:

```bash
node server.js
```
