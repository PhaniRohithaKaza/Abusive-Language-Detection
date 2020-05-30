# Abusive-Language-Detection

### How to train
- Every task has estimator to train, evaluate and predict
- While building model function you have to pass which model type to use
- There are three options for model_type:
    1. simple
    2. lstm
    3. attention
- Upon setting "model_type" the model function builder will build the respective model graph 
- Load the datasets and run the estimator to train the model

### Fine-Tuning Methods
- BERT BASE and LARGE models
- Three techniques are used to perform the tasks
- First approach just uses simple softmax layer
- Second approach uses sequence output of BERT for representation of sentence.
- Third approach calculates attention weights and context vector of sequence output.
- Second and third approaches uses weighted cross entropy cost to handle class imbalance
- More details about training and fine tuning are in project report.

### Requirements
1. Programming language used : Python3
2. Framework used to build deep learning models : Tensorflow version 1.15
3. Visualisation tools : Matplotlib, Tensorboard
4. Other libraries and packages: pandas, numpy, scikit-learn etc.
5. Cloud GPU or TPU as hardware accelerators

### Datasets
Toxic Comment Classification:
https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge

Offensive Language Identification Dataset:
https://competitions.codalab.org/competitions/20011

### Pretrained Weights
BERT Pretrained Weights:
https://storage.googleapis.com/bert_models/2018_10_18/cased_L-12_H-768_A-12.zip
https://storage.googleapis.com/bert_models/2018_10_18/cased_L-24_H-1024_A-16.zip

XLNet pretrained Weights:
https://storage.googleapis.com/xlnet/released_models/cased_L-12_H-768_A-12.zip
https://storage.googleapis.com/xlnet/released_models/cased_L-24_H-1024_A-16.zip




 
