# Largest-of-three-numbers
## Aim:
To write a C# program to find the largest of three numbers.

## Algorithm:
### Step1: 
Start.
### Step2:
Create a class and declare three variable with integer datatype.
### Step3:
Use if condition to check whether num1 is largest than num2 and num3.
### Step4:
Use elif condition to check whether num2 is largest than num1 and num3.
### Step5:
Use else condition to display that third variable is largest among all the variables.
### Step6:
stop.

## Program:
```c#
using System;
public class Hello
{
    public static void Main()
    {
        int num1, num2, num3;
        Console.Write("Find the largest of three numbers:\n");

        Console.Write("Enter the 1st number :");
        num1 = Convert.ToInt32(Console.ReadLine());
        Console.Write("Enter the 2nd number :");
        num2 = Convert.ToInt32(Console.ReadLine());
        Console.Write("Enter the 3rd number :");
        num3 = Convert.ToInt32(Console.ReadLine());

        if (num1 > num2)
        {
            if (num1 > num3)
            {
                Console.Write("Largest Number is " + num1);

            }
            else
            {
                Console.Write("Largest Number is " + num3);

            }
        }
        else if (num2 > num3)
            Console.Write("Largest Number is ", +num2);

        else
            Console.Write("Largest Number is  " + num3);


    }
}

```
## Output:

![img](https://user-images.githubusercontent.com/75413726/163683685-63812fef-3fb3-4ade-b92e-bdb349a4311f.png)

## Result:
Thus the C# program to find the largest of three numbers is executed successfully.
