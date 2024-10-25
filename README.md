# Expense-tracker

## Overview

Build a React.js web app for effective expense tracking, allowing users to add, edit, and delete expenses by category and date, view expense summaries, and monitor wallet balance in real-time. The app stores data persistently to maintain user information across sessions.

## Features

- **Wallet Balance Management**: Start with a default balance of ₹5000.User can track wallet balance, add funds, and ensure expenses don’t exceed available balance.
- **Expense Management**: Add, edit, and delete expenses. Update wallet balance dynamically based on expense actions.
- **Expense Summary & Trends**: View expenses by category in a pie chart and trends in a bar chart.
- **Persistent Data**: Stores wallet balance and expenses in localStorage.
- **Responsive Design**: Optimized for use on all devices.

## Technologies Used

- **Frontend**: React.js, HTML, CSS, JavaScript
- **Libraries**:
  - [Recharts](https://recharts.org/en-US) for charts
  - [React-Modal](https://reactcommunity.org/react-modal/) for modals
  - [Notistack](https://notistack.com/getting-started) for notifications
  - [React Icons](https://react-icons.github.io/react-icons/) for icons

## Usage

- **Add Balance**: Increase your wallet balance by clicking the "Add Balance" button.<br>
- **Add Expense**: Use the "Add Expense" form to record new expenses with a category and date.<br>
- **Edit Expense**: Modify an expense's details by selecting the "Edit" button.<br>
- **Delete Expense**: Remove an expense by clicking the "Delete" button.<br>
- **View Summary**: Review your categorized expenses with a pie chart.<br>
- **View Trends**: Analyze spending patterns by category using the bar chart.

 ## Installation

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/MayurDange15/EXPENSE-TRACKER.git
   cd EXPENSE-TRACKER
   ```

2. **Install Dependencies**:

   ```bash
   npm install
   ```

3. **Run the Application**:

   ```bash
   npm start
   ```

   This will start the development server, and you can view the application in your browser at `http://localhost:3000`.
   
## Future Enhancements

- **Recurring Expenses**: Set up recurring expenses on a schedule.<br>
- **Expense Filtering**: Enable filtering by date and category.
