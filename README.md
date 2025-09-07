# 📚 Book Recommender System using Machine Learning  

![Python](https://img.shields.io/badge/Python-3.7.10-blue?style=flat&logo=python)
![Streamlit](https://img.shields.io/badge/Streamlit-App-FF4B4B?style=flat&logo=streamlit)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML-F7931E?style=flat&logo=scikit-learn)

---

## 📌 Project Overview  

Recommendation systems are an essential part of today’s digital ecosystem where users face **information overload** but limited time.  
This project implements a **Book Recommender System** using **Collaborative Filtering (Nearest Neighbors)** and provides recommendations via an **interactive Streamlit web app**.  

The system helps users discover new books based on **ratings and user-item interactions**, making reading suggestions more personalized and efficient.  

---

## 🎯 Objectives  

- 📖 Build a **recommendation engine** tailored to book preferences.  
- 🤝 Use **Collaborative Filtering** to recommend books based on user-item similarity.  
- 🌐 Deploy as a **Streamlit web application** for real-time interactive use.  
- 🔧 Provide a system that can easily be extended to other domains (movies, products, music).  

---

## 🧠 Types of Recommendation Systems  

1️⃣ **Content-Based Filtering**  
- Uses item attributes (e.g., author, genre).  
- Example: YouTube or Spotify.  
- ❌ Limitation: Over-specialization → always recommends similar items.  

2️⃣ **Collaborative Filtering (Used in this Project)**  
- Based on **user-item interactions** (ratings, feedback).  
- Finds **clusters of similar users/books**.  
- Example: Book recommendation using user ratings.  
- ❌ Limitation: Computationally expensive, biased towards popular items.  

3️⃣ **Hybrid Filtering**  
- Combines content + collaborative filtering.  
- More robust and widely used in modern systems.  

---

## 📂 About This Project  

- ✅ Streamlit **web application** to recommend books.  
- ✅ Built with **Collaborative Filtering** using **Nearest Neighbors algorithm**.  
- ✅ Dataset-driven → recommends **similar books** based on user’s selection.  
- ✅ Simple, interactive, and extendable system.  

---

## 📊 Dataset  

- Dataset contains information about **books, users, and ratings**.  
- Features include: book titles, authors, ratings, and user feedback.  
- [🔗 Dataset Link](#) *(Add link here)*  

---

## 🔧 Core Algorithm – Nearest Neighbors (KNN)  

Steps for building the model:  

1. 📥 Load the dataset  
2. ⚙️ Initialize value of **k** (neighbors)  
3. ➗ Calculate **Euclidean distance** between books  
4. 📊 Sort distances in ascending order  
5. 🔝 Select top-`k` neighbors  
6. 📚 Recommend the top similar books  

---

## 📊 Workflow Diagram  

```mermaid
flowchart TD
    A[📂 Dataset] --> B[🔍 Preprocessing<br>(Ratings, User-Item Matrix)]

    B --> C[🤖 Nearest Neighbors Model<br>(Collaborative Filtering)]

    C --> D[📚 Recommendation Engine]

    D --> E[🌐 Streamlit Web App<br>(User Input → Recommended Books)]

##  🛠 Tech Stack

Programming Language: Python 🐍

Libraries: Pandas, NumPy, Scikit-learn

Visualization: Matplotlib, Seaborn

Framework: Streamlit 🌐

## 🚀 How to Run
1️⃣ Clone the Repository
git clone https://github.com/entbappy/Books-Recommender-System-Using-Machine-Learning.git
cd Books-Recommender-System-Using-Machine-Learning

2️⃣ Create Conda Environment
conda create -n books python=3.7.10 -y
conda activate books

3️⃣ Install Requirements
pip install -r requirements.txt

4️⃣ Generate the Model

Run the notebook:

Books Recommender.ipynb

5️⃣ Launch the App
streamlit run app.py

## 📈 Results

✅ Provides personalized book recommendations

✅ Uses Collaborative Filtering (KNN) for similarity search

✅ Interactive Streamlit UI for seamless user experience

## 🌟 Key Features

✔️ Interactive web interface (Streamlit)
✔️ Collaborative filtering recommendation engine
✔️ Built with Nearest Neighbors algorithm
✔️ Lightweight, easy to deploy, extendable to movies/music/products
