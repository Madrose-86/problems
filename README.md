# problems-

import java.util.Scanner;

public class practise{

    public static void main(String[] arg){
    
        Scanner sc = new Scanner(System.in);
        
        System.out.println("first number:");
        double a = sc.nextDouble();
        
        System.out.println("Second number:");
        double b = sc.nextDouble();
        
        System.out.println("third number: ");
        double c = sc.nextDouble();

        if (a>b && a>c){
            System.out.println("greatest number is:" + a);
        }
        else if (b>a && b>c){
            System.out.println("greatest number is:" + b);
        }
        else{
            System.out.println("greatest number is:" + c);
        }
    }

    }
