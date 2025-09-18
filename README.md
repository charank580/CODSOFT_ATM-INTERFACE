# CODSOFT_ATM-INTERFACE

COMPANY: CODSOFT

NAME: KEMIDI SRI CHARAN

INTERN ID: :BY25RY220708

DOMAIN: JAVA PROGRAMMING

DURATION: 4 WEEKS

# DESCRIPTION: 
The given Java program is a simple ATM Interface simulation that demonstrates the fundamental concepts of object-oriented programming such as classes, objects, encapsulation, and methods. The main objective of this program is to allow a user to interact with a virtual ATM system where they can check their balance, deposit money, withdraw money, or exit the session. It mimics the basic real-world operations of an ATM machine while also handling common conditions like invalid input and insufficient balance.

The program is divided into three main classes: BankAccount, ATM, and ATMInterface. Each class plays a unique role. The BankAccount class is responsible for maintaining and managing the user’s bank balance. It contains methods for depositing money, withdrawing money, and checking the current balance. The constructor of this class initializes the account balance with an amount provided when creating the object. If a negative value is given, the balance is automatically set to zero. The deposit method ensures that only positive amounts can be added, and the withdraw method checks for sufficient funds before allowing the transaction. If the requested withdrawal amount exceeds the available balance, the program informs the user about insufficient funds. This ensures that the system behaves like a real ATM.

The ATM class acts as an interface between the user and the bank account. It contains the menu system and transaction logic. The displayMenu method shows the options available to the user, such as checking balance, depositing, withdrawing, or exiting. The performTransaction method takes the user’s choice as input and executes the appropriate action. For deposits and withdrawals, it asks the user to enter the desired amount and then calls the corresponding methods from the BankAccount class. By keeping these methods private (checkBalance, deposit, and withdraw), the program ensures that all interactions go through the ATM interface instead of directly modifying the account balance, which demonstrates encapsulation.

The ATMInterface class contains the main method, which is the entry point of the program. It creates a BankAccount object with an initial balance of 1000 rupees and then passes it to the ATM object. Using a do-while loop, the program keeps showing the menu to the user until they select the exit option. This design makes the program interactive and allows multiple transactions in a single session. The scanner is used to read input from the user at each step, making the system dynamic.

To use the program, the user simply runs it in a Java-supported environment. They will first see the ATM menu and can choose any option by entering the corresponding number. For example, selecting option 1 will display the current balance, option 2 will allow a deposit after entering an amount, and option 3 will attempt a withdrawal. If the user chooses option 4, the program terminates with a thank-you message.

Overall, this ATM simulation provides a practical example of Java programming concepts. It shows how classes and objects can work together to model real-world systems. It also highlights the importance of input validation, user interaction, and error handling. This makes it not only a useful project for beginners but also a stepping stone to understanding larger and more complex software systems.

# OUTPUT:


