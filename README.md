# 🧠 Handwritten Digit Recognition 📊

A deep learning project that uses a Convolutional Neural Network (CNN) to recognize handwritten digits (0–9) from the MNIST dataset. Achieves 95%+ accuracy and supports predictions from custom digit images. Built with Python, TensorFlow, and Keras.

---

## ✨ Features  
- Loads and preprocesses MNIST dataset for training/testing  
- Builds and trains a CNN using TensorFlow & Keras  
- Processes custom digit images for prediction (`digit.png`)  
- Visualizes training performance and results using Matplotlib  

---

## 🛠️ Prerequisites  
- Python 3.6 or higher  
- Visual Studio Code or any IDE  
- Handwritten digit image (`digit.png`, 28x28 grayscale)

---

## 🚀 Installation  
#bash
# Clone the repository
git clone https://github.com/your-username/handwritten-digit-recognition.git
cd handwritten-digit-recognition

# Set up virtual environment
python3 -m venv env

# Activate the environment
# Windows:
.\env\Scripts\activate
# Mac/Linux:
source env/bin/activate

# Install dependencies
pip install numpy pandas matplotlib tensorflow pillow
