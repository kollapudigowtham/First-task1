# First-task1import java.util.Scanner;
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
