# ⚡ ML Preprocessing CLI

A beginner-friendly **Command-Line Interface (CLI)** tool to automate essential data preprocessing tasks in machine learning workflows — from missing value handling to encoding and feature scaling.

[![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)](https://www.python.org/)
[![Status](https://img.shields.io/badge/Project-Active-brightgreen)]()

---

## 🎯 Features

- 📊 Dataset summary and null value statistics  
- 🧹 Missing value handling (drop or impute)  
- 🧠 Categorical encoding (Label Encoding, One-Hot Encoding)  
- 📏 Feature scaling (Standard or Min-Max)  
- 📥 Export cleaned dataset to CSV  
- 🧪 Interactive terminal menu — no notebook required!

---

## 🧰 Installation

Make sure you have Python 3.10+ installed.

```bash
git clone https://github.com/mohakamitpatel/ML_Preprocessing_CLI.git
cd ML_Preprocessing_CLI
pip install -r requirements.txt
```

---

## 🗂️ Project Structure

📂 ML_Preprocessing_CLI  
├── data/ → Sample datasets (optional)  
├── data_input.py → Reads the dataset  
├── data_description.py → Summarizes the dataset  
├── imputation.py → Missing value imputation  
├── categorical.py → Encoding categorical features  
├── feature_scaling.py → Feature scaling logic  
├── download.py → Saves the cleaned dataset  
├── main.py → CLI entry-point  
└── requirements.txt → Required Python libraries

---

## 💻 How to Use

Run the CLI from the terminal:

```bash
python main.py
```

You will be guided through a step-by-step menu to:

1. Upload dataset  
2. Handle missing values  
3. Encode categorical variables  
4. Scale features  
5. Download processed file

---

## 🔍 Example Usage

```bash
$ python main.py
📁 Please enter the path to your CSV file: data/sample.csv

✅ Dataset Loaded!
Choose an option:
[1] Describe Data
[2] Handle Missing Values
[3] Encode Categorical Features
[4] Scale Features
[5] Export Cleaned Data
```

---

## 📦 Dependencies

- pandas  
- numpy  
- scikit-learn  
- tabulate  
- termcolor  

Install via:

```bash
pip install -r requirements.txt
```

---

## 🎥 Demo Preview

Watch the full walk-through of this CLI tool in action:  
▶️ [YouTube Demo](https://www.youtube.com/watch?v=n2kXr99IVzU)

<img src="https://github.com/mohakamitpatel/ML_Preprocessing_CLI/blob/main/Image.png" width="640"/>

---

## 💡 Future Ideas

- Add support for command-line arguments  
- Integrate GUI using Tkinter or Streamlit  
- Auto EDA with visualizations  
- Upload directly from URL or cloud storage  

---

## 🤝 Contributing

Pull requests are welcome!  
If you have suggestions or find bugs, feel free to fork and improve.

---

## 🫡 Peace out.

