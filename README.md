# Hello World

```
using System;

namespace HelloWorld
{
  class Program
  {
    static void Main(string[] args)
    {
      Console.WriteLine("Hello World!");
    }
  }
}
```

Console is a class of the System namespace, which has a WriteLine() method that is used to output/print text. In our example it will output "Hello World!".

# Commenting

- single //
- multiple /\* \*/

# DataType

- int like 1 or -1
- double like 54.44 or -54.44
- char like "A"
- string like "Hello World"
- bool like true or false

Data Type Size Description
int 4 bytes Stores whole numbers from -2,147,483,648 to 2,147,483,647
long 8 bytes Stores whole numbers from -9,223,372,036,854,775,808 to 9,223,372,036,854,775,807
float 4 bytes Stores fractional numbers. Sufficient for storing 6 to 7 decimal digits
double 8 bytes Stores fractional numbers. Sufficient for storing 15 decimal digits
bool 1 bit Stores true or false values
char 2 bytes Stores a single character/letter, surrounded by single quotes
string 2 bytes per character Stores a sequence of characters, surrounded by double quotes

# How to define variable

type variableName = variableValue;

like
string address = "New Delhi, India";

# How to define const to variable

If you don't want others (or yourself) to overwrite existing values, you can add the const keyword in front of the variable type.

const type variableName = variableValue;

like:
const string address = "New Delhi, India";

# Concatenate the string or variable

**by "+"**

Example:

string name = "John";
Console.WriteLine("Hello " + name);

Note: For numeric values, the + character works as a mathematical operator (notice that we use int (integer) variables here):

# Delare Multiple variable

one variable of the same type, use a comma-separated list.
Like: int a=10, b=20, c=300;

or int a,b,c;
a=b=c=100;

# Explicity Cast

Convert.ToBoolean, Convert.ToDouble, Convert.ToString, Convert.ToInt32 (int) and Convert.ToInt64 (long):

```
int myInt = 10;
double myDouble = 5.25;
bool myBool = true;

Console.WriteLine(Convert.ToString(myInt));    // convert int to string
Console.WriteLine(Convert.ToDouble(myInt));    // convert int to double
Console.WriteLine(Convert.ToInt32(myDouble));  // convert double to int
Console.WriteLine(Convert.ToString(myBool));   // convert bool to string
```

or

```
double myDouble = 9.78;
int myInt = (int) myDouble;    // Manual casting: double to int

Console.WriteLine(myDouble);   // Outputs 9.78
Console.WriteLine(myInt);      // Outputs 9
```

# Read from console

You need to use Console.ReadLine()

# Operators

Operator Name Description Example Try it

    +	Addition	Adds together two values	x + y
    -	Subtraction	Subtracts one value from another	x - y
    *	Multiplication	Multiplies two values	x * y
    /	Division	Divides one value by another	x / y
    %	Modulus	Returns the division remainder	x % y
    ++	Increment	Increases the value of a variable by 1	x++
    --	Decrement	Decreases the value of a variable by 1	x--

## Comparison Operator

    Operator	Name	Example	Try it
    ==	Equal to	x == y
    !=	Not equal	x != y
    >	Greater than	x > y
    <	Less than	x < y
    >=	Greater than or equal to	x >= y
    <=	Less than or equal to	x <= y

## Logical Operators

    Operator	Name	Description	Example	Try it
    && 	Logical and	Returns True if both statements are true	x < 5 &&  x < 10
    || 	Logical or	Returns True if one of the statements is true	x < 5 || x < 4
    !	Logical not	Reverse the result, returns False if the result is true	!(x < 5 && x < 10)
