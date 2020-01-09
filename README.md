# toxic-question-predictive-model [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/4ndyparr/toxic-question-predictive-model/master)
Neural Network built with PyTorch for the **Kaggle** competition [Quora Insincere Questions Classification](https://www.kaggle.com/c/quora-insincere-questions-classification).
It finished in the top 2% with a F1-Score of 0.70445 (F1-Score of the winning model was 0.71323).

A **binary classifier** (toxic question or not), this model uses pre-trained embeddings and blends with some extra features the outputs
from a binary LSTM with Attention, a GRU with Attention, a Global Average Pooling layer, a Global
Max Pooling layer and a Capsule layer.  

Some of the machine learning techniques applied in the model are: Meta-Embeddings by Averaging, Cyclic Learning Rate and Threshold Optimization. 

![Diagram](https://github.com/4ndyparr/toxic-question-predictive-model/blob/master/diagram.png)

Kaggle Profile: https://www.kaggle.com/andrewparr

Take a look at the code at: https://mybinder.org/v2/gh/4ndyparr/toxic-question-predictive-model/master
