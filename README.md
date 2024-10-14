# Transformer

The repository contains a notebook implementing GPT-3 architecture using Pytorch. The model can be trained on the following tasks,

1. Random number sequence reversal: This is useful to ensure correctness for the masked attention module. Without any masking, the model learns to reverse the number sequence perfectly. However, with the masked version, it can learn to reverse only the second half of the sequence.
2. Language model on Shakespeare. 

Resources

- https://github.com/jacobhilton/deep_learning_curriculum/blob/master/1-Transformers.md
