## AI_Project
Project for the [Artificial Intelligence](https://didattica.unipd.it/off/2018/LM/SC/SC1176/000ZZ/SCP6076337/N0) course, Computer Science faculty at UniPD (Padova, Italy).

## Progetto di Intelligenza Artificiale 
Progetto per l'insegnamento di [Intelligenza artificiale](https://didattica.unipd.it/off/2018/LM/SC/SC1176/000ZZ/SCP6076337/N0), corso di laurea in Informatica (Padova, Italia).\
Il progetto prevede l'implementazione di uno spam filter.   
Il progetto è stato realizzato in Python, sono state utilizzate la seguenti librerie: 
1. [Keras](https://keras.io/): definizione della rete neurale e training di essa, questa è stata importata da [Tensorflow](https://www.tensorflow.org/), che dalla versione 2.0.0 la contiene al suo interno;
2. [Pandas](https://pandas.pydata.org/): conversione del dataset in formato CSV;
3. [scikit-learn](https://scikit-learn.org/stable/): pre-processing dei dati e utilizzo dell'algoritmo di LogisticRegression;
4. [Kaggle API](https://github.com/Kaggle/kaggle-api): scaricamento del dataset in formato *.zip*.

Il dataset utilizzato per il progetto è reperibile al seguente link [Spam Collection Dataset](https://www.kaggle.com/uciml/sms-spam-collection-dataset) 

## Come eseguirlo 
È necessario ***possedere un account Kaggle*** dal quale poter scaricare il dataset tramite l'utilizzo di una *KAGGLE_KEY* personale, vedi [API Credentials](https://github.com/Kaggle/kaggle-api#api-credentials) per maggiori info.   
Una volta ottenuta la chiave di Kaggle è necessario salvarla nel campo *key* presente in terza riga.  
Per eseguire il progetto si suggerisce di appoggiarsi alla  piattaforma [Google Colab](https://colab.research.google.com/) che presenta già la versione di TensorFlow 2.0.0 integrata.  
Il notebook è eseguibile anche in [Jupyter](https://jupyter.org/), previo scaricamento del dataset e installazione di [TensorFlow 2.0.0](https://www.tensorflow.org/beta/). 

