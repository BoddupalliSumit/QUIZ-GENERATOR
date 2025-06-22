# 🧠 Quiz Generator

A simple Python-based **Quiz Generator** that loads questions from a CSV file and presents them to the user via a graphical user interface (GUI). This project is ideal for practicing Python basics, working with files, and creating interactive applications using **Tkinter** or **Jupyter Notebook**.

---

## 📁 Project Structure

```
├── QUIZ GENERATOR.ipynb       # Jupyter Notebook with GUI code and logic
├── quiz_questions.csv         # CSV file containing quiz questions and answers
└── README.md                  # Project documentation
```

---

## 📌 Features

- Load questions dynamically from a CSV file  
- Supports **Multiple Categories** and **Difficulty Levels**
- GUI-based quiz interface (via `Tkinter` or notebook widgets)
- Score calculation and result display
- Randomized question order for each session

---

## 📝 CSV Format (`quiz_questions.csv`)

Each row in the CSV should have the following columns:

| category | difficulty | question         | option1 | option2 | option3 | option4 | answer         |
|----------|------------|------------------|---------|---------|---------|---------|----------------|
| Science  | Easy       | What gas do plants absorb? | Oxygen | Carbon Dioxide | Hydrogen | Nitrogen | Carbon Dioxide |

---

## ▶️ How to Run

### 🧪 Option 1: Jupyter Notebook
1. Open `QUIZ GENERATOR.ipynb` in Jupyter Notebook.
2. Run all cells.
3. The quiz GUI will appear with questions loaded from the CSV file.

### 💻 Option 2: Python Script
If exported as a `.py` script:
```bash
python quiz_generator.py
```

---

## 📦 Requirements

Install dependencies using pip:
```bash
pip install pandas
```

If using GUI:
```bash
pip install tk
```

---

## 🚀 Future Improvements

- Add timer-based questions
- User login and score tracking
- Support for images or audio-based questions
- Export results to CSV

---

## 📃 License

This project is open source and available under the [MIT License](LICENSE).
