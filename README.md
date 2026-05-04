# 🚀 ITPM Assignment 1: Transliteration Accuracy Testing

Welcome to the automated testing repository for the **IT3040 - Information Technology Project Management (ITPM)** module, Assignment 1. 

This project evaluates the accuracy of a live Chat Sinhala transliteration application. It uses **Python** and **Playwright** to automate the execution of 50 structured test cases, covering 24 distinct Singlish input types, and automatically records the results into an Excel file.

## 🎯 Objectives
* To evaluate the correctness of the Singlish-to-Sinhala chat transliteration function.
* To automate repetitive UI testing scenarios using Playwright.
* To analyze system weaknesses in a structured manner based on various Singlish chat patterns.

## 🛠️ Technologies & Tools Used
* **Language:** Python (v3.11 / v3.12)
* **Automation Framework:** Playwright
* **Data Handling:** Openpyxl / Pandas (Excel integration)

## 📁 Repository Structure
* `test_automation.py` - The main Python script containing the Playwright automation logic.
* `Assignment 1 - Test cases.xlsx` - The Excel file containing the 50 negative test cases mapped to the 24 input types.
* `README.md` - Project documentation and setup instructions.

## ⚙️ Setup & Installation Instructions

Follow these steps to set up the environment and run the automated tests on your local machine:

**1. Install Python**
Ensure that Python 3.11 or 3.12 is installed on your system.

**2. Install Dependencies**
Open your terminal or command prompt, navigate to this project folder, and run the following commands:
```bash
pip install -U pip
pip install playwright openpyxl
playwright install
