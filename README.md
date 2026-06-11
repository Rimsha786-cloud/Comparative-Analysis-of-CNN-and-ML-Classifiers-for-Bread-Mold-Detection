# Comparative-Analysis-of-CNN-and-ML-Classifiers-for-Bread-Mold-Detection
This project focuses on detecting mold in bread images using Machine Learning and Deep Learning techniques. A comparative analysis was performed between Convolutional Neural Network (CNN), K-Nearest Neighbors (KNN), and Support Vector Machine (SVM) classifiers to determine the most effective approach for bread mold detection.
The system allows users to upload an image of bread through a web interface and receive a prediction indicating whether the bread is Fresh or Moldy.

🎯 Objectives
Detect mold in bread images automatically.
Compare the performance of CNN, KNN, and SVM classifiers.
Evaluate models using multiple performance metrics.

📂 Dataset
Dataset: Bread Mold Dataset
Source: https://github.com/NawanolT/Bread-Mold-Datasets
Classes: Fresh Bread, Moldy Bread
Approximate Size: ~3000 images
microscopic image from dataset sample:
<img width="505" height="505" alt="image" src="https://github.com/user-attachments/assets/37a313a6-0bd3-4f75-9c57-3effbce853fd" />

🛠️ Technologies Used
Python
TensorFlow / Keras
Scikit-learn
HTML, CSS, JavaScript
NumPy


🤖 Models Implemented
1. Convolutional Neural Network (CNN)
Built using MobileNetV2 transfer learning.
Automatically learns image features.
Best performing model in the project.

2. K-Nearest Neighbors (KNN)
Uses similarity-based classification.
Operates on flattened image features.

4. Support Vector Machine (SVM)
Margin-based classification algorithm.
Effective for binary classification tasks.



⚙️ Methodology
<img width="781" height="510" alt="Screenshot 2026-04-28 105644" src="https://github.com/user-attachments/assets/48ad91f2-9c71-4624-9890-4f233bdcff3a" />

Collect and organize dataset.
Perform image preprocessing:
Resizing
Normalization
Train CNN, KNN, and SVM models.
Evaluate model performance.
Deploy models .
<img width="1283" height="745" alt="Screenshot 2026-04-26 155111" src="https://github.com/user-attachments/assets/fe46e7da-42c7-4773-8ba7-ae1e963dff68" />





📊 Evaluation Metrics
The models were evaluated using:
Accuracy
<img width="1114" height="910" alt="Screenshot 2026-04-28 100547" src="https://github.com/user-attachments/assets/7ab7a7cd-d63a-4964-80d6-7eb70350227f" />

Precision
Recall
<img width="1136" height="850" alt="Screenshot 2026-04-28 100644" src="https://github.com/user-attachments/assets/3e15073b-08d3-47c3-82f2-ca6b2e9b3c7d" />

F1-Score
ROC Curve
<img width="1358" height="971" alt="Screenshot 2026-04-28 100701" src="https://github.com/user-attachments/assets/0f37b2ee-e038-47a7-afdc-e0190e84b82c" />

AUC Score

Key Results
ModelAccuracyCNN87.8%KNN83.6%SVM82.9%
Best AUC Score: 0.90 (CNN)

🚀 Running the Project
Clone Repository
git clone <repository-url>cd bread-mold-detection
Install Dependencies
pip install -r requirements.txt
Run Backend
cd backendpython app.py
Run Frontend
Open the frontend using Live Server or any local web server.

📈 Future Enhancements


Improve CNN accuracy with larger datasets.
Implement multi-class mold classification.
use hybrid models for mold classification.



👥 Team Members
Rimsha Wadiwala
Priyankka Dwarampudi
Team Member 2

📄 License
This project is developed for academic and research purposes.
