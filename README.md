# 🧮 Employee Net Salary Calculator - Django Web App

A simple Django web application that calculates the **Net Salary** of an employee based on user input (Gross Salary, Tax %, and Bonus %) and also includes a fun **Jumbled Word Generator**.

---

## 🚀 Features

- 🌐 Form-based input using plain HTML (no Django Forms)
- 📊 Net Salary calculation using:
  
Net Salary = Gross Salary - (Gross Salary * Tax%) + (Gross Salary * Bonus%)


- 🧠 Word jumbling feature: enter a word and see it shuffled
- 📝 No database entries required – fully functional using Django views and templates

---

## 🧩 Functional Requirements

### Salary Calculator

- Input fields:
- Employee Name
- Age
- Company
- Gross Salary
- Tax (%)
- Bonus (%)
- Output:
- Employee Name
- Net Salary

### Word Jumbler

- Input:
- Any single word
- Output:
- Randomized (jumbled) version of the input word

---

## 📁 Project Structure

employee_salary_project/ │ ├── employee_salary_project/ │ └── settings.py, urls.py, wsgi.py, ... │ ├── employee_app/ │ ├── views.py │ ├── urls.py │ └── templates/ │ ├── form.html │ ├── result.html │ └── jumble.html │ ├── db.sqlite3 ├── manage.py └── README.md
