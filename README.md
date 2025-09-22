# TourismRecommender-CNN


# 🏛️ Preserving Heritage: Enhancing Tourism with AI  

## 📌 Project Overview  
This capstone project combines **computer vision** and **recommendation systems** to enhance cultural heritage preservation and improve the tourism experience.  

- **Part 1:** Classified historical structures using **CNNs with transfer learning** to support heritage monitoring.  
- **Part 2:** Built a **collaborative filtering recommendation system** to suggest tourist attractions based on user demographics and ratings.  

---

## 🧠 Part 1: Image Classification of Historical Structures  

### Objective  
Develop a **TensorFlow/Keras CNN model** to categorize historical structures from images.  

### Workflow  
- **Data Preparation:** Unpacked and organized structure datasets.  
- **Visualization:** Used **OpenCV** to display sample images per class.  
- **Modeling:**  
  - Implemented **MobileNetV2** with transfer learning.  
  - Frozen convolutional layers, added dense layers + dropout for regularization.  
- **Training:**  
  - Configured callbacks with **EarlyStopping**.  
  - Trained models with and without data augmentation.  
- **Evaluation:** Visualized accuracy/loss curves, checked for overfitting.  

### Tech Stack  
`TensorFlow`, `Keras`, `OpenCV`, `NumPy`, `Matplotlib`, `Seaborn`  

---

## 🗺️ Part 2: Tourism Recommendation Engine  

### Objective  
Develop a **collaborative filtering recommender system** to personalize tourist attraction suggestions.  

### Workflow  
- **Data Cleaning:**  
  - Removed duplicate/missing values.  
  - Dropped irrelevant columns (empty, redundant, or high missing %).  
- **EDA:**  
  - Explored user demographics (age distribution, source of tourists).  
  - Analyzed categories of tourist spots and city-level insights.  
- **Modeling:**  
  - Implemented **cosine similarity** and **Truncated SVD** for collaborative filtering.  
  - Recommended places based on user similarity and past ratings.  

### Tech Stack  
`Pandas`, `NumPy`, `Scikit-learn`, `Matplotlib`, `Seaborn`  

---

## 🚀 Results  
- **CNN classifier** achieved strong validation accuracy in categorizing historical structures.  
- **Tourism recommender system** successfully provided personalized attraction suggestions tailored to user interests and demographics.  

---

## 🔑 Skills Highlighted  
- Deep Learning (CNNs, Transfer Learning, MobileNetV2)  
- Computer Vision (Image Classification, OpenCV)  
- Recommendation Systems (Collaborative Filtering with Cosine Similarity & SVD)  
- Data Cleaning & EDA (Pandas, NumPy, Visualization)  
- Model Training, Hyperparameter Tuning, and Evaluation  

---


## ✨ Future Improvements  
- Experiment with **ResNet, Inception, EfficientNet** for higher classification accuracy.  
- Extend recommender to **hybrid (content + collaborative filtering)** approach.  
- Deploy both models as a **web app (Flask/Streamlit)** for real-time use.  
