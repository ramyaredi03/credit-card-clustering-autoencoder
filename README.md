# 💳 Credit Card Customer Segmentation using K-Means & Autoencoders

This project performs **customer segmentation** on credit card transaction data using both traditional machine learning (**K-Means clustering**) and deep learning (**Autoencoders**).  
The goal is to identify different customer groups based on their spending behavior, payment patterns, and credit usage.

This type of segmentation is widely used in:
- Marketing
- Risk management
- Customer retention
- Targeted promotions

---

## 📊 Dataset

**Source:** Kaggle – Credit Card Dataset  
https://www.kaggle.com/arjunbhasin2013/ccdata

The dataset contains ~9,000 credit card customers and 17 behavioral features including:
- Credit limit
- Purchases
- Cash advances
- Payments
- Balance
- Tenure
- Minimum payments
- Full payment ratio

---

## 🧠 Project Workflow

The notebook follows a professional data science pipeline:

### 1️⃣ Business Understanding
Understanding why customer segmentation matters for:
- Targeted marketing
- Risk control
- Customer lifetime value optimization

---

### 2️⃣ Data Preprocessing
- Handling missing values
- Feature scaling using **StandardScaler**
- Normalizing numerical values

---

### 3️⃣ Exploratory Data Analysis (EDA)
Visualizations created to understand:
- Distributions of spending
- Payment behavior
- Credit usage patterns

---

### 4️⃣ K-Means Clustering
Customers are grouped into clusters based on similarity.

Steps:
- Apply K-Means
- Use the **Elbow Method** to find the optimal number of clusters
- Assign each customer a cluster label

This reveals groups such as:
- High-spending customers
- Low-balance low-usage customers
- Heavy cash-advance users

---

### 5️⃣ PCA (Principal Component Analysis)
Used to reduce 17 dimensions into 2–3 dimensions for visualization.

This allows:
- Plotting customer clusters in 2D/3D
- Seeing how well clusters are separated

---

### 6️⃣ Autoencoder (Deep Learning)
A neural network is used to:
- Compress 17 features into a low-dimensional representation
- Learn hidden customer behavior patterns
- Perform **non-linear dimensionality reduction**

Architecture:
- Encoder → compresses data
- Bottleneck → 10 features
- Decoder → reconstructs original data

The compressed features are then used for clustering.

---

### 7️⃣ Comparison
Clusters from:
- K-Means
- PCA
- Autoencoder

are compared to see which method gives the best separation of customers.

---

## 🛠️ Technologies Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- TensorFlow / Keras
- Google Colab

---

## 📁 Files in Repository

| File | Description |
|------|------------|
| `credit-card-clustering-autoencoder.ipynb` | Main project notebook |
| `Marketing_data.csv` | Credit card customer dataset |
| `.gitignore` | Git configuration |
| `README.md` | Project documentation |

---

## 🎯 Key Learning Outcomes

- Customer segmentation using machine learning
- Choosing K using the Elbow method
- Visualizing clusters with PCA
- Using deep learning (Autoencoders) for feature extraction
- Comparing classical ML vs neural networks

---

## 🚀 Use Cases

This model can be used by banks to:
- Identify premium vs risky customers
- Design targeted credit card offers
- Improve fraud and default risk models
- Increase customer lifetime value

---

## 👤 Author

**Ramyasri Chapala**  

