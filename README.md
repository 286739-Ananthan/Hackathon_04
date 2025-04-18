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

```
Hackathon 4/
├── employee_salary_project/
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── employee_app/
│   ├── views.py
│   ├── urls.py
│   └── templates/
├── db.sqlite3 
├── manage.py
```

🌐 Salary Calculator: http://127.0.0.1:8000/
🌐 Jumble Tool: http://127.0.0.1:8000/jumble/

## 📸 Screenshot
![image](https://github.com/user-attachments/assets/526475e4-0c8a-44a9-ac1e-1a150b4b2e54)
![image](https://github.com/user-attachments/assets/09520cc2-b4ec-4e7d-ae6d-236acdd143cf)

