# CognoRise-Infotech
intership task
Task 1
import java.util.Scanner;

public class Calculator3 {
	public static void main(String[] args) {
		Scanner sc=new Scanner(System.in);
	 int k=0;
    System.out.println("1 for addition");
    System.out.println("2 for Subtraction");
    System.out.println("3 for multiplication");
    System.out.println("4 for division");
    System.out.println();
    System.out.println("enter your choice");
    k=sc.nextInt();
	         switch(k) {  
	         case 1:System.out.println("Addition");
	         		System.out.println("enter any two numbers");
	         		int a=sc.nextInt();
	         		int b=sc.nextInt();
	         		int sum=0;
	         		sum=a+b;
	         		System.out.println("Addition of "+a+" and "+b+" is "+sum);   
	         		break;
	         case 2:System.out.println("substraction");
      				System.out.println("enter any two numbers");
	         		int a1=sc.nextInt();
	         		int b1=sc.nextInt();
	         		int sub=0;
	         		sub=a1-b1;
	         		System.out.println("Subtraction of "+a1+" and "+b1+" is "+sub);   
	         		break;
	         case 3:System.out.println("multiplication");
      				System.out.println("enter any two numbers");
	         		int a2=sc.nextInt();
	         		int b2=sc.nextInt();
	         		int p=0;
	         		p=a2*b2;
	         		System.out.println("Product of "+a2+" and "+b2+" is "+p);   
	         		break;
	         case 4:System.out.println("division");
      				System.out.println("enter dividend ");
	         		int a3=sc.nextInt();
	         		System.out.println("enter divisor");
	         		int b3=sc.nextInt();
	         		int q=0;
	         		try {
	         		q=a3/b3;
	         		System.out.println("Division of "+a3+" by "+b3+" is "+q);   

	         		}
	 
	         		catch(ArithmeticException ae) {
	         			System.out.println(" divisor is zero please enter a valid number other than 0");
	         			
	         		}  
	         		break;
	         default:System.out.println("Invalid choice");
	}
}
}

