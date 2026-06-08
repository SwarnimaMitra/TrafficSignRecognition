# Traffic Sign Recognition using CNN

## 🚦 Project Overview

Traffic Sign Recognition is a Deep Learning project that automatically identifies and classifies traffic signs from road images. This technology is an essential component of autonomous vehicles and Advanced Driver Assistance Systems (ADAS), helping vehicles understand road regulations and improve driving safety.

This project uses a Convolutional Neural Network (CNN) trained on the German Traffic Sign Recognition Benchmark (GTSRB) dataset to classify traffic signs into multiple categories with high accuracy.

---

## 🎯 Objectives

* Detect and classify traffic signs from images.
* Improve road safety through automated sign recognition.
* Assist autonomous vehicles in understanding traffic rules.
* Build a robust image classification model using Deep Learning.

---

## 🛠️ Technologies Used

* Python
* TensorFlow / Keras
* Convolutional Neural Networks (CNN)
* NumPy
* Pandas
* Matplotlib
* OpenCV
* Scikit-learn

---

## 📂 Dataset

**German Traffic Sign Recognition Benchmark (GTSRB)**

The dataset contains thousands of images belonging to 43 different traffic sign classes, including:

* Speed Limit Signs
* Stop Signs
* Yield Signs
* No Entry Signs
* Priority Road Signs
* Traffic Direction Signs

Dataset Link:
https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign

---

## 📊 Project Workflow

### 1. Data Collection

* Download the GTSRB dataset.
* Organize images according to class labels.

### 2. Data Preprocessing

* Resize images to a fixed dimension.
* Normalize pixel values.
* Convert images into arrays.
* Split dataset into training and testing sets.

### 3. Model Building

* Create a CNN architecture consisting of:

  * Convolution Layers
  * ReLU Activation
  * Max Pooling Layers
  * Dropout Layers
  * Fully Connected Dense Layers
  * Softmax Output Layer

### 4. Model Training

* Train the CNN on traffic sign images.
* Monitor training and validation accuracy.

### 5. Model Evaluation

* Evaluate performance on test data.
* Generate classification metrics and accuracy scores.

### 6. Prediction

* Input a traffic sign image.
* Predict the corresponding traffic sign category.

---

## 🧠 CNN Architecture

Input Image

↓
Convolution Layer + ReLU

↓
Max Pooling

↓
Convolution Layer + ReLU

↓
Max Pooling

↓
Flatten Layer

↓
Dense Layer

↓
Dropout Layer

↓
Output Layer (43 Classes)

---

## 📈 Expected Results

* High classification accuracy on unseen traffic sign images.
* Reliable recognition of traffic signs under different conditions.
* Improved decision-making capability for autonomous driving systems.

---

## 📁 Project Structure

```text
Traffic-Sign-Recognition/
│
├── dataset/
├── models/
├── notebooks/
├── images/
├── train.py
├── predict.py
├── requirements.txt
├── traffic_sign_model.h5
└── README.md
```

## ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Traffic-Sign-Recognition.git
cd Traffic-Sign-Recognition
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## 🚀 Run the Project

Train the model:

```bash
python train.py
```

Make predictions:

```bash
python predict.py
```

## 📊 Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

---

## 🔮 Future Enhancements

* Real-time traffic sign detection using webcam.
* Integration with autonomous vehicle systems.
* Support for multiple international traffic sign datasets.
* Deployment as a web application using Flask or Streamlit.

---

## 🤝 Contributing

Contributions are welcome. Feel free to fork the repository and submit pull requests for improvements.

---

## 📜 License

This project is intended for educational and research purposes.

---

## 👩‍💻 Author

Swarnima Mitra

Machine Learning & AI Enthusiast
