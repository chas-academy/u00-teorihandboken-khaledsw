# Teorihandboken - JavaScript (JS)
Studerande: Khaled Ahmed

## JS 1.1 JavaScript / ECMAScript
JavaScript, often referred to as ECMAScript (ES), is a versatile, high-level programming language primarily used for web development. It is an integral part of web browsers and plays a pivotal role in creating interactive and dynamic client-side functionality on websites.

Key Concepts:

Interpreted Language: JavaScript is an interpreted language, which means that it doesn't require a separate compilation step. Web browsers or server-side runtime environments directly execute JavaScript code.

Client-Side and Server-Side: JavaScript can be utilized both on the client side, where it runs in web browsers, and on the server side using technologies like Node.js. This versatility allows developers to create full-stack applications using a single language.

Dynamic and Weakly Typed: JavaScript is dynamically typed, meaning that variable types are determined at runtime. Additionally, it is weakly typed, allowing for flexible variable type conversions.

Event-Driven and Asynchronous: JavaScript excels at handling events and asynchronous operations, making it well-suited for building responsive and interactive web applications.

How JavaScript / ECMAScript is Used:
JavaScript is extensively employed in web development to enhance user experiences. Developers utilize it to create dynamic web pages, add interactivity, perform form validation, and communicate with web servers asynchronously through technologies like AJAX.

Modern JavaScript features enhancements like modules, classes, and arrow functions. The ecosystem includes popular libraries and frameworks such as React, Angular, and Vue.js, simplifying complex front-end development.

On the server side, Node.js enables developers to use JavaScript for building scalable, high-performance server applications, making it a popular choice for back-end development.

Why Use JavaScript / ECMAScript?:

JavaScript is essential for web development because it enables developers to create interactive, responsive web applications. Its versatility and widespread adoption ensure that JavaScript skills are in high demand in the software development industry.

When to Use JavaScript / ECMAScript:
JavaScript is the primary language for web development. It should be used whenever interactivity, DOM manipulation, or client-side and server-side applications are required. Additionally, it is crucial for developing browser extensions, mobile applications, and even desktop applications using frameworks like Electron.

How Knowledge of JavaScript / ECMAScript Benefits Product Development:
Proficiency in JavaScript is a foundational skill for web developers. It empowers them to build feature-rich, interactive web applications and provides the basis for full-stack development when combined with server-side technologies like Node.js. A strong grasp of JavaScript is essential for creating modern web products and maintaining competitiveness in the web development field.


## JS 1.2 JavaScript-ramverk och -bibliotek
JavaScript frameworks and libraries are vital components in modern web development, simplifying and accelerating the creation of dynamic and interactive web applications. They provide pre-written code, established structures, and ready-to-use functionalities, empowering developers to build robust and feature-rich web solutions efficiently.

Frameworks:

React: Developed by Facebook, React is a leading front-end library for building user interfaces. It employs a component-based architecture and a virtual DOM, making it highly efficient for rendering complex UIs.

Angular: Google's Angular is a comprehensive front-end framework offering tools for building dynamic web applications. It includes features like two-way data binding and dependency injection.

Vue.js: Vue.js is a progressive JavaScript framework known for its simplicity and versatility. It excels at creating interactive web interfaces and can be easily integrated into projects incrementally.

Libraries:

jQuery: jQuery is a widely adopted JavaScript library that simplifies DOM manipulation, event handling, and AJAX interactions. It streamlines cross-browser development and enhances user interface interactivity.

D3.js: D3.js is a data visualization library that empowers developers to create dynamic, data-driven visualizations using HTML, SVG, and CSS. It's instrumental in crafting informative and engaging data presentations.

Lodash: Lodash is a utility library that offers a rich collection of functions for simplifying common programming tasks, such as array manipulation, object handling, and data processing.

Frameworks like React, Angular, and Vue.js are ideal for building complex web applications, providing structure and scalability. Libraries such as jQuery, D3.js, and Lodash specialize in specific areas, enhancing web development by addressing common challenges. The choice between frameworks and libraries depends on project requirements and developer preferences, with each offering unique advantages for web development.


## JS 1.3 Promises
Promises are a crucial concept in JavaScript for managing asynchronous operations. They provide a structured way to handle asynchronous tasks, making code more readable and maintainable when dealing with operations that may take an unknown amount of time to complete.

A Promise is essentially an object representing the eventual outcome of an asynchronous operation. It can be in one of three states:

Pending: The initial state, before the operation completes.
Resolved (Fulfilled): The operation completed successfully, and the Promise holds the result data.
Rejected: The operation encountered an error, and the Promise holds an error message.
Promises allow developers to initiate asynchronous tasks, like making HTTP requests or reading files, and then attach callback functions to handle the results when they become available. This approach eliminates the need for deeply nested callbacks, often referred to as "callback hell," making code more readable and easier to reason about.

