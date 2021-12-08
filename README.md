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
```crvar abc;
console.log(abc);
```
#### The result
> nul
What if i using 
```crvar abc = "Hello Everybody"
console.log(abc);
```
#### The result [2]
> CEPLJS: PrintVar.CPL, at line 323: NOT A VALID OR INVALID VARIABLE!
> 
> CEPLJS: declareVar.CPL, at line 213, in module "CrVarModule":  NOT A VALID OR INVALID VARIABLE!

## FOR & WHILE & Do-While
## TModule Using
TModule like a library, and not required to declare at first line of a .CPL file
At TModule, all JavaScript or default CEPLJS rule is broken.
### Print[TModule]
At default CEPLJS, print using 'console.log' [https://github.com/TuanminhDev/Tuanminh-new-code-compiler/#Print]. But in TModule, it using a complex
 
