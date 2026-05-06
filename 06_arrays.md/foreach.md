# 06. for each in Arrays

## 1. Concept
A for each is used to iterate over the array, instead of using a for loop. We would enter the type of the array or just 'var', with the arrayName. Although this lets us see every element in the array, unlike the for loop, we cannot edit anything inside the for each.
## 2. Key C# Syntax
### iterate with a foreach
```csharp
foreach(var elem in arrayName)
{
	Console.WriteLine(elem);
}
//var will get the type of the array
```
### iterate with a for loop
```csharp
for (int i=0; i<arrayName.Length; i++)
{
	Console.WriteLine(arrayName[i]);
}
```
## 3. Eureka Exercise/Moment
On exercise 1 of assignment 7, I tried using a foreach to print out all the elements of the array with the i+1 inside, and I realized that the foreach doesn't work for that type of usage.
## 4. Common Beginner Mistake
A common mistake is trying to change a value inside the foreach.
## 5. Research References
Assignment 7 from Teams
