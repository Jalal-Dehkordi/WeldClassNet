# WeldClassNet
Designing a Deep learning model for Classifying Welding Defects from industrial X-ray images

![image](https://github.com/user-attachments/assets/e1a44a46-458b-48a1-872b-21b7413caa03)





## Project Overview
**WeldClassNet** is a deep learning-based neural network designed for the automatic classification of weld defects from industrial X-ray (radiographic) images. The model is built upon the EfficientNetB1 architecture, which is fine-tuned and enhanced to suit the specific needs of weld defect detection and classification. It introduces a custom classification head and additional convolutional layers to improve feature extraction and accuracy.

## Key Features
- **EfficientNetB1 Backbone**: Utilizes the EfficientNetB1 pre-trained model for strong feature extraction.
- **Custom Classification Layers**: Modified with additional CNN layers, sequential linear layers, and ReLU activations to improve classification performance.
- **Squeeze-and-Excitation Block**: Enhances model capacity to focus on the most important features by introducing a Squeeze-and-Excitation block.
- **Transfer Learning**: Fine-tuning on a custom dataset of weld defects for optimal performance.

## Benefits
- **Automatic Detection**: Automates the identification of different types of weld defects, reducing manual inspection time.
- **Improved Accuracy**: Tailored architecture for weld defect classification ensures higher accuracy compared to generic models.
- **Scalability**: Can be adapted for other industrial defect detection tasks by fine-tuning.

## Dataset
The model is trained and evaluated on a custom dataset comprising radiographic images of welds, categorized into different defect types. The dataset is split into training, validation, and test sets.

## Installation
To run this project, you will need to install the following dependencies:
* Python 3.7+
* PyTorch
* torchvision
* matplotlib
* tqdm
* scikit-learn

## Visualization
The training and validation metrics, such as accuracy and loss, are plotted for better understanding of the model's performance over time. The confusion matrix is used to visualize classification results and analyze model accuracy.
![image](https://github.com/user-attachments/assets/07b24d6e-9e8b-4c12-847a-fc1197ba0c1a)





## Usage
You can modify the number of epochs, learning rate, and other hyperparameters in the training function to suit your hardware capabilities and dataset size.

## Contributions
Contributions are welcome! Feel free to open an issue or submit a pull request to improve the model or add new features.
