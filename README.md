# 🌟 JavaScript - The Language of the Web

## 📄 About JavaScript

JavaScript is a very popular and powerful programming language used to make websites interactive and dynamic. It allows web pages to respond to user actions like clicks, form submissions, animations, or updating content without reloading the whole page.

Today, JavaScript is not just limited to browsers. It runs on servers (using Node.js), mobile apps, desktop apps, and even smart devices.

---

## 🛠️ How was JavaScript made?

JavaScript was created in **1995** by **Brendan Eich**, who was working at Netscape Communications (a company that built one of the first web browsers).

Netscape wanted a lightweight scripting language that could be used easily by designers and beginner programmers to add small features to web pages.

Brendan Eich developed the first version of JavaScript in just **10 days**!

---

## 🗓️ History of JavaScript

- **1995**: JavaScript is created and first called *Mocha*, then *LiveScript*, and finally named **JavaScript**.
- **1996**: Microsoft introduces their own version called *JScript*, which leads to problems with browser compatibility.
- **1997**: JavaScript becomes standardized as **ECMAScript**, so all browsers can follow one set of rules.
- **2005**: The rise of *Ajax* makes websites faster and more dynamic (for example, Gmail and Google Maps).
- **2009**: *Node.js* is released, allowing JavaScript to be used on the server side (backend).
- **2015**: *ES6* (ECMAScript 6) is released, adding new and powerful features like `let`, `const`, arrow functions, classes, etc.
- **Today**: JavaScript is the most widely used language for web development and has many modern frameworks and libraries (React, Angular, Vue, etc.).

---

## 💬 Why is it called "JavaScript"?

The name **JavaScript** was chosen for marketing reasons. At that time, Java (a different language) was very popular, so Netscape used a similar name to get more attention.

However, **Java** and **JavaScript** are completely different and not directly related.

---

# JavaScript Variables - Complete Guide

Variables in JavaScript are containers that store data values. They act as named storage locations that can hold different types of data and can be referenced and manipulated throughout your code.

## Variable Declaration Keywords

JavaScript provides three keywords for declaring variables:

### `var`
- **Function-scoped** or **globally-scoped**
- **Hoisted** to the top of their scope
- Can be **redeclared** and **updated**
- **Legacy** keyword (ES5 and earlier)

```javascript
var name = "John";
var name = "Jane"; // Redeclaration allowed
name = "Bob";      // Update allowed
```

### `let`
- **Block-scoped**
- **Hoisted** but not initialized (Temporal Dead Zone)
- Cannot be **redeclared** in the same scope
- Can be **updated**
- **Modern** keyword (ES6+)

```javascript
let age = 25;
// let age = 30; // Error: Cannot redeclare
age = 30;        // Update allowed
```

### `const`
- **Block-scoped**
- **Hoisted** but not initialized (Temporal Dead Zone)
- Cannot be **redeclared** or **reassigned**
- Must be **initialized** at declaration
- **Modern** keyword (ES6+)

```javascript
const PI = 3.14159;
// const PI = 3.14; // Error: Cannot redeclare
// PI = 3.14;       // Error: Cannot reassign
```
