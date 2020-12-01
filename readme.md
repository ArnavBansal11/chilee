# Chilee

Chilee is a beginner friendly programming language names after (you guessed it), eSpice. 

## Installation
1. Download the project as a ZIP file
2. Unzip it and place it in `C:/`
3. Add the path to the main `chilee` folder in the PATH environment variable

Thats it you are all set now!

## Basic Format and Features
1. Semicolons (;) are optional
2. File names end with the extension `.ci`
3. The language follows a JavaScript like syntax so its easy to pickup
4. Beginners can easily shift from Chilee to other languages due to similar syntax

## Built In Functions
1. Print - `print("hello world")`
2. Array Length - `length([1,2,3])`
3. To String - `toString(someVar)`
4. Is checks - `isList(someVar)`, `isString(someVar)`, `isFunction(someVar)`
5. Input and Input Number - `input("Input text: ")`, `inputInt("Input text: ")`

## Comments
Comments start with an `@` symbol and end at the next line

`@ This is a comment`

## Loops
Chilee has support for `for` and `while` loops

#### For loops-

```@ Without step in an ascending order
for(i = 1: to 10){
  print(i)
}

@ With step
for(i = 1: to 10: step 2){
  print(i)
}

@ With step in descending order
for(i = 10: to 1: step -1){
  print(i)
}```
