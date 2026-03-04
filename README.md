# deep-learning-projects

A collection of deep learning implementations built from scratch using **PyTorch**, developed as part of my M.Tech coursework in Computer Science (Artificial Intelligence) at Defence Institute of Advanced Technology, Pune.

Each notebook is self-contained and demonstrates hands-on understanding of core deep learning architectures — from foundational MLPs to advanced convolutional networks and sequence models.

---

## Projects

### 1. MLP with Activation Function Comparison — MNIST
`DNN_Assignment_1_MLP_MNIST.ipynb`

Implemented a Multi-Layer Perceptron (MLP) from scratch on the MNIST handwritten digit dataset. Compared the effect of four activation functions — **ReLU, Tanh, Sigmoid, and LeakyReLU** — on training convergence and classification accuracy, with visualizations of results and predictions from the best-performing model.

- **Framework:** PyTorch
- **Dataset:** MNIST
- **Key concepts:** MLP architecture, activation functions, training loops, evaluation

---

### 2. CNN from Scratch — CIFAR-10
`DNN_Assignment_3_CNN_CIFAR10.ipynb`

Designed and trained a Convolutional Neural Network (CNN) from scratch for image classification. Includes data preparation, model definition, training loop, loss visualization, and prediction samples.

- **Framework:** PyTorch
- **Dataset:** CIFAR-10
- **Key concepts:** Convolutional layers, pooling, image classification, training & evaluation

---

### 3. VGG19 from Scratch — CIFAR-10
`DNN_Assignment_4_VGG19_CIFAR10.ipynb`

Implemented the **VGG19 architecture from scratch** (without pretrained weights) and trained it on CIFAR-10. Demonstrates a deep understanding of the VGG design philosophy — uniform 3×3 convolutions, depth scaling, and fully connected classifier layers.

- **Framework:** PyTorch
- **Dataset:** CIFAR-10
- **Key concepts:** Deep CNN architecture, VGG design, training from scratch

---

### 4. DenseNet from Scratch — CIFAR-10
`DNN_Assignment_5_DenseNet_CIFAR10.ipynb`

Built **DenseNet from the ground up**, implementing custom `DenseLayer`, `DenseBlock`, and `TransitionLayer` modules. Trained and evaluated on CIFAR-10.

- **Framework:** PyTorch
- **Dataset:** CIFAR-10
- **Key concepts:** Dense connectivity, feature reuse, skip connections, batch normalization

---

### 5. InceptionV3 Implementation — CIFAR-10
`DNN_Assignment_5_InceptionV3_CIFAR10.ipynb`

Implemented the **InceptionV3 architecture** with custom inception modules, trained on CIFAR-10. Covers the multi-scale convolution design that makes Inception networks computationally efficient.

- **Framework:** PyTorch
- **Dataset:** CIFAR-10
- **Key concepts:** Inception modules, multi-scale feature extraction, factorized convolutions

---

### 6. Stock Price Prediction with RNN — Netflix
`DNN_Assignment_StockPredRNN.ipynb`

Built a Recurrent Neural Network (RNN) to predict **Netflix (NFLX) closing stock prices** using historical data fetched via the `yfinance` API. Includes time-series preprocessing, MinMax normalization, sequence dataset construction, and evaluation using MSE and MAE.

- **Framework:** PyTorch
- **Dataset:** Netflix stock data (2010–2022) via `yfinance`
- **Key concepts:** RNN, time-series forecasting, sequence modeling, MinMax scaling

---

## Tech Stack

| Category | Tools |
|---|---|
| Framework | PyTorch |
| Data & Preprocessing | NumPy, Pandas, Scikit-learn |
| Visualization | Matplotlib |
| Environment | Google Colab / Jupyter Notebook |
| Data Sources | torchvision datasets, yfinance |

---

## About

These projects are part of my deep learning coursework and reflect a bottom-up approach to understanding neural network architectures — building components from scratch rather than relying on pretrained models.

Feel free to explore, fork, or raise issues!

**Ananya Reetha Noble**
M.Tech CSE (AI) | DIAT Pune
[LinkedIn](https://www.linkedin.com/in/ananya298/) • [GitHub](https://github.com/ananyarn)
