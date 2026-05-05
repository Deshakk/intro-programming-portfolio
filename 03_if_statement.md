# 03. If Statements

## 1. Concept
If statements are a way to tell the program that IF a certain condition **IS TRUE**, then proceed with the code **INSIDE** the IF-Block; however, IF the condition **IS NOT TRUE** then **SKIP** the IF-Block. There are If-Else If statements that add a **2nd condition** to check if the **1st condition** is **FALSE**; if the 2nd condition is **TRUE**, it goes inside the Else-If-Block; if it's **FALSE**, it skips it as well. There's the If-Else If-Else statement, which adds a 3rd route to the code, which checks that if **the 1st and 2nd conditions** are **FALSE**, then do the 3rd block (The Else-Block). There are certain rules for the If-block; you can have as many Else-If as you want; however, you can't start an if block with an else-if. You **MUST** have **1 IF** to start the If-Block, but you can have either **1 or 0 Else** at the end.
## 2. Key C# Syntax
### If-Statement
```csharp
if(/*condition*/)
{
  //do smth
}
```
### If-Else if Statement
```csharp
if(/*condition 1*/)
{
  //do smth
}
else if(/*condition 2*/)
{
  //do smth else
}
```
### If-Else if-Else Statement
```csharp
if(/*condition 1*/)
{
  //do smth
}
else if(/*condition 2*/)
{
  //do smth else
}
else
{
  //do the last possible smth
}
```
### If-Else Statement
```csharp
if(/*condition*/)
{
  //do smth
}
else
{
  //do smth else
}
```
## 3. Eureka Exercise/Moment
I didn't have any problems with the if-statements from the start, so I don't have a eureka moment.
## 4. Common Beginner Mistake
A common mistake is adding a semicolon at the end of the if statement. Another mistake is putting them in the wrong order; for example, If-Else-Else If.
## 5. Research References
I used the assignment 3 reference from Teams
