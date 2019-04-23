# toxic-question-predictive-model [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/4ndyparr/toxic-question-predictive-model/master)
Neural Network built with PyTorch for the **Kaggle** competition [Quora Insincere Questions Classification](https://www.kaggle.com/c/quora-insincere-questions-classification).
It finished in the top 2% with a F1-Score of 0.70445 (F1-Score of the winning model was 0.71323).

It is basically a blending of an Embeddings layer, a binary LSTM with
Attention, a GRU with Attention, a Global Average Pooling, a Global Max Pooling, a Capsule layer
and a layer with extra features added.

Kaggle Profile: https://www.kaggle.com/andrewparr

You can take a look at the code online at https://mybinder.org/v2/gh/4ndyparr/toxic-question-predictive-model/master.
