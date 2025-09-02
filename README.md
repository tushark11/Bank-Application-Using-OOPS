# Bank-Application-Using-OOPS

This is a console-based Bank Application developed in Java following an Object-Oriented Programming (OOP) approach.
It simulates the basic operations of a banking system, where users can create an account, view details, check balance, deposit money, withdraw money, and update account details.

The project is designed with interfaces, models, service implementation, and controllers to follow a clean architecture and modular design.

✨ Features

📋 Create Account → Register a new user with personal and financial details.

👤 Show Account Details → Retrieve account holder information.

💰 Show Account Balance → Check the available balance in the account.

💳 Withdraw Amount → Withdraw money securely with balance updates.

💵 Deposit Amount → Deposit money into the account and update balance.

📝 Update Account Details → Modify name, address, email, or mobile number.

🚪 Exit → Close the application safely.

🏗️ Project Structure
BankingApplication/
│── src/com/tushar/bankapplication/
│   ├── controller/
│   │   └── BankController.java   # Main controller to run the application
│   ├── model/
│   │   └── Account.java          # Account model (POJO class)
│   ├── service/
│   │   └── RBI.java              # RBI interface (bank contract)
│   └── serviceimpl/
│       └── HDFC.java             # HDFC bank implementation of RBI

⚙️ Technologies Used

Java (JDK 21)

OOP Concepts (Encapsulation, Abstraction, Interfaces)

Eclipse IDE / IntelliJ IDEA (Development environment)

▶️ How to Run

Clone the repository:

git clone https://github.com/your-username/BankingApplication.git


Open the project in Eclipse or IntelliJ IDEA.

Navigate to:

src/com/tushar/bankapplication/controller/BankController.java


Run the main method.

Follow the console menu to interact with the banking system.
