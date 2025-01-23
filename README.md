# Project Overview

This project implements a network of **Izhikevich Neurons**, which are defined by two state variables—`u` (membrane recovery) and `v` (membrane potential). The model also includes four parameters (`a`, `b`, `c`, `d`) that influence the dynamics of these state variables. The network is designed to resemble the structure of the mammalian cortex, with inhibitory and excitatory neurons in a 1:4 ratio. These neurons are interconnected through synaptic strengths (`S`), which vary between the two neuron classes.

## Goals

The objective of this implementation is to analyze the response of the network to static visual inputs from different classes. To achieve this:
1. An input pipeline was developed to **rate-code static images** into a suitable input current for the neurons.
2. Original visualization methods were retained to enable analysis of the network responses.
3. A **Classifier** was integrated to predict the label of input images based on the network's response, allowing for validation of the model's outputs.

---

## Bonus Feature

An alternative implementation of the model is available, which processes **audio data** as input, demonstrating the flexibility of the approach across different input modalities.
