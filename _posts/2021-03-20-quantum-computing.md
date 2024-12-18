---
layout: post
title:  My perspective on Quantum Computing and Quantum Machine Learning
date:   2021-03-20 10:00:00
description: My solution to one of the tasks of QML-HEP GSOC 2021 Evaluation Tasks
tags: quantum, qml, quantum-computing
categories: miscellaneous
---
We are currently in the **Noisy Intermediate Scale Quantum** [(NISQ)](https://en.wikipedia.org/wiki/Noisy_intermediate-scale_quantum_era){:target="_blank"} Computing
era. The recent quantum supremacy experiment by Google was remarkable.
The key reason why quantum circuits or quantum computers can be much
faster than their classical counterparts is because of [**quantum entanglement**](https://en.wikipedia.org/wiki/Quantum_entanglement){:target="_blank"}
or [**Bell states**](https://en.wikipedia.org/wiki/Bell_state){:target="_blank"}, which are not classically realisable. For a quantum circuit to
outperform a classical circuit, this is an essential requirement.  

The crux of machine learning or deep learning is the [**Universal Approximation Theorem**](https://en.wikipedia.org/wiki/Universal_approximation_theorem){:target="_blank"}, which informally means that by choosing a suitable deep neural
network, we can approximate any arbitrary function as closely as possible. All
the other types of machine learning algorithms, like Convolutional Neural
Networks, Residual Networks, LSTMs, Graph Neural Networks, etc. are making
use of this theorem in one way or the other. But in the present times, the stateof-
the-art machine learning algorithms are beating human-level performance,
along with becoming increasingly complex. Consider the recently released
**Generative Pre-Trained Transformer 3** [(GPT-3)](https://en.wikipedia.org/wiki/GPT-3){:target="_blank"} which is one the best models
built by the scientists, but it has a whooping 175 billion parameters! It costs
huge money for any person to fine-tune such a model for his work/research. It
takes a lot of time to train too! But all this can be hopefully circumvented by
developing and using [**Quantum Machine Learning**](https://en.wikipedia.org/wiki/Quantum_machine_learning){:target="_blank"}, i.e., by making use of
quantum circuits to approximate functions.  

We know that we can derive a quantum circuit which produces results similar to
any classical circuit/function. By making use of Bell states, we can increase the
speed of making those computations. So, if we choose a generalized universal
approximation theorem (informally), we can create fast and efficient algorithms
giving comparable results and maybe outperforming the current classical
state-of-the-art methods. Me being someone interested in quantum computing
and quantum machine learning, I would like to focus on deriving quantum
circuits which make extensive use of quantum entanglements and learn to do
tasks at hand, exploiting quantum parallelism.  

One quantum algorithm that I like the most is the idea of [**Superdense Coding**](https://en.wikipedia.org/wiki/Superdense_coding){:target="_blank"}.
In superdense coding, we generate and exploit a Bell state, and with a slight
overhead of classical symbol coding, we can send/receive information
equivalent to 2 classical bits using one quantum bit (qubit). If a communication
standard is developed using this algorithm, this will improve the bandwidth efficiency by orders of magnitude. This will lead to more higher speeds of data communication and higher speeds of internet. Such high speed communication can also be used in the context of autonomous driving. An autonomously
driven car needs to send and receive data constantly and should act as per the
actions happening in its surroundings. If such a car uses this type of
communication, it can act better in the case of emergencies and latencies will
be drastically reduced.  

The quantum software that I am familiar with is the combination [**Cirq**](https://quantumai.google/cirq){:target="_blank"} +
[**Tensorflow Quantum**](https://www.tensorflow.org/quantum){:target="_blank"} by Google. I found this software extremely user-friendly
and highly intuitive to use. It has implementations ready for all the standard
quantum gates and it also compatible with [**Sympy**](https://en.wikipedia.org/wiki/SymPy){:target="_blank"}, using which, we can define
symbolic names to the circuit parameters and then assemble them in the form
of [**Parametrized Quantum Circuits**](https://www.tensorflow.org/quantum/tutorials/hello_many_worlds){:target="_blank"}. These are also compatible with classical
[**Tensorflow**](https://www.tensorflow.org/){:target="_blank"} and [**Keras**](https://keras.io/){:target="_blank"} models, and has a similar API too. I recommend this
software to anyone getting started with quantum computing and quantum
machine learning. We can also train hybrid models involving both classical and
quantum parts. One's imagination is the only boundary here!  

Lastly, I would like to contribute to any work which explores and demonstrates
that Quantum Computing can be the new paradigm, and by using it we can
reduce the amount of computational resources required drastically, which inturn
helps in solving even more computationally intensive problems. This is the
beginning of a new era in Artificial Intelligence and Computing and I would like
to contribute my best to the proof of principle by taking guidance from the
experts.