# 💰 Expense Tracker CLI

A command‑line interface (CLI) tool for tracking and managing personal expenses.  
This project allows you to add expenses, list them, update or delete records, and view summaries of your spending.

---

## 🚀 Features

- ➕ Add a new expense with a description and amount  
- 📋 List all recorded expenses  
- ✏️ Update or delete an expense by its ID  
- 📊 View a summary of total expenses and optionally by month  
- 💾 Simple data storage and retrieval (e.g., JSON file or database)  
- 🖥️ Easy to use from the terminal  

---

## ⚙️ Getting Started

### ✅ Prerequisites

- Python 3.8 or higher installed on your system  
- Terminal / command‑line access  

---

### 📦 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/nabeelahmad55/expense-tracker-cli.git
   ```

2. **Navigate to the project directory**
   ```bash
   cd expense-tracker-cli
   ```

3. **(Optional) Create a virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

4. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

---

## 🧠 Usage

- **Add an Expense**
  ```bash
  python main.py add "Groceries" 50.75
  ```

- **List All Expenses**
  ```bash
  python main.py list
  ```

- **Update an Expense**
  ```bash
  python main.py update 1 "Dinner" 30.00
  ```

- **Delete an Expense**
  ```bash
  python main.py delete 1
  ```

- **View Summary**
  ```bash
  python main.py summary
  ```

---


## 🤝 Contributing

Contributions are welcome!

1. Fork the repository  
2. Create your feature branch  
   ```bash
   git checkout -b feature/AmazingFeature
   ```
3. Commit your changes  
   ```bash
   git commit -m "Add some feature"
   ```
4. Push to the branch  
   ```bash
   git push origin feature/AmazingFeature
   ```
5. Open a Pull Request  


---

## 📧 Contact

**Developer:** Nabeel Ahmad  
**GitHub:** [nabeelahmad55](https://github.com/nabeelahmad55)  
**Project Link:** [Expense Tracker CLI](https://github.com/nabeelahmad55/expense-tracker-cli)

---

