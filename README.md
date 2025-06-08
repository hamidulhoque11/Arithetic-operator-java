// Arithetic-operator-java

import java.util.Scanner;
class Main {
    public static void main(String[] args) {
       Scanner sc = new Scanner(System.in);
       
      int numb1,numb2,result;
     
      
      System.out.print("number1 =");
      numb1=sc.nextInt();
       System.out.print("number2 =");
      numb2=sc.nextInt();
      
      //plus
      result=numb1+numb2;
      System.out.println("number1+number2 ="+result);
      
      //minus
     
      result=numb1-numb2;
      System.out.println("number1-number2 ="+result);
      
      //Multipication
      result=numb1*numb2;
      System.out.println("number1*number2 ="+result);
      
      //divition
      result=numb1/numb2;
      System.out.println("number1/number2(Deviation) ="+result);
      
      //reminder
      result=numb1%numb2;
      System.out.println("number1%number2(Reminder) ="+result);
      
    }
}
