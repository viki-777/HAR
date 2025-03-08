# Human Activity Recognition (HAR) Using Accelerometer Data

## 📌 Overview
This project focuses on **Human Activity Recognition (HAR)** using data collected from accelerometer sensors. The goal is to classify human activities such as walking, jogging, sitting, standing, and more based on time-series accelerometer data.

## 📂 Dataset
We use the **WISDM (Wireless Sensor Data Mining) dataset**, which contains accelerometer readings collected from smartphones placed in users' pockets. The dataset includes the following features:
- **User ID**
- **Activity label** (e.g., Walking, Jogging, Sitting, etc.)
- **Accelerometer readings (X, Y, Z)**

### 🔹 Preprocessing Steps
1. **Data Cleaning**: Handling missing values and formatting the dataset.
2. **Feature Extraction**: Windowing the time-series data into frames.
3. **Normalization**: Scaling accelerometer values for better model performance.

## 🏗 Model Architecture
We use a **Deep Learning model** based on **Convolutional Neural Networks (CNNs)** to improve activity classification accuracy.

### 🔹 Model Features:
- **Input:** Processed accelerometer data (frames)
- **Layers:**
  - **2D Convolutional layers** for feature extraction
  - **Batch normalization** for stable learning
  - **Max pooling** to reduce dimensionality
  - **Fully connected layers** for classification
- **Output:** Predicted activity label

## 🛠 Implementation
### 🔹 Dependencies
Ensure you have the required libraries installed:
```bash
pip install numpy pandas tensorflow scikit-learn scipy
```

### 🔹 Run the Project
1. **Preprocess the dataset:**
   ```python
   python preprocess.py
   ```
2. **Train the model:**
   ```python
   python train.py
   ```
3. **Evaluate the model:**
   ```python
   python evaluate.py
   ```
4. **Make predictions on new data:**
   ```python
   python predict.py
   ```

## 📊 Performance Metrics
- **Accuracy**: ~93% on test data


## 📌 Future Improvements
- Experimenting with **LSTMs/GRUs** for sequence modeling
- Incorporating **sensor fusion** (e.g., gyroscope data)
- Deploying the model on **mobile devices** for real-time HAR

## 🤝 Contributors
- **Vikash Kumar** (Your Email)
-**Gontu Sandeep Kumar** (Your Email)
-**Prabhat Kumar** (Your Email)
-**Ajay Kumar Meena**
- Open to contributions! Feel free to create a pull request.



