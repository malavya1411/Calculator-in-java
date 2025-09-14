# Calculator in Java
Code to perfom basic calculations from operations decided by user

```java
import java.util.Scanner;
class calculator
{
   public static void main(String[]args)
{
   Scanner sc = new Scanner(System.in);
   
   int o;
   float a,b,c,d,e,f;
   System.out.println("For Addition input 1");
   System.out.println("For Substraction input 2");
   System.out.println("For Multiplication input 3");
   System.out.println("For Division input 4");
   
   System.out.print("Enter first number:");
   a=sc.nextInt();
   System.out.print("Enter second number:");
   b=sc.nextInt();
   
   System.out.print("Enter Operation to perform:");
   o=sc.nextInt();

   c=a+b;
   d=a-b;
   e=a*b;
   f=a/b;

   if(o==1) {
    System.out.println("Addition of two numbers is:"+c);}
   else 
    if(o==2)  
       System.out.println("Substraction of two numbers is :"+d);
   else 
    if(o==3)  
       System.out.println("Multiplication of two numbers is :"+e);
   else 
    if(o==4)  
       System.out.println("Division of two numbers is :"+f);    

    else
        System.out.println("Invalid Operation");

   
}
}
