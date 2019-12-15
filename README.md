# Positive-or-negative
# Java program to check whether the number is positive or negative
#                  Practical no:1a
import java.io.*;
import java.util.*;
class number
{
public static void main(String args[])
  {
int n;
Scanner sc=new Scanner(System.in);
System.out.println("Enter number:");
n=sc.nextInt();
if(n>0)
{
System.out.println(n+"  is positve");
}
else if(n<0)
{
System.out.println(n+" is negative");
}
else
{
System.out.println(n+" no is zero");
}
  }
}
