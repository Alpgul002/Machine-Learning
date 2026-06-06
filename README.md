# Machine Learning Projects

This repository contains my academic and practical work in **Machine Learning**. It includes projects and notebooks covering supervised learning, neural networks, optimization, convolutional neural networks, image classification, text classification, and word embeddings.

The main purpose of this repository is to document my progress in machine learning by combining theoretical concepts with practical Python implementations.

## Topics Covered

* Supervised Learning
* Classification
* Regression
* K-Nearest Neighbors
* Decision Trees
* Logistic Regression
* Polynomial Regression
* Mini-Batch Stochastic Gradient Descent
* Momentum Optimization
* ADALINE
* Multilayer Perceptrons
* ReLU Activation
* Binary Cross-Entropy
* Convolutional Neural Networks
* Image Classification
* Text Classification
* Bag-of-Words
* Multinomial Naive Bayes
* Word Embeddings
* GloVe
* Cosine Similarity
* Word Analogies
* t-SNE Visualization

## Repository Structure

```text
Machine-Learning-Projects/
│
├── ML1.ipynb
│   └── K-Nearest Neighbors and Decision Tree Classification
│
├── ML2.ipynb
│   └── Logistic Regression and Polynomial Regression
│
├── ML3.ipynb
│   └── Mini-Batch SGD, Momentum, ADALINE, and MLPs
│
├── ML4.ipynb
│   └── CNNs, MLPs, and Food Image Classification
│
└── ML5.ipynb
    └── Word Embeddings and Text Classification
```

## K-Nearest Neighbors and Decision Tree Classification

This notebook focuses on classical supervised classification methods using the Breast Cancer dataset.

Main topics:

* Dataset loading and exploration
* Train, validation, and test splitting
* Feature scaling with standardization
* Class distribution analysis
* K-Nearest Neighbors classification
* Hyperparameter tuning for different `k` values
* Decision Tree classification
* Hyperparameter tuning with `max_depth` and `min_samples_split`
* Model evaluation with accuracy
* Confusion matrix visualization
* Feature importance analysis

This part helped me understand how classical classification models work and how validation data is used to choose model parameters.

## Logistic Regression and Polynomial Regression

This notebook focuses on two fundamental machine learning tasks: classification with logistic regression and curve fitting with polynomial regression.

Main topics:

* Synthetic dataset generation
* Sigmoid function
* Binary classification
* Logistic regression loss
* Gradient computation
* Model training
* Polynomial feature construction
* Polynomial regression
* Mean squared error
* Underfitting and overfitting
* Model complexity analysis

This part helped me understand how gradient-based models are trained and how regression models change as polynomial degree increases.

## Mini-Batch SGD, Momentum, ADALINE, and MLPs

This notebook focuses on optimization and neural network fundamentals.

Main topics:

* ADALINE model
* Mini-Batch Stochastic Gradient Descent
* Momentum optimization
* Weight updates
* Learning rate effects
* ReLU activation
* Sigmoid activation
* Binary Cross-Entropy loss
* Multilayer Perceptron implementation
* Forward propagation
* Backpropagation
* Decision boundary visualization
* Non-linear classification

This part helped me understand how neural networks learn through gradient-based optimization.

## CNNs, MLPs, and Food Image Classification

This notebook focuses on image classification using neural networks. It compares MLP-based image classification with convolutional neural network approaches.

Main topics:

* Food image classification
* Food-101 subset
* Image preprocessing
* Image resizing
* Normalization
* Train and validation splitting
* MLP classifier
* CNN classifier
* Convolutional layers
* Output size calculation
* Weight sharing
* Translation equivariance
* Model training with PyTorch
* Validation accuracy
* Test accuracy

This part helped me understand why CNNs are more suitable than standard MLPs for image data.

## Word Embeddings and Text Classification

This notebook focuses on natural language processing and text-based machine learning.

Main topics:

* Pre-trained GloVe word embeddings
* Word vector loading
* Cosine similarity
* Nearest neighbor search
* Word analogy arithmetic
* t-SNE visualization
* Sentiment classification
* Text preprocessing
* Bag-of-Words representation
* Unigram and bigram features
* Multinomial Naive Bayes
* Train/test splitting
* Model evaluation

This part helped me understand how words can be represented as vectors and how classical machine learning methods can be used for text classification.

## Technologies Used

* Python
* Jupyter Notebook
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* PyTorch
* Torchvision
* Gensim
* NLTK / text preprocessing tools
* t-SNE
* GloVe embeddings

## Main Learning Outcomes

Through this repository, I practiced both the theory and implementation of machine learning.

I worked on:

* Training classical machine learning models
* Evaluating classification models
* Using validation sets for hyperparameter selection
* Implementing logistic regression concepts
* Understanding regression and model complexity
* Training models with gradient descent
* Implementing neural network components
* Understanding CNNs for image classification
* Applying NLP techniques for text classification
* Working with word embeddings and semantic similarity

## How to Run

Clone the repository:

```bash
git clone https://github.com/your-username/your-repository-name.git
```

Go into the project directory:

```bash
cd your-repository-name
```

Install the required libraries:

```bash
pip install numpy pandas matplotlib scikit-learn torch torchvision gensim
```

Open the notebooks:

```bash
jupyter notebook
```

Then run the notebook files step by step.

## Purpose of This Repository

The purpose of this repository is to present my machine learning learning process through practical notebooks. The work starts with classical supervised learning models and gradually moves toward neural networks, CNNs, image classification, word embeddings, and text classification.

This repository demonstrates my experience with both traditional machine learning and deep learning-based approaches.

## Author

**Alp Eren Gül**
Computer Science and Engineering Student
Sabancı University
