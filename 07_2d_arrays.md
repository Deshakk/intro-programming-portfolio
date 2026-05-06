# 07. 2D Arrays

## 1. Concept
2D arrays are the same as a regular array, except they are in a grid. To print out a 2D array, you need a nested loop. The inner and outer loops work together to situate the location of the index. For example, [0,0] would be the index on the 1st row and 1st column.
## 2. Key C# Syntax
```csharp
datatype[,] varName = new datatype [3,5]; //intializing the 2D array

//Assigning the array elements
for (int i = 0; i < varName.GetLength(0); i++) //foreach row, i goes from row 0 to row 2
{
    for (int j = 0; j < varName.GetLength(1); j++) //foreach column, j goes from column 0 to column 4
    {
        varName[i, j] = j + 1; //assigning a value
    }
	Console.WriteLine(); //Goes to the next line after each row
}
//Displaying the array elements
for (int i = 0; i < 3; i++)
{
    for (int j = 0; j < 5; j++)
    {
        Console.Write($"{varName[i, j]} "); //display the value at the index [i,j]
    }
	Console.WriteLine(); //Goes to the next line after each row
}
```
You can also hardcode the 2D array
```csharp
int[,] numbers2D = {    { 9, 99 },
                        { 3, 33 },
                        { 5, 55 }
                    };
//this array is a [3,2]
```
## 3. Eureka Exercise/Moment
The Pascal exercise made me start actually thinking about how the rows and columns were assigned with the for loops, instead of just trying random numbers until I get it right.
## 4. Common Beginner Mistake
Instead of doing (varName.GetLength()), they do (varName.Length) out of habit from arrays. Using <= instead of < causes the OutOfBounds error. Forgetting to put a Console.WriteLine(); to skip the line after each row when displaying
## 5. Research References
I used the 2D array source code from Teams
