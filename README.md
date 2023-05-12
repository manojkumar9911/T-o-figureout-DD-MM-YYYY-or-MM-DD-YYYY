# T-o-figureout-DD-MM-YYYY-or-MM-DD-YYYY

CODE FOR TO FIGURE OUT WHETHER IT IS DD/MM/YYYY OR MM/DD/YYYY IS:



import java.util.*;
import java.lang.*;
import java.io.*;
class Codechef
{

	public static void main (String[] args) throws java.lang.Exception
	
	{
	
		// your code goes here
		
		Scanner sc=new Scanner(System.in);
		int t=sc.nextInt();
		//creating a string.
		String s =new String();
		
		while(t-->0){
		    s=sc.next();
		    //to convert a string to an integer.
		    
		    int m=Integer.parseInt(s.substring(0,2));
		    int n=Integer.parseInt(s.substring(3,5));
		    
		    if(m>12){
		    System.out.println("DD/MM/YYYY");
		     }
		     
		     else if(n>12){
		         System.out.println("MM/DD/YYYY");
		     }
		     
		     else
		     System.out.println("BOTH");
		    
		}
	}
}