Promises can be chained together using .then() to create a sequence of asynchronous operations. This chaining enables developers to express complex asynchronous workflows in a more linear and intuitive way.

Additionally, Promises provide a .catch() method to handle errors in a centralized manner, simplifying error handling.

Promises have become a standard feature in JavaScript, and they are widely used in modern web development. Many APIs, including the Fetch API for making network requests and libraries like Axios, return Promises for handling asynchronous operations. This ensures that developers can create responsive and efficient web applications while maintaining clean and organized code.


## JS 1.4 OOP i JavaScript
Object-Oriented Programming (OOP) is a programming paradigm that emphasizes the use of objects and classes to structure code. JavaScript, despite being a prototype-based language, supports OOP principles, making it a versatile language for building complex and organized applications.

Key Concepts:
Objects and Classes: In JavaScript, objects are the primary building blocks. Objects are instances of classes, which are defined as constructor functions or, in modern JavaScript, using the class keyword. These classes define the structure and behavior of objects.

Encapsulation: Encapsulation in JavaScript involves bundling data (properties) and methods (functions) that operate on that data within an object. This ensures that data is accessed and modified through well-defined interfaces, promoting data integrity.

Inheritance: JavaScript supports inheritance through a prototype chain. Objects can inherit properties and methods from other objects, allowing for code reuse and hierarchical structures.

Polymorphism: Polymorphism enables objects of different classes to be treated as instances of a common parent class. This allows for flexibility and abstraction in code design.

How OOP is Used:
OOP in JavaScript is used to create structured and modular code. Developers define classes to model real-world entities, such as users, products, or vehicles, and then create instances of these classes (objects) to work with in the application. Methods within these objects encapsulate behavior, making it easier to reason about and maintain code.

Why Use OOP in JavaScript:
OOP promotes code organization, reusability, and maintainability. It helps developers create complex applications by breaking them down into smaller, more manageable pieces (objects and classes). OOP also encourages best practices, such as encapsulation and separation of concerns, leading to more robust and maintainable code.

When to Use OOP in JavaScript:
OOP is beneficial when building applications with complex data structures or when multiple components interact. It's particularly useful in scenarios where you need to model real-world entities and relationships between them.

Understanding OOP in JavaScript empowers developers to create well-structured and scalable applications, promoting code reusability and maintainability. It is a valuable skill for modern web development.


## JS 1.5 DOM-manipulation
DOM manipulation is a fundamental concept in web development, enabling developers to interact with and manipulate the content and structure of web pages dynamically. The Document Object Model (DOM) represents the web page as a tree-like structure, with each element on the page as a node. JavaScript provides powerful tools for accessing and modifying this DOM tree.

Key Concepts:
DOM Tree: The DOM tree is a hierarchical representation of the web page's structure, with elements like HTML tags, attributes, and text as nodes. JavaScript allows developers to traverse and manipulate this tree.

Selecting Elements: JavaScript provides various methods to select elements from the DOM, such as getElementById, getElementsByClassName, getElementsByTagName, and modern methods like querySelector and querySelectorAll.

Modifying Content: Developers can change the content, attributes, or structure of DOM elements using properties and methods. For instance, you can update the text within a <p> element or change the class of a <div>.

Creating and Deleting Elements: JavaScript enables the creation and removal of DOM elements dynamically. You can generate new elements and append them to the DOM or remove existing ones.

Event Handling: DOM manipulation often involves event handling, where JavaScript code responds to user interactions like clicks, mouse movements, or keyboard inputs. Event listeners are used to attach functions to these events.

How DOM Manipulation is Used:
DOM manipulation is used extensively in web development to create interactive and responsive web applications. It allows developers to:

Update page content without reloading the entire page (Ajax).
Validate user input and provide feedback.
Create dynamic user interfaces that respond to user interactions.
Implement features like image sliders, accordions, and form validation.
Fetch and display data from web services or APIs.

Why Use DOM Manipulation:
DOM manipulation is essential for creating engaging and dynamic web experiences. It enables developers to build interactive web applications and respond to user actions, making websites more user-friendly and feature-rich.

When to Use DOM Manipulation:
DOM manipulation is used whenever you need to change or update the content, structure, or behavior of a web page dynamically. It's especially valuable for single-page applications (SPAs) and websites with rich interactivity.

Mastery of DOM manipulation is a crucial skill for web developers, as it is at the core of creating modern, user-friendly web applications.


## JS 1.6 HTTP-requests
HTTP (Hypertext Transfer Protocol) requests are a fundamental concept in web development, enabling communication between a client (usually a web browser) and a server. They facilitate the retrieval and exchange of data, allowing web applications to function seamlessly.

