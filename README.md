import java.util.*;

public class Main
{
   public static void main(String[] args)
   {
    int num1 = 0;
    int num2 = 0;
    char operator;
    double answer=0.0;
    Scanner scanObject = new Scanner(System.in);
    System.out.println("Please enter first number: ");
    num1 = scanObject.nextInt();
    System.out.println("Please enter second number: ")
    num2 = scanObject.nextInt();
    System.out.println("What operation");
    operator = scanObject.next().charAt(0);
    switch(operator)  {
    
        case '+': answer = num1 + num2;
                  break;
        case '-': answer = num1 - num2;
                  break;
        case '*': answer = num1 * num2;
                  break;
        case '/': answer = num1 / num2;
                  break;
      }
      System.out.println(num1+" "+operator+" "+num2+" = "+answer);
    }
 }
 
 Output:
 Please enter first number:
 3
 Please enter second number:
 5
 What operation
 +
 3 + 5 = 8.0
