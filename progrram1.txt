import java.util.Scanner;
class Progrram1
{
	public static void main(String[] args) 
	{
	   int number;
	   System.out.println("enter any  number");
	   Scanner sc = new Scanner(System.in);
	   number=sc.nextInt();
	   if (number>0) 
	   {
	   	System.out.println(number+"is possitive number");	
	   }
	   else if (number==0) 
	   {
	   	System.out.println(number+"is niether +ve nor -ve number");
	   }
	   else
	   {
	   	System.out.println(number+"is Negative number");
	   }	
	}
}