# 🎓 Student Placement Predictor

**Student Placement Predictor** is a Machine Learning project that predicts whether a student is likely to be placed based on their academic and personal attributes. The project explores classification algorithms and deploys a live web application to assist institutions and students with early insights into placement readiness.

This project demonstrates how ML classification workflows can be built, trained, and deployed using Scikit-learn, with a Flask-based web interface.

---

## 🚀 Features

- Cleaned and preprocessed student dataset  
- Feature scaling using StandardScaler  
- Classification models tested: ✅ Support Vector Classifier (SVC), ✅ Random Forest         C
- Final model saved using `pickle`  
- Web application using Flask + HTML  
- Real-time placement prediction based on user inputs  

---

## 🧠 How It Works

1. User fills in academic and personal details through the web interface  
2. The backend applies preprocessing and feeds the input into the trained ML model  
3. The model predicts whether the student is likely to be placed or not  
4. The result is displayed in real-time on the web page  

---

## 📁 Dataset

The dataset includes features such as CGPA, gender, SSC/HSC percentage, stream, degree type, etc.  
The project uses a cleaned version of the data with categorical and numerical features encoded for model training.

---

## 🧰 Tech Stack

- Python 3.13  
- Scikit-learn  
- Pandas  
- NumPy  
- Flask  
- HTML/CSS (for the web UI)  
- Pickle (for model saving/loading)  

---

## 👥 Contributors

This project was originally developed as part of a group academic project.

**Group Members:**

- Amil Gauri (Maintainer)  
- Tanmay Buchade  
- Om Dubey  
- Meeth Amin  

> Project documented and maintained by **Amil Gauri** for public release.

---

## 📄 License

This project is open-source under the **MIT License**.  
You are free to use, modify, and distribute it with proper credit.

See the [LICENSE](LICENSE) file for full details.
