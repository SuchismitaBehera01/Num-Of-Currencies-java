# Num-Of-Currencies-java
import java.util.Scanner;
class NumOfCurrencies
{
	public static void main (String[]args)
	{
	Scanner sc=new Scanner(System.in);
	System.out.println("Enter the Amount(multiple of 100)");
	int amt =sc.nextInt();
	if(amt >=2000){
	System.out.println("2000 X"+(amt/2000));
	amt = amt %2000;
	}
	if(amt >=500){
	System.out.println("500 X"+(amt/500));
	amt = amt %500;
	}
	if(amt >=200){
	System.out.println("200 X"+(amt/200));
	amt = amt %200;
	}
	if(amt >=100){
	System.out.println("100 X"+(amt/100));
	amt = amt %100;
	}
   }
}
