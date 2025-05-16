# forestfire_detection_using_deep_learning 
# 🔥 Wildfire Detection with CNN  
*“When the forest speaks in flames, let AI be the first to listen.”*

Welcome to a project built to **detect wildfires** using the power of **deep learning**. In a world where climate change fuels natural disasters, early detection can save ecosystems, lives, and resources. This CNN model aims to be a digital firefighter — spotting the spark before the blaze.

---

## 🌍 Project Overview

We trained a **Convolutional Neural Network (CNN)** to classify images as either:

- 🔥 `Fire`
- 🌲 `NoFire`

The model is trained on [The Wildfire Dataset](https://www.kaggle.com/datasets) from Kaggle, containing curated real-world images of forests with and without wildfires.

## 🧠 Model Highlights

Our CNN architecture includes:

- 📦 **Conv2D Layers** for feature extraction  
- 📉 **MaxPooling Layers** for dimensionality reduction  
- 🔄 **Dropout Layers** to avoid overfitting  
- 🧮 **Dense Layers** for classification  
- 🎯 **Sigmoid Output** for binary decision-making

Model performance: **~80% test accuracy** — and we’re still improving!

---

## 🗃️ Dataset Structure

wildfire_dataset/
├── train/
│ ├── Fire/
│ └── NoFire/
├── validation/
│ ├── Fire/
│ └── NoFire/
└── test/
├── Fire/
└── NoFire/

📌 *Total images*: 6,437  
📁 *Split*: Train, Validation, Test

---

## ⚙️ Getting Started

## 1. 🚀 Clone the Repo
## 2. Install Dependencies
pip install -r requirements.txt  
## 3. Download Dataset from Kaggle and unzip it into the wildfire_dataset/ folder.
## 🏋️‍♀️ Train the Model
python train.py  
After training, the model is saved as wildfire_cnn_model.keras and visualizations are generated.

## 🔍 Predict from Image
python predict.py --image path/to/image.jpg  
Output will be either 🔥 Detected: Fire or 🌲 Detected: No Fire.

## 📈 Visual Results
🚧 What’s Next?
Real-time video fire detection

Data augmentation for tougher scenarios

Streamlit web demo

Transfer learning with MobileNet or ResNet

## 📚 Tech Stack
Tool	Use
Python	Programming
TensorFlow	Deep Learning
OpenCV	Image Processing
Matplotlib	Visualization
Scikit-learn	Evaluation

## 🙏 Acknowledgments
Thanks to Kaggle for the dataset, and all the frontline workers preventing wildfires worldwide.

##📄 License
MIT License – feel free to use and contribute
##🔗 Connect
Built with 🔥 by Dev singh
📧 mahgalcoco@gmail.com
