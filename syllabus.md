# Titolo del Corso
## AI e Machine Learning per Diagnostica Medica Avanzata
## Obiettivo del Corso
Fornire competenze tecniche e pratiche per sviluppare, ottimizzare e implementare soluzioni basate su AI e ML per:
- Analisi avanzata delle immagini radiografiche ed ecografiche.
- Interpretazione di dati complessi derivanti dall’analisi dei campioni di alito respirato.

Un modulo introduttivo su Python sarà incluso per garantire che tutti i partecipanti siano in grado di seguire gli esercizi pratici.
---
## Durata
**40 ore totali**
- **Teoria:** 24 ore (30%)
- **Pratica:** 56 ore (70%)
---
## Prerequisiti
- Familiarità con concetti di base in diagnostica medica.
- Nessuna conoscenza pregressa di Python o AI necessaria.
---

## Programma Dettagliato
Eviteremmo il modulo 0, perché si tratta di argomenti già di nostra conoscenza. Magari sarebbe utile giusto indicare del materiale su cui prepararsi offline.

### Modulo 0: Introduzione a Python (10 ore)
**Sessioni Online (Teoria: 3 ore, Pratica: 7 ore)**

- **Fondamenti di Python**
  - Installazione e configurazione dell'ambiente (Google Colab, Jupyter Notebook).
  - Variabili, tipi di dati, strutture di controllo (if, for, while).

- **Strutture Dati**
  - Liste, dizionari, tuple e set.
  - Operazioni fondamentali e gestione dei dati.

- **Funzioni e Librerie**
  - Definizione e utilizzo di funzioni.
  - Introduzione alle librerie fondamentali: NumPy, pandas e Matplotlib.

- **Primi Script per l’Analisi dei Dati**
  - Lettura di file CSV.
  - Visualizzazione di dati con grafici base.

**Workshop Pratico:**
- Creazione di un semplice script per analizzare dati medici.
---

### Modulo 1: Fondamenti di AI e Machine Learning (6 ore)
**Sessioni Online (Teoria: 2 ore, Pratica: 4 ore)**

- **Introduzione all’AI e ML**
  - Differenze tra AI, ML e Deep Learning.
  - Applicazioni in diagnostica medica.

- **Pipeline di un progetto ML**
  - Raccolta e pre-elaborazione dati.
  - Addestramento, validazione e testing.

- **Strumenti e librerie principali**
  - Python: scikit-learn, TensorFlow, PyTorch.

**Workshop Pratico:**
- Implementazione di un modello di classificazione semplice usando scikit-learn.
---

### Modulo 2: Elaborazione di Immagini Mediche (17 ore)
**Sessioni Online (Teoria: 6 ore, Pratica: 11 ore)**

- **Pre-elaborazione delle immagini radiografiche**
  - Rimozione del rumore e miglioramento del contrasto.
  - Normalizzazione e segmentazione delle immagini.
  - Tecniche avanzate di segmentazione (U-Net, Mask R-CNN).

- **Reti Neurali Convoluzionali (CNN)**
  - Struttura e funzionamento.
  - Applicazione per la classificazione e rilevazione di patologie.
  - Transfer Learning per migliorare l'accuratezza con dataset limitati.

- **Augmentazione dei dati medici**
  - Tecniche di augmentazione specifiche per immagini mediche.
  - Uso di librerie come Albumentations.

- **Explainable AI (XAI) per immagini mediche**
  - Interpretabilità con Grad-CAM e LIME.
  - Valutazione dell'affidabilità del modello.

**Workshop Pratico:**
- Addestramento di una CNN per il rilevamento di anomalie polmonari con dataset open-source (NIH Chest X-rays).
- Implementazione di tecniche di segmentazione per immagini ecografiche.
- Applicazione di XAI per spiegare le decisioni del modello.

  Sul modulo 2 proporremmo uno studio su immagini ecografiche piuttosto che uno studio su immagini raggi X. Per esempio, da sottoporre all’istruttore quanto segue:

  Segmentazione e classificazione benigna/maligna di lesioni al seno: https://qamebi.com/breast-ultrasound-images-database/
  Classificazione delle proiezioni fetali: https://zenodo.org/records/3904280
  Dataset da utilizzare come base per il transfer learning: https://paperswithcode.com/dataset/us-4 

---

### Modulo 3: Analisi dei Campioni di Alito Respirato (17 ore)
**Sessioni Online (Teoria: 6 ore, Pratica: 11 ore)**

- **Introduzione ai dati biologici complessi**
  - Caratteristiche dei campioni di alito.
  - Correlazioni tra biomarcatori e patologie.

- **Pre-elaborazione dei dati**
  - Tecniche di pulizia e normalizzazione.
  - Riduzione della dimensionalità con PCA e t-SNE.

- **Tecniche di Machine Learning**
  - Regressione logistica per la classificazione di dati clinici.
  - Random Forest e Gradient Boosting per pattern recognition.
  - Classificatori ensemble per migliorare l'accuratezza.

- **Deep Learning per segnali biologici**
  - LSTM e RNN per dati temporali e sequenziali.
  - Modelli transformer per l'analisi dei dati respiratori.

- **Validazione e testing avanzati**
  - K-fold cross-validation.
  - Metriche di valutazione specifiche per dati medici (ROC, AUC).

**Workshop Pratico:**
- Progettazione e implementazione di un modello per rilevare anomalie nei campioni di alito.
- Addestramento di un modello LSTM per identificare pattern nei dati temporali.
- Visualizzazione dei risultati e interpretazione con tecniche di explainability.
---

## Materiali e Supporto
**Materiali Forniti:**

- Dataset di esempio per immagini e analisi del respiro.
- Codice sorgente per implementazioni di base.
- Slide e dispense del corso.

**Supporto:**

- Forum tecnico e sessioni di mentoring.
---

## Strumenti Richiesti

**Software:**

- Python 3.7+ (Google Colab o Jupyter Notebook).
- Librerie: TensorFlow, PyTorch, scikit-learn, NumPy, pandas.

**Hardware:**

- Computer con accesso a GPU per accelerare il training (facoltativo: Google Colab Pro).

