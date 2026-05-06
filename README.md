## 📊 Data Analysis & NLP Quick Projects

Questa repository è una raccolta (ancora in evoluzione) di progetti veloci, esercitazioni e *homework* accademici, il cui obiettivo è quello di fornire una panoramica più generale dei task su cui ho lavorato e degli strumenti utilizzati.

La raccolta è eterogenea, com'è eterogeneo il mio percorso di formazione, i contenuti spaziano da NLP e text-mining all'analisi di dati più in generale.

---

## 📂 Indice dei Progetti

La repository è organizzata in cartelle monotematiche. Ogni progetto è autonomo e contiene codice, output e documentazione.

### 1. [Analisi della Dimensionalità e Correlazioni](./Correlation-between-factors-and-dimensionality-reduction)
Confronto tra tecniche di riduzione della dimensionalità e analisi delle correlazioni su toy dataset di Scikit-learn.

*   **Obiettivi:** Implementazione modulare di PCA e SVD; calcolo e visualizzazione delle correlazioni (Pearson, Spearman).
*   **Dataset:** *Diabetes* (Sklearn), *Wine* (Sklearn), *Breast Cancer* (Sklearn).
*   **Strumenti:** Python, Pandas, Scikit-learn, SciPy, Matplotlib.
*   **Struttura:** Notebook commentato e generazione automatizzata di dataset ridotti in formato `.csv`.

---

### 2. [Banking Customer Sentiment Analysis](./banking-customer-intent-analysis/)
Il progetto consite nello sviluppo di una pipeline di NLP in grado di individuare all'interno di un dataset di messaggi di clienti di un servizio di banking
i topic maggiormente critici. 


*   **Strumenti:** Python, NLP (Natural Language Processing), BERT Embeddings, SpaCy, Hugging Face, Scikit-learn, Matplotlib.
*   **Dataset:** *nataliaElv/banking77_topic_and_sentiment*
*   **Pipeline di data cleaning:** Implementazione di un sistema di preprocessing, lemmatizzazione, rimozione stop-words e  filtraggio semantico.
*   **Modello di embedding:** *Transformer (BERT-based)* implementato tramite *Sentence-Transformers* per catturare il contesto semantico delle query.
*   **Sviluppo del Classificatore:** Creazione di un modello per la classificazione dei topic, che raggiunge un'accuratezza del **76%** su una tassonomia complessa di 48 intenti bancari diversi.
*   **Analisi dei Risultati:** Correlazione statistica tra i topic emersi e il sentiment negativo per mappare i degli utenti (es. gestione delle carte in scadenza), fornendo dati azionabili per il miglioramento del customer care.

*Nuovi progetti in arrivo a breve...*

#### ⚙️ Come utilizzare questa repository

Ogni progetto può essere facilmente riprodotto in locale clonando la repository.