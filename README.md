## (EN) Project for Artificial Intelligence course 
Project for the teaching of [Artificial Intelligence](https://didattica.unipd.it/off/2018/LM/SC/SC1176/000ZZ/SCP6076337/N0), computer science degree course (Padua, Italy)

The project involved the implementation of a spam filter. This was done using Python using the following libraries:
1. [Keras](https://keras.io/) definition of the neural network and its training;
2. [Pandas](https://pandas.pydata.org/): conversion of the dataset into .csv format;
3. [scikit-learn](https://scikit-learn.org/stable/): data pre-processing and use of the [*LogisticRegression*](https://en.wikipedia.org/wiki/Logistic_regression) algorithm;

The dataset used for the project can be found at the following link: [Spam Collection Dataset](https://www.kaggle.com/uciml/sms-spam-collection-dataset).

### How to run it
To ***run*** the project it is suggested to lean on the platform [Google Colab](https://colab.research.google.com/) which already has the integrated version of TensorFlow 2.0.0.

To ***import*** the project into your personal Colab platform, you need to log in to your Colab account and click on Upload notebook and load the previously downloaded notebook.

### Download dataset
You must have the credentials of a Kaggle account from which you can download the dataset using a personal *KAGGLE_KEY*, see [API Credentials](https://github.com/Kaggle/kaggle-api#api-credentials) for more info.

Once the Kaggle key is obtained, it is necessary to perform the following operations in the **first cell** of the files you want to execute:
1. Save the key obtained in the key field;
2. Write your personal Kaggle username in the username field.
   
If everything has been set correctly, the cell automatically downloads the dataset from Kaggle and saves it in **.zip** format to then decompress it in **.csv** format which is used for neural network training.

## (IT) Progetto di Intelligenza Artificiale 
Progetto per l'insegnamento di [Intelligenza artificiale](https://didattica.unipd.it/off/2018/LM/SC/SC1176/000ZZ/SCP6076337/N0), corso di laurea in Informatica (Padova, Italia).

Il progetto prevedeva l'implementazione di uno spam filter. Questo è stato realizzato tramite Python utilizzando la seguenti librerie: 
1. [Keras](https://keras.io/): definizione della rete neurale e training di essa, questa è stata importata da [Tensorflow](https://www.tensorflow.org/), che dalla versione 2.0.0 la contiene al suo interno;
2. [Pandas](https://pandas.pydata.org/): conversione del dataset in formato .csv;
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
   
Se tutto è stato settato correttamente la cella scarica automaticamente il dataset da Kaggle e lo salva in formato **.zip** per poi scomprimerlo in formato **.csv** che viene utilizzato per il training della rete neurale.  