# NIPS - 2017 Paper Implementations

### Towards Accurate Binary Convolutional Neural Network
**Link**: https://papers.nips.cc/paper/6638-towards-accurate-binary-convolutional-neural-network.pdf

**Summary** : This paper talks about using only -1 or +1 as weights and activations while building CNNs. Paper claims that this tweak to the traditional CNNs uses significantly lesser amount of memory, faster inference in runtime on test data and comparable performance on IMAGENET.

**To-do** to implement the paper:
  - Constrain the weights to {-1, +1} - This ensures convolutions are only additions or subtractions
  - Use five binary activations instead of two.
  - ...(Work in progress)
