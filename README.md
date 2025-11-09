# 🧠 Flash – English-Greek Flashcard App

**Flash** is a Python-based flashcard application that helps users learn English-to-Greek vocabulary through an interactive graphical interface. Built with **Tkinter** and **Pandas**, it displays a new word every few seconds and allows users to track which words they've mastered.

## 🚀 Features

- Displays English words and flips to show the Greek translation after 3 seconds
- Users can mark words as "known" to remove them from future sessions
- Progress is saved automatically in `words_to_learn.csv`
- Clean and responsive GUI using Tkinter
- Randomized word selection for varied learning

## 🛠 Technologies Used

- Python 3
- Tkinter (GUI)
- Pandas (data handling)
- CSV files for persistent progress tracking


## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/KKostika/Flash_Card_ENG_GR
2. Make sure you have the required packages
   ```bash
   pip install pandas
3. Run the app:
   ```bash
   python main.py

## 📌 Notes
If words_to_learn.csv does not exist, the app will automatically load from english_words.csv.

You can customize the vocabulary by editing the CSV files in the data/ folder.

## 👩‍💻 Author
Developed by Kyriaki Kostika

