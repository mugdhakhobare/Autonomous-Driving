# 🚗 Autonomous Driving & Tesla Autopilot Safety Analysis (AIML Capstone)

## 📌 Project Overview

This project explores two key aspects of autonomous driving:

1. **Vehicle Detection using Deep Learning (CNN)**
2. **Tesla Autopilot Safety Data Analysis**

The objective is to apply Artificial Intelligence techniques to detect vehicles in images and analyze real-world Tesla autopilot accident data to identify patterns and insights.

---

## 🧠 Part 1 – Vehicle Detection using Deep Learning

### 🎯 Objective

Build a Convolutional Neural Network (CNN) model to detect vehicles from image data.

### 📂 Dataset

* Image dataset in `.jpg` and `.png` format
* All images labeled under a single class: **vehicle**
* Images resized to **128 × 128**

### ⚙️ Steps Performed

* Imported required libraries
* Loaded images from dataset folder
* Resized images to fixed dimension
* Normalized pixel values
* Assigned labels
* Split dataset into train and test
* Built CNN model
* Trained model
* Evaluated performance
* Predicted vehicle from sample image

### 🏗️ Model Architecture

* Conv2D (32 filters)
* MaxPooling
* Conv2D (64 filters)
* MaxPooling
* Conv2D (128 filters)
* Flatten
* Dense Layer
* Dropout
* Output Layer (Softmax)

### ✅ Result

The CNN model successfully detects vehicles from input images with good training accuracy.

---

## 📊 Part 2 – Tesla Autopilot Safety Analysis

### 🎯 Objective

Analyze Tesla autopilot accident dataset and extract meaningful insights.

### 📂 Dataset Features

* Year
* Country
* State
* Deaths
* Tesla Driver
* Tesla Occupant
* Other Vehicle
* Cyclists / Pedestrians
* Tesla Model
* Autopilot Claimed

### 🧹 Data Preprocessing

* Loaded dataset using Pandas
* Cleaned column names
* Removed duplicates
* Handled missing values
* Converted numeric columns

### 📈 Exploratory Data Analysis

* Events by Year
* Events by Country
* Events by State
* Death distribution
* Autopilot claimed analysis
* Tesla model involvement
* Cyclist and pedestrian cases
* Correlation analysis

### 🔍 Key Insights

* Accident cases increased in recent years
* Some Tesla models involved more frequently
* Autopilot claimed in several incidents
* Multiple accidents involved other vehicles
* Death distribution varies by location

---

## 🛠️ Technologies Used

* Python
* Jupyter Notebook
* TensorFlow / Keras
* OpenCV
* NumPy
* Pandas
* Matplotlib
* Seaborn

---

## 📸 Project Screenshots

### Part 1

* Model Training Accuracy
* Sample Prediction Output
* CNN Model Architecture

### Part 2

* Events by Year Graph
* Autopilot Distribution Pie Chart
* Tesla Model Involvement Graph

---

## 🚀 How to Run

1. Clone the repository
2. Install dependencies

```
pip install numpy pandas matplotlib seaborn tensorflow opencv-python
```

3. Open Jupyter Notebook
4. Run:

   * `Vehicle Detection.ipynb`
   * Tesla Analysis Notebook

---

## 📌 Future Improvements

* Multi-class vehicle detection (car, bus, truck)
* Real-time vehicle detection
* YOLO object detection
* Deployment using Streamlit
* Predictive accident modeling

---

## 👩‍💻 Author

**Mugdha Khobare**
AIML Capstone Project

---


