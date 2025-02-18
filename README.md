# Movie_recommender_system
Based on your **Jupyter Notebook (`Movie_recommendation_system.ipynb`)** and **Streamlit app (`app.py`)**, here is the **optimized README file** for your **Movie Recommendation System** project:

---
## 🚀 **Features**
✅ Recommends **5 similar movies** based on input  
✅ Uses **TF-IDF & Cosine Similarity** for recommendations  
✅ Fetches **movie posters** via **TMDb API**  
✅ **Interactive UI** with **Streamlit**  
✅ **Fast & Efficient** using **precomputed similarity matrix**  

---

## 📂 **Project Structure**
```
📂 Movie-Recommendation-System/
│-- 📜 app.py                   # Streamlit web app  
│-- 📜 Movie_recommendation_system.ipynb  # Jupyter Notebook for ML model  
│-- 📜 movie_dict.pkl            # Pickle file containing processed movie data  
│-- 📜 similarity.pkl            # Precomputed similarity matrix  
│-- 📂 dataset/                  # Raw and processed datasets  
│-- 📜 requirements.txt          # Dependencies  
│-- 📜 README.md                 # Project documentation  
```

---

## 🛠️ **Tech Stack**
- **Python**
- **Pandas & NumPy** (for data processing)
- **Scikit-Learn** (for similarity computation)
- **Streamlit** (for UI)
- **TMDb API** (for movie posters)

---

## 🔹 **Installation & Setup**
### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/yourusername/Movie-Recommendation-System.git
cd Movie-Recommendation-System
```

### **2️⃣ Install Dependencies**
```bash
pip install -r requirements.txt
```

### **3️⃣ Run the Streamlit App**
```bash
streamlit run app.py
```

---

## 🖥️ **How It Works?**
### 🎭 **1. Content-Based Filtering**
- Uses **TF-IDF Vectorization** to analyze movie descriptions.
- Computes **Cosine Similarity** between movies to find the closest matches.
  
### 🔗 **2. TMDb API Integration**
- Fetches **movie posters** dynamically from **TMDb API**.
- Improves **user experience** with rich visuals.

---
## 🔥 **Future Enhancements**
- ✅ Implement **Collaborative Filtering** for personalized recommendations  
- ✅ Use **Deep Learning (Neural Networks)** for better accuracy  
- ✅ Improve **UI with more features**  

---
