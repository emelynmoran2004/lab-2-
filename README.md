public class BudgetCalculator {
 public static final double SALARY = 3000.0;
 public static final double SAVING_PERCENT = 0.20;
 public static final double RENT_PERCENT = 0.30;
 public static final double GROCERIES_PERCENT = 0.15;
 public static final double ENTERTAINMENT_PERCENt = 0.10;
 public static viod main (String [] args) {
     double monthlySalary = SALARY;
     double savedAmount;
     double rentAmount;
     double groceriesAmount;
     double entertainmentAmount;
     double totalExpenses;
     double remainBalance;
      
       savedAmount = monthlySalary* SAVING_PERCENT;
       rentAmount = monthlySalary* RENT_PERCENT;
       groceriesAmount = monthlySalary * GROCERIES_PERCENT;
       entetainmentAmount = monthlySalary * ENTERTAINMENT_PERCENT;

       totalExpenses = rentAmount + groceriesAmount + entertainmentAmount;
        remainingBalance = monthlySalary - totalExpenses;

      System.out.println("=== Monthly Budget Summary ===");
        System.out.println("Monthly Salary: $" + monthlySalary);
        System.out.println("Amount Saved: $" + savedAmount);
        System.out.println("Amount Spent on Rent: $" + rentAmount);
        System.out.println("Amount Spent on Groceries: $" + groceriesAmount);
        System.out.println("Amount Spent on Entertainment: $" + entertainmentAmount);
        System.out.println("Total Expenses: $" + totalExpenses);
        System.out.println("Remaining Balance: $" + remainingBalance);
    }
}
