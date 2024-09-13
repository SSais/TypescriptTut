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
<br>

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

<br>
You are able to determine type in JavaScript using typeOf, TypeOf is not perfect, it is not able to determine the type of array. Please read the following to see the limitations of typeOf: <br /> 

* (Recommended) https://www.w3schools.com/js/js_typeof.asp <br /> 
* (Optional) https://javascriptweblog.wordpress.com/2011/08/08/fixing-the-javascript-typeof-operator/

**Exercise 1:** Please complete exercise1.js.

### Typescript

TypeScript is a programming language that builds on top of JavaScript. The main feature that Typescript adds is static typing (this is optional, valid JavaScript will still work without static typing). Static typing is where you can specify types for variable, function parameters, and return values.

Below is an example of a simple string, in both JavaScript and Typescript. Notice the difference, and also think about how you would apply this to other datatypes:  
<br>
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

The big advantage of typescript is that it sanitises code as it can add type safety to critical parts of an application, such as forms where users can input inforamtion. As you can see from the example above, typescript also helps you catch errors earlier as the type definitions make the code more self documenting and easier to follow and understand. Which is particualrly helpfull when working in teams, making collabroation easier. 


### So how can I use it?

Let's start by creating a file that will allow us to write Typescript.

First you need to ensure that you have node, npm and a code editor installed.


Navigate to the directory where this file is kept and run the following commands to set up Typescipt:



```bash
npm init -y
npm install typescript --save-dev
npx tsc --init

```


```bash

```


normal js 


with typescript 
