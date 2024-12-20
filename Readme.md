# 🐝 Bee and Ant Classifier 🐜

Welcome to the **Bee and Ant Classifier** project! This repository contains a deep learning model built using PyTorch to classify images of bees and ants. 

## 📦 Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Training](#training)
- [Results](#results)
- [License](#license)

## 🌟 Features
- **Image Classification**: Classifies images into two categories: Bees and Ants.
- **Data Augmentation**: Utilizes random resizing, horizontal flipping, and normalization for better model performance.
- **Visualization**: Includes functions to visualize training results and confusion matrix.

## 🛠️ Installation
To get started, clone the repository and install the required packages:

> git clone https://github.com/yourusername/bee-ant-classifier.git
> cd bee-ant-classifier
> pip install -r requirements.txt


## 🚀 Usage
To use the model for predictions, run the following command:

> python predict.py --image_path path/to/your/image.jpg


## 📈 Training
To train the model on your dataset, execute:
> python train.py --data_dir path/to/dataset



### Training Parameters:
- **Epochs**: Number of training epochs (default: 10)
- **Batch Size**: Size of each training batch (default: 32)

## 📊 Results
The model's performance is evaluated based on loss and accuracy metrics. Visualizations of training and validation losses over epochs are provided.

![Loss vs Epochs]

### Confusion Matrix:
A confusion matrix is generated to visualize the classification performance.

![Confusion Matrix]

## 📄 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Feel free to contribute to this project by submitting issues or pull requests! 😊





