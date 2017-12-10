# Nips 2017 Paper Summaries

This repository contains the summaries of projects in this organisations.



# How to add your own Summary
1. Fork this repo
2. Add a folder with your Paper Name
3. Create a Readme.md file in that folder
4. Write your summary there. You can include additional files (E.g. reference images) under your folder
5. Submit a pull request on github


### This is done to prevent merge conflicts

___

# NIPS - 2017 Paper Implementations

### Towards Accurate Binary Convolutional Neural Network
**Link**: https://papers.nips.cc/paper/6638-towards-accurate-binary-convolutional-neural-network.pdf

**Summary** : This paper talks about using only -1 or +1 as weights and activations while building CNNs. Paper claims that this tweak to the traditional CNNs uses significantly lesser amount of memory, faster inference in runtime on test data and comparable performance on IMAGENET.

**To-do** to implement the paper:
  - Constrain the weights to {-1, +1} - This ensures convolutions are only additions or subtractions
  - Use five binary activations instead of two.
  - ...(Work in progress)

**Implementations and Results**:
  - Detailed Summary and Results: Link-to-Your-Folder-Name-In-This-Repo. Code: Your-Repo-Here.
