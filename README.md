# 🏦 Bank Management System (Online Banking System)

A modern, web-based application for seamless banking operations. Built with **React.js (Frontend)**, **FastAPI (Backend)**, and **Supabase (PostgreSQL Database)**, the system allows user registration, secure transactions, account & loan management, and an admin dashboard.

---

## 👥 Group Information

**Group Name:** `return sleep;`  
**Group No:** P36

| Name                    | Role                                      | GitHub   |
|-------------------------|-------------------------------------------|----------|
| Krishna Kumar Dey       | Backend API development, Database design | [GitHub](#) |
| Vishakha Khurangale     | UI/UX design, Frontend integration       | [GitHub](#) |
| Dharani Devi Akurathi   | Transaction management, API security     | [GitHub](#) |
| Preethi Hena            | Account deletion, history management     | [GitHub](#) |

---

## 🧱 Technology Stack

- **Frontend:** React.js  
- **Backend:** FastAPI (Python)  
- **Database:** Supabase (PostgreSQL)  
- **Authentication:** JWT  
- **Security:** HTTPS, bcrypt password hashing, Role-Based Access Control (RBAC)

---

## 🚀 Features

### 1. 👤 Customer Registration
- Unique account number generation
- Secure password hashing
- Email & mobile number verification
- Address validation using external API

### 2. 🗃️ Account Management
- Update username, password, email, and phone number
- View account balance and transaction history

### 3. 💸 Transactions
- Deposit, withdrawal, and fund transfers
- Transaction history stored in Supabase
- Secure re-authentication before processing

### 4. 🏦 Loan Management
- Customers can apply for loans
- Admin can approve/reject loan requests
- Track repayment status

### 5. 🛡️ Admin Dashboard
- View all customer accounts
- Approve/reject loan requests
- Generate analytics and reports

---

## ⚙️ Installation & Setup

### 🧬 Clone the Repository
```bash
git clone https://github.com/your-org/Bank-Management-System.git
cd Bank-Management-System
```

### 🐍 Backend Setup (FastAPI)
```bash
python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate
pip install -r requirements.txt
uvicorn main:app --reload
```

### ⚛️ Frontend Setup (React.js)
```bash
cd frontend
npm install
npm start
```

### 🛢️ Database Setup (Supabase)
1. Create an account on [Supabase](https://supabase.io)
2. Create a new project
3. Set up your PostgreSQL tables and roles
4. Update `.env` with your database credentials

---

## 📡 API Endpoints

### 🔐 Authentication
- `POST /register` – Register a new user  
- `POST /login` – Authenticate and return JWT token  

### 🧾 Accounts
- `GET /account/{id}` – Retrieve account details  
- `PUT /account/update` – Update account/user details  

### 💰 Transactions
- `POST /transaction/deposit` – Deposit funds  
- `POST /transaction/withdraw` – Withdraw funds  
- `POST /transaction/transfer` – Transfer funds  
- `GET /transaction/history` – Transaction history  

### 🏦 Loans
- `POST /loan/apply` – Apply for a loan  
- `GET /loan/status/{id}` – Check loan application status  

### 🔐 Admin Controls
- `GET /admin/users` – View all user accounts  
- `POST /admin/approve-loan/{id}` – Approve loan application  
- `GET /admin/reports` – Generate analytics/report  

---

## 🔒 Security Measures

- Passwords hashed using **bcrypt**
- JWT-based **token authentication**
- **HTTPS** enforced for all data transmission
- **RBAC** for secure user/admin segregation

---

## ✅ Conclusion

This **Bank Management System** ensures modern digital banking functionality with a focus on **security**, **scalability**, and **usability**. Built with industry-grade tools—**React, FastAPI, Supabase**—it’s designed for real-world applications and academic excellence.

---

## 📄 License

This project is for academic use only. No license currently applied.

---

> 💡 _Want to contribute or report issues? Open a PR or create an issue in this repo._

