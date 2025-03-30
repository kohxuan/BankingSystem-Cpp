# 🏦 Banking System
The **Banking System** is a console-based application designed to manage customer accounts, including savings and checking accounts. This project is implemented in C++ and provides functionalities for deposits, withdrawals, and account statistics.
<br><br>

### ✨ Features
- **Account Management**: Supports both savings and checking accounts with unique features and service charges.
- **Deposits and Withdrawals**: Allows users to deposit and withdraw funds, with specific rules for each account type.
- **Interest Calculation**: Calculates and applies monthly interest to account balances.
- **Service Charges**: Applies service charges based on account activity and type.
- **Account Status**: Manages account status (active/inactive) based on balance thresholds.
- **Monthly Processing**: Resets transaction counts and applies monthly charges and interest.
- **File I/O**: Reads account data from a file and writes updates back to the file.
<br>

### 🛠️ Technical Overview
- **C++**: Utilizes object-oriented programming principles to manage account operations.
- **File Handling**: Uses file input/output to persist account data between sessions.
<br>

### 📁 File Structure
- **BankingSystem.cpp**: Main program file containing the implementation of account operations and user interaction.
- **Customer.txt**: Data file storing account information, including account type, number, balance, interest rate, and transaction counts.
<br>

### 🚀 Getting Started
1. **Compile the Program**: Use a C++ compiler to compile `BankingSystem.cpp`.
2. **Run the Program**: Execute the compiled program to interact with the banking system.
3. **Manage Accounts**: Follow the on-screen prompts to deposit, withdraw, and view account statistics.
4. **Data Persistence**: Account changes are saved to `Customer.txt` for future sessions.
<br>
