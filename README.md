# 💡 Money Mentor  with Chatbot

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

## System Flow 🔄

![WhatsApp Image 2026-03-29 at 9 59 22 PM](https://github.com/user-attachments/assets/f780567c-2bb8-4d7a-ad7e-52ad3f548f1e)

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

## website look
<img width="1061" height="641" alt="Screenshot 2026-03-29 230415" src="https://github.com/user-attachments/assets/e9d465cd-4512-4674-87c2-35ffa3dd0c96" />
<img width="1160" height="535" alt="Screenshot 2026-03-29 230757" src="https://github.com/user-attachments/assets/d161a953-80b1-47ef-ada0-7c2bbf289e3a" />


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

## How to Run the Project 🚀

### 1. Clone Repository
```bash
git clone <your-repository-link>
cd project-folder
