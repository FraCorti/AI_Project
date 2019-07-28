## Progetto di Intelligenza Artificiale 
Progetto per l'insegnamento di [Intelligenza artificiale](https://didattica.unipd.it/off/2018/LM/SC/SC1176/000ZZ/SCP6076337/N0), corso di laurea in Informatica (Padova, Italia).

Il progetto prevedeva l'implementazione di uno spam filter. Questo è stato realizzato tramite Python utilizzando la seguenti librerie: 
1. [Keras](https://keras.io/): definizione della rete neurale e training di essa, questa è stata importata da [Tensorflow](https://www.tensorflow.org/), che dalla versione 2.0.0 la contiene al suo interno;
2. [Pandas](https://pandas.pydata.org/): conversione del dataset in formato CSV;
3. [scikit-learn](https://scikit-learn.org/stable/): pre-processing dei dati e utilizzo dell'algoritmo di [*LogisticRegression*](https://en.wikipedia.org/wiki/Logistic_regression);
4. [Kaggle API](https://github.com/Kaggle/kaggle-api): scaricamento del dataset in formato *.zip*.

Il dataset utilizzato per il progetto è reperibile al seguente link: [Spam Collection Dataset](https://www.kaggle.com/uciml/sms-spam-collection-dataset) 

### Come eseguirlo 
Per ***eseguire*** il progetto si suggerisce di appoggiarsi alla  piattaforma [Google Colab](https://colab.research.google.com/) la quale presenta già la versione di TensorFlow 2.0.0 integrata.

Per ***importare*** il progetto nella propria piattaforma Colab personale è necessario accedere al proprio account Colab e cliccare sulla voce *Upload notebook* e caricare il notebook precedentemente scaricato. 

### Scaricamento dataset
È necessario ***possedere le credenziali*** di un account Kaggle dal quale poter scaricare il dataset tramite l'utilizzo di una *KAGGLE_KEY* personale, vedi [API Credentials](https://github.com/Kaggle/kaggle-api#api-credentials) per maggiori info.   
Una volta ottenuta la chiave di Kaggle è necessario effettuare le seguenti operazioni nella **prima cella** dei file che si vogliono eseguire: 
1. Salvare la chiave ottenuta nel campo *key*;
2. Scrivere nel campo *username* il proprio username personale di Kaggle. 
   
Se tutto è stato settato correttamente la cella scarica automaticamente il dataset da Kaggle e lo salva in formato **.zip** per poi scomprimerlo in formato .  