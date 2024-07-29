# Ant.ai - Generate new Indian Style recepies

## 
Built an minigpt that mimics the conversation of two individuals.

GPT's are generatively pretrained Transformers.
Introduced in the paper "Attention is all you need" that translate english to french
Transforms are neural network thatget input a sequence and predicts the next token in that sequence.
Components:
It contains an encoder with multi-head self attention,feed forward neural network and a decoder with 2 MHA and a feed forword.

Our implementation:
It is an charcter level model .each token is a character
This repository has implements positional encoding,multihead self attention ,add and norm and feed forward sections of the transformer predict the next text.

Positional Encoding
The token are embedded with the position to gain more context of the word.

Multi-head Self Attention
The architecture contains a  multi-head self attention mechanism that is the core of transformer which helps in knowing the 
context of the word.use three vector Q-Query,V-Value,K-Key.

Add and Norm:
adds the X vector that is the original vector with the MHA output and normalise it .

Feed-forward neural network:
a simple neural network with multiple hidden layers.

Softmax- it is an normalization algorithm.

Thus created an simple language model.


Framework:pytorch.


