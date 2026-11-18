# ValutaCasa · ICON 2024/25

Progetto per il corso di Ingegneria della Conoscenza (Università di Bari, A.A. 2024/25).

**ValutaCasa** stima il prezzo di un immobile a partire dalle sue caratteristiche (metri quadri, città, via, stato…), con un'interfaccia desktop in Tkinter.

<p align="center"><img src="screen/valutacasa.png" alt="ValutaCasa" width="600"/></p>

## Cosa c'è dentro

- `Model.py`: preparazione del dataset, clustering (DBSCAN), regressione con Random Forest e classificazione con SGD, ottimizzati con Grid Search e K-Fold cross validation
- `ValutaCasa.py`: interfaccia grafica per inserire i dati della casa e ottenere la stima
- `house.csv`, `data.csv`: dataset
- `grafici_features/`, `screen/`: grafici delle feature e schermate
- `Documentazione_ICON.pdf`, `Presentazione_ICON.pdf`: documentazione e presentazione del progetto

## Avvio

```bash
pip install numpy pandas matplotlib scikit-learn tqdm
python ValutaCasa.py
```
