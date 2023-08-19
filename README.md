# Palindrome


## Aim:
To write a C# program to find whether the given string is a Palindrome or not.
## Algorithm:
Step 1:
Create a new Class named palindrom.

Step 2:
Declare three variables of string data type.

input - Store the input from user.
str - Convert user input to lower case and store it.
pal - Reverse the string str and store it.

Step 3:
Get input from the user and store it. Then convert it to lower case.

Step 4:
Using for loop, iterate through the each character from the end to begining and add it to the new variable called pal

Step 5:
Using If-else statement check whether the input string & reversed string are same.

Step 6:
Print the input and reversed string along with the whether palindrom or not.

Step 7:
End of the Program

## Program:

```
NAME:KATHIRVEL.A
REG NO:212221230047
```

```
using System;
class HelloWorld
{
    static void Main()
    {
        string num1, rem, rev = "";
        num1 = Console.ReadLine();
        rem = num1;
        for (int s = num1.Length - 1; s >= 0; s--)
        {
            rev += num1[s];
        }
        Console.WriteLine(rev);
        if (rev == rem)
            Console.WriteLine(rem + ":is a palindrome");
        else
            Console.WriteLine(rem + ":is not a palindrome");

    }
}
```



## Output:



![image](https://github.com/KathirvelAIDS/Palindrome/assets/94911373/3a5386cd-fa38-468f-8270-ff0f6d38d19f)




![image](https://github.com/KathirvelAIDS/Palindrome/assets/94911373/78dbcf03-7e81-4a8b-b7e1-8c674a7915ee)



## Result:
Thus the C# program to display whether the given string is Palindrome or not is executed successfully.
