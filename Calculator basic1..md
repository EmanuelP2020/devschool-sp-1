mport java.util.Scanner;
public class Calc {


    public static void main(String[] args) {

         int x;
         int y;
	 float rezultat; 	
	
	
         Scanner input=new Scanner(System.in);
         System.out.println("Numar 1");
         x=input.nextInt();
         System.out.println("Numar 2");
         y=input.nextInt();

         System.out.println("Selecteaza  + - / sau *");
         Scanner op=new Scanner(System.in);
         String operation = op.next();

         if (operation.equals("+")){
             System.out.println("Rezultatul este: " + (x+y));
         }
         if (operation.equals("-")){
             System.out.println("Rezultatul este: "+ (x-y));
         }
         if (operation.equals("/")){
             System.out.println("Rezultatul este: "+ (x/y));
         }
         if (operation.equals("*")){
            System.out.println("Rezultatul este: "+ (x*y));
         }
    }

}

