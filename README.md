# Practice-1.14
package second_oneone;

import java.util.Scanner;

public class cashier {
	public static void main(String[] args) {
       Scanner scanner = new Scanner(System.in);
       int a = scanner.nextInt();
       int b = scanner.nextInt();
       char operator = scanner.next().charAt(0);
       int result;
       switch(operator) {
       case '+':
    	   result = a+b;
    	   break;
       case '-':
    	   result = a-b;
    	   break;
       case '*':
    	   result = a*b;
    	   break;
       case '/':
    	   if (b == 0){
    		   System.out.println("Error");
    		   return;
    	   }
    	   break;
    				
    	   }
    		   
    	   }
       }
      
	
	
