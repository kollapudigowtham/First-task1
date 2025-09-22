# Simple Java Calculator 🧮

This is a basic Java console-based calculator that performs arithmetic operations like addition, subtraction, multiplication, and modulus.

### 💡 Features:
- Takes two integer inputs from the user.
- Accepts an operator (`+`, `-`, `*`, `%`) to perform the calculation.
- Displays the result accordingly.
- Shows an error message if an invalid operator is entered.

### 🛠️ How to Run:
1. Compile the file:
   ```bash
   javac Calculator.java
import java.util.Scanner;
class Calculator {
    public static void main(String args[]){
        Scanner sc=new Scanner(System.in);
        System.out.println("enter first number ");
        int a=sc.nextInt();
        System.out.println("enter second number");
        
        int b=sc.nextInt();
        System.out.println("enter any operator ");
        char op=sc.next().charAt(0);
        switch(op){
            case '+':
                System.out.println(a+b);
                break;
            case '-':
                 System.out.println(a-b);
                 break;
            case '*':
                System.out.println(a*b);
                break;
            case '%':
                System.out.println(a%b);
                break;
            default:
            System.out.println("invalid operator");
        }
    }
}
