# 📊 Student Exam Score Prediction

*A machine learning project to predict student exam scores based on study habits, environment, and academic history.*

## 📖 Overview

This project develops a predictive model to estimate student exam performance using machine learning. By analyzing factors like study habits, attendance, and previous academic performance, the model can identify key drivers of student success and provide accurate score predictions.

The implemented solution achieved **75.8% explained variance** in test scores using a Polynomial Regression model, demonstrating strong predictive capability for educational outcomes.

## 🎯 Key Findings

The analysis revealed several important insights:

- **Previous scores** are the strongest predictor of future performance (correlation: 0.92)
- **Regular attendance** significantly impacts exam results
- **Hours studied** has a meaningful but smaller effect than expected
- Demographic factors showed minimal predictive value compared to behavioral metrics

### Model Performance Comparison

| Model | MAE | MSE | R² Score |
|-------|-----|-----|----------|
| Linear Regression | 1.01 | 4.39 | 0.68 |
| **Polynomial Regression** | **0.55** | **3.14** | **0.75** |
| Linear 	Regression (Top 5 Features) | 1.22 | 4.91 | 0.65 |
| Linear 	Regression (No Sleep Hours) | 1.01 | 4.39 | 0.68 |

*Polynomial Regression (degree=2) emerged as the best performing model*

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=matplotlib&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

## 🚀 Getting Started

### Prerequisites

- Python 3.8+
- pip (Python package manager)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/AlishaRafique43/student-score-prediction.git
cd student-score-prediction
```

2. Create a virtual environment (recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install required packages:
```bash
pip install -r requirements.txt
```

### Running the Project

1. Launch Jupyter Notebook:
```bash
jupyter notebook
```

2. Open and run `student_score_prediction.ipynb` to:
   - Explore the data analysis
   - See model training and evaluation
   - Generate predictions

## 👨‍💻 Author

**Alisha Rafique** 
- Aspiring Data Scientist passionate about machine learning and its real-world applications.
- Connect with me on [LinkedIn](https://linkedin.com/in/) or check out my other projects on [GitHub](https://github.com/AlishaRafique433)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## 🙏 Acknowledgments

- Dataset provided by Kaggle
- Inspired by educational research on student performance predictors
- Built with guidance from the data science community
