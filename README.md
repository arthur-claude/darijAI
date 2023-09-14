# darijAI

English - Darija machine translator

## Introduction

The goal of this project was to implement a sequence to sequence model in order to build a machine translator from English to Darija (Moroccan Arabic).
I followed a tutorial available on the PyTorch website (Sean Robertson. NLP from scratch: Translation with a sequence to sequence network and attention. Available at: https://pytorch.org/tutorials/intermediate/seq2seq_ translation_tutorial.html). This tutorial explain how to teach a neural network to translate from French to English and was adapted for Darija. A sequence to sequence network, in which two recurrent neural networks work together to transform one sequence to another is used, and an attention mechanism, which lets the decoder learn to focus over a specific range of the input sequence allow to improve the results. 

## Files

data_preparation.ipynb is a notebook allowing to prepare the Data that was used to train the model.
seq2seq_train_test_darija.ipynb is a notebook containing all the functions needed to build the neural network, train it and test it.

## About the Data

The Data used to train the model is extracted from the databases created as part of the Darija Open Dataset project (DODA, available at https://darija-open-dataset.github.io/). It is composed of +19k phrases and words translated from English to Darija.





