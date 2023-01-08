## C# Basics
This sheet contains basics for C# language. PS. C# is fun and amazing. I feel it's the intersection of all languages I know, Java, Javascript and C++.

### Key Findings
What findings I got after learning so much about C#
+ C# defaults all camelCase function names whereas C++ defaults for underscores ('_'). So it might take some time to switch contexts or else you mix up both.

### Syntax
+ To declare variables use `var` keyword, e.g. 
  + `var name="Ayush"`
+ 

### Functions
#### Built-in functions
command|description
-------|-----------
Console.WriteLine(string);| Writes string in the console, or Console.WriteLine("something"+variable); or COnsole.WriteLine($"something {variable}");

#### String functions
command|description
-------|-----------
String.ToUpper()| to uppercase
String.ToLower()| to lowercase

#### Loops
1. `for` loop
```c#
var list = new[] {...items}
foreach( var item in list){
  // do something
}
```
