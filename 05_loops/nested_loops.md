# 05. Nested Loops

## 1. Concept
A nested loop is just a loop inside another loop, each taking care of something different. You need 2 variables: the outer loop, which takes care of the row. The inner loop, which takes care of the columns. You use it when you want to take care of 2d arrays or grids, printing patterns or finding combinations. You would use a for-loop for each loop.
## 2. Key C# Syntax
```csharp
for(int i=1; i<=5; i++) //outer loop
{
  for(int j=1; j<=5; j++) //inner loop
  {
    Console.WriteLine($"Row {i], Column {j}");
  }
  Console.WriteLine(); //goes to the next row
}
```
## 3. Eureka Exercise/Moment
The exercise that really helped me understand this was the loop patterns. I tested so many different results that I ended up learning a lot.
## 4. Common Beginner Mistake
Not understanding what the outer and inner loops do. Forgetting to add a Console.WriteLine() for the outer loop when they want to make a grid.
## 5. Research References
Assignment 5 - For Loop patterns on Teams
