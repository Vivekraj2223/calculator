# calculator
//Making a calculator
import java.util.*; 
class Main{
    public static void main (String[] args){
        Scanner sc = new Scanner(System.in);
        System.out.println("enter 1st no. :");
        int a = sc.nextInt();
        System.out.println("enter your operation (+,-,/,*):");
        char opp = sc.next().charAt(0);
        System.out.println("enter 2nd no. :");
        int b = sc.nextInt(); 
        System.out.println("your result is :");
        if (opp=='+'){
             System.out.println(a+b);
        } else if (opp=='-') {
             System.out.println(a-b);
        } else if (opp=='*') {
             System.out.println(a*b);
        } else if (opp=='/') {
             System.out.println(a/b);
        } else {
         System.out.println("invalid");   
        }
    }
}

    











