# 04. Switches

## 1. Concept
The Switch is another way to make a fork in the program. If you want to switch what happens based on a certain variable, you can have a switch case go through and check if the variable has the required value. For example, you switch the variable x. In the case that x == 5, do smth and then break to the end right away, if x != 5, then go to the next case if there is one and repeat until the last break. You would use this over the if statement if you are checking a single variable and comparing it with many specific values. If there are also 3 or more conditions, it's a lot easier to read for the user.
## 2. Key C# Syntax
```csharp
switch(/*var*/)
{
  case /*value 1*/: //if value 1 is true, go into the case
    //instructions here
    break; //break out of the switch
  case /*value 2*/: //if value 2 is true, go into the case
    //instructions here
    break; //break out of the switch
}
```
You can also have a default case that acts as an else block
```csharp
switch(/*var*/)
{
  case /*value 1*/:   //if value 1 is true, go into the case
    //instructions here
    break;
  default: //if no other case is true, default to here
    //instructions here
    break; //break out of the switch
}
```
## 3. Eureka Exercise/Moment
I understood how efficiently I could use the switches instead of if statements with exercise #1 in assignment 4
## 4. Common Beginner Mistake
A common mistake is forgetting to put the ":" after the case or using a "{" instead. Forgetting to break at the end of each case is also a regular habit for beginners.
## 5. Research References
I gave the prompt "When would you use a switch instead of an if statement in C#" to Gemini to figure out when you would use a switch instead of an if statement. I also used assignment 4 in Teams.
