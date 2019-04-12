## Project Overview

This repository hosts code used in third project on Recurrent Neural Networks (RNN) project in the Deep Learning Nanodegree. In addition to meeting the project specifications, I also added on a few things. 

The aim is to generate Seinfeld TV scripts using RNNs using Seinfeld dataset of scripts from 9 seasons. The Neural Network built generates a new, "fake" TV script. 

## Project To Do List

### Rubrics
| Criteria                                           | Specifications                                                                                                                                                                                        | Finished |
|----------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------|
| Pre-processing Data | The function `create_lookup_tables` and `token_lookup` is implemented |<ul><li>[x] </li></ul>|
| Batching Data    | Data is broken into sequences, created using TensorDataset and batched correctly  |<ul><li>[x] </li></ul>|
| Build the RNN    | The RNN is defined and includes at least one LSTM (or GRU) and fully-connected layer.  |<ul><li>[x] </li></ul>|
| RNN Training | Reasonable hyperparameters are selected for training   |<ul><li>[x] </li></ul>|
|Generate TV Script | The generated script can vary in length, and should look structurally similar to the TV script in the dataset.  |<ul><li>[x] </li></ul>|
| Prepare report    | Refer the [rubrics](https://review.udacity.com/#!/rubrics/2260/view)  |<ul><li>[x] </li></ul>|


### Suggestions
- [ ] Use validation data to choose the best model
- [ ] Initialize your model weights, especially the weights of the embedded layer to encourage model convergence
- [ ] Use topk sampling to generate new words.
- [ ] Generate your own Bach music using like [DeepBach](https://arxiv.org/pdf/1612.01010.pdf).
- [ ] Predict seizures in intracranial EEG recordings on [Kaggle](https://www.kaggle.com/c/seizure-prediction).
