# TourismRecommender-CNN


# 🏛️ Preserving Heritage: Enhancing Tourism with AI  

## 📌 Project Overview  
This project combines **computer vision** and **recommendation systems** to solve real-world challenges in tourism and cultural heritage.  

- **Part 1:** Classify images of historical structures using **CNNs with transfer learning** to monitor heritage sites and assist preservation.  
- **Part 2:** Build a **tourism recommendation engine** that personalizes attraction suggestions for users based on demographics, preferences, and ratings.  

---

## 🧠 Part 1: Image Classification of Historical Structures  

### Objective  
Develop a **TensorFlow/Keras CNN model** to categorize historical structures from images.  

### Workflow  
- **Data Preparation:** Loaded training & test datasets (`Structures_dataset.zip`, `dataset_test`).  
- **Exploratory Data Analysis:** Visualized samples with **OpenCV**.  
- **Modeling:**  
  - Transfer learning with pre-trained CNN backbones.  
  - Added dense layers + dropout for regularization.  
  - Hyperparameter tuning (optimizer, loss function, callbacks).  
- **Training:**  
  - With and without data augmentation.  
  - Early stopping to prevent overfitting.  
- **Evaluation:** Monitored validation accuracy; visualized learning curves.  

### Tech Stack  
`TensorFlow`, `Keras`, `OpenCV`, `NumPy`, `Matplotlib`, `Seaborn`  

---

## 🗺️ Part 2: Tourism Recommendation Engine  

### Objective  
Develop a **collaborative filtering recommender system** using user ratings and attraction metadata.  

### Workflow  
- **Datasets:**  
  - `user.csv` → user demographics  
  - `tourism_with_id.csv` → attraction details (category, city, price, rating)  
  - `tourism_rating.csv` → user ratings  
- **EDA:**  
  - Cleaned and merged datasets.  
  - Analyzed demographics, top-rated attractions, and category insights.  
- **Modeling:**  
  - Built collaborative filtering model to recommend places.  
  - Generated recommendations based on user history and similar tourists.  

### Tech Stack  
`Pandas`, `NumPy`, `Scikit-learn`, `Matplotlib`, `Seaborn`  

---

## 🚀 Results  
- **CNN classifier** that categorizes heritage structures with strong accuracy.  
- **Tourism recommender system** that personalizes attraction suggestions, helping enhance visitor experience.  

---

## 🔑 Skills Highlighted  
- Deep Learning (CNNs, Transfer Learning)  
- Computer Vision (Image Classification, OpenCV)  
- Recommendation Systems (Collaborative Filtering)  
- Data Cleaning & EDA (Pandas, NumPy, Visualization)  
- Model Training, Tuning, and Evaluation  

---

---

## ✨ Future Improvements  
- Experiment with **ResNet, Inception, EfficientNet** for higher classification accuracy.  
- Extend recommender to **hybrid (content + collaborative filtering)** approach.  
- Deploy both models as a **web app (Flask/Streamlit)** for real-time use.  
