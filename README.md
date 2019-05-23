#group assignment 1 done by rohit

package test1package;
import java.util.Scanner;

public class testclass {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
// question 1
		System.out.println("hello");
		System.out.println("Alexandra Abramov");
		
   Scanner s = new Scanner (System.in);
   int a,b,Testdata;
  
   System.out.println("enter the value of a" );
   a = s.nextInt();
   System.out.println("enter value of b");
   b = s.nextInt();
   Testdata = a+b;
   System.out.println("sum of a and b =" +Testdata);
   
  //program to divide two numbers and print on the screen
   
  System.out.println("to divide two numbers a and b");
  System.out.println("eneter value of a");
  a = s.nextInt();
  System.out.println("enter value of b");
  b = s.nextInt();
  Testdata = a/b;
  System.out.println("division of a and b =" +Testdata);
   
   //Java program to print the result
  
  System.out.println("Java program to print the result of the following operations");
  System.out.println("-5+8*6 =" +(-5+8*6));
  System.out.println("(55+9) % 9  =" +((55+9) % 9));
  System.out.println("20 + -3*5 / 8  =" +((20 - 3*5/8)));
  System.out.println("5 + 15 / 3 * 2 - 8 % 3  =" +(5 + 15 / 3 * 2 - 8 % 3));
  
  
 //Java program that takes two numbers as input and display the product of two numbers.  

  System.out.println("Java program that takes two numbers as input and display the product of two numbers");
  
  System.out.println("enter the value of a=" );
  a = s.nextInt();
  System.out.println("enter value of b");
  b = s.nextInt();
  System.out.println("product of a and b=" +(a*b));
  
  //Java program to print the sum (addition), multiply, subtract, divide and remainder of two numbers
  System.out.println("to print sum,multiply,subtract,divide,remainder");
  System.out.println("enter the value of a=" );
  a = s.nextInt();
  System.out.println("enter value of b");
  b = s.nextInt();
  System.out.println("sum is = "+(a+b));
  System.out.println("subtraction is = "+(a-b));
  System.out.println("multiplication is = "+(a*b));
  System.out.println("division is = "+(a/b));
  System.out.println("modulus is = "+(a%b));
  
  //program that takes a number as input and prints its multiplication table upto 10
  
  System.out.println("program that takes a number as input and prints its multiplication table upto 10");
  
  System.out.println("enter the value of a=" );
  a = s.nextInt();
  for (int a1=1;a1<=10;a1++)
  {
	  System.out.println(a+"*"+a1+"=" +(a*a1));  
	  
  }
  
  //Java program to compute the specified expressions 
  System.out.println("Java program to compute the specified expressions and print the output");
  System.out.println("((25.5*3.5-3.5*3.5)/(40.5-4.5))="+(((25.5*3.5-3.5*3.5)/(40.5-4.5))));
  
  //Write a Java program to compute a specified formula
  System.out.println("Java program to compute a specified formula");
  System.out.println("4.0*(1-(1.0/3)+(1.0/5)-(1.0/7)+(1.0/9)-(1.0/11)) ="+(4.0*(1-(1.0/3)+(1.0/5)-(1.0/7)+(1.0/9)-(1.0/11))) );
  
  
	}

	
}
