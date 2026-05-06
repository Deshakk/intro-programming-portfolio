# 05. For vs While loops

## 1. Concept
The For and While loops both loop a certain action, a certain number of times; however, they're chosen depending on different factors, as explained below. 
### For Loop
**The For Loop** is used when we need to repeat an action x amount of times, and that x is specified or deduced. Or when you need to iterate over a specific range of numbers. The for statement header has 3 fields: the initialization, the condition, and the increment. The steps for the loop are 1. You initialize a variable 2. Check the condition if it's true 3. Do the action inside the loop 4. Increment the variable, then repeat back to step 2. 
### While Loop
**The While Loop** is used when we want to repeat an unknown number of times, we need to increment in a non-standard way or to read a file. The while loop follows the same order of execution; the condition needs to be true to execute the loop, but the increment is not limited to i++. The steps are the same as the For loop. however intializing the variable is done outside the loop, and incrementing is done inside the loop.
## 2. Key C# Syntax
### For Loop
```csharp
for (int i= startValue; i< endValue; i++)
{
    Console.WriteLine("do something");

    //1 initialize
    //2 check condition
    //3 do program inside the loop
    //4 increment value
    //5 repeat steps 2-4 until condition is false
}
```
You can also keep fields empty in the header
```csharp
for( ; ; )
{
    //infinite loop
}
for(   ; i<endValue; i++)
{
    //missing initialization and assumed it's already declared
}
for(int i = startValue;  ;i++)
{
    //missing condition, the loop has no stop, so it will loop forever until there's a break or return
}
for(int i = startValue; i<endValue; )
{
    //missing increment, the loop will not update the counter, which results in only 1 iteration
}
```
### While Loop
```csharp
int i = startValue;
while(i<endValue)
{
    Console.WriteLine("do something");
  
    i += someValue;
  
    //1 initialize
    //2 check condition
    //3 do program inside the loop
    //4 increment value
    //5 repeat steps 2-4 until condition is false
}
```
## 3. Eureka Exercise/Moment
The loop patterns in assignment 5 fully got me to understand how to make it work and what each field does
## 4. Common Beginner Mistake
Common mistakes are usually logical errors, such as entering the condition incorrectly. Or even forgetting to enter a field, resulting in different outcomes.
## 5. Research References
I used assignment 5 in Teams and the Gemini prompt "what happens when u leave fields empty in the for header" to see what happens for each field
