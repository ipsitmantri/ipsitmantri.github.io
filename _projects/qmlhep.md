---
layout: page
title: QML-HEP
description: A GSOC evaluation task
img: assets/img/qmlhep.png
importance: 1
category: Miscellaneous
---
This project is my attempt to solve the tasks given as a part of screening process for [Quantum Machine Learning for High Energy Phiysics (QML-HEP) Google Summer of Code (GSOC) projects](https://ml4sci.org/gsoc/projects/2021/project_QMLHEP.html){:target="_blank"}. However, I didn't submit a project proposal🥲

## Task 1 - Quantum Computing
![QC](/assets/img/qmlhep_t1.png)  
I had to implement basic quantum circuits involving different gates and measure probabilities of states using the [Google Cirq](https://quantumai.google/cirq){:target="_blank"}. 

## Task 2 - Quantum Generative Adversarial Network (QGAN)
![QGAN](/assets/img/qmlhep.png)  
I had to explore how to apply a QGAN to solve a High Energy Data analysis issue, more specifically, separating the signal events from the background events. I had to use the [Google Cirq](https://quantumai.google/cirq){:target="_blank"} and [Tensorflow Quantum](https://www.tensorflow.org/quantum){:target="_blank"} libraries.

## Task 3 - Quantum Convolutional Neural Network (QCNN)
![QCNN](/assets/img/qmlhep_t3.png)  
I had to setup and apply a quantum CNN on particle physics data to perform a binary classification on electrons and photons. Again I had to use [Tensorflow Quantum](https://www.tensorflow.org/quantum){:target="_blank"} library.

## Task 4 - Classical Graph Neural Network (GNN)
I had to use ParticleNet's data for Quark/Gluon jet classification and use 2 GNN architectures of my choice to classify the jets as being quarks or gluons. I did this using [Deep Graph Library](https://www.dgl.ai/){:target="_blank"}.

## Task 5 - Open Task
I had to comment on quantum computing or quantum machine learning. I had to include one quantum algorithm or one quantum software that I was familiar with. I will post my solution as a blog post soon.

For the codes and jupyter notebooks, please check [here](https://github.com/ipsitmantri/QML-HEP-Evaluation-Test-GSOC-2021){:target="_blank"}.