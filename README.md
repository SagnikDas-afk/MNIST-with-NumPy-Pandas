# MNIST-with-NumPy-Pandas
The MNIST dataset is one of the most well-known benchmarks for testing image classification algorithms. It contains 70,000 grayscale images of handwritten digits (0–9), where:
- 60,000 images are used for training
- 10,000 images are used for testing
Each image is 28×28 pixels in size and represents a single handwritten digit. The pixel intensity values range from 0 (black) to 255 (white), which can be normalized to the range [0, 1] for easier computation.

This project demonstrates how to load, analyze, and classify MNIST digits using only NumPy and Pandas, without relying on deep learning frameworks like PyTorch or TensorFlow.


I implemented a simple two-layer neural network and trained it on the MNIST digit recognizer dataset. It's meant to be an instructional example, through which you can understand the underlying math of neural networks better.
Our NN will have a simple two-layer architecture. Input layer  a[0]
  will have 784 units corresponding to the 784 pixels in each 28x28 input image. A hidden layer  a[1]
  will have 10 units with ReLU activation, and finally our output layer  a[2]
  will have 10 units corresponding to the ten digit classes with softmax activation.

<img width="621" height="147" alt="image" src="https://github.com/user-attachments/assets/862fdfd4-9462-418f-8878-828ae5da6961" />
<img width="652" height="238" alt="image" src="https://github.com/user-attachments/assets/89ea20da-09c5-405d-9a98-030734179cfd" />
<img width="635" height="143" alt="image" src="https://github.com/user-attachments/assets/518590b1-e21c-4543-86d9-5961271cb482" />



