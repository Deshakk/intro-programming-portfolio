# 06. Arrays

## 1. Concept
An array is an object that holds multiple values that are of the same data type and is allocated in memory. Instead of creating 100 variables for integers, you can make 1 int array with a size of 100. You can either fill an array by hardcoding it or by going through each index with the help of a For Loop. Once the size is set, it cannot be changed. If an array index doesn't have a value, it will use the **default** value of the data type, for example, int = 0. The array name is in camelCaseNotation.
## 2. Key C# Syntax
### declaring and initializing an array
```csharp
//declaring an array
data_type[]arrayName; //camelCase
//initializing an array
arrayName = new data_type [5]; //array filled with default values

//declaring and initializing an array
data_type[]arrayName = new data_type [5]; //array filled with default values
```
### instantiate an array
```csharp
//hardcoding an array
byte[]arrayName = new byte {1, 2, 3, 4, 5}; //array filled with actual values

//with a for loop
for (int i = 0; i < arrayName.Length;i++) //arrayName.Length gets the length of the array, so in this case, it would be 4 because the index goes from 0 to 4
{
  arrayName[i]=i+1; // would do i+1 on index 0 which gives 0+1 = 1;
}
```
## 3. Eureka Exercise/Moment
I was confused about what to do with arrays until I realized I could use a for loop to instantiate the array so much faster.
## 4. Common Beginner Mistake
Forgetting that the index starts counting at 0, causing an IndexOutOfRangeException.
## 5. Research References
using Assignment 7 from Teams
