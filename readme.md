# Introduction
The scope of this tutorial is to introduce the audience to the world of deep learning models and PyTorch as a training framework.

We will use a simple country prediction task to achieve this goal. More details on the task is available below.

# Task description
The task we will try to model today is that of predicting the country of a person from his name, i.e given a name string predict the country where he most probably belongs to.

We will achieve this using a deep learning model using Character-level Convolutional Neural Network (Char-CNN). More details on the model and intuitions as to why this architecture is chosen will be made clear in the following sections.

# Dataset
The dataset we will be using is a very simple one used in one of the PyTorch introductory tutorials. It consists of a small zip file containing names of people from 18 different nationalities/regions.

We will use this data to train our model and then test it out.
