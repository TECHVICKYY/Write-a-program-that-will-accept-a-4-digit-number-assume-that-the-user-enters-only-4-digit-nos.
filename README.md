# Write-a-program-that-will-accept-a-4-digit-number-assume-that-the-user-enters-only-4-digit-nos.
import java.util.*;
import java.util.Scanner;
public class A1_Ex4 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		Scanner sc =new Scanner(System.in);
		int n= sc.nextInt(),num, sum=0;;
		while(n>0) {
		num = n%10;
		sum = sum+num;
		n = n/10;
		}
		System.out.println("Sum of Entered number is "+sum);
		}
	}
