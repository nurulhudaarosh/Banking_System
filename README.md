# 🏦 Banking System

A **console-based Banking System** built in **C** using **ncurses** library.  
It simulates a simple banking application with a user-friendly interface for managing accounts and transactions.

---

## ✨ Features
- 📝 Create a new bank account  
- 💰 Deposit money into an account  
- 💸 Withdraw money from an account  
- 📜 Check account balance  
- 🧾 Transaction history  
- ❌ Input validation (e.g., invalid account numbers, negative amounts)  
- 🎨 Console-based UI with **ncurses**

---

## 🛠️ Tech Stack
- **Language:** C  
- **Library:** ncurses (for interactive console UI)  
- **Paradigm:** Procedural Programming  

---

## 📂 Project Structure
```bash
Banking_System/
├── main.c          # Entry point and main menu
├── banking.h       # Header file with function prototypes
├── banking.c       # Core functions implementation
├── accounts.dat    # Data file storing accounts (generated after running)
└── README.md       # Project documentation
```
---

## 🚀 Getting Started

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/nurulhudaarosh/Banking_System.git
cd Banking_System
```

2️⃣ Install ncurses (if not installed)

# For Debian/Ubuntu
```bash
sudo apt-get install libncurses5-dev libncursesw5-dev
```
3️⃣ Compile the Code
```bash
gcc main.c banking.c -lncurses -o banking_system
```
4️⃣ Run the Program
```bash
./banking_system
```

⸻

🖥️ Example Usage
```bash
==========================
 Welcome to Banking System
==========================

1. Create Account
2. Deposit Money
3. Withdraw Money
4. Check Balance
5. Transaction History
6. Exit

Enter your choice: 1

Enter account number: 1001
Enter name: Arosh
Enter initial deposit: 5000
✅ Account created successfully!
```

⸻

📚 Concepts Used
	•	Procedural programming in C
	•	File handling for account storage
	•	Input validation and error handling
	•	Interactive console UI using ncurses

⸻

🚀 Future Improvements
	•	Password-protected accounts
	•	Transfer between accounts
	•	GUI version using C or Python
	•	Export transactions to CSV

⸻

🤝 Contributing

Contributions are welcome! Feel free to fork this repo and submit a pull request.

⸻

📧 Contact

Author: MD. Nurul Huda Arosh
📩 Email: nurulhuda5801@gmail.com
🌐 GitHub: nurulhudaarosh

---
