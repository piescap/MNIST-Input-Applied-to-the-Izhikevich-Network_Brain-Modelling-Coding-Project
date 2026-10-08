# Brain Modelling Coding Project: MNIST Input Applied to the Izhikevich Network
<p align="center">30  December 2024</p> 

---

## Overview
The **coding project** for the course: *"Brain Modelling"* held by **Professor Claudia Casellato** in the **[L-31] Artificial Intelligence** bachelor's degree program.

The main objective of the project is the implementation of a network of Izhikevich Neurons designed to process visual stimuli. The model simulates the dynamics of membrane potential and recovery variables for both excitatory and inhibitory neurons. A specific focus of the project is to study the variations in the network's response when provided with static visual inputs from the MNIST dataset. To achieve this, an input pipeline was developed to rate-code static images into suitable input currents that drive the neuronal activity.

---

## Objectives
- Simulate a spiking neural network composed of excitatory and inhibitory neurons using the **Izhikevich model**
- Configure intrinsic neuron parameters ($a, b, c, d$) and tune synaptic connection strength
- Preprocess and load static images from the **MNIST dataset**
- Implement a rate-coding mechanism to translate static pixel intensities into input currents
- Analyze network responses under varying stimulus conditions (e.g., changes in brightness, light distribution, and intensity)
- Generate **Raster Plots** and **Average Firing Rates** to visualize neuronal activity and highlight dynamic patterns
- Implement an **LSTM** deep neural network classifier to predict the original MNIST image labels based on sequential spike patterns



