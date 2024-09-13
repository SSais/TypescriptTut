# Typescript 101

👋
Welcome! <br /> 
This is my beginners guide to Typescript tutorial. Please clone the repsitory. For the best experience, **please read this document on github or in preview mode!!** <br /> 
This tutorial assumes that you have basic knowledge of JavaScript, any feedback is welcome!

### Introduction

In JavaScript, a data type refers to the classification or categorization of data values. As JavaScript is a dynamic language, type can change throughout a program. As you may already know, there are 2 data types in JavaScript: primitive and non-primitive. <br />
Do you remember what they are?
<br>

**What are the primitive data types?**
<details>

  <summary>Click me for the answer!</summary>
  
1) Number
2) String
3) Boolean
4) Undefined
5) Null
6) Symbol 
7) BigInt 
</details>

**What are the non-primtive data types?**
<details>

  <summary>Click me for the answer!</summary>
  
1) Object
2) Function
3) Array
4) Date
5) Regex
6) Map
</details>


`typeof`
 can be used determine type in JavaScript. It is not perfect as it can't determine the type of an array. Please read the following to see the limitations: <br /> 

* (Recommended) https://www.w3schools.com/js/js_typeof.asp <br /> 
* (Optional) https://javascriptweblog.wordpress.com/2011/08/08/fixing-the-javascript-typeof-operator/

**Exercise 1:** Please complete exercise1.js.

### Typescript

TypeScript is a programming language that builds on top of JavaScript. The main feature that Typescript adds is static typing (this is optional, valid JavaScript will still work without static typing). Static typing is where you can specify types for variable, function parameters, and return values.

Below is an example of a simple string, in both JavaScript and Typescript. Notice the difference, and also think about how you would apply this to other datatypes:  


```js
//In JavaScript
let greeting = "Hello, World!";

console.log(greeting);  // Output: Hello, World!
```

```tsx
//In Typescript
let greeting: string = "Hello, World!";

console.log(greeting);  // Output: Hello, World!
```

The big advantage of typescript is that it sanitises code as it can add type safety to critical parts of an application, such as forms where users can input inforamtion. As you can see from the example above, typescript also helps you catch errors earlier as the type definitions make the code more self documenting and easier to follow and understand. This is particualrly helpfull when working in teams, making collaboration easier. 


### So how can I use it?

Let's start by creating a file that will allow us to write Typescript. 

First you need to ensure that you have node, npm and a code editor installed. Navigate to the directory where this file is kept and run the following commands in the command line:

**Installing Typescript**
```bash
npm init -y
```
```bash
npm install typescript --save-dev
```

**Setting up the compiler**
The compiler is a crucial part of component of TypeScript. It's responsible for converting TypeScript code into JavaScript code but also provides feedback during development as it performs static type analysis on your code and catches type related errors. Catching errors early!
```bash
npx tsc --init
```

You should notice that a new file has been generated called: tsconfig.json. This file is where the compiler settings can be adjusted, the file is already pre-populated with some instructions, feel free to read it. For now enter the instructions below, this is commonly used instructions:

```bash
{
  "compilerOptions": {
    "target": "es6",
    "module": "commonjs",
    "outDir": "./dist",
    "rootDir": "./src",
    "strict": true
  }
}
```

**Setting up the src directory**

Now you have to create a src directory where the TypeScript files will be saved
Inside the src directory create a file named Exercise2.ts.

Enter the following into the file: 

```typescript
function greet(name: string): string {
  return `Hello, ${name}!`;
}

let user = 'World';
console.log(greet(user));
```

Navigate to the src directory in your command line and the following command:

```bash
run npx tsc
```

You should have noticed that the TypeScript compiler converted the TypeScript file to JavaScript, and saved this in a newly generated dist folder. Any errors picked up by the compiler will be printed in the terminal during the compilation. 
