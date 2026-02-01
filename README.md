
Author :  Naman Bhatt

```
# End-to-End Machine Learning Project – Forest Fire Prediction

This is an end-to-end Machine Learning project built using Python and Flask.  
The application predicts the **Fire Weather Index (FWI)** based on multiple environmental and weather parameters.

---

## Project Overview
This project demonstrates the complete Machine Learning workflow starting from data preprocessing and exploratory data analysis (EDA) to model training, evaluation, and deployment using a Flask web application.

---

## Tech Stack
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  
- Flask  
- HTML (Jinja2 Templates)

---

## Project Structure
```

end to end ML PROJ/
│
├── application.py
├── models/
│   ├── ridge.pkl
│   └── scaler.pkl
├── notebooks/
├── templates/
│   └── index.html
├── requirements.txt
└── README.md

```

---

## How to Run the Project

### Step 1: Clone the repository
```

git clone [https://github.com/USERNAME/REPO_NAME.git](https://github.com/USERNAME/REPO_NAME.git)
cd REPO_NAME

```

### Step 2: Create a virtual environment
```

python -m venv venv
source venv/bin/activate   # macOS/Linux
venv\Scripts\activate      # Windows

```

### Step 3: Install dependencies
```

pip install -r requirements.txt

```

### Step 4: Run the Flask application
```

python application.py

```

Open the browser and visit:
```

[http://127.0.0.1:5001/](http://127.0.0.1:5001/)

```

---

## Input Features
- Temperature  
- Relative Humidity (RH)  
- Wind Speed (Ws)  
- Rain  
- FFMC  
- DMC  
- ISI  
- Classes  
- Region  

---

## Output
The application predicts the **Fire Weather Index (FWI)** based on the input values.

---


## Note
This project is created for learning and academic purposes as part of a Machine Learning / Data Science curriculum.
```

---
