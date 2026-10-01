Day 1/ 1-10-2026
Playwright:
It is an open source tool by Microsoft for automating web browser testing 
Released in 2020
It is an open source node.js library, where node.js is the Javascript runtime enviroment that executes JS code outside of a web browser
Features:
*Supports cross browser testing(Works with Chromium(chrome,Edge), Firefox, WebKit(Safari))
*Supports cross platform testing-Runs on Windows, Mac and Linux
*Supports cross language scripting-JS,TS, Java, Python, C#
*Supports mobile web application testing for chrome browser for Android devices and Safari browsers for iOS devices
*Playwright includes built-in API testing, allowing to test backend APIs 
*Auto-waiting mechanism-Playwright waits for elements to be ready before performing actions, reducing test flakiness. By default it waits for 30 seconds
*Complex web elements like iframe,shadow DOM elements are easily handled in Playwright which are tricky for other tools
*Supports parallel execution- running tests simultaneously in multiple browser instances for faster execution
*Provides built in reporters and provides various report formats like HTML, JSON, JUnit and more. Supports thrid party reporting tools like Allure
1.Inspector: Helps debug tests by showing click points and verifying locators in real time.
2.Code Generation(code gen): The Codegen tool records your actions and converts them into test scripts in any
supported language.
3.Tracing(Trace Viewer): Captures screenshots, records videos, retries flaky tests, and logs steps automatically. Capture all the information to investigate the test failure.

JavaScript ---> Dynamically typed language

let age=30
let name="John"
age="thirty"

TypesScript --- Statically typed language

let age:number=30
let name:string="John"
age="thirty"

Why TypeScript?
JavaScript (ES3,ES4,ES5,ES6)
ECMAScript - ECMAScript(ES) is the standard to which all JavaScript code must comply.

TypeScript - superset of JavaScript

A vendor such as Microsoft cannot add features to the JavaScript language without breaking ECMAScript compliance.
In contrast, with TypeScript, Microsoft can add any new features it wants, so long as the generated JavaScript is ECMAScript-compliant. 
That gives Microsoft all the freedom in the world to make TypeScript as feature-full as any other programming language.

What is TypeScript? 
• TypeScript is superset of JavaScript—it adds extra features to JavaScript. 
• It compiles (converts) into regular JavaScript, so it runs anywhere JavaScript does. 
• Files end in .ts (instead of .js).
How TypeScript Works? 
1.You write code in TypeScript (.ts files). 
2.The TypeScript compiler converts it into JavaScript (.js files). 
3.The JavaScript runs in browsers, Node.js, or any JS environment. 
Why Use TypeScript? 
• Helps catch mistakes early (before running the code). 
• Makes large projects easier to manage. 
• Works smoothly with existing JavaScript code. 

Install the TypeScript Compiler 
npm install -g typescript 
tsc -v   (or)  tsc --version 
To execute TypeScript files without compiling them first: 
npm install -g tsx

tsc app.ts  
node app.js 
 
Run TypeScript Without Compiling , we use typsecript executor
tsx app.ts 

var 
1.Scope – Function-scoped (limited to the function where it is declared). 
2.Can be redeclared and reinitialized within the same scope. 
3.Assigning a value at the time of declaration is optional. 
let 
1.Scope – Block-scoped (limited to the enclosing {...} block). 
2.Cannot be redeclared within the same scope but can be reinitialized. 
3.Assigning a value at the time of declaration is optional. 
const 
1.Scope – Block-scoped (limited to the enclosing {...} block). 
2.Cannot be redeclared or reinitialized within the same scope. 
3.Assigning a value at the time of declaration is mandatory.

Shortcut (Windows/Linux): Ctrl + / 
Shortcut (Windows/Linux): Shift + Alt + A

JavaScript is a Dynamically Typed Language 
• In JavaScript, variable types are checked at runtime, and you can change the type of 
a variable later.
TypeScript is a Statically Typed Language 
• In TypeScript, variable types are checked at compile time, and you cannot change 
the type later. 

TypeScript Types (Data Types) 
Built-in or custom categories for variables (e.g., number, string, boolean). 
Type Annotations 
Explicitly telling TypeScript the type of a variable using : type.
Type Inference 
TypeScript automatically guesses the type if you don’t annotate it.

Typescript Primtive types:
1.Number
2.String
3.Boolean
4.Null
5.Undefined
6.Any
7.Union
8.Void

Non-Primitive Types (Objects & Custom Types) 
1.Array 
2.Tuple 
3.Class 
4.Functions 
5.Interface

Any type will violate the typesafety feature of Typescript.

