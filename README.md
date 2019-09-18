# alternate_swap
package june2019;
import java.math.BigInteger;
import java.util.Scanner;
import java.util.*;
public class HelloWorld {
	public static void main(String[] args) {

		int a[]= {1,2,3,4,5,6,7,8,9};// initailizing array.

		int temp;
		
			for(int i=0;i<a.length-1;i=i+2) {
				temp=a[i];
				a[i]=a[i+1];
				a[i+1]=temp;
			}
		
		System.out.println(Arrays.toString(a)); // converts arrays to string

	}
}
