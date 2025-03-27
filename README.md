# Glaucoma Detection Using Deep Learning

## Overview
This project focuses on detecting glaucoma using deep learning models. Transfer learning is applied to pre-trained models like GoogLeNet, AlexNet, ResNet50 and VGG16 to classify fundus images as normal or glaucomatous. The goal is to develop an efficient and accurate automated glaucoma detection system.

## Dataset
The dataset consists of eye images labeled as either normal or glaucomatous. The data is preprocessed and split into training and testing sets.

## Models Used
- **GoogLeNet**
- **AlexNet**
- **ResNet50**
- **VGG16**

## Methodology
1. **Data Preprocessing**: Image resizing, normalization, and augmentation techniques are applied to enhance model performance.
2. **Transfer Learning**: Pre-trained models are fine-tuned for glaucoma detection.
3. **Model Training**: The models are trained using appropriate hyperparameters.
4. **Evaluation**: Performance metrics such as accuracy, precision, recall, F1-score and confusion matrix are used to evaluate the models.

## Results
The trained models achieve promising results in distinguishing normal eyes from glaucomatous eyes. The best-performing model is identified based on evaluation metrics. Among all the models, GoogleNet achieved the highest accuracy (89.28%), followed by ResNet50 (86.16%), while VGG16 and AlexNet scored 44.64%.

![image](https://github.com/user-attachments/assets/5c26ae26-a405-4689-9089-74b34c8540c1)
Normal Eye

![image](https://github.com/user-attachments/assets/a1739481-fcef-43a1-8be5-8e93071045ed)
Glaucomatous Eye

## Installation & Usage
### Prerequisites
- Google Colab
- PyTorch
- NumPy
- Matplotlib

### Steps to Run
1. Clone this repository:
   ```sh
   git clone https://github.com/Khushi9898/Glaucoma-Detection.git
   ```
2. Navigate to the project directory:
   ```sh
   cd Glaucoma-Detection
   ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
4. Open and run the `final.ipynb` notebook in Jupyter Notebook.

## Future Scope
- Enhancing model accuracy with more advanced architectures.
- Deploying the model as a web application for real-time glaucoma detection.
- Expanding the dataset for better generalization.

## Contributors
- **geeta614** 

