# AI in Software Engineering 

This project demonstrates how AI can be applied in software engineering to automate code writing, perform testing, and support decision-making through predictive analytics.

## Overview

This notebook includes implementations of:
1. **AI-Powered Code Completion** using Python functions and comparisons.
2. **Automated Testing** using Selenium WebDriver for UI test automation.
3. **Predictive Analytics** using the Breast Cancer dataset to classify patient outcomes.

---

## Project Tasks

###  Task 1: AI-Powered Code Completion

- Wrote a Python function to sort a list of dictionaries by a given key.
- Compared manual implementation with AI-suggested version (e.g., from GitHub Copilot).
- Analysis showed both were functional, but AI-suggested code included better error handling using `.get()`.

###  Task 2: Automated Testing with Selenium

- Used Selenium WebDriver to simulate user login functionality.
- Tested valid and invalid credentials.
- Captured success and failure rates.
- AI tools can expand test coverage and improve maintainability.

###  Task 3: Predictive Analytics for Resource Allocation

- Dataset: Breast Cancer Wisconsin (Diagnostic) Data Set from `sklearn.datasets`.
- Model: Random Forest Classifier.
- Metrics used: Accuracy and F1-score.
- Achieved high accuracy and identified key influencing features.

---

## Tools & Libraries

- Python 3
- GitHub Copilot (for AI code suggestions)
- Selenium WebDriver (for UI automation)
- Scikit-learn (for ML modeling)
- Jupyter Notebook / Google Colab

---




## How to Run

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/AI-Software-Engineering.git
   cd AI-Software-Engineering
   
2. **Install Required Libraries**
   ```bash
        pip install selenium scikit-learn pandas numpy
   
3. **Run the Notebook**

Open AI_Software_Engineering_Assignment.ipynb using Jupyter or upload to Google Colab.
Make sure you have ChromeDriver installed for Selenium tests.

**Ethical Reflection**
- **Bias:** Training data like medical datasets can reflect real-world inequalities (e.g., underrepresentation of certain groups).

- **Mitigation:** Tools like IBM Fairness 360 can assess and reduce bias.

- **Security:** Selenium automation should avoid storing sensitive login credentials in plain text.

  


