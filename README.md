# Progetto GIS

Il progetto consiste in uno sviluppo di un'applicazione con interfaccia grafica interattiva basata sulla mappa del campus di Fisciano.
Il sistema permette di calcolare il percorso ottimale tra due punti dell'università, lasciando scegliere all'utente l'itinerario più ombreggiato o più soleggiato.

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
