# 🌿 Hybrid Deep Learning for Plant Disease Diagnosis

## 📌 Overview
This project presents a hybrid deep learning approach for automated plant disease diagnosis using Convolutional Neural Networks (CNNs) and XGBoost.

The system is designed for real-world agricultural applications, focusing on accurate and efficient detection of diseases in Indian ridge gourd leaves. It integrates deep feature extraction with machine learning classification to improve performance over traditional CNN models.

---

## 🧠 Research Contribution
- First-author research work titled:  
  **“A Hybrid Deep Learning Approach for Automated Plant Disease Diagnosis in Indian Ridge Gourd”**
- Presented at:  
  **7th International Conference on Machine Learning, Image Processing, Network Security and Data Sciences (MIND-2025), MNIT Jaipur**
- Currently under publication  

> 📌 Note: Full paper is not included due to publication restrictions.

---

## 📊 Dataset
- Custom dataset of Indian ridge gourd leaves **developed and published by us**
- Real-world images collected from agricultural fields  
- Augmented dataset for improved generalization  

### Classes:
- Healthy  
- Leaf Minor Infestation  
- Mosaic Virus  

🔗 Dataset Link:  
https://ieee-dataport.org/documents/preprocessed-indian-ridge-gourd-leaf-image-dataset-healthy-and-diseased-leaf-minor

---

## ⚙️ Methodology
1. Data collection from real farm environments  
2. Image preprocessing and augmentation  
3. Feature extraction using CNN architectures  
4. Classification using XGBoost  
5. Performance evaluation using accuracy, precision, recall, and F1-score  

---

## 🤖 Models Implemented
- Normal CNN  
- Custom CNN  
- MobileNet  
- MobileNetV2 (Softmax)  
- CNN + SVM  
- ⭐ Hybrid CNN (DenseNet121) + XGBoost (Proposed Model)  

---

## 🚀 Key Results
- Hybrid CNN + XGBoost achieved **~92% accuracy**  
- Outperformed baseline CNN and transfer learning models  
- Demonstrated strong generalization on real-world data  

---

## 📁 Project Structure
```
models/
 ├── hybrid_cnn_xgboost.py
 ├── custom_cnn.py
 ├── mobilenet.py
 ├── mobilenetv2_softmax.py
 ├── normal_cnn.py
 └── cnn_svm.py
```

---

## 🌍 Applications
- Smart agriculture systems  
- Early plant disease detection  
- Farmer assistance tools  
- Crop monitoring and yield optimization  

---

## 🔮 Future Work
- Extend dataset to more crops and diseases  
- Deploy model on mobile devices (TensorFlow Lite)  
- Integrate IoT-based real-time monitoring  
- Develop real-time video-based disease detection  

---

## 👨‍💻 Author
**Pranay Agarwal**  
First Author & Corresponding Author  
Machine Learning | Deep Learning | Computer Vision  

---

## ⭐ Support
If you found this project useful, consider giving it a ⭐ on GitHub!
