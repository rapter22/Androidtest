# Androidtest

import java.util.*;   
public class test
{  
   public static void main(String args[])  
   {  
      String original, reverse = ""; 
      Scanner in = new Scanner(System.in);   
      System.out.println("Enter ");  
      original = in.nextLine();   
      int length = original.length();   
      for ( int i = length - 1; i >= 0; i-- )  
         reverse = reverse + original.charAt(i);  
      if (original.equals(reverse))  
         System.out.println("Entered.");  
      else  
         System.out.println("Entered .");   
   }  
}
