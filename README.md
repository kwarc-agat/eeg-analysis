# EEG Classification

Experiments with various methods of classifying EEG signals. 

**Movie Emotions (ME) dataset**  was gathered during VR simulations aimed at evoking different emotions - the goal is to decide if the subject was calm or alert based on registerd brainwaves. Originally it had form of bandpowers (delta, theta, alpha, beta and gamma) and was obtained as a part of student project.

**Drivers Dataset (DD) dataset** is publicly available, professional dataset [[3]](#3). It contains event-related potentials of car drivers during VR session. The aim is to define whether the subject was attentive during the simulated drive, based on their EEG. This experiment was inspired by study [[4]](#4)

## Features

- deep learning
    - EEGNet [[1]](#1)[[2]](#2)
- machine learning methods
    - Support Vector Machine
    - k-Nearest Neighbours
    - Decision Tree
- datasets preprocessing
    - cleaning
    - smoothing
    - augmentation
    - reformatting
- predictions visualisation

## Technologies

- Python
    - sklearn
    - mne
    - sktime
    - pandas, numpy
    - matplotlib, seaborn
- Tensorflow Keras API
- Jupyter Notebook

## Demo

<i>in preparation</i>

## Getting started

Browse attached Jupyter Notebooks.

## Literature

<a id="1">[1]</a>
Lawhern, V.J., Solon, A.J., Waytowich, N.R., Gordon, S.M., Hung, C.P., Lance, B.J.,Eegnet: a compact convolutional neural network for eeg-based brain–computer interfaces, Journal ofneural engineering. 2018, tom 15, 5, str. 056013.

<a id="2">[2]</a>
A collection of convolutional neural network models for eeg signal processing and classi-fication, using keras and tensorflow: https://github.com/vlawhern/arl-eegmodels

<a id="3">[3]</a>
Cao, Z., Chuang, C.H., King, J.K., Lin, C.T., Multi-channel eeg recordings during asustained-attention driving task, Scientific data. 2019, tom 6, 1, str. 1–8.

<a id="4">[4]</a>
Atilla, F., Alimardani, M., Eeg-based classification of drivers attention using convolutional neural network, [2021](https://arxiv.org/ftp/arxiv/papers/2108/2108.10062.pdf)