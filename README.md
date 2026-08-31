# 🔐 Random Password Generator — Python

A simple and beginner-friendly **Random Password Generator** developed using Python. The program allows users to specify the password length and choose whether to include uppercase letters, numbers, and symbols.

## 📌 Project Overview

The Random Password Generator creates a random password based on the user's requirements.

The program allows the user to:

* Choose the password length.
* Include or exclude uppercase letters.
* Include or exclude numbers.
* Include or exclude symbols.
* Generate a random password automatically.

## 🎯 Objective

The main objective of this project is to create a Python program that demonstrates:

* User input handling
* Conditional statements
* Loops
* Random character selection
* Python strings
* Basic Python programming concepts

## 🛠️ Technologies Used

* **Python 3**
* **Google Colab / Jupyter Notebook**
* `random` module
* `string` module

No external libraries need to be installed.

## ⚙️ How It Works

The program first creates a character set containing lowercase letters.

Based on the user's choices, it adds:

* **Uppercase letters:** `A-Z`
* **Numbers:** `0-9`
* **Symbols:** punctuation characters

The program then randomly selects characters from the resulting character set until the requested password length is reached.

## ▶️ How to Run

### Using Google Colab

1. Open **Google Colab**.
2. Upload `task_2.ipynb`.
3. Open the notebook.
4. Run the code cell.
5. Enter the required password length.
6. Select whether to include uppercase letters, numbers, and symbols.
7. The generated password will be displayed.

### Using Python

Run the notebook using Jupyter Notebook or convert the code into a Python file.

```bash
python task_2.py
```

## 💻 Sample Input

```text
===================================
      RANDOM PASSWORD GENERATOR
===================================

Enter password length: 12
Include uppercase letters? (yes/no): yes
Include numbers? (yes/no): yes
Include symbols? (yes/no): yes
```

## 📤 Sample Output

```text
===================================
          GENERATED PASSWORD
===================================

aT7@qP2#xLm9

===================================
```

> **Note:** The generated password will be different each time because the program selects characters randomly.

## ✨ Features

* 🔢 Custom password length
* 🔠 Optional uppercase letters
* 🔢 Optional numbers
* 🔣 Optional symbols
* 🎲 Random password generation
* 💻 Simple command-line interface
* 🚀 Easy to run in Google Colab
* 📚 Beginner-friendly Python project

## 📁 Project Structure

```text
Random-Password-Generator/
│
├── task_2.ipynb
└── README.md
```

## 🔮 Future Enhancements

The project can be improved by adding:

* Password strength checking
* Guaranteed inclusion of at least one character from each selected category
* Copy-to-clipboard functionality
* Graphical User Interface (GUI)
* Password generation history
* Secure password generation using Python's `secrets` module

## 👨‍💻 Author

**Simica**

## 📄 License

This project is created for educational and learning purposes.


