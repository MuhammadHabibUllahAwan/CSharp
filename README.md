# CSharp
https://www.freecodecamp.org/learn/foundational-c-sharp-with-microsoft/write-your-first-code-using-c-sharp/write-your-first-c-sharp-code
## CSharp
What is a literal value?
A literal value is a constant value that never changes. Previously, you displayed a literal string to the output console. In other words, you literally wanted that string of alphanumeric characters H, e, l, l, o, and so on, displayed in the output console.

Use the string data type whenever you have alphanumeric words, phrases, or data for presentation, not calculation. What other kinds of literal data can you print to output?

##  Data Types
1-char literals  
2-int Literals  
3-Floating point Literals(float,double,decimal)  
4-Boolean Literal  
##  Here's a few important considerations about variable names:

1. Variable names can contain alphanumeric characters and the underscore character. Special characters like the hash symbol # (also known as the number symbol or pound symbol) or dollar symbol $ are not allowed.
2. Variable names must begin with an alphabetical letter or an underscore, not a number.
3. Variable names are case-sensitive, meaning that string Value; and string value; are two different variables.
4. Variable names must not be a C# keyword. For example, you cannot use the following variable declarations: decimal decimal; or string string.
## Why use the var keyword?
The var keyword has been widely adopted in the C# community. It's likely that if you look at a code example in a book or online, you'll see the var keyword used instead of the actual data type name, so it's important to understand its usage.  
The var keyword has an important use in C#. Many times, the type of a variable is obvious from its initialization. In those cases, it's simpler to use the var keyword. The var keyword can also be useful when planning the code for an application. When you begin developing code for a task, you may not immediately know what data type to use. Using var can help you develop your solution more dynamically.  
As you get started, it is recommended that you continue to use the actual data type name when you declare variables until you become more comfortable working with code. Using the data type when you declare variables will help you be purposeful as you write your code.
## Recap
Here's what you've learned about the var keyword so far:

1. The var keyword tells the compiler to infer the data type of the variable based on the value it is initialized to.
2. You'll likely see the var keyword as you read other people's code; however, you should use the data type when possible.
