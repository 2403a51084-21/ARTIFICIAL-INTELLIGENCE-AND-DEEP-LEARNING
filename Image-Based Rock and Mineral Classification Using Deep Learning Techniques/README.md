# 🪨 Image-Based Rock and Mineral Classification Using Deep Learning Techniques

## 📌 Project Overview

This project focuses on classifying rock images into their respective categories using Deep Learning techniques. The objective is to explore and compare different neural network architectures for image-based rock classification.

Three deep learning models are implemented:
- Convolutional Neural Network (CNN)
- Artificial Neural Network (ANN)
- Recurrent Neural Network (RNN) using LSTM

The models are trained and evaluated using a rock image dataset. Their performance is compared using various classification metrics and visualizations.

---

## 🎯 Objectives

- Classify rock images into different categories using deep learning.
- Preprocess image data for neural network training.
- Implement and train CNN, ANN, and RNN (LSTM) models.
- Evaluate the performance of each model.
- Compare the models using classification metrics and visualizations.

---

## 📂 Dataset

The project uses a rock classification image dataset obtained from Kaggle.

**Dataset source:** [Rock Classification Dataset – Kaggle](https://www.kaggle.com/datasets/salmaneunus/rock-classification)

The dataset contains images belonging to different rock categories, organized according to class labels.

### Data Preprocessing
- Images are resized to **64 × 64 pixels**.
- Pixel values are normalized to the range of **0 to 1**.
- The dataset is divided into:
  - **70% Training**
  - **15% Validation**
  - **15% Testing**
- Stratified splitting is used to maintain class proportions across the subsets.

---

## 🧠 Deep Learning Models

### 1. Convolutional Neural Network (CNN)
CNN is used to learn spatial features from images through convolutional and pooling layers. It is suitable for image classification tasks involving patterns, textures, and visual features.

### 2. Artificial Neural Network (ANN)
ANN processes flattened image data using fully connected neural network layers to learn patterns and classify images.

### 3. Recurrent Neural Network (RNN – LSTM)
The image is represented as a sequence of rows and processed using an LSTM-based recurrent neural network.

For a 64 × 64 RGB image:
- Number of time steps: 64
- Features per time step: 192

The LSTM processes the sequence to learn relationships across image rows.

---

## ⚙️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming language |
| Google Colab | Development and execution environment |
| TensorFlow / Keras | Deep learning model development |
| NumPy | Numerical computations |
| Matplotlib | Data visualization |
| Scikit-learn | Dataset splitting and evaluation metrics |
| Kaggle | Dataset source |

---

## 🔬 Methodology

1. Dataset acquisition
2. Image loading and preprocessing
3. Image resizing to 64 × 64
4. Pixel normalization
5. Stratified dataset splitting
6. CNN model training
7. ANN model training
8. RNN-LSTM model training
9. Model evaluation
10. Performance comparison and visualization

---

## 📊 Model Evaluation

The models are evaluated using the following metrics:

- **Accuracy** – Measures the proportion of correctly classified samples.
- **Precision** – Measures the correctness of positive predictions.
- **Recall** – Measures how effectively actual class instances are identified.
- **F1-Score** – Combines precision and recall.
- **Confusion Matrix** – Visualizes actual versus predicted classifications.
- **ROC Curve** – Evaluates classification performance across different thresholds.
- **AUC (Area Under the Curve)** – Summarizes ROC curve performance.

Weighted precision, recall, and F1-score are used for multiclass evaluation.

---

## 📈 Visualization

The project includes visualizations such as:

- Training and validation accuracy curves
- Training and validation loss curves
- Model performance comparison
- Confusion matrices
- ROC curves
- AUC comparison

These visualizations help analyze the learning behavior and performance of the models.

---

## 🛠️ Training Configuration

| Parameter | Value |
|---|---|
| Image Size | 64 × 64 |
| Batch Size | 32 |
| Maximum Epochs | 10 |
| Optimizer | Adam |
| Loss Function | Sparse Categorical Crossentropy |
| Dataset Split | 70% / 15% / 15% |
| Early Stopping | Patience = 3 |

---

## 🚀 How to Run the Project

1. Clone or download this repository.
2. Open the project notebook in Google Colab.
3. Ensure the required libraries are installed.
4. Download and load the dataset.
5. Execute the notebook cells in order.
6. Train the CNN, ANN, and RNN-LSTM models.
7. Review the evaluation metrics and visualizations.

---

## 📁 Project Structure

```text
Image-Based Rock and Mineral Classification Using Deep Learning Techniques/
│
├── Dataset/
│   └── Rock image categories/
│
├── AIDL_PROJECT_CODE.ipynb
├── AIDL_PROJECT.ipynb - Colab.pdf
├── 2403A51084_Project_Documentation.docx
├── Image-Based Rock and Mineral Classification Using Deep Learning Techniques.pptx
└── README.md
```

---

## 🔮 Future Scope

- Improve classification performance using transfer learning.
- Experiment with pretrained models such as ResNet and MobileNet.
- Expand the dataset with more rock and mineral samples.
- Apply data augmentation techniques.
- Develop a web-based or mobile-based rock classification application.
- Integrate real-time image classification.
- Evaluate the model using field-collected rock images.

---

## ⚠️ Limitations

- Performance depends on the quality and diversity of the dataset.
- Classification is limited to the classes represented in the dataset.
- Images from different lighting conditions, backgrounds, or environments may affect predictions.
- The model provides image-based predictions and does not replace professional geological analysis.

---

## 👩‍💻 Project Details

**Project Title:** Image-Based Rock and Mineral Classification Using Deep Learning Techniques  
**Student ID:** 2403A51084  
**Department:** Computer Science & Artificial Intelligence  
**Project Guide:** Dr. Anurodh Kumar

---

## 📚 References

- Kaggle – Rock Classification Dataset
- TensorFlow Documentation
- Keras Documentation
- Scikit-learn Documentation

---

*This project was developed as part of an Artificial Intelligence and Deep Learning (AIDL) academic project.*
