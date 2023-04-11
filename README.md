# User Identification from Accelerometer and Gyroscope Sensor with Federated Learning

# Authors
- Rafael Veiga 
- Rodrigo Flexa
- Lucas Bastos
- Iago Medeiros
- Denis Rosário
- Eduardo Cerqueira

# Abstract

In this new era of mobile devices with many types of sensors, IoT, and other devices with sensitive data, much of this data is shared for application apps. A smartphone can collect and use this data in machine learning approaches, and a request for this process is to use them with more user security. These sensors can collect biometric behaviors from users during their devices. However, an identification system using a mobile device does not need to share sensitive data, focusing on data security and sharing just user weights. This paper introduces a Federated Learning approach for defining an accelerometer and gyroscope using a unique identifier to identify a user's behavior for continuous user identification. This study used several convolutional neural networks (CNN) to evaluate their performance for IoT devices. Thus, our simulation revealed the best configuration using FCN with 5 and 3 epochs.

# Big picture

![alt text](big.PNG)

# federated_run.py

The python file is for running our simulation federated learning. In this, we choose some Convolutional neural networks to evaluate and the metrics we search to identify users like the False positive rate and rejection rate. Thus, we made a code to run federated learning in his main strategy FedAVG. We use some CNNs from Sktime-dl to run users using gyroscope sensors as unique identifiers.

# analysis_final.ipynb

In this Jupyter project, we do a complete analysis of BrainRun to understand how they collect and distribute this data. The times to span each sample and how this influences the data frame. The code shows the many groups created from the number of timestamps. With this, we prepare the minimum values we need to prepare the data frame we will use for Federated Learning. 

