## Mall Customer Segmentation using K-Means Clustering

# Project Overview

This project performs **Customer Segmentation** using the **K-Means Clustering Algorithm**.  

The goal of this project is to group mall customers into different segments based on their:

- 👤 Age  
- 💰 Annual Income (k$)  
- 🎯 Spending Score (1–100)  
Customer segmentation helps businesses understand different types of customers and apply targeted marketing strategies.

The project includes:
- Data Preprocessing  
- Feature Scaling using StandardScaler  
- Elbow Method for optimal cluster selection  
- K-Means Clustering model training  
- Model saving using Joblib  
- Interactive Streamlit Web Application  

## 📊 Dataset Information

Dataset used: **Mall_Customers.csv**
Features used for clustering:
- Age  
- Annual Income (k$)  
- Spending Score (1-100)  
Target:  
- Cluster label generated using K-Means

## 🧠 Machine Learning Algorithm

# K-Means Clustering (Unsupervised Learning)
K-Means is used to:
- Divide customers into K groups
- Minimize Within-Cluster Sum of Squares (WCSS)
- Identify patterns in customer behavior

# Elbow Method

The Elbow Method is used to determine the optimal number of clusters by plotting:
- Number of Clusters (K)
- WCSS (Within Cluster Sum of Squares)
The optimal K is selected where the graph forms an "elbow".

# Technologies Used
- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Streamlit
- Plotly
- Joblib

## 📂 Project Structure

# 🛍️ Mall Customer Segmentation using K-Means Clustering

## 📌 Project Overview

This project performs **Customer Segmentation** using the **K-Means Clustering Algorithm**.  

The goal of this project is to group mall customers into different segments based on their:

- 👤 Age  
- 💰 Annual Income (k$)  
- 🎯 Spending Score (1–100)  

Customer segmentation helps businesses understand different types of customers and apply targeted marketing strategies.

The project includes:

- Data Preprocessing  
- Feature Scaling using StandardScaler  
- Elbow Method for optimal cluster selection  
- K-Means Clustering model training  
- Model saving using Joblib  
- Interactive Streamlit Web Application  

---

## 📊 Dataset Information

Dataset used: **Mall_Customers.csv**

Features used for clustering:

- Age  
- Annual Income (k$)  
- Spending Score (1-100)  

Target:  
- Cluster label generated using K-Means

---

## 🧠 Machine Learning Algorithm

### 🔹 K-Means Clustering (Unsupervised Learning)

K-Means is used to:

- Divide customers into K groups
- Minimize Within-Cluster Sum of Squares (WCSS)
- Identify patterns in customer behavior

### 🔹 Elbow Method

The Elbow Method is used to determine the optimal number of clusters by plotting:

- Number of Clusters (K)
- WCSS (Within Cluster Sum of Squares)

The optimal K is selected where the graph forms an "elbow".

---

## ⚙️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Streamlit
- Plotly
- Joblib

---

## 📂 Project Structure


Mall-Customer-Clustering/
│
├── clustered_mall.ipynb # Model training & Elbow method
├── app.py # Streamlit Web Application
├── Mall_Customers.csv # Original Dataset
├── clusters_data.csv # Dataset with cluster labels
├── Kmeans_model.pkl # Trained KMeans Model
├── requirements.txt # Required libraries
├── readme.md # Project documentation


## 🚀 How to Run the Project

# 1️⃣ Clone the Repository

git clone https://github.com/ChitthaluriChandu/kmean.git


# 2️⃣ Install Dependencies

pip install -r requirements.txt


# 3️⃣ Run the Streamlit Application

streamlit run app.py

## 🖥️ Application Features

✔ Interactive sliders for Age, Income, and Spending Score  
✔ Predict customer cluster instantly  
✔ 3D Cluster visualization  
✔ Cluster distribution pie chart  
✔ Business recommendations for each cluster  
✔ Clean and responsive UI  

## 📈 Business Use Case

Customer segmentation helps businesses:
- Identify High Value Customers  
- Target Potential Customers  
- Design Loyalty Programs  
- Improve Marketing Campaigns  
- Increase Profitability  

## 🎯 Cluster Categories

Example customer segments identified:
- High Value Customers  
- Potential Target Customers  
- Average Customers  
- Loyal Customers  
- Budget Conscious Customers  
Each cluster represents a different purchasing behavior pattern.

## 📌 Model Saving

The trained KMeans model is saved using:
joblib.dump(model, "Kmeans_model.pkl")

It is later loaded in the Streamlit app for prediction.

## 🧪 Future Improvements

- Add Random Forest for classification comparison  
- Deploy on Streamlit Cloud  
- Add real-time database integration  
- Improve visualization dashboard  

## 👩‍💻 Author

**CHITTHALURI CHANDU**  
B.Tech Student  
Machine Learning & Web Development Enthusiast