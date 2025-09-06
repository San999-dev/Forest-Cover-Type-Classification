# 🌲 Forest Cover Type Classification

## 📌 Overview
This project predicts the **type of forest cover** using cartographic features such as elevation, slope, soil type, and wilderness area.  
It applies machine learning algorithms to classify forest regions into categories, helping in **environmental monitoring** and **resource management**.  

---

## 🗂️ Dataset
The dataset (Forest Cover Type from UCI/Kaggle) contains the following features:
- Elevation, Aspect, Slope  
- Horizontal & Vertical distances to hydrology  
- Horizontal distance to roadways & fire points  
- Soil type (categorical)  
- Wilderness area (categorical)  
- **Cover_Type** (target variable: 7 forest cover categories)

---

## ⚙️ Tech Stack
- Python 🐍  
- Pandas & NumPy (data processing)  
- Matplotlib & Seaborn (visualization)  
- Scikit-learn (modeling & evaluation)  

---

## 🚀 Workflow
1. Load and explore dataset  
2. Handle missing values & preprocess categorical features  
3. Split dataset into training and testing sets  
4. Scale numerical features  
5. Train classification models (Random Forest, Decision Tree, Logistic Regression)  
6. Evaluate performance using **Accuracy**, **Classification Report**, and **Confusion Matrix**  

---

## 📊 Results
- The model achieved good accuracy in predicting forest cover types.  
- Feature importance showed **Elevation**, **Soil Type**, and **Wilderness Area** as strong predictors.  

---

## ▶️ How to Run
1. Clone the repo:
   ```bash
   git clone https://github.com/San999-dev/forest-cover-classification.git
   cd forest-cover-classification
   Install dependencies:

pip install -r requirements.txt


Run the Jupyter Notebook:

jupyter notebook forest_cover_classification.ipynb

📈 Example Prediction

# Example input (Elevation, Aspect, Slope, Horizontal_Distance_To_Hydrology)

sample = np.array([[3000, 45, 10, 100]])

sample_scaled = scaler.transform(sample)


prediction = model.predict(sample_scaled)

print("Predicted Cover Type:", prediction[0])

📄 License

This project is licensed under the MIT License.

🙌 Acknowledgements

UCI Machine Learning Repository – Forest Cover Type Dataset

Kaggle contributors and open-source community
  
