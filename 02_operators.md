# 02. Operators

## 1. Concept
There are three different types of operators: arithmetic operators, relational operators and conditional logic operators. Arithmetic Operators are the (+, -, *, /, %), which are used to evaluate to a number or a char. Relational Operators are the (<, <=, >=, >, ==, !=) which are used to evaluate to a boolean value, true or false. and the Conditional Operators are the (&&, ||, !), which are used to evaluate two expressions into a true or false value. The Modulo is a bit unique as it is used to find the remainder (for example, 4%3 = 1 because 4/2 = 2 and there's still a remainder of 1 that can't get divided)
## 2. Key C# Syntax
### Arithmetic Operators
```csharp
x+n //Addition
x++; //post increment -- adds one to x after
++x; //pre increment -- adds one to x before
x+=n; //compound assignment increment Left Hand Side with Right Hand Side

x-n //Subtraction
x--; //post decrement -- decrease one to x after
--x; //pre decrement -- decrease one to x before
x-=n; //compound assignment decrement Left Hand Side with Right Hand Side

x*n //Multiplication
x*=n; //compound assignment multiply Left Hand Side with Right Hand Side

x/n //Division
x/=n; //compound assignment divide Left Hand Side with Right Hand Side BUT n can't be zero

x%n //Modulo
x%=n; //compound assignment
```
### Relational Operators
```csharp
x<n //x stictly less than n
x<=n //x strictly less than or equal to n
x>n //x stictly greater than n
x>=n //x strictly greater than or equal to n
x==n //x equal to n
x!=n //x not equal to n
```
### Conditional Logic Operators
```csharp
//X AND Y
T && T == T
T && F == F
F && T == F
F && F == F
//X OR Y
T || T == T
T || F == T
F || T == T
F || F == F
//NOT X
!true == false
!false == true
```
## 3. Eureka Exercise/Moment
I finally understood the Modulo when I used it in the context of finding the leap year and seeing if it's DIVISIBLE by 4. It all made sense to me with that exercise, because it let me test out and understand that % lets me see if something is divisible by a number, meaning if it equals 0 or not.
## 4. Common Beginner Mistake
Mistaking && and || with each other. Using = instead of == for the Relational Operator. Not knowing how the Module functions.
## 5. Research References
I used the notes in Assignment 3 in Teams as a reference.
