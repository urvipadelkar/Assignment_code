# Assignment Code

## 📊 Project Overview
This project is an **LLM-powered Booking Analytics & Q&A System** designed to:
- Analyze hotel booking data to extract meaningful insights  
- Generate visual analytics like **revenue trends**, **cancellation rates**, and **booking lead times**  
- Provide intelligent question answering using **Retrieval-Augmented Generation** (FAISS + LLM)  
- Offer a simple and accessible **Flask REST API** for both analytics and Q&A  

---

## ✅ Features
Here’s what’s implemented:
- 🔧 **Data Preprocessing**  
  Cleans data by handling missing values, formatting dates, and standardizing entries  
- 📈 **Analytics & Reporting**  
  Visualizes key metrics like revenue trends, cancellation rates, customer distribution, and more  
- 🤖 **LLM-based Q&A**  
  Uses FAISS + Sentence Transformer to answer user queries based on booking data  
- 🌐 **Flask API**  
  Exposes endpoints to access analytics and query the Q&A system programmatically  

---

## 📁 Project Structure
- `assignment_code.ipynb` → Complete implementation in a Colab-friendly notebook  
- `hotel_bookings.csv` → Sample dataset used for testing and analysis  
- `README.md` → This file! Contains project info and instructions  

---

## 🚀 How to Use

### 📍 Option 1: Run on Google Colab  
The easiest way:
1. Open `assignment_code.ipynb` in [Google Colab](https://colab.research.google.com/)
2. Upload the `hotel_bookings.csv` file when prompted  
3. Run each cell in order and explore the outputs  

### 💻 Option 2: Run Locally  
If you prefer to run it on your machine:
1. Make sure Python is installed  
2. Install dependencies:
   ```bash
   pip install flask flask-cors pandas numpy matplotlib seaborn faiss-cpu sentence-transformers
   ```
3. Run the Flask app:
   ```bash
   python app.py
   ```

---

## 🤝 Acknowledgment
This project is part of the assignment. It combines data analytics with modern NLP techniques to deliver a functional and insightful application.
