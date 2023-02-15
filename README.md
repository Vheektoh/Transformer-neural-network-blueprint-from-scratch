# Transformer-neural-network-blueprint-from-scratch
## Introduction
Before the state of the art transformer was developed, early models were used to solve Natural Language Processing problems.
These models were the Naive bayes classifier, the recurrent neural network, the gated recurrent unit, the LSTMs, but these gave
issues due to vanishing and exploding gradients so the attention was developed and used in the sequence to sequence model, LSTM
at the early stage. Before the famous attention paper implementation using the transformer neural network.

## Basic parts of the Transformer.
when building the transformer, these layers must be accounted for before one can say the transformer model has been implememted
- POS embedding
- scaled dot product attention
- multi head dot product attention
- encoder
- decoder
- encoder layer
- decoder layer
- sequence transformer(adding the above together).

## Note
Knowledge on how each layer works is crucial in understanding how the transformer works generally, so with the above listed one can
take them one by one, learn each from the code implementation posted the add all together. Also, this is just the general blueprint
of the transformer so if we want to process a text file a different module for learning how to do that would have to be looked up.
