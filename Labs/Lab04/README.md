# Lab 04: Simulating Spiking Neurons with Python

## Overview
This lab explored spiking neural behavior using the Leaky Integrate-and-Fire (LIF) neuron model. The assignment focused on how biological neurons encode and transmit information through spikes rather than continuous values. Through simulations and experiments, I examined membrane potential dynamics, spike generation, temporal coding, and simple spiking neural networks.

## What I Did
- Implemented a Leaky Integrate-and-Fire (LIF) neuron model in Python using Google Colab.
- Simulated membrane potential changes over time using input current, leakage, threshold firing, and reset behavior.
- Visualized neuron activity with membrane potential plots and spike timing outputs.
- Explored rate coding and temporal coding methods for representing information as spikes.
- Created raster plots to compare spike encoding strategies.
- Built a small spiking neural network with connected neurons and synaptic weights.
- Conducted experiments testing threshold sensitivity, membrane time constant effects, and noisy input currents.
- Analyzed how changes in neuron parameters affected spike frequency and network behavior.

## What I Learned
This lab helped me understand how spiking neurons differ from traditional artificial neurons used in most neural networks. I learned that biological neurons communicate using discrete spikes and that timing can be just as important as firing frequency. I also observed how membrane leakage, threshold values, and input current shape neuron behavior over time.

Additionally, I gained a stronger understanding of rate coding versus temporal coding and how information can be represented differently depending on the neural strategy being used. Building a small spiking network also demonstrated how signals propagate through interconnected neurons in a biologically inspired system.

## Challenges
One of the biggest challenges in this lab was correctly implementing the LIF differential equation and debugging situations where the neuron either failed to spike or spiked continuously. Understanding the relationship between input current, threshold, and membrane leakage required experimentation and troubleshooting. Another challenge was interpreting raster plots and understanding how temporal coding differs conceptually from rate-based encoding.

## Files
- `L04_Hillary_Bruton_ITAI4374.ipynb`
