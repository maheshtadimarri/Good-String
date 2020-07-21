import java.util.*;
import java.io.*;
import java.lang.Math;
class GoodStringHackerEarth
{
    static int good(String s,int len)
	    {
	    	 int c=len;
	         double m=len/2;
	         int k=(int)Math.ceil(m);
	         
	         for(int i=0;i<k;i++)
	         {
	             if(c<=i)
	             {
	                 break;
	            }
	             for(int j=len-1;j>i;j--)
	             {
	                 if(s.charAt(i)==s.charAt(j))
	                 {
	                     int c1=len-j-1+i;
	                     if(c>c1)
	                     {
	                         c=c1;
	                     }
	                     break;
	                 }
	             }
	         }
	         if(c==len)
	         {
	        	 return -1;
	         }
	         else
	         {
	        	 return c;
	         }
	    }

	    public static void main(String args[])
	    {
	        Scanner in=new Scanner(System.in);
	        int n=in.nextInt();
	        for(int i=0;i<n;i++)
	        {
	        	String s=in.next(); 
	        	int len=s.length();
	        	int k=good(s,len);
	        	System.out.println(k);
	        }
	   
	    }
	}
