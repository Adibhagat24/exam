# exam
jai shree ram
radhe radhe









1.	Test cases for addition program.

package practicejunit;
	
public class exp1 {
      public int add(int a,int b) {
    	  return a+b;
      }
    	 
}
	



2.	Test case for Palindrome
    
     		package practicejunit;

public class exp2 {
       public int palindrome(int a) {
    	   int r,sum=0;
    	   while (a>0) {
    		   r=a%10;
    		   sum=(sum*10)+r;
    		   a=a/10;
    	   }
    	   return sum;
       }
}

}



3.	Test Case for prime or not.


 	    package practicejunit;

public class exp3 {
      public boolean primeOrNot(int num) {
    	  int i=2;
    	  boolean sum=false;
    	  while(i<=num/2) {
    		  if(num % i == 0) 
    			  sum=false; 			  
    		  else
    			  sum = true;
    	  }
    	  return sum;
    }
}
