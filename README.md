# Typescript 101

👋
Welcome! <br /> 
This is my beginners guide to Typescript tutorial. Please clone the repsitory. For the best experience, **please read this document on github or in preview mode!!** <br /> 
This tutorial assumes that you have basic knowledge of JavaScript, any feedback is welcome!

### Introduction

In JavaScript, a data type refers to the classification or categorization of data values. As JavaScript is a dynamic language, type can change throughout a program. As you may already know, there are 2 data types in JavaScript: primitive and non-primitive. <br />
Do you remember what they are?

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

You are able to determine type in JavaScript using typeOf, TypeOf is not perfect, it is not able to determine the type of array. Please read the following to see the limitations of typeOf:
* (Recommended) https://www.w3schools.com/js/js_typeof.asp
* (Optional) https://javascriptweblog.wordpress.com/2011/08/08/fixing-the-javascript-typeof-operator/

**Exercise 1** Please complete exercise 1 in index... and determine what all the types are.

#### Typescript

TypeScript is a programming language that builds on top of JavaScript. It adds a "type system" to JavaScript, which means:
You declare what type of data each part of your code should be (like numbers, text, or more complex structures).
The TypeScript tool checks your code as you write it, pointing out potential mistakes before you run the program.

It's a superset of JavaScript, which means that any valid JavaScript code is also valid TypeScript code. TypeScript adds optional static typing and other features to JavaScript, aiming to make it easier to develop and maintain large-scale applications.
Key features of TypeScript include:
Static typing: You can specify types for variables, function parameters, and return values.
Object-oriented programming: It supports classes, interfaces, and modules.


### Why and when should I use typescript?

The big advantage is that it helps catch errors early and makes it easier to work on large projects, especially in teams. When you're done, TypeScript code gets converted into regular JavaScript so web browsers can understand it.

TypeScript offers several benefits that make it attractive for developers and organizations. Here are the key advantages and scenarios where TypeScript is particularly beneficial:
Benefits of using TypeScript:

Enhanced code quality:
Static typing helps catch errors early in development
Reduces runtime errors and makes debugging easier


Improved maintainability:
Type definitions make code more self-documenting
Easier to refactor and understand code structure


Better developer experience:
Improved autocomplete and IntelliSense in IDEs
Faster development due to early error detection


Scalability:
Designed for building large-scale applications
Improves code organization through modules and namespaces


Enhanced collaboration:
Type definitions serve as a form of documentation
Easier for team members to understand and work with each other's code


JavaScript compatibility:
Can gradually adopt TypeScript in existing JavaScript projects
Compiles to JavaScript, ensuring broad compatibility

Libraries and frameworks:
Developing reusable code that others will consume
Creating APIs with clear interfaces


Refactoring legacy JavaScript:
Gradually improving existing JavaScript codebases
Adding type safety to critical parts of an application





Projects using modern JavaScript features:

TypeScript supports the latest ECMAScript features, even before full browser adoption


Applications requiring high reliability:

Financial systems, healthcare applications, or other domains where errors can have significant consequences


Integration with other typed languages:

Projects that interface with backend services written in typed languages (e.g., Java, C#)



While TypeScript offers many benefits, it's worth noting that it may introduce some complexity and a learning curve for developers new to static typing. It also requires a compilation step, which can slightly increase build times. However, for many projects, especially larger ones, the benefits often outweigh these considerations.
Would you like me to expand on any specific aspect of TypeScript's benefits or use cases?





### So how can I use it?





normal js 


with typescript 





```tsx

type Color = {
    color1:number;
    color2: string;
    isValid: boolean;
    addressLines: string[];
};

console.log(Adress)

```
### Knowledge check

How can you determine type in JavaScript?
<details>

  <summary>Click me</summary>
  
  ### Heading
  1. Foo
  2. Bar
     * Baz
     * Qux

  ### Some Javascript
  ```js
  function logSomething(something) {
    console.log('Something', something);
  }
  ```
</details>




### Time to Typescript  

