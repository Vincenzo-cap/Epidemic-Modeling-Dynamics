# Epidemic-Modeling-Dynamics
Simulazione numerica di modelli compartimentali (SIR/SEIR) tramite sistemi di equazioni differenziali.
# Simulating Epidemics via the Theory of Dynamical Systems 

Questo progetto esplora la diffusione delle epidemie attraverso l'analisi e la simulazione numerica di modelli compartimentali. Il lavoro si concentra sulla transizione di fase tra la scomparsa dell'epidemia e la sua propagazione endemica.

## Caratteristiche del Progetto
- **Modellizzazione:** Implementazione di modelli SIR (Susceptible-Infected-Recovered) e varianti (SEIR).
- **Analisi Matematica:** Studio dei punti di equilibrio, calcolo del numero di riproduzione di base ($R_0$) e analisi della stabilità lineare.
- **Simulazione:** Risoluzione numerica di sistemi di equazioni differenziali ordinarie (ODE) in Python.

## Tecnologie Utilizzate
- **Linguaggio:** Python
- **Librerie Scientifiche:** - `SciPy` (modulo `integrate.odeint` per la risoluzione delle equazioni)
  - `NumPy` (calcolo vettoriale)
  - `Matplotlib` (generazione di grafici temporali e piani delle fasi)

##  Contenuto del Repository
- `epidemic_simulation.ipynb`: Notebook principale con il codice e i commenti tecnici.
- `presentation.pdf`: Presentazione tecnica dei risultati e dei grafici di evoluzione.
## Navigazione Rapida
Clicca sui link per aprire direttamente i notebook con i risultati:

* [Modelli SIR Stocastici](notebooks/01_SIR_Stochastic_Basics.ipynb)
* [Analisi delle Topologie di Rete](notebooks/02_Network_Topologies_Analysis.ipynb)
* [Esponenti di Lyapunov e Stabilità](notebooks/03_Lyapunov_and_Map_Dynamics.ipynb)
* [Reti Sparse e Matrici CSR](notebooks/04_Sparse_Networks_Epidemics.ipynb)
* [Modello Finale con Mortalità](notebooks/05_Advanced_Mortality_Stackplots.ipynb)
- [Leggi la Presentazione Tecnica (PDF)](Simulazione_epidemiologica.pdf)
---
*Progetto realizzato nell'ambito del corso di Metodi computazionali della fisica.*
