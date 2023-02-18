/* package codechef; // don't place package name! */

import java.util.*;
import java.lang.*;
import java.io.*;

/* Name of the class has to be "Main" only if the class is public. */
class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
	    Scanner sc=new Scanner(System.in);
	    int t;
	    t=sc.nextInt();
	    while(t-->0){
	        int a,b;
	        a=sc.nextInt();
	        b=sc.nextInt();
	         int d=0;
	        for(int i=1;i<=10;i++){
	           d=a+b+i;
	            if(d==21) { System.out.println(i); break;}
	           }
	           if(d!=21) System.out.println(-1);   
	        
	        	    }
		// your code goes here
	}
}