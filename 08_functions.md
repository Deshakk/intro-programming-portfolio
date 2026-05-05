# 08. Functions

## 1. Concept
Functions are used as a way to make reading the code easier for the user, or when you see yourself rewriting the same code multiple times and want a shortcut. You would have to define the function at the bottom of your program, and whenever you want to use the function, you would do a function call. There are two types of return types: a function with void, which doesn't return anything, and a function with a data type, which returns the specified value, depending on the data type of the function. You use a void function when you just want to print code, and you use a return type function when you want a value to be returned. The function name is in PascalCaseNotation, meaning each first letter is capitalized, and it must be informative. There could be formal parameters, which are what you need to operate the function.
## 2. Key C# Syntax
### Function Definition
```csharp
return_type FunctionName(/*formal_operators*/) //the formal operator is optional, if none then leave it empty ()
{
	//do smth

	return value;	//must be of the return type
	//if return_type is void, no need for a return
}
double AddTwoNumbers(double num1, double num2)
{
	return num1 + num2; //returns a double
}
```
### Function Call
```csharp
//if the return type is void
FunctionName(); //add the parameters if there are, if none then leave it empty ()

//if the function returns a value
Console.WriteLine(AddTwoNumbers(num1,num2)); //it would print the sum of num1 + num2
```
## 3. Eureka Exercise/Moment
Doing the TicTacToe exercise made me realize how much time it saves me from copy-pasting and how much it improves the readability of the code.
## 4. Common Beginner Mistake
Forgetting to add a return type. having the return type be different from the data type.
## 5. Research References
My notes from class and Assignment 8 - functions on Teams
