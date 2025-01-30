---
title: "Optimization of Gravitational waves Detection"
subtitle: "A TDA viewpoint."
excerpt: "Use toplogical features to optimize the gravitational wave detection."
date: 2025-01-30
author: "Alejandro Ucan-Puc"
draft: false
tags:
  - research
  - TDA
  - IA
categories:
  - research
  - TDA
  - IA
links:
- icon: github
  icon_pack: fab
  name: code
  url: 
---

Gravitational Waves detection is a hard work due to the nature of signals and the noise that is present in the data. In this project, we are interested in research and develop optimized methods to detect, classify and denoise signals with the behavior of gravitational waves.


The first direct detection of gravitational waves was made by the LIGO and Virgo collaborations in 2015, when they observed the merger of two black holes. Since then, several other detections have been made, including the merger of neutron stars and the collision of a black hole with a neutron star. The detection of gravitational waves has opened up a new window on the universe, allowing us to observe phenomena that are invisible to traditional telescopes.

Although several similar observations have been made since then, detecting such waves poses significant challenges due to intrinsic and environmental noise affecting the measuring instruments. These extremely faint signals must be picked up by highly sensitive gravitational wave detectors such as LIGO and Virgo, which are designed to detect minute deformations in space-time. However, these instruments are subject to a wide range of noise sources, from seismic vibrations and nearby human activity to thermal and electromagnetic fluctuations. The extreme sensitivity required to detect gravitational waves also amplifies these noises, complicating the process of distinguishing between genuine signals and interference. Therefore, the development and refinement of advanced filtering and data analysis techniques to identify and extract the relevant signals from the prevailing noise is critical. 

Topological Data Analysis look a good candidate to work on this task, and this follows from the fact that with TDA algorithms we can understand the underlying properties of the signals. Bresten and Jung (2019) proposed a novel approach using convolutional neural networks and persistent homology, but it was on 2024 where its paper was published. 

## Project 1: 

Inspired by the work of Bresten and Jung, we proposed to ad Persistent images in the Convolutional neural networks in addition with a Fourier Analysis of the signal data base. This modification shown a good performance of the Neural network with best accuracy compared with the one in Bresten and Jung.

This work was part of the MA2007B Challenge, with the team:

* Ángel Azahel Ramírez Cabello (A01383328@tec.mx, MTY)
* Annette Pamela Ruiz Abreu (A01423595@tec.mx, MTY)
* Avril Michelle Ruiz Martínez (A00833018@tec.mx, MTY)
* Franco Mendoza Muraira (A01383399@tec.mx, MTY)
* Jorge Raúl Rocha López (A01740816@tec.mx, MTY)
* Luis Angel López Chávez (A01571000@tec.mx)

We are working actively on the preprint with the results.

## Project 2

We know that the Noise Ratio Index in the data base is fundamental in the performance of the Neural network for a good classification. From that fact, and the fact that in nature, the gravitational wave signals comes with a high level of noise. We propose a novel approach to denoise that signals and reconstruct a smooth way using topological features.

This work was part of the MA2007B Challange, with the team:

* Felipe Felix Arredondo
* Sofia Alvarez Sandoval
* Valeria María Serna Salazar
* Raúl Alejandro Perez Saucedo
* Ana Paola Almeida Pérez
* David Alejandro Matamoros Alvarado


We are working actively on the preprint with the results


### References

* BRESTEN, C., & JUNG, J. H. (2024). DETECTION OF GRAVITATIONAL WAVES USING TOPOLOGICAL DATA ANALYSIS AND CONVOLUTIONAL NEURAL NETWORK. JOURNAL OF THE KOREAN SOCIETY FOR INDUSTRIAL AND APPLIED MATHEMATICS, 28(4), 243-255.