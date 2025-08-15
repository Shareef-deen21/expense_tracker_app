# 💰 Expense Tracker

A simple and intuitive web-based expense tracker application built with HTML, CSS, and JavaScript. Track your income and expenses, monitor your balance, and manage your transaction history all in one place.

## 🌟 Features

- **Add Transactions**: Easily add income and expense transactions
- **Real-time Balance Calculation**: Automatically calculates and displays your current balance
- **Income & Expense Tracking**: Separate tracking for income and expenses with individual totals
- **Transaction History**: Complete history of all transactions with the ability to delete entries
- **Dynamic Updates**: Balance and totals update automatically when transactions are added or deleted
- **User-friendly Interface**: Clean and intuitive design for easy navigation

## 🚀 How to Use

### Adding Transactions

1. **Enter Transaction Name**: Type a description for your transaction in the "Transaction Name" field
2. **Enter Amount**: 
   - For **Income**: Simply enter the positive amount (e.g., `1000`)
   - For **Expenses**: Add a minus sign before the amount (e.g., `-500`)
3. **Click "Add Transaction"**: The transaction will be processed and added to your records

### Understanding the Dashboard

- **Balance Section**: Shows your current total balance (Income - Expenses)
- **Income Section**: Displays total income amount
- **Expense Section**: Shows total expense amount
- **History Section**: Lists all transactions with options to delete individual entries

### Managing Transactions

- **View History**: All transactions appear in the history section with transaction name and amount
- **Delete Transactions**: Click the delete button next to any transaction to remove it
- **Automatic Updates**: When you delete a transaction, the income, expense, and balance amounts automatically adjust

## 🛠️ Technologies Used

- **HTML**: Structure and layout
- **CSS**: Styling and responsive design
- **JavaScript**: Interactive functionality and dynamic updates

## 📁 File Structure

```
expense-tracker/
│
├── index.html          # Main HTML file
├── styles.css          # CSS styling
├── script.js           # JavaScript functionality
└── README.md          # This file
```

## 🔧 Installation & Setup

1. **Clone the repository**:
   ```bash
   git clone (https://github.com/Shareef-deen21/expense_tracker_app)
   ```

2. **Navigate to the project directory**:
   ```bash
   cd expense-tracker
   ```

3. **Open in browser**:
   Simply open `index.html` in your preferred web browser, or use a local server:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js (if you have http-server installed)
   npx http-server
   ```

4. **Start tracking**: Begin adding your income and expenses!

## 💡 Usage Examples

### Adding Income
- Transaction Name: "Salary"
- Amount: `3000`
- Result: Adds $3000 to income and balance

### Adding Expense
- Transaction Name: "Groceries"
- Amount: `-150`
- Result: Adds $150 to expenses and deducts from balance

## 🎯 Future Enhancements

- [ ] Data persistence (localStorage/database)
- [ ] Category-based filtering
- [ ] Date-wise transaction tracking
- [ ] Export functionality (CSV/PDF)
- [ ] Charts and visual analytics
- [ ] Mobile app version
- [ ] User authentication
- [ ] Budget planning features

## 📞 Contact

- **Developer:** [Shareef Deen]
- **GitHub:** [Shareef-deen21](https://github.com/Shareef-deen21?tab=repositories)
- **LinkedIn:** [Shareef Deen](https://lk.linkedin.com/in/shareef-deen-69480331a)

## ⭐ Show Your Support

If you found this project helpful, please give it a star! ⭐

---

**Happy Tracking! 💰📊**
