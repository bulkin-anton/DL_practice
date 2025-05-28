# 🧠 Deep Learning Practice

This repository is a collection of practical assignments for the **“Introduction to Deep Learning”** course at the Computational Mathematics and Cybernetics Faculty (MSU CMC). It covers a variety of DL topics (from CNNs to RNNs, for example).  
Each task is provided as a Jupyter Notebook containing both implementation and an exploration of specific neural-network architectures and methods.

---

## 📁 Repository Structure

The repository is organized into thematic folders, each dedicated to a particular domain or architecture.

### [`Fully-Connected Neural Network in NumPy`](https://github.com/bulkin-anton/DL_practice/blob/main/0_nn_numpy/nn_on_numpy.ipynb)
- Building neural networks **from scratch** with NumPy, without high-level frameworks  
- Walk-through of forward and backward propagation  
- Experiments with different activation functions and weight-initialization strategies  

### [`Image Classification with a Fully-Connected Network in PyTorch`](https://github.com/bulkin-anton/DL_practice/blob/main/1_nn_pytorch/nn_on_pytorch.ipynb)
- Designing and training neural networks in PyTorch  
- Defining models, loss functions, and optimizers  
- Training on real datasets and analyzing the results  

### [`Image Segmentation`](https://github.com/bulkin-anton/DL_practice/blob/main/2_image_segmentation/image_segmentation_nns.ipynb)
- Segmentation tasks (e.g., U-Net)  
- Pre-processing medical and other image datasets  
- Evaluating segmentation quality with IoU and Dice metrics  

### [`Recurrent Neural Networks`](https://github.com/bulkin-anton/DL_practice/blob/main/3_RNN/RNN.ipynb)
- RNNs including LSTM and GRU  
- Applications to sequential data: text, time series  
- Comparing different architectures and hyperparameters  

### [`Conformer for Audio Denoising`](https://github.com/bulkin-anton/DL_practice/blob/main/5_denoising_conformer/denoising_conformer.ipynb)
- Conformer model for noise reduction in audio signals  
- Combining convolutional and transformer blocks  
- Training on noisy audio data and assessing performance

### [`pi-GAN for 3D Car Images Generation`](https://github.com/bulkin-anton/DL_practice/blob/main/6_pi-GAN_for_3D_car_generation/task-05-bulkin-final.ipynb)
- Implementation of pi-GAN: a generative model with periodic activations for 3D conscious image generation.
- Training on a set of images of cars using neural radiation fields and volumetric rendering.
- Visualization of the generation results and comparison with the original pi-GAN implementation.
- Analysis of the generation quality and model capabilities in the context of 3D conscious image synthesis.

---

## 🛠️ Technologies Used

- **Language**: Python  
- **Libraries**:  
  - NumPy  
  - PyTorch  
  - Matplotlib  
  - Librosa  
  - OpenCV  
- **Tools**:  
  - Jupyter Notebook  

---

> **Each practical assignment contains detailed theoretical background, a Python implementation, and demonstration examples that showcase the methods in practice.**
