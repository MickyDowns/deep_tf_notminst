# TF for Not-Minst character recognition and for Text Sequencing

## Overview

These are my Jupyter notebook annotations and extensions to the Google / Udacity Deep Learning course: https://www.udacity.com/course/deep-learning--ud730. That course was a great intro to TensorFlow. However, the Python knowledge requirement was "advanced" making the class less accessible. So, I've saved of my models / annotations in these notebooks. 

## Who this may help

If you're taking the course and struggling with how to translate concepts to code or want to see results under a variety of assumptions, these notebooks may help. If your not taking the course but are interested in seeing a curated version of how Google implements CNN and RNN/LSTM networks, this should help.

## What's Implemented

**Deep Learning:** a branch of machine learning that models high-level data abstractions using multiple (often layered) non-linear transformations. In this case, we're talking about networks with 2-5 hidden layers. 

**Convolutional Neural Nets (CNN):**  feed-forward network used for image recognition as neurons are arranged to respond to overlapping data regions... like your eyeballs.  The objective here is Non-MINST character recognition which are implemented with variations for network depth, activation units and regularization including dropout. 

**Recurrent Neural Nets (RNN):** cyclic network used for natural language processing (NLP) as directed cycle enables network to process arbitrary sequences of inputs and, thereby, detect temporal behavior. The objective here is to implement word2Vec and LSTM models in an unsupervised environment to embed words then predict context and, thereby, meaning. 

## Getting Started

The project technology is Python2, Jupyter notebook, TensorFlow. Udacity / Google have created a Docker environment here: https://github.com/tensorflow/tensorflow/tree/master/tensorflow/examples/udacity. If you're more ambitious, you can install TensorFlow directly: https://github.com/tensorflow/tensorflow. 