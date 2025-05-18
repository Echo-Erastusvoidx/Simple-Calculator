# Simple-Calculator

## This is the code

import java.util.Scanner;

public class Calculator{
    public static void main(String[] args){

        Scanner scanner=new scanner(System.in);
        
        System.out.println("Enter first num");
        int num1=sc.nextInt();

        System.out.println("Enter second num");
        int num2=sc.nextInt();

        int sum=num1+num2;
        System.out.println("The total is :" + sum);

        //Basically this is to avoid the system from crashing & We're closing the scanner
        sc.close();
    }
}
