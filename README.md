##1.) control statement(if) practice
import java.util.*;
public class Main{
    public static void main(String[]args)
    {
        Scanner sc=new Scanner (System.in);
        int accountnumber=9894;
        System.out.println("WELCOME TO NATIONAL BANK OF INDIA");
        System.out.println("Enter your account number");
        int enterednumber=sc.nextInt();
        if(enterednumber==accountnumber)
        {
            System.out.println("hello jeeva");
            System.out.println("your balance amount is 1000");
            int balance=1000;
            int interestamount;
            interestamount=balance*5/100;
            
            
            System.out.println("your interest amount is "+interestamount);
            System.out.println("your overall amount is "+(balance+=interestamount));
        
            
                System.out.println("congratlation you are eligible for loan");
                }
        else
        {
            System.out.println("enter the pin again");
        }
        
        
        
        sc.close();
    }
}
output:
import java.util.*;
public class Main{
    public static void main(String[]args)
    {
        Scanner sc=new Scanner (System.in);
        int accountnumber=9894;
        System.out.println("WELCOME TO NATIONAL BANK OF INDIA");
        System.out.println("Enter your account number");
        int enterednumber=sc.nextInt();
        if(enterednumber==accountnumber)
        {
            System.out.println("hello jeeva");
            System.out.println("your balance amount is 1000");
            int balance=1000;
            int interestamount;
            interestamount=balance*5/100;
            
            
            System.out.println("your interest amount is "+interestamount);
            System.out.println("your overall amount is "+(balance+=interestamount));
        
            
                System.out.println("congratlation you are eligible for loan");
                }
        else
        {
            System.out.println("enter the pin again");
        }
        
        
        
        sc.close();
    }
}
import java.util.*;
public class Main{
    public static void main(String[]args)
    {
        Scanner sc=new Scanner (System.in);
        int accountnumber=9894;
        System.out.println("WELCOME TO NATIONAL BANK OF INDIA");
        System.out.println("Enter your account number":);
        int enterednumber=sc.nextInt();
        if(enterednumber==accountnumber)
        {
            System.out.println("hello jeeva");
            System.out.println("your balance amount is 1000");
            int balance=1000;
            int interestamount;
            interestamount=balance*5/100;
            
            
            System.out.println("your interest amount is "+interestamount);
            System.out.println("your overall amount is "+(balance+=interestamount));
        
            
                System.out.println("congratlation you are eligible for loan");
                }
        else
        {
            System.out.println("enter the pin again");
        }
        
        
        
        sc.close();
    }
}
output 1:
    WELCOME TO NATIONAL BANK OF INDIA
    Enter your account number:9894
    hello jeeva
    your balance amount is 1000
    your interest amount is 50
    your overall amount is 1050
    congratlation you are eligible for loan
output 2:
        WELCOME TO NATIONAL BANK OF INDIA
         Enter your account number:9893
         enter the pin again
         

    
    
