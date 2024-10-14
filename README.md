# transformers

The repository contains a notebook with the implementation of GPT-3 architecture using Pytorch. The model can be trained on the following tasks,

1. Random number sequence reversal: this is useful to ensure correctness for masked attention module. Without any masking, the model learns to reverse the number sequence perfectly. However, with the masked version, it can learn to reverse only the 2nd half of the sequence.
2. Laguage model on Shakespeare. 
