# Driver Drowsiness Detection System  

## 📝 Overview  
The Driver Drowsiness Detection System is designed to enhance road safety by monitoring the driver's eye and mouth movements to detect signs of drowsiness. The system alerts the driver with an alarm sound 🔔 when drowsiness is detected and logs the incident in a MySQL database 💾. Additionally, the **Eye Aspect Ratio (EAR)** and **Mouth Aspect Ratio (MAR)** values are plotted 📊 to visualize the driver's alertness levels over time.

---

## Features  
- **CNN Model**:  
  A Convolutional Neural Network (CNN) model has been developed for feature extraction from the driver's face, focusing on the eyes and mouth regions.

- **Facial Landmarks**:  
  The system utilizes the `dlib` library for computer vision applications and Haar-cascade files for detecting facial landmarks.

- **Database**:  
  A SQL database 💾 is used to store the timestamps of alarms triggered when drowsiness is detected.

- **Data Visualization**:  
  EAR (Eye Aspect Ratio) and MAR (Mouth Aspect Ratio) values are plotted 📊 to provide a visual representation of the driver's drowsiness levels.

- **Alarm Sound**:  
  When a certain threshold for EAR or MAR is met, an alarm sound 🔔 is triggered to alert the driver.

---

## Dataset  
The dataset used for training and testing the system can be found at the following link:  
🔗 [Yawn & Eye Dataset - Kaggle](https://www.kaggle.com/serenaraju/yawn-eye-dataset-new)

---

## How It Works  

1. **Feature Extraction**:  
   The CNN model extracts features from the driver's face, specifically focusing on the eyes️ and mouth.

2. **Facial Landmark Detection**:  
   The `dlib` library and Haar-cascade files are used to detect facial landmarks.

3. **EAR and MAR Calculation**:  
   The system calculates the Eye Aspect Ratio (EAR) and Mouth Aspect Ratio (MAR) 📐 to determine drowsiness.

4. **Drowsiness Detection**:  
   If the EAR falls below a certain threshold or the MAR exceeds a certain threshold, an alarm sound 🔔 is triggered.

5. **Database Logging**:  
   The timestamps of drowsiness events are stored in a MySQL database 💾.

6. **Data Visualization**:  
   The EAR and MAR values are plotted 📊 to analyze the driver's drowsiness levels.
