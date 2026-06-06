# 🩺 Health Diagnosis System

A Machine Learning-based healthcare diagnosis system that predicts diseases based on user symptoms and provides personalized recommendations including medications, precautions, diet plans, and workout suggestions.

## 🚀 Features

- Disease prediction using Machine Learning
- Symptom-based diagnosis
- Medication recommendations
- Precaution suggestions
- Diet recommendations
- Workout recommendations
- User-friendly web interface using Flask

## 🛠️ Tech Stack

### Frontend
- HTML
- CSS

### Backend
- Python
- Flask

### Machine Learning
- Scikit-learn
- Pandas
- NumPy

### Model
- Support Vector Classifier (SVC)

## 📂 Project Structure

```text
Health-Diagnosis/
│
├── Dataset/
│   ├── description.csv
│   ├── diets.csv
│   ├── medications.csv
│   ├── precautions_df.csv
│   ├── symptoms_df.csv
│   ├── Symptom-severity.csv
│   ├── Training.csv.zip
│   └── workout_df.csv
│
├── models/
│   ├── Healthcare.ipynb
│   └── svc.pkl
│
├── static/
│   └── img.png
│
├── templates/
│   ├── index.html
│   ├── about.html
│   ├── blog.html
│   ├── contact.html
│   └── developer.html
│
├── main.py
├── requirements.txt
└── README.md
```

## 📊 Dataset

The project uses healthcare symptom datasets containing:

- Diseases
- Symptoms
- Medications
- Precautions
- Diet recommendations
- Workout recommendations

## ⚙️ Installation

### Clone the Repository

```bash
git clone https://github.com/Akansha7701/Health-Diagnosis.git
cd Health-Diagnosis
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Virtual Environment

Windows:

```bash
venv\Scripts\activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Application

```bash
python main.py
```

Open your browser and visit:

```text
http://127.0.0.1:5000
```

## 🎯 How It Works

1. User enters symptoms.
2. Symptoms are processed and converted into model input.
3. Trained SVC model predicts the disease.
4. System displays:
   - Predicted Disease
   - Description
   - Medications
   - Precautions
   - Diet Plan
   - Workout Recommendations

## 📈 Future Enhancements

- User authentication
- Doctor appointment booking
- Chatbot integration
- Medical report analysis
- Deep Learning-based diagnosis
- Multi-language support

## 👩‍💻 Author

**Akansha**

GitHub:
https://github.com/Akansha7701

