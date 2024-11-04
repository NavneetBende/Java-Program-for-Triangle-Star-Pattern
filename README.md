Printing Triangle Star Pattern
In this problem we will be coding a Java Program for triangle star pattern which will have n number of stars in it rows and m number of stars in column hence it will be a n x m triangle star pattern. Pattern programming is a basic technique of programming which is followed by young programmers in order to master loops and learn their working.

Java Program for Triangle Star Pattern
Algorithm:
Take the number of rows as input from the user  and store it in any variable.(‘row‘ in this case).
Take the number of colas input from the user  and store it in any variable.(‘col‘ in this case).
Run a loop ‘row’ number of times to iterate through each of the rows. From i=0 to i<row. The loop should be structured as for (int i = 1; i <= row; i++)
 Run a nested loop inside the main loop to print the stars in each row of the triangle. From j=1 to j<=i. The loop should be structured as for (int i = 1; i <= row; i++)
In the nested loop print star System.out.print(“*”);.
In the main loop print a new line System.out.println();.
Code in Java:
import java.util.Scanner;
public class Pattern1 {

	public static void main(String[] args) {
     Scanner sc = new Scanner(System.in);
     System.out.println("Enter row ");
     int row = sc.nextInt();
    
     
     for (int i = 1; i <= row; i++) {
	     for (int j = 1; j <=i ; j++) 
			System.out.print("*");
	     System.out.println();
	 }
  }
}
