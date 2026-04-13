# AI Finance Tracker

## Overview

AI Finance Tracker is a smart web-based platform designed to help users **track, analyze, and optimize their financial activities** using AI-driven insights.
It simplifies personal finance management by providing real-time tracking, intelligent suggestions, and visual analytics.

---

## Problem Statement

Managing personal finances manually is often inefficient and error-prone. Users struggle with:

* Tracking expenses consistently
* Understanding spending patterns
* Making data-driven financial decisions

This platform solves these issues by integrating **automation and AI-based analysis**.

---

##  Key Features

### Expense & Income Tracking

* Add, edit, and categorize transactions
* Real-time updates of financial data

###  AI-Based Insights

* Smart analysis of spending habits
* Personalized financial suggestions
* Predictive insights for better planning

###  Data Visualization

* Interactive charts and graphs
* Monthly and category-wise breakdown

###  Secure Authentication

* User login and data protection
* Secure storage of financial records

###  Responsive UI

* Clean and intuitive interface
* Works across devices

---

## Tech Stack

### Frontend

* React.js 
* Tailwind CSS

### Backend

* Node.js

### Database

* Supabase and PostgreSQL

### AI Integration

* Custom logic / AI APIs for financial insights

---

## How It Works

1. User logs into the platform
2. Adds income and expenses
3. Data is stored securely in the database
4. AI module analyzes spending behavior
5. Insights and visual reports are generated

---


## 🧪 Setup Instructions

```bash
# Clone the repository
git clone https://github.com/your-username/ai-finance-tracker.git

# Navigate to project folder
cd ai-finance-tracker

# Install dependencies
npm install

# Run the project
npm run dev
```

---

##  Future Enhancements

*  Mobile app integration
*  OCR for bill scanning
*  Advanced AI forecasting models
*  Smart alerts for overspending

---

##  Author

**Nishant Kumar**
B.Tech (ECE), IIT Patna

* Passionate about Technology
* Interested in AI, Web Development, and Trading

---

##  Contribution

Feel free to fork this repo and contribute!
If you like this project, don’t forget to ⭐ the repository.

---


### Make sure to create a `.env` file with following variables -

```
DATABASE_URL=
DIRECT_URL=

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding

GEMINI_API_KEY=

RESEND_API_KEY=

ARCJET_KEY=
```
