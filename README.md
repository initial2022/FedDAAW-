# FedDAAW-
FedDAAW: Dynamic Client Selection and Precision Adaptive Aggregation for Heterogeneous Federated Learning
1）Description
     This repository contains four distinct deep learning projects, each implemented as a separate Jupyter Notebook (.ipynb file). The experiments cover both classification and regression tasks across four benchmark datasets: MNIST, CIFAR-10, IMDB Reviews, and California Housing.

2）Dataset Information
     The following publicly available datasets are used in these experiments:
     MNIST: Handwritten digit recognition dataset containing 70,000 28×28 grayscale images (60,000 training, 10,000 test samples).
     CIFAR-10: Color image classification dataset with 60,000 32×32 images across 10 classes (50,000 training, 10,000 test samples).
     IMDB Reviews: Binary sentiment analysis dataset containing 50,000 movie reviews (25,000 training, 25,000 test samples).
     California Housing: Regression dataset with 20,640 samples and 8 features for predicting median house values.

3）All datasets are automatically downloaded during code execution and do not need to be manually prepared.

4）Code Information
     The repository contains four Jupyter Notebook files, each implementing a different experiment:
     MNIST Experiment: Handwritten digit classification using neural networks.
     CIFAR-10 Experiment: Image classification with convolutional neural networks.
     IMDB Reviews Experiment: Sentiment analysis using embedding layers and recurrent neural networks.
     California Housing Experiment: Regression task with fully connected neural networks.

    Each notebook is self-contained and includes data loading, preprocessing, model definition, training, and evaluation.

5）Usage Instructions
    (1) Prerequisites
            Install Anaconda3 (conda version 24.11.3 or compatible)
            Ensure Python 3.11.7 is installed

    (2) Installation Steps
           A. Create and activate a conda environment (optional but recommended):
	conda create -n dl_experiments python=3.11.7
	conda activate dl_experiments
           B.Install required dependencies:
	conda install numpy matplotlib scikit-learn scipy tensorflow -y
           C. Launch Jupyter Notebook:
                jupyter notebook
      (3) Running the Experiments
           A. Open the Jupyter Notebook interface in your web browser.
           B.  Navigate to the directory containing the four .ipynb files.
           C.Open and run each notebook sequentially or independently:
               (a) Execute cells in order (using Shift+Enter or the "Run" button)
               (b) Follow any additional instructions within each notebook

6) Requirements
    The following Python packages are required:
      numpy>=1.24.0
      matplotlib>=3.7.0
      scikit-learn>=1.3.0
      scipy>=1.11.0
      tensorflow>=2.13.0
      jupyter>=1.0.0

7) Methodology
     Each experiment follows a consistent methodology:
      (1)Data Loading: Automatic download and loading of the dataset
      (2) Preprocessing: Data normalization, splitting, and preparation
      (3)Model Architecture: Implementation of appropriate neural network architectures
      (4)Training: Model training with validation monitoring
      (5)Evaluation: Performance assessment using task-appropriate metrics
      (6)Visualization: Results visualization and analysis

     Specific model architectures vary by task:
	MNIST/CIFAR-10: Convolutional Neural Networks (CNNs)
	IMDB Reviews: Embedding layers with LSTM/GRU networks
	California Housing: Fully connected deep neural networks

8) License & Contribution Guidelines
This project is provided for educational and research purposes. Users are free to modify and distribute the code with proper attribution to the original sources. For contributions, please follow standard GitHub collaboration practices: fork the repository, create a feature branch, and submit a pull request with clear documentation of changes.
