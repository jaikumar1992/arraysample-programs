# arraysample-programs
sort,copyof,fill,copyofrange etc.

import java.util.Arrays;
 
class arrayex
{
public static void main(String []args)
{	
int []no={1,5,3,6,4,9};
for(int i=0;i<6;i++)
{
System.out.println("numbers or not sorted "+no[i]);
}
int total=0;
for(int i=0;i<6;i++)
{
total =total+ no[i];	
}
System.out.println(total);
}
}
class sortmethod
{
public static void main(String args[])
{
	int [] marks={60,70,55,75,90};
		Arrays.sort(marks);
	for(int mark:marks)

	{
			System.out.println(mark);
	}
			}
}

class fillmethod
{
	public static void main(String[] args)
	{
		String []myname = new String[8];
		Arrays.fill(myname,"jaikumar");
		for(String name:myname)
		{
			System.out.println(name);
		}
	}
}

class compareto
{
	public static void main(String []args)
	{
		String [] sub={"maths","science","social","physics"};
        String [] sub1={"maths","science","social","physics"};
        System.out.println("sub and sub1 are :"+Arrays.deepEquals(sub,sub1));  
		
		String [] sub3={"maths","science","social"};
        System.out.println("sub and sub3 are :"+Arrays.deepEquals(sub,sub3));  
		 
		}
}
class copyofrange
{
	public static void main(String []args)
	{
		int []num={4,3,5,6,8,7,2};
		System.out.println("my numbers are ");
		for(int no:num)
		{
			System.out.println(no);
		}
		int []num1=Arrays.copyOfRange(num,2,5);
		System.out.println("my new numbers are :");
		for(int no:num1)
		{
			System.out.println(no);
		}
	}
}

class copyoff
{
	public static void main(String[] args)
	{
		int[] nums={3,4,2,9,7,8,5};
		System.out.println("my numbers are :"+nums.length);
		int[]newnums=Arrays.copyOf(nums,10);
		System.out.println("new number are :"+newnums.length);
	}
}

class exary
{
	public static void main(String[] args)
	{
		int[] num={5,6,3,8,2};
	
		for(int i=0;i<5;i++)
		{
			System.out.println(num[i]);
		}
int[]jai =	Arrays.copyOfRange(num,0,3);
for(int x=0;x<5;x++){	
System.out.println(jai[2]);}
	}
}
