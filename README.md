# Core-Java
Login Code in Java
/*we have one abstact class it contains two undefined methods then provide 
functionalities for these methods by using concrete class invoke by providing 
dynamic inputs*/
import java.util.*;
abstract class A
{
	abstract void m1(int a);
	abstract int m2(String a);
}
class Abs extends A
{
	static Scanner sc=new Scanner(System.in);
	void m1(int a)
	{	
		System.out.println("hi "+a);
	}	
	int m2(String a)
	{
		System.out.println("hello "+a);
		return 01;
	}
	public static void main(String args[])
	{
		Abs obj=new Abs();
		obj.m1(sc.nextInt());
		obj.m2(sc.next());
	}
}
