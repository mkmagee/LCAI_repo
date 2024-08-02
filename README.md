# LCAI_repo


## Comparing CPU and GPU Performance for Training and Inference with PyTorch
This notebook compares the performance of training and inference of a neural network model using a CPU versus a GPU. The model is implemented using PyTorch, and the dataset used is MNIST. Key metrics such as training time, inference time, throughput, CPU usage, and memory usage are measured and reported.

## Overview
- Device Switching: Utilizes PyTorch's torch.device to switch between CPU and GPU for model computations.
- Training: On both devices, the model is trained using forward and backward passes.
- Inference: Performance metrics are calculated during the inference phase, including accuracy, inference time, throughput, CPU usage, and memory usage.