Key Concepts:
HTTP Methods: HTTP requests are categorized into different methods, each serving a specific purpose. Common methods include:

GET: Retrieve data from the server.
POST: Send data to the server, often used for submitting forms or creating new resources.
PUT: Update an existing resource on the server.
DELETE: Remove a resource from the server.
Request Headers: Requests include headers that convey metadata about the request, such as the browser type, accepted content types, and more.

Request Body: Some requests, like POST and PUT, include a request body that contains data to be sent to the server, typically in JSON or form-encoded format.
Response: After receiving and processing a request, the server sends back a response. This response includes an HTTP status code (e.g., 200 for success, 404 for not found) and a response body containing the requested data or an error message.
Asynchronous Requests: In modern web development, most HTTP requests are made asynchronously using technologies like XMLHttpRequest or the Fetch API. This allows web applications to remain responsive while data is fetched from the server.

How HTTP Requests are Used:
HTTP requests are used in various scenarios in web development, such as:
Retrieving data from a server (e.g., loading a web page's content).
Submitting user input (e.g., submitting a form).
Updating data on the server (e.g., saving changes to a user's profile).
Deleting resources (e.g., removing a post or comment).
Communicating with external APIs to fetch data.

Why Use HTTP Requests:
HTTP requests are the backbone of modern web applications. They enable dynamic interactions between clients and servers, allowing web applications to provide real-time updates, fetch data from databases, and integrate with third-party services and APIs.

When to Use HTTP Requests:
HTTP requests are used whenever data needs to be fetched from a server or sent to a server for processing. They are essential for creating interactive and data-driven web applications.

A solid understanding of HTTP requests is crucial for web developers, as they form the basis of client-server communication and are essential for building responsive and dynamic web applications.


## JS 1.7 Lexical scope
Lexical scope, also known as static scope, is a fundamental concept in programming languages, including JavaScript. It defines the rules for variable accessibility and resolution based on where variables and functions are declared within the source code, rather than where they are called or invoked during runtime. Lexical scope is essential for understanding how variables and functions are scoped and accessed within a program.

Key Concepts:
Scope Hierarchy: Lexical scope establishes a hierarchy of scopes within a program. Each function or block of code creates a new scope, and these scopes nest hierarchically based on how the code is structured.
Variable Resolution: When a variable is referenced within a scope, JavaScript looks for that variable's declaration within the current scope. If it finds the declaration, it uses that variable. If not, it continues to the outer (enclosing) scope and searches there until it either finds the variable declaration or reaches the global scope. This process is known as variable resolution.
Closure: Lexical scope is a fundamental concept for understanding closures in JavaScript. Closures occur when a function "remembers" its lexical scope, even if it is executed outside of that scope. This allows functions to access variables from their containing scopes even after those scopes have exited.

How Lexical Scope is Used:
Lexical scope determines variable visibility and access within a program. It ensures that variables declared within a function or block of code are not accessible outside of that scope, preventing unintended side effects and naming conflicts.

Why Use Lexical Scope:
Lexical scope provides predictability and clarity in variable access and resolution. It helps developers write code that is easier to reason about and maintain, as variable behavior is determined by the code's structure rather than its runtime state.

When to Use Lexical Scope:
Lexical scope is a foundational concept in programming, especially in languages like JavaScript. It is used implicitly in all code to determine how variables are accessed. Understanding lexical scope is essential for writing clean and maintainable code and for avoiding common scope-related bugs.
In summary, lexical scope defines how variable access and resolution work in a program based on the structure of the code. It is a core concept in JavaScript and many other programming languages, providing order and predictability to variable behavior.


## JS 1.8 Event handling
Event Handling in JavaScript is a software routine that processes actions that happen when a user interacts with the page, such as mouse movements and keystrokes.  Event handlers can be used to handle and verify user input, user actions, and browser actions

## JS 1.9 Prototype inheritance
Prototype inheritance in javascript is the linking of prototypes of a parent object to a child object to share and utilize the properties of a parent class using a child class.

## JS 1.10 Higher-order functions
Higher-order functions in JavaScript are functions that can accept other functions as arguments or return functions as their results, enabling powerful functional programming techniques such as map, filter, and reduce. 

## JS 1.11 Single-thread programming
JavaScript is a single-threaded language, which means it has only one call stack that is used to execute the program.

## JS 1.12 OAuth från frontend
OAuth from the frontend in JavaScript involves user authentication or accessing third-party APIs by redirecting users to authorization endpoints, obtaining tokens for secure resource access. Backend servers are often used for token exchange and storage of sensitive information.

## JS 1.13 Websockets
The WebSocket API is an advanced technology that makes it possible to open a two-way interactive communication session between the user's browser and a server.

