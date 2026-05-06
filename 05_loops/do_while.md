# 05. Loops with Do-Whiles

## 1. Concept
The Do-While is one of the ways to loop in a program. The program goes through the instructions once before checking the condition set; if true, then it repeats again until the condition is false. You use this loop if you want to validate the users' input or if you want to repeat the program. For example, "Would you like to play again? (y/n)" And you would do a do-while to validate to make sure the user enters only 'y ' or 'n'. And you would do another do-while to repeat the program when 'y' == true. Or you can do while(true) so that the program is in a constant loop until a break.
## 2. Key C# Syntax
### Infinite Loop
```csharp
do
{
    //do smth until we see a break in the program
}while (true); //because the condition is true, the loop is infinite
```
### Validation
```csharp
do
{
    Console.Write("Enter a number between 1 and 10: "); //prompt the user
    num = Convert.ToByte(Console.ReadLine()); //Read it, assuming its correct

    validInput = num >= 1 && num <= 10;

}while(validInput == false); // set the condition accordingly (if the input is false, repeat the prompt)
//}while (!(num >= 1 && num <=10)); //!validInput --> invalidInput
//}while (num < 1 || num > 10);
```
### Loop Depending on the user's answer
```csharp
do
{
    //The entire game program
    //prompt if the user would like to go again and validate
    Console.WriteLine("Would you like to play again? (y/n)");
    ans = Convert.ToChar(Console.ReadLine());

}while (ans == 'y');
//}while (ans.Equals('y'));
```
## 3. Eureka Exercise/Moment
Exercise #3 in assignment 4 helped me understand how to validate correctly and how to think of the conditions in the do-while loop logically.
## 4. Common Beginner Mistake
Mistaking what condition we need to set for it to loop logically is sometimes confusing at the start for most beginners. For example, we want (validInput == false) to be true for it to loop again when we are validating.
## 5. Research References
I used assignment 4 on Teams as a reference
