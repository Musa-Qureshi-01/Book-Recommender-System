# 📚 Book Recommender System
A simple machine learning-based web application that recommends books based on user interest. Built using Python, Pandas, and Flask. Using Pycharm

## 🚀 Live Demo
[Preview](https://book-recommender-system-pnem.onrender.com/)
## 🧠 Features
- 📖 Recommends similar books based on input
- 📊 Uses collaborative filtering / content-based filtering
- 🖥️ Built with Flask (or Streamlit if you're using it)
- 💾 Uses a trained .pkl model
- 🌐 Frontend with Bootstrap & Jinja2 (if used)

## 🛠 Tech Stack
- Python (Pandas, Scikit-learn)
- Flask (or Streamlit)
- HTML/CSS + Bootstrap (Frontend)
- Jupyter Notebook (for EDA and model training)

## 📁 Project Structure
```
Book-Recommender-System/
│
├── app.py                # Flask application
├── model.pkl             # Trained ML model
├── templates/            # HTML files
├── static/               # CSS, JS, images
├── requirements.txt      # Python dependencies
└── README.md             # Project overview

```
## ✅ Setup Instructions
Clone the repo

- git clone https://github.com/Musa-Qureshi-01/Book-Recommender-System.git
- cd Book-Recommender-System
- Create a virtual environment (optional but recommended)
- python -m venv venv
- venv\Scripts\activate  # on Windows
- Install dependencies
- pip install -r requirements.txt
- Run the app
- python app.py
- Open in browser
- http://127.0.0.1:5000/
---

## 🔮 Future Plans
- Add user-based recommendations
- Improve UI/UX
- Deploy to Render or Hugging Face Spaces
- Add login/signup with personalized history
