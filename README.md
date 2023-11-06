# DependencyParserNN

Neural Network model that is trained on dependency structure data 

**Utility Files for Training Data Preparation**

conll_reader.py: Defines DependencyStructure class Read in the dependency relation from the data file

extract_training_data.py: Read in training data and convert it input and output representation

get_vocab.py: Returns vocabulary set from data

**Training the Model**

train_model.py: Defines the Model and trains it using input and output representations

**Evaluating Model**

decoder.py: Decodes the output of the neural network

evaluate.py: Evaluates the model

**Results File**

model.h5: Final Model created from the process. Given a sentence, predicts its part of speech 

pos.vocab: extracted part of speech vocab from the data

words.vocab: extracted word vocab from the data
