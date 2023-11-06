# DependencyParserNN

Training a Neural Network model on dependency structure data 

**Utility Files for Training Data Preparation**
1. conll_reader.py: Defines DependencyStructure class Read in the dependency relation from the data file
2. extract_training_data.py: Read in training data and convert it input and output representation
3. get_vocab.py: Returns vocabulary set from data

**Training the Model**

1. train_model.py: Defines the Model and trains it using input and output representations

**Evaluating Model**

1. decoder.py: Decodes the output of the neural network
2. evaluate.py: Evaluates the model

**Results File**

1. model.h5: Final Model created from the process. Given a sentence, predicts its part of speech
2. pos.vocab: extracted part of speech vocab from the data
3. words.vocab: extracted word vocab from the data

**Data File**
1. data.zip
