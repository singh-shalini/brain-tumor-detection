# 🧠 Brain Tumor Detection from MRI using Deep Learning

This project leverages Convolutional Neural Networks (CNNs) to automatically detect brain tumors from MRI scans. It aims to assist medical professionals by providing a reliable and efficient method for preliminary diagnosis.

## 📁 Project Overview

- **Problem**: Brain tumors are life-threatening conditions that require early detection for effective treatment. Manual diagnosis through MRI scans is time-consuming and prone to human error.
- **Solution**: A CNN-based classification model trained on labeled MRI images to identify the presence of brain tumors.
- **Model**: Built using TensorFlow and Keras; includes preprocessing, model training, and evaluation.

## 🛠️ Technologies Used

- Python 
- Jupyter Notebook 
- TensorFlow / Keras 
- NumPy & Matplotlib 
- OpenCV (for image processing)

## 📊 Dataset

- **Source**: [Brain Tumor MRI Dataset - Kaggle](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset)
- **Classes**: `Tumor`, `No Tumor`
- **Image Format**: `.jpg` MRI scans

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/brain-tumor-detection.git
   cd brain-tumor-detection ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the notebook:
   ```bash
   jupyter notebook Brain_Tumor_Detection_CNN.ipynb

   ```
## 📸 Screenshots

![image](https://github.com/user-attachments/assets/f88ab1ab-caec-4c66-b897-34a6ce540575)

![image](https://github.com/user-attachments/assets/b0dea9f6-6ad3-41d7-a3a5-cd0a0b2affb2)

![image](https://github.com/user-attachments/assets/f8cf80a0-3c58-4600-81fe-b9d8536d8674)

![image](https://github.com/user-attachments/assets/43e9cf50-847b-4aa5-b0cb-449224b8e68b)

![image](https://github.com/user-attachments/assets/260d7eac-d227-4a62-ae9d-92227143dc9d)


## 📈 Model Performance

1. Accuracy: ~95% on validation data
2. Optimizer: Adam
3. Loss Function: Binary Crossentropy

## 📌 Features

- Data preprocessing & augmentation
- CNN architecture from scratch
- Model evaluation using accuracy, loss graphs
- Simple, interpretable architecture suitable for deployment

## 📄 License

This project is licensed under the **MIT License**.  
You are free to use, modify, and distribute this software with proper attribution.

See the [LICENSE](LICENSE) file for full license details.
