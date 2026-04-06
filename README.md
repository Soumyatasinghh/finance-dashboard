# 💰 Finance Dashboard

A clean and interactive **Finance Dashboard** built using **HTML, CSS, and Vanilla JavaScript**.
This project allows users to track financial activity, analyze spending patterns, and manage transactions in a simple, intuitive, and responsive interface.

---

## 🚀 Features

### 📊 Dashboard Overview

* Displays key financial metrics:

  * **Total Balance**
  * **Total Income**
  * **Total Expenses**
* Summary cards for better visual feedback
* **Balance Trend (Line Chart)** for time-based financial analysis
* **Spending Breakdown (Pie Chart)** for category-wise insights

---

### 💳 Transactions Management

* View all transactions with:

  * Date
  * Category
  * Amount
  * Type (Income / Expense)
* Features:

  * 🔍 Search by category, type, or date
  * 🔽 Filter by income or expense
  * 🗑 Delete transactions (Admin only)
* Handles empty or no-data cases gracefully

---

### 🔐 Role-Based UI

* **Viewer**
  * Can only view financial data
   
* **Admin**
  * Can add and delete transactions
* Role switching is implemented via a dropdown (frontend simulation)

---

### 📈 Insights Section

Provides meaningful financial observations:

* Identifies **highest spending category**
* Shows **monthly comparison of expenses**
* Displays **basic spending behavior insights**

---

### 🧠 State Management

Managed using plain JavaScript (no external libraries):

* Transactions data
* Search and filter states
* Selected user role
* Theme (light/dark)

Efficient handling ensures smooth UI updates and data consistency.

---

### 💾 Data Persistence

* Uses **localStorage** to store user data
* Ensures:

  * Data remains after page refresh
  * Admin-added transactions are saved
* Smart data merging:

  * Existing data is preserved
  * New data from code is added without duplication

---

### 🔄 Mock API Integration

* Simulates API calls using asynchronous functions
* Mimics real-world backend interaction
* Helps demonstrate understanding of async data handling

---

### 📤 Export Functionality

* Export transaction data in:

  * **CSV format**
  * **JSON format**
* Useful for reporting and external usage

---

### 🎨 UI / UX

* Clean, minimal, and user-friendly interface
* Smooth animations and transitions
* Fully responsive across:

  * Mobile 📱
  * Tablet 📲
  * Desktop 💻
* Dark mode support 🌙
* Interactive elements with hover and transition effects

---

## 🛠️ Tech Stack

* **HTML5**
* **CSS3 (Plain CSS + Animations)**
* **JavaScript (Vanilla JS)**
* **Chart.js** (for data visualization)

---

## 📂 Project Structure

```plaintext
Finance-Dashboard/
│
├── index.html      # Main structure + JavaScript logic
├── styles.css      # Styling and responsiveness
└── README.md       # Project documentation
```

---

## ⚙️ How to Run

1. Download or clone the project
2. Open `index.html` in any browser

No installation or dependencies required.

---

## 📌 Key Highlights

* Fully frontend-based (no backend required)
* Clean and modular code structure
* Real-world features like:

  * Role-based UI
  * Data persistence
  * Export functionality
  * Data visualization
* Focused on usability, clarity, and performance

---

## 🚀 Future Improvements

* Edit transaction feature
* Backend/API integration
* User authentication system
* Advanced analytics and filters

---

## 👨‍💻 Author

**Soumyata Singh**

---
