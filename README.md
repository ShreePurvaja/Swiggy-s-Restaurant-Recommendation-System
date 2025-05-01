# 🍽️ Swiggy Restaurant Recommendation System

A smart, fast, and user-friendly Streamlit app that recommends restaurants based on city, cuisine, rating, and cost preferences. Built using machine learning and real Swiggy data.

---

## 🔍 Overview

This system uses a **pre-encoded dataset** (`encoded_data.csv`) and a **pre-trained encoder** (`encoder.pkl`) to compute similarity between user preferences and restaurant features using **Cosine Similarity**.

Users can:
- Select their city
- Choose their preferred cuisine
- Set minimum rating and maximum budget
- Get top 5 restaurant recommendations with address and Swiggy link for ordering

---

## ✨ Features

- 🍜 **Cuisine-based filtering** (e.g., Chinese, South Indian, Italian)
- 🏙️ **City selection**
- ⭐ **Minimum rating** slider
- 💰 **Maximum cost** selector
- 📍 Shows restaurant **address**
- 🔗 **"Order Now"** button linking to Swiggy page
- 💡 Uses **cosine similarity** for recommendations
- 🧠 Uses **pre-encoded features** with a **trained encoder** for speed and efficiency


---

## ⚙️ Tech Stack

| Component        | Technology              |
|------------------|--------------------------|
| Frontend         | Streamlit                |
| Backend Logic    | Python, Scikit-learn     |
| Data Handling    | Pandas, NumPy            |
| Model            | OneHotEncoder + Cosine Similarity |
| Dataset          | Custom (Swiggy restaurant data)  |


---

## ▶️ How to Run Locally

### 🔧 Prerequisites
Make sure you have Python 3.8+ and `pip` installed.

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/swiggy-recommendation-system.git
cd swiggy-recommendation-system
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the App
```bash
streamlit run app.py
```

## 📦 Download Dataset
[swiggy.csv (Google Drive)](https://drive.google.com/file/d/1oFn9nfrL1sx2XvRBwysffu66waHX7Sm4/view)

## 🗂 Project Structure

swiggy-recommendation-system/

├── app.py                       # Main Streamlit app


├── Swiggy_Recommendation        # Cleaned dataset (to be added)


├── requirements.txt             # Python dependencies


└── README.md                    # Documentation

## 🧑‍💻 Author
Name : Shree Purvaja D

Email :📧 shreepurvaja@gmail.com

LinkedIn : [Shree Purvaja D](https://www.linkedin.com/in/shree-purvaja-d/)


## 🪪 License
This project is licensed under the MIT License.

## ⭐ Contribute
Feel free to fork this repo and build on top of it.

If you find it useful, give it a ⭐ on GitHub



