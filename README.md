
# 🥊 UFC Fight Outcome Predictor (Machine Learning Project)

This is a data-driven machine learning project that predicts the outcome of a UFC fight between two selected fighters using historical fight statistics. The system analyzes fighter attributes, applies preprocessing, trains a classification model, and outputs the predicted winner and win method — via a fully interactive interface using IPyWidgets in Jupyter Notebook.

---

## 🚀 Overview

- Built with Python, scikit-learn, and Jupyter Notebook
- Trained a **Random Forest Classifier** to predict fight winner
- Used **custom features** like KO%, submission %, striking accuracy, etc.
- Includes **interactive fighter selection UI** by weight class
- Displays predicted winner and method (Knockout, Submission, or Decision)

---

## 🧠 Technologies Used

| Component             | Tools & Libraries                                   |
|-----------------------|------------------------------------------------------|
| Data Collection       | CSV dataset (`fighters_data.csv`)                   |
| Preprocessing         | Pandas, NumPy, MinMaxScaler                         |
| Modeling              | RandomForestClassifier (scikit-learn)              |
| Model Saving          | joblib                                              |
| UI/Interactivity      | IPyWidgets, IPython `display`, Dropdowns           |
| Visualization         | Inline image display for fighters (optional)       |

---

## 🔍 Features

- Automatically fills missing data using mean/mode
- Converts and scales numeric features like reach, accuracy, and strike rate
- Allows users to select weight class and two fighters
- Predicts the winner and how they'll likely win
- Fully interactive inside Jupyter Notebook

---

## 📂 Project Structure

```
UFC-Fight-Predictor/
├── UFC_Fight_Predictor.ipynb        # Main code with widgets & ML logic
├── fighters_data.csv                # Dataset
├── UFC_Predictor_Synopsis.pdf
├── UFC_Predictor_Report.pdf
└── UFC_Predictor_SRS.pdf


---

## 📈 Model Performance

| Metric     | Score |
|------------|-------|
| Accuracy   | ~91%  |
| F1 Score   | ~0.9 |

> Scores can vary depending on dataset version and preprocessing steps.

---

## 🧪 How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/yourusername/UFC-Fight-Predictor.git
   cd UFC-Fight-Predictor
   ```

2. Open in Jupyter/Google colab:
   ```bash
   jupyter notebook UFC_Fight_Predictor.ipynb
   ```

3. Make sure `fighters_data.csv` is in the same folder

4. Run all cells and use the dropdowns to select fighters and predict fight results


---

## 📄 Reports & Documents

- [✔️ Synopsis](./report/UFC_Predictor_Synopsis.pdf)
- [✔️ SRS – Software Requirement Spec](./report/UFC_Predictor_SRS.pdf)
- [✔️ Final Project Report](./report/UFC_Predictor_Report.pdf)

---

## 📌 Future Enhancements

- Deploy as a web app using Flask or Streamlit
- Integrate live UFC stats using an API
- Add confidence score to predictions
- Include more advanced feature engineering

---

## 🙌 Author

**Siddharth Kshirsagar**  
📧 siddharth.kshirsagar378@gmail.com  
🔗 [LinkedIn](https://linkedin.com/in/siddharth-kshirsagar-0559761b4)  
🔗 [GitHub](https://github.com/SiddKshir1234)

---

## 🏷 Tags

`Python` `Machine Learning` `Random Forest` `Sports Analytics` `UFC` `Fight Prediction` `Data Science` `IPyWidgets` `Project Portfolio`
