/**
 * 
 *
 * @author (your Dad)
 * @time(at 2:00 AM)
 */
import java .util.*;
public class hello_World
{
  Scanner sc=new Scanner(System.in);
     public void Print(){
        Scanner sc=new Scanner(System.in);
        System .out.println("\n\t\t\t\t\tHello Noobs!");
        System.out.println("\n\t\t\t\t\tEnter 1 to print Hello_world properly");
        System.out.print("\n\t\t\t\t\tEnter 2 to print on your own risk->");
        int b=sc.nextInt();
    switch(b){
           case 1:System.out.println("\n\t\t\t\t\tHello World");
                  break;
           case 2:System.out.println("\n\t\t\t\t\tSorry man but it was your choice so");
                  System.out.println("\n\t\t\t\t\t\t-------------------------------------");
                  System.out.println("\n\t\t\t\t\tHey you Fuc*er why you pressed this noob you stupid but then to== Hello World");
                  System.out.println("\n\t\t\t\t\t\t-------------------------------------");
                  System.out.println("\n\t\t\t\t\tHey once again sorry it's a joke don't take it serious");
                  System.out.println("\n\t\t\t\t\t\tThese word are not to you readers");
                  break;
           default:System.out.println("\n\t\t\t\t\tuseless  Enter correct number");
                   Print();
        }
    }
  public static void main (String args[]){
    hello_World ob=new hello_World();
    ob.Print();
        }
    }
