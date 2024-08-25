package Assignment_1;

public class Bank {
    String accountType;
    double accountBalance;
    // Parameterized constructor
    public Bank(String accountType, double accountBalance) {
        this.accountType = accountType;
        this.accountBalance = accountBalance;
   }
    // Method to deposit money
    public double deposit(double amount) {
        this.accountBalance += amount;
        return accountBalance;
   }
    // Method to withdraw money
    public double withdrawal(double amount) {
        if (amount > this.accountBalance) {
            System.out.println("Insufficient funds.");
            return 0;
        }
        this.accountBalance -= amount;
        return amount;
   }
    public void display() {
        System.out.println("The account type is " + accountType + " and the balance is " + accountBalance);
    }
}


