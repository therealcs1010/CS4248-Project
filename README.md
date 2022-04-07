# General Directories

There are 2 general directories that contain the training and test corpus to be processed and used.

`processed_data` contains the training and testing json. Can just load into a pandas dataframe. 

`raw_data` contains the raw txt files. If you want to do your own preprocessing etc can use. 

# Personal Directories

They contain the various models that have been done and also include additional files that may be required for the given models.

`Yu Jie` - Implementation of various neural network models. FeedForward Neural Network, CNN and LSTM implementations. Implements models with the following feature engineering methods:

1. TF-IDF Vectorization
2. Spacy Document Embeddings
3. Simple Text 2 Sequence
4. GloVe Embeddings

Has a catalogue of stored models that have been pre-trained and ready for test and use.

`Fatin` - Implementation of various classical models such as Naive Bayes, Decision Trees, Logistic Regression, SGDClassifier and neural networks.

`Ailanthus` - Implementation of the Support Vector Machine model and also a simple CNN implementation with some data.

`Jarrod` - Implementation of Learning Vector Quantization model and hyperparameter tuning within the same implementation. Running the notebook in the folder itself will work accordingly.

# Running the Jupyter Notebooks

In order to try a model, it would suffice to clone the entire repository and open the Jupyter notebook that has the model that you are interested in. The data for the models should be handled within the personal directories for each model.