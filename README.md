# 🧮 BMI Calculator — Python

A simple **BMI (Body Mass Index) Calculator** developed using Python. This beginner-friendly project takes the user's name, height, and weight as input, calculates their BMI, and determines their BMI category.

## 📌 Project Overview

The BMI Calculator is a command-line Python application that helps users calculate their Body Mass Index based on their height and weight.

The program:

* Takes the user's name as input.
* Takes height in meters.
* Takes weight in kilograms.
* Calculates BMI using the standard formula.
* Classifies the result into a BMI category.
* Displays the user's details and calculated result.

## 🎯 Objective

The main objective of this project is to create a simple Python program that demonstrates:

* User input handling
* Mathematical calculations
* Conditional statements
* Variables and data types
* Formatted output
* Basic Python programming concepts

## 🧮 BMI Formula

The BMI is calculated using the following formula:

**BMI = Weight (kg) / Height² (m²)**

For example:

```text
Weight = 60 kg
Height = 1.65 m

BMI = 60 / (1.65 × 1.65)
BMI ≈ 22.04
```

## 📊 BMI Categories

| BMI Range    | Category      |
| ------------ | ------------- |
| Below 18.5   | Underweight   |
| 18.5 – 24.9  | Normal Weight |
| 25 – 29.9    | Overweight    |
| 30 and above | Obesity       |

## 🛠️ Technologies Used

* **Python 3**
* **Google Colab / Jupyter Notebook**

No external Python libraries are required.

## ▶️ How to Run

### Using Google Colab

1. Open Google Colab.
2. Upload `task_1.ipynb`.
3. Open the notebook.
4. Run the code cell.
5. Enter your:

   * Name
   * Height in meters
   * Weight in kilograms
6. The program will display your BMI and category.

### Using Python

Save the code as:

```text
bmi_calculator.py
```

Then run:

```bash
python bmi_calculator.py
```

## 💻 Sample Input

```text
===================================
          BMI CALCULATOR
===================================

Enter your name: Rahul
Enter your height in meters: 1.75
Enter your weight in kilograms: 70
```

## 📤 Sample Output

```text
===================================
             RESULT
===================================
Name: Rahul
Height: 1.75 m
Weight: 70.0 kg
BMI: 22.86
Category: Normal Weight
===================================
```

## 📁 Project Structure

```text
/
│
├── task_1.ipynb
└── README.md
```

## 🌟 Features

* Simple and beginner-friendly
* Easy-to-use command-line interface
* Fast BMI calculation
* Automatic BMI classification
* No external libraries required
* Can be executed in Google Colab

## 🚀 Future Enhancements

The project can be improved by adding:

* Height input in centimeters and feet/inches
* Weight input in pounds
* Input validation
* Graphical User Interface (GUI)
* BMI history
* Personalized health recommendations
* Mobile or web-based interface

## 👨‍💻 Author

**Simica**

## 📄 License

This project is created for educational and learning purposes.
