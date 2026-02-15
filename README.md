# Traffic Sign Image Classifier 🚦

A Convolutional Neural Network (CNN) built using TensorFlow/Keras to classify traffic signs from the German Traffic Sign Recognition Benchmark (GTSRB) dataset.

## Dataset
- German Traffic Sign Recognition Benchmark (GTSRB)
- 43 traffic sign classes
- Images resized to 32×32

Dataset source: https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign

## Model Architecture
- Conv2D + ReLU
- MaxPooling
- Conv2D + ReLU
- MaxPooling
- Flatten
- Dense (ReLU)
- Dense (Softmax)

## Training
- Optimizer: Adam
- Loss: categorical_crossentropy
- Epochs: 10
- Train/Validation split: 80/20

## Results
- Achieved ~98.99% validation accuracy
- Evaluated on official GTSRB test set

## How to Run
1. Install dependencies:
   ```bash
   pip install tensorflow numpy opencv-python matplotlib scikit-learn
2. Open the notebook:
     traffic_sign_cnn.ipynb
3. Run all cells in order
