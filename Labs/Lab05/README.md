# Lab 05: Sensory Processing and Perception

## Overview
This lab explored how biological sensory systems process visual and auditory information and how those principles relate to artificial intelligence systems. The assignment focused on retinal processing, edge detection, visual cortex feature extraction, convolutional neural networks (CNNs), and auditory spectrogram analysis. Through biological-inspired filters and signal processing techniques, I examined how both brains and AI systems transform raw sensory input into meaningful representations.

## What I Did
- Implemented a center-surround receptive field filter using a Difference of Gaussians (DoG) model to simulate retinal ganglion cell behavior.
- Applied center-surround filtering to multiple images to observe how biological vision emphasizes contrast and edges rather than uniform brightness.
- Implemented Gabor filters to simulate orientation-sensitive neurons in the primary visual cortex (V1).
- Applied Gabor filters at different orientations to analyze directional edge detection.
- Compared biological visual processing to feature extraction in convolutional neural networks (CNNs).
- Generated and analyzed auditory spectrograms to study how sound frequencies change over time.
- Explored how biological auditory systems and AI models both rely on frequency decomposition and hierarchical sensory processing.

## What I Learned
This lab demonstrated that biological sensory systems perform significant preprocessing before information reaches higher cognitive areas. I learned that the retina is not simply a passive camera, but an active computational system that enhances edges and suppresses uniform illumination through lateral inhibition. I also observed how Gabor filters closely resemble the edge detectors learned in the early layers of convolutional neural networks.

Additionally, the auditory portion of the lab helped me understand how spectrograms represent sound as changing frequency information over time, similar to how the cochlea performs frequency decomposition in the human auditory system. Overall, the lab reinforced how many modern AI architectures are strongly inspired by neuroscience and biological perception.

## Challenges
One of the most challenging parts of this lab was implementing and debugging the center-surround Difference of Gaussians filter to ensure the filter produced the correct ON-center/OFF-surround response. Understanding why uniform regions disappear after filtering also required deeper analysis of lateral inhibition and contrast processing. Another challenge was connecting the mathematical image filters used in AI to the underlying biological mechanisms they were designed to approximate.

## Files
- `L05_Hillary_Bruton_ITAI4374.ipynb`
