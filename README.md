# bankingsystem
online banking system

 
# Bank Management System

> *Banking Management System is a web-based application built using JavaScript (React for frontend), Python (FastAPI for backend), and Supabase (PostgreSQL) for database management. The system allows customer registration, account management, transactions, loan applications, and an admin dashboard for overseeing banking operations.*

#### Group Name
```return sleep;```

#### Group No
```P36```

## GROUP MEMBERS

NAME | ROLE | GITHUB
:---------------------------- | ----------------------- | ---------------------------
*[Krishna Kumar Dey](https://github.com/ogwusearch)* | Backend API development, Database design | [GitHub](https://github.com/ogwusearch)
*[Vishakha Khurangale](https://github.com/vile)* | UI/UX design, Frontend integration | [GitHub](https://github.com/visle)
*[Dharani Devi Akurathi](https://github.comi0607)* | Transaction management, API security | [GitHub](https://github.com/D07)
*[Preethi Hena](https://github.com/phena)* | Account deletion, history management | [GitHub](https://github.com/pena)

## Technology Stack

- **Frontend:** React.js
- **Backend:** FastAPI (Python)
- **Database:** Supabase (PostgreSQL)
- **Authentication:** JWT
- **Security:** HTTPS, data encryption
- **Admin Panel:** React.js with role-based access control

## Features

### **1. Customer Registration**
- Unique account number generation
- Secure password hashing
- Email & mobile number verification
- Address validation using external API

### **2. Account Management**
- Update username, password, email, and phone number
- Check account balance and transaction history

### **3. Transactions**
- Deposit, withdrawal, and fund transfers
- Transaction history stored in Supabase
- Secure authentication before processing transactions

### **4. Loan Management**
- Apply for loans
- Admin approval system
- Track loan repayment status

### **5. Admin Dashboard**
- View all customer accounts
- Approve or reject loans
- Generate reports and analytics

## Installation & Setup

### Clone the Repository
```sh
git clone https://github.com//Bank-Management-System.git
cd Bank-Management-System
```

### **Backend Setup (FastAPI)**
```sh
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
pip install -r requirements.txt
uvicorn main:app --reload
```

### **Frontend Setup (React.js)**
```sh
npm install
npm start
```

### **Database Setup (Supabase)**
1. Create an account on [Supabase](https://supabase.io/)
2. Create a new project and configure PostgreSQL
3. Update `.env` file with database credentials

## API Endpoints

### **Authentication**
- `POST /register` - Register a new user
- `POST /login` - Authenticate and return JWT token

### **Accounts**
- `GET /account/{id}` - Retrieve account details
- `PUT /account/update` - Update user details

### **Transactions**
- `POST /transaction/deposit` - Deposit money
- `POST /transaction/withdraw` - Withdraw money
- `POST /transaction/transfer` - Transfer funds
- `GET /transaction/history` - View transaction history

### **Loans**
- `POST /loan/apply` - Apply for a loan
- `GET /loan/status/{id}` - Check loan status

### **Admin Controls**
- `GET /admin/users` - View all user accounts
- `POST /admin/approve-loan/{id}` - Approve loan application
- `GET /admin/reports` - Generate analytics

## Security Measures
- Passwords are hashed using bcrypt
- JWT authentication for API access
- HTTPS enforced for secure data transmission
- Role-based access control (RBAC) for admins and users

## Conclusion
This **Bank Management System** is designed to be scalable, secure, and easy to manage. Using **React.js, FastAPI, and Supabase**, the system ensures smooth banking operations with modern web technologies.
```

This Markdown format ensures correct syntax highlighting and readability on GitHub. Let me know if you need any modifications! 🚀
