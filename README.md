# NLU-PROJECT
## Word-level Language Modeling Using RNN


### Overview

In word-level language modeling tasks, each element of the sequence is a word, where the model is expected to predict
the next incoming word in the text. We evaluate the temporal convolutional network as a word-level language model on
PennTreebank

### Data

**PennTreebank**: We used the PennTreebank (PTB) (Marcus et al., 1993) for both character-level and word-level
language modeling. When used as a character-level language corpus, PTB contains 5,059K characters for training,
396K for validation, and 446K for testing, with an alphabet
size of 50. When used as a word-level language corpus,
PTB contains 888K words for training, 70K for validation,
and 79K for testing, with a vocabulary size of 10K. This
is a highly studied but relatively small language modeling
dataset (Miyamoto & Cho, 2016; Krueger et al., 2017; Merity et al., 2017).
  
### Code
There are 3 files Present for different Implementation of RNN using Penn-Treebank Dataset.
-- Vanilla-LSTM-Penn-Treebank.ipynb, Used Vanilla with LSTM Network.
-- 2-Layer-LSTM-Penn-Treebank.ipynb, Used LSTM with 2 layer of Linear Classifier.
-- 	3-Layer-LSTM-Penn-Treebank.ipynb, Used LSTM with 3 Layer of Linear Classifier.

### To Run
We just need to give the path of the ptb dataset and run the .ipynb files
