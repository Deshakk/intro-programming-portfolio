# 09. Structures

## 1. Concept
A struct is a value type that groups multiple values into one structure for easy access and improved readability. The struct class is written with PascalCaseNotation, and the variable name is in camelCaseNotation. There are two steps to a struct: defining the struct and declaring the values. It's best used for grouping small data that remains constant, for example, student info.
## 2. Key C# Syntax
### defining the structure
```csharp
struct Student //PascalCase
{
  public long ID; //PascalCase notation
  public string Name;
  public float GPA;
}
```
### Declaring the values
```csharp
Student s1; //camelCase
s1.ID = 2602077;
s1.Name = "Faress";
s1.GPA = 4.0f;
```
### Displaying the values
```csharp
//easier to use a function
void DisplayStudentInfo(Student aStudent) //aStudent = s1
{
  Console.WriteLine(aStudent.ID);
  Console.WriteLine(aStudent.Name);
  Console.WriteLine(aStudent.GPA);
}
```
## 3. Eureka Exercise/Moment
Since structs are a value type, I learned during practice that I can also use them as a type for arrays, making the array much more organized for getting data
## 4. Common Beginner Mistake
Forgetting to put the public when declaring the values. Using the wrong case notation.
## 5. Research References
I used the Structure Source Code from Teams and my own notes from class.
