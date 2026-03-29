# 💡 Money Mentor Financial Advisor Landing Page with Chatbot

## Description 🌱
Money Mentor is a simple and practical financial advisor web application designed to help users understand their financial health and plan their future. It combines a clean landing page with a rule-based chatbot that answers common financial queries.

This project focuses on solving real-world problems where people struggle with financial planning due to complexity, high advisor costs, and lack of awareness. Instead of using heavy AI models, the system applies clear financial rules to generate easy-to-understand insights.

---

## Problem Statement 🚨
In real life, most people:
• Do not track their financial health  
• Do not maintain an emergency fund  
• Take financial decisions based on random advice  
• Avoid planning for retirement  

Result:
• Poor financial stability  
• No long-term growth  
• High financial risk  

---

## What This Project Does 🎯
Money Mentor:
• Takes basic financial inputs from the user  
• Applies simple financial rules  
• Generates instant insights and recommendations  
• Provides chatbot support for guidance  

⚠️ Note:  
This is a rule-based system. It does not predict stock markets or use real-time financial data.

---

## Core Features 🧠

### 1. Money Health Score 💰
Calculates the user’s financial condition based on:

• Emergency Fund  
• Debt Ratio  
• Savings Habit  

Score is calculated out of 100 and provides insights like:
• Whether savings are sufficient  
• Whether debt is risky  
• Whether spending habits are balanced  

---

### 2. FIRE Planner 🔥
Helps users plan for retirement using a simple approach:

• Calculates required retirement corpus  
• Estimates monthly investment needed  
• Suggests basic asset allocation  

---

## System Flow 🔄

User Input (Form)  
↓  
Data Validation  
↓  
Financial Calculations (Rule-Based Logic)  
↓  
Result Generation  
↓  
Display Output + Chatbot Response  

---

## Working Flow 🚀

1. User opens the website  
2. Enters financial details  
3. Clicks "Analyze"  
4. System calculates:
   • Financial Score  
   • Retirement Plan  
5. Results are displayed instantly  
6. Chatbot assists with additional queries  

---

## Logic Used 🧩

### Financial Score Calculation
Total Score = Emergency Fund + Debt Health + Savings Habit (out of 100)

• Emergency Fund:
  Required = 6 × monthly expenses  

• Debt Health:
  Debt Ratio = EMI / Income  

• Savings Habit:
  Savings Ratio = (Income - Expenses) / Income  

---

### Retirement Planning Logic
• Time to Retirement = Target Age - Current Age  
• Retirement Corpus ≈ 25 × Annual Expenses  
• Monthly Investment ≈ Remaining Amount / Months  
• Asset Allocation:
  Equity = 100 - Age  
  Debt = Age  

---

## Technology Stack 🪣

Frontend:
• HTML  
• CSS  

Backend:
• Flask  

Libraries:
• PyTorch  
• NLTK  

Languages:
• Python  
• JavaScript  

---

## Screenshots 📸
![Landing page](<Screenshot 2024-03-17 140327.png>)  
![Bot Working](<Screenshot 2024-03-17 140645.png>)  

---

## How to Run the Project 🚀

### 1. Clone Repository
```bash
git clone <your-repository-link>
cd project-folder