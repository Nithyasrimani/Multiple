# Multiple
/*
 * Prompt user for 2 integers and check if 1st is a multiple of the 2nd
 */
import java.util.Scanner;  // For keyboard input

public class Multiple {   // Save as Add2Integer.java
   public static void main (String[] args) {
      // Declare variables
      int number1, number2;
      Scanner in = new Scanner(System.in);  // Scan the keyboard
      
      // Put up prompting messages and read inputs
      System.out.print("Enter 1st integer: ");  // prompting message
      number1 = in.nextInt();  // read integer
      System.out.print("Enter 2nd integer: ");
      number2 = in.nextInt();
      
      // Compute sum
      if (number1 % number2 == 0) {
         System.out.printf ("%d IS a multiple of %d", +number1, +number2);
      }
      else {
         System.out.printf ("%d IS NOT a multiple of %d", +number1, +number2);
      }
      
   }
}
