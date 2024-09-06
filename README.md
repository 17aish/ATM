# ATM
The ATM (Automated Teller Machine) project is designed to simulate the functionality of a real ATM.The primary goal is to provide basic banking operations like checking account balance, withdrawing money, and depositing funds

**Key Features**
 1. **User Authentication:**
     - **Login:** Users must log in with their account number and PIN.
     - **Session Management:** Handle the user session once they are logged in.

 2. **Account Management:**
     - **Check Balance:** Display the current balance of the user’s account.
     - **Deposit Funds:** Allow users to deposit money into their account.
     - **Withdraw Funds:** Allow users to withdraw money, ensuring they don’t exceed their balance.
     - **Print Receipt:** Optionally print a receipt for each transaction.

 3. **Error Handling:**
     - **Invalid Login:** Handle incorrect account numbers or PINs.
     - **Insufficient Funds:** Handle cases where the user tries to withdraw more than the available balance.
     - **Input Validation:** Ensure that all user inputs are valid and reasonable.

**Enhancements**
Once you have the basic functionality working, you might consider adding more features:
     - **Security Enhancements:** Encrypt PINs and sensitive data.
     - **Transaction History:** Keep a log of transactions.
     - **Multiple Accounts:** Handle multiple accounts for a single user.
     - **Graphical User Interface (GUI):** Create a GUI using Swing or JavaFX.
