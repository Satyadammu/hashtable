# hashtable
import java.util.*; 

public class map1

 { 

   public static void main(String args[]) 

   {

      Hashtable<Integer,Integer> x=new Hashtable<Integer,Integer>(); 

      Scanner sc=new Scanner(System.in); 

      int n; 

      int key; 

      int value; 

      System.out.println("enter n value"); 

      n=sc.nextInt(); 

      for(int i=0;i<n;i++) 

      { 

        key=sc.nextInt(); 

        value=sc.nextInt();

         x.put(key,value);

       } 

          System.out.println(x); 

        System.out.println("Enter the key for search:");

        int key1=sc.nextInt();

        if(x.containsKey(key1))

        {

         x.put(key1,x.get(key1)+5000);

        System.out.println(x);

        }

        else

       System.out.println("false");

     }
}
