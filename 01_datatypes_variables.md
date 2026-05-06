# 01. Datatypes and Variables

## 1. Concept
There are different data types that we would choose depending on the information needed. Some info, like whole numbers, has multiple datatypes; we would choose which one depending on how much memory we would be using. For example, if you need numbers below 255, you would choose a byte because it's the most efficient memory usage. The datatypes are needed to declare/initialize a variable, and they reserve space in memory for that variable. The convention for entering a variable name is camelCase notation. You would start the word with a lower-case letter, and then each word after that starts with an upper-case.

## 2. Key C# Syntax
```csharp
//declaring syntax
byte myByte;
//initialize after declaring syntax
myByte = 10;

//initialization syntax
byte myByte = 10; //Byte
short myShort = 10; //Int16
int myInteger = 10; //Int32
long myLong = 10; //Int64

float myFloat = 8.8f;  //Single
double myDouble = 12.5;  //Double

char myChar = 'a';  //Char

bool myBool = true;  //Boolean

string myString = "Faress";  //String
```

## 3. Eureka Exercise/Moment
A eureka moment I had was when I was declaring a float, and I got a syntax error until I realized I had forgotten to put f at the end
## 4. Common Beginner Mistake
A common mistake is forgetting the semicolon or using a comma instead of a period when putting a decimal number. Not knowing to put the f when it's a float, not using '_' for char and "_" for string
## 5. Research References
I used the notes on the assignment on Teams as a reference.
