# parameterized-constructor
Using System;
namespace CSharp_Shell
{
  Public class Program 
   {
  Int r;
  String n;
  Program(int rollno,string name)
     {
             r=rollno;
             n=name;
           Console.WriteLine(r+”\t“+n);
      }
      Program()
      {
       Console.WriteLine(“Constructor called”);
      }
     Public static void Main(string [] args)
  {
	Program p=new Program();
         Program p1=new Program(107,”harshali”);
	}
      }
 }

