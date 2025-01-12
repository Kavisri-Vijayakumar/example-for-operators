import java.util.Scanner;
public class OperatorsExample {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        System.out.print("Enter the first number: ");
        int num1 = scanner.nextInt();
        System.out.print("Enter the second number: ");
        int num2 = scanner.nextInt();
        int sum = num1 + num2;
        int difference = num1 - num2;
        int product = num1 * num2;
        double division = (double) num1 / num2;  // Cast to double to handle decimal values
        int modulus = num1 % num2;
        boolean isEqual = (num1 == num2);
        boolean isGreater = (num1 > num2);
        boolean isLesser = (num1 < num2);
        boolean logicalAnd = (num1 > 0 && num2 > 0);  // True if both numbers are positive
        boolean logicalOr = (num1 > 0 || num2 > 0);   // True if at least one number is positive
        System.out.println("\nArithmetic Operations:");
        System.out.println("Sum: " + sum);
        System.out.println("Difference: " + difference);
        System.out.println("Product: " + product);
        System.out.println("Division: " + division);
        System.out.println("Modulus: " + modulus);
        System.out.println("\nRelational Operations:");
        System.out.println("Are the numbers equal? " + isEqual);
        System.out.println("Is the first number greater than the second? " + isGreater);
        System.out.println("Is the first number less than the second? " + isLesser);
        System.out.println("\nLogical Operations:");
        System.out.println("Both numbers are positive? " + logicalAnd);
        System.out.println("At least one number is positive? " + logicalOr);
        scanner.close();
    }
}
output
Enter the first number: 10
Enter the second number: 5
Arithmetic Operations:
Sum: 15
Difference: 5
Product: 50
Division: 2.0
Modulus: 0
Relational Operations:
Are the numbers equal? false
Is the first number greater than the second? true
Is the first number less than the second? false
Logical Operations:
Both numbers are positive? true
At least one number is positive? true

