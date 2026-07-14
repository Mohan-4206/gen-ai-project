# AI Powered Debt Relief & Financial Recovery Platform

## Overview

The AI Powered Debt Relief & Financial Recovery Platform is a web application that helps borrowers manage loans, analyze their financial health, receive AI-based settlement recommendations, and generate professional negotiation letters. The platform combines modern web technologies with Google Gemini AI to provide intelligent financial decision support.

---

## Features

- User Registration and Login
- Financial Dashboard
- Loan Management
- AI Settlement Prediction
- AI Negotiation Letter Generation
- Financial Health Analysis
- AI Negotiation History
- JWT Authentication

---

## Technology Stack

### Frontend
- React.js
- Vite
- JavaScript

### Backend
- FastAPI
- Python

### Database
- SQLite
- SQLAlchemy ORM

### AI Integration
- Google Gemini API

---

## Project Structure

```
gen-ai-project
│
├── backend
│   ├── app
│   ├── requirements.txt
│
├── frontend
│   ├── src
│   ├── package.json
│   └── vite.config.js
│
└── README.md
```

---

## Installation

### Clone the Repository

```bash
git clone https://github.com/Mohan-4206/gen-ai-project.git
cd gen-ai-project
```

### Backend Setup

```bash
cd backend
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
uvicorn app.main:app --reload
```

### Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

The backend runs on:

```
http://localhost:8000
```

The frontend runs on:

```
http://localhost:5173
```

---

## Use Cases

### AI Settlement Recommendation
The borrower enters loan details such as outstanding amount, EMI, overdue duration, and monthly income. The platform analyzes the financial profile and provides personalized settlement recommendations along with financial health insights.

### AI Negotiation Letter Generation
The borrower selects a loan account and requests a negotiation strategy. Google Gemini AI generates professional negotiation emails and settlement request letters based on the borrower's financial condition.

### Financial Health Dashboard
The dashboard displays financial metrics including monthly surplus, EMI ratio, debt stress level, settlement percentage, and AI-generated negotiation history.

---

## System Architecture

Add the architecture diagram to the repository and reference it as:

```markdown
![System Architecture](architecture.png)
```

---

## Future Enhancements

- Multi-bank integration
- Credit score prediction
- Loan document upload
- Email notifications
- Multi-language support
- Cloud deployment
## License

This project is developed for educational and learning purposes.
