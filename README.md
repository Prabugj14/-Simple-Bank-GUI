# 🏦 Simple Bank GUI

A desktop banking application built with Python and Tkinter. This app simulates core banking operations including account creation, secure login, fund transfers, and transaction history tracking.

## ✨ Features

- **Account Management:** Create new accounts with Name, Email, and a secure PIN.
- **Secure Authentication:** User PINs are hashed using SHA-256 before being stored.
- **Banking Operations:**
  - 💰 Deposit funds
  - 💸 Withdraw funds (includes insufficient funds check)
  -  Transfer funds between accounts
- **Transaction History:** View a detailed, chronological log of all account activities.
- **Admin Panel:** A protected admin view to list all registered accounts and their balances.
- **Data Persistence:** All account data and transactions are automatically saved locally in a JSON file (`bank_data.json`).

## ️ Tech Stack

- **Language:** Python
- **GUI Framework:** Tkinter
- **Data Storage:** JSON
- **Security:** Hashlib (SHA-256)

## 🚀 How to Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Prabugj14/Simple-Bank-GUI.git
   cd Simple-Bank-GUI
