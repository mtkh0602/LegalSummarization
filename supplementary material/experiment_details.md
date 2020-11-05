### Experiment details

In this experiment we train a simple bi-lstm neural network. The experiment details are given below:

1. A 2-layer BiLSTM with \
  a. Hidden Weights of 128 dimension \
  b. Dropout = 0.3
2. Forward and Backward Hidden Weights were concated and used as input for a linear layer with 2 output nodes for two classes for summary worthy and not worthy sentences.
3. Word Embeddings of size 150 intialized using Xavier Normal Distribution. Pretrained embeddings, such as glove and word2vec, performed poorly most likely because of most of the legal vocabulary was missing in the models.
4. Max sentence length is set to 150 words, i.e, the average length of the sentences in the Indian Supreme Court Judgements. 
5. Total vocabulary size used is 10000 words selected based on the frequency of words in the Indian Supreme Court Judgements.
6. Batch Size = 32

### NN-Threshold 

Threshold values were set on the classifier output value for summary worth sentences. We tried different threshold starting from 0.5 to 0.85 , with gap 0.05. Best Rouge F1 scores of 0.604 were reported on 0.75.
