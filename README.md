# Compression of Deep Neural Networks 

## Abstract

Using multiple hidden layers and over-parameterization, Deep Neural Networks have recently become popular
due to their ability to fit a vast array of large datasets. In this era of data explosion, however, the resultant large
size poses challenges for running and evaluating these models on devices with limited memory and computation
power. In this project, we explore and compare the performance of different DNN compression techniques like
Network Pruning, Quantization, and Knowledge Transfer across various benchmarks like Accuracy, Size, and
Latency.

## Structure

It is a project composed of multiple jupyter notebooks and is built heavily with the help of pytorch.
Kindly install pytorch (compatible with CUDA) or use Google Collab to reproduce the results. 

Please run the Jupyter Notebooks individually to replicate the results.

The structure of the project is -

### ---- CIFAR10 (Baseline)

------------ training_CIFAR10.ipynb

### -------- Network Pruning

------------ training_CIFAR10_random_pruning.ipynb

------------ training_CIFAR10_unstructured_pruning.ipynb

### -------- Quanitization

------------ dynamic_quantization.ipynb

------------ static_quantization.ipynb

### -------- KnowledgeDistillation

------------ Knowledge_Distillation.ipynb
