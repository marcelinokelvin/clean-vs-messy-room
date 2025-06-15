# Messy vs Clean Room Classifier 🧹🛏️
Messy vs Clean Room Classifier is a binary image classification project made by Kelvin Marcelino for the Dicoding course Belajar Machine Learning untuk Pemula, using Convolutional Neural Networks (CNN) in TensorFlow/Keras to identify whether a room is messy or clean.

## 📦 Dataset
* Dataset URL:  
  [Messy vs Clean Room](https://github.com/dicodingacademy/assets/raw/main/ml_pemula_academy/messy-vs-clean-room.zip)  
* Contains images divided into `train/clean`, `train/messy`, `val/clean`, and `val/messy`.

## 🛠️ Tools & Libraries
* Python 3
* TensorFlow / Keras
* NumPy
* Matplotlib
* Google Colab (for training environment)

## 🧠 Model Architecture
* 4 Convolutional layers + MaxPooling
* 1 Fully Connected layer (Dense)
* 1 Output node with `sigmoid` activation
* Loss: `binary_crossentropy`
* Optimizer: `Adam`

## 🏋️ Training Details
* Image size: 150x150 pixels
* Batch size: 4
* Epochs: 25
* Augmented training with:
  * Horizontal flip
  * Shear
  * Rotation
* Achieved ~77% accuracy

## 🧪 How to Use
1. Clone and open the notebook in Colab.
2. The dataset will be downloaded and extracted automatically.
3. Train the model using the provided code.
4. Upload a new image to test if the room is classified as **messy** or **clean**.

## 📁 Files
* `messy_clean_classifier.ipynb` — Full notebook for training and testing
* Dataset is downloaded directly in runtime
