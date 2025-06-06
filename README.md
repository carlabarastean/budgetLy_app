# BudgetLy


![platform](https://img.shields.io/badge/platform-Web%20App-blue)
![stack](https://img.shields.io/badge/stack-React%2FNode%2FMongoDB-purple)

**BudgetLy** is a collaborative finance management web application that helps users track expenses, set budgets, and analyze financial habits. Developed as a team project, the app offers a modern and intuitive user interface backed by a full-stack implementation.

---

## Features

- Dashboard overview with financial summaries  
- Add and manage income and expenses  
- Categorized transaction tracking  
- Monthly financial summary and chart visualization  
- Friends module for shared expenses and reminders  
- Interface customization (theme, currency, chart visibility)  

---

## Tech Stack

- **Frontend**: React.js  
- **Backend**: Node.js with Express  
- **Database**: MongoDB 
 
---

## Preview

### Landing Page

Initial landing section, displaying promotional content and app statistics.

<img src="./images/landing-dashboard-preview.png" width="900" alt="Landing page" />

---

### Personalized Dashboard

Financial overview with key metrics like net flow, upcoming payments, and category-based spendings.

<img src="./images/personalized-overview-dashboard.png" width="900" alt="Overview dashboard" />

---

### Income & Expense Summary

Central section where users can manage income, expenses, and visualize their monthly balance.

<img src="./images/expenses-income-summary.png" width="900" alt="Expenses and income summary" />

---

### Adding Transactions

Below is the process for logging new transactions, showing the modal for type selection, income form, and category dropdown:

<table align="center">
  <tr>
    <td><img src="./images/select-transaction-type.png" alt="Select transaction type" height="250"></td>
    <td><img src="./images/add-income.png" alt="Add income form" height="250"></td>
    <td><img src="./images/income-category.png" alt="Income category dropdown" height="250"></td>
  </tr>
</table>


---

### Friends & Payments

View and manage debts between friends, including reminder options and payment history.

<img src="./images/friends-payments-module.png" width="900" alt="Friends module" />

---

### Interface Settings

Users can customize the app by switching themes, currencies, or enabling/disabling charts.

<img src="./images/interface-settings-panel.png" width="900" alt="Settings panel" />

---

## Setup

1. Clone the repository:  
   ```bash
   git clone https://github.com/carlabarastean/BudgetLy_app.git
   ```
2. Navigate to the actual project directory:
   ```bash
   cd II_PROIECT/iiProject
   ```
   
3. Install dependencies:  
   ```bash
   cd client
   npm install

   cd ../server
   npm install
   ```

4. Start development:  
   Backend:  
   ```bash
   npm start dev
   ```  
   Frontend:  
   ```bash
   cd ../client
   npm start
   ```

---

## Future Improvements

We’d love to take **BudgetLy** even further with:

- **Export options** — Let users download their transaction history as CSV or PDF for offline use or reporting.
- **Smart reminders** — Add customizable notifications for budget limits or upcoming due dates.
- **AI-powered insights**:  
  - **Spending predictions & saving suggestions** – Help users better plan by estimating future expenses and potential savings.  
  - **Automatic transaction categorization** – Use an AI model trained on transaction descriptions to sort spending into relevant categories (groceries, utilities, entertainment, etc.).  
  - **Anomaly detection & subscription tracking** – Flag unusual transactions or forgotten subscriptions (like a streaming service unused for months), and suggest possible actions.



   ---
## Contact

For more details or collaboration:
- Email: carlabarastean@gmail.com
- LinkedIn: [linkedin.com/in/carla-barastean-621326269](https://www.linkedin.com/in/carla-barastean-621326269)

Thank you for visiting this project!
