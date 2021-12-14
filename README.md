# Tuanminh new code compiler (call it is CEPLJS(Computer Easy Programming Language using JavaScript))
This is my new compiler. I cannot programming it. I need help now.
## ABOUT
Tuanminh's CEPLJS is a easy version of JavaScript, something is right for JavaScript's rule, something is edited (spelling, code, library, complex command to easy command, for, while,...)
## Print
Print to screen is a basic and very needed and important if it is programming language. In javascript, we using
> console.log("Anything");
> 
> console.log(var);

And in CEPLJS then it still

> console.log("Anything");
> 
> console.log(var);
## Variables
In javascript, we have `var` `let` `const` `catch` `...`
In CEPLJS, we just have var(to create variable with content inside it) and crvar(to create variable with content is "nul" inside it)
EXAMPLES:
```
crvar abc;
console.log(abc);
```
#### The result
> nul

What if i using 
```
crvar abc = "Hello Everybody"
console.log(abc);
```
#### The result [2]
> CEPLJS: PrintVar.CPL, at line xxx: NOT A VALID OR INVALID VARIABLE!
> 
> CEPLJS: declareVar.CPL, at line xxx, in module "CrVarModule":  NOT A VALID OR INVALID VARIABLE!

## FOR & WHILE & Do-While
### For
In CEPLJS, we not using 'For' while
### While
The while loop is using so much in JavaScript programming, then we won't remove it.
Syntax:
```while (condition) {
  // code block to be executed
}
```
In some case we need the while var "i" +1 to it equal to 10, we use:
```var i = 10
while (i < 10) {
  text += "The number is " + i;
  i++;
}
```
> If you forget to increase the variable used in the condition, the loop will never end. This will crash your CPU because the loop just in < 1 milisecond
### Do-While
Do-While is so much in use not less than 'While'
Syntax:
```
do {
  // Do anything
}
while (condition);
```
### Date and time
We are planning
## TModule Using
TModule like a library, and not required to declare at first line of a .CPL file
At TModule, all JavaScript or default CEPLJS rule is broken.
### Print[TModule]
At default CEPLJS, print using 'console.log' [https://github.com/TuanminhDev/Tuanminh-new-code-compiler/#Print]. But in TModule, it using a complex command, like 'TModule.TextCfg.PrintText.Content("Var then not need double quotes, but normal content is need and very highy important and required double quotes");'
### FUNCTION REMOVAL PROCLATION
So bad, TModule is too hard to creating and building... We will stop this at 9th, December, 2021; 5:00 AM Utc+7
