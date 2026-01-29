Language Detection & Translation Tool (Python)

A simple Python desktop application that detects the language of user-provided text, translates it into English, and applies basic spelling correction using TextBlob. The application uses a Tkinter GUI for user input and output.

📌 Features

Detects the source language automatically

Translates text to English

Performs spelling correction on translated text

Simple GUI input dialog and output popup

Uses Natural Language Processing (NLP) via TextBlob

🛠 Technologies & Libraries

Python

TextBlob

NLTK

Tkinter

Pandas (imported, optional/future use)





it’s a **GUI-based language detection, translation, and correction tool** built on top of **TextBlob + Tkinter**. 

# 🌍 Language Detection & Translation Tool (TextBlob + Tkinter)

This project is a simple **desktop application** that detects the language of user-entered text, translates it into English, performs basic spelling correction, and displays the result using a graphical interface.

It leverages **TextBlob** for NLP tasks and **Tkinter** for user interaction.

---

## Features

***Automatic Language Detection**
***Translation to English**
***Spelling & Grammar Correction**
***Simple GUI input dialog**
***Built using lightweight Python libraries



## Technologies Used

* **Python 3**
* **TextBlob**
* **NLTK**
* **Tkinter**
* **Pandas** (imported, optional for future enhancements)



## Project Structure



├── main.py          # Main application script
├── README.md        # Project documentation
|__ country.csv      # Language Code file




## How It Works

1. A Tkinter dialog prompts the user to enter text.
2. The application:

   * Detects the language of the input text
   * Translates it to English
   * Applies spelling correction
3. The corrected English output is shown in a message box and printed in the console.

---

## Example Workflow

**Input (any language):**

```
Hola, cómo estas?
```

**Detected Language Code:**

```
es
```

**Output (English, corrected):**

```
Hello, how are you?
```

---

##  Code Overview

### Key Components

* `TextBlob.detect_language()`
  Detects the source language.

* `TextBlob.translate()`
  Translates text into English.

* `TextBlob.correct()`
  Applies spelling correction.

* `tkinter.simpledialog.askstring()`
  Collects user input via GUI.

* `tkinter.messagebox.showinfo()`
  Displays translated output.

---

## 📦 Installation

### 1️ Clone the Repository

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### 2️ Install Dependencies

```bash
pip install textblob nltk pandas
```

### 3️ Download NLTK Corpora

```python
import nltk
nltk.download('punkt')
nltk.download('averaged_perceptron_tagger')
```

---

##  Run the Application

```bash
python main.py
```

A dialog box will appear asking for text input.

---

##  Notes & Limitations

* Requires an **internet connection** for language detection and translation.
* TextBlob’s translation relies on Google Translate (unofficial API).
* Some unused classifier imports are commented out — these suggest planned ML extensions.

---

## Future Improvements

* Add language selection dropdown
* Show detected language name instead of code
* Add batch file translation
* Integrate ML classifiers (Naive Bayes, Random Forest, etc.)
* Improve GUI layout

---

## Author

**Md Ruhul Kibria Maruf**
Md ruhul Kibria Maruf
GitHub:https://github.com/Rkmaruf


