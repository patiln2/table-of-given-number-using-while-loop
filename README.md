using System;
using System.IO;
using System.Linq;
using System.Collections.Generic;
public class printWorld
{
	public static void Main()
	{
		int i=1;
	int n;
	Console.WriteLine("enter a number");
	n=Convert.ToInt32(Console.ReadLine());
	Console.WriteLine("table of given number");
	while(i<=10)
	{
		Console.WriteLine(n*i);
		i++;
	}
	}
}
