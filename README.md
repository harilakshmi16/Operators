# Operators
Operators

import java.util.Scanner;

public class OperatorsExample {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.print("Enter two numbers: ");
        int a = sc.nextInt();
        int b = sc.nextInt();

        System.out.println("Addition: " + (a + b));
        System.out.println("Subtraction: " + (a - b));
        System.out.println("Multiplication: " + (a * b));
        System.out.println("Division: " + (a / b));
        System.out.println("Modulo: " + (a % b));
    }
}

Output

Enter two numbers: 10 3  
Addition: 13  
Subtraction: 7  
Multiplication: 30  
Division: 3  
Modulo: 1
