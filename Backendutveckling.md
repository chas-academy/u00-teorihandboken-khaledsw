# Teorihandboken - Backendutveckling (BE)
Studerande: Khaled Ahmed

## BE 1.1 PHP
PHP, originally known as Personal Home Page, is a server-side scripting language designed for web development. It is widely used for creating dynamic web pages and web applications and is embedded within HTML code. PHP is known for its simplicity, versatility, and widespread adoption, making it a popular choice for web developers.

Key Concepts:

Server-Side Scripting: PHP is executed on the web server, not on the user's browser. It generates dynamic content by processing code on the server before sending the HTML to the client's browser. This allows for the creation of interactive and data-driven websites.

Open Source: PHP is an open-source language, which means it is free to use, and the source code can be modified and customized by developers. This has contributed to its popularity and a large community of users.

Database Integration: PHP can interact with various databases, including MySQL, PostgreSQL, and SQLite, making it suitable for developing database-driven web applications. It enables data retrieval, storage, and manipulation.

Embedding in HTML: PHP code is typically embedded within HTML using special delimiters <?php ... ?>. This allows developers to seamlessly mix server-side logic with client-side markup.

Wide Platform Support: PHP is platform-independent and can run on various operating systems, including Windows, macOS, and Linux. It is also compatible with different web servers, such as Apache and Nginx.

How PHP Is Used:
PHP is used to build a wide range of web applications, including blogs, e-commerce websites, content management systems (CMS) like WordPress, and social media platforms. It handles user authentication, form processing, database operations, and much more. PHP frameworks like Laravel and Symfony provide a structured and efficient way to develop complex web applications.

Why Use PHP:
Ease of Learning: PHP has a shallow learning curve, making it accessible to beginners in web development.
Versatility: It can be used for a variety of tasks, from creating simple contact forms to building large-scale applications.
Community and Resources: PHP has a vast and active community, offering extensive documentation, libraries, and online support.


## BE 1.2 OOP i PHP
Object-Oriented Programming (OOP) is a programming paradigm that revolves around the concept of objects, which represent real-world entities or concepts. PHP, a versatile server-side scripting language, offers robust support for OOP principles, enabling developers to create modular, maintainable, and scalable code.

Key Concepts:

Classes and Objects: In PHP, a class is a blueprint for creating objects. It defines the properties (attributes) and methods (functions) that objects of the class will have. Objects are instances of classes, representing individual entities with their own data and behavior.
Encapsulation: Encapsulation is the practice of bundling data (attributes) and methods (functions) that operate on that data within a class. It restricts direct access to an object's internal state, promoting data integrity and security.
Inheritance: Inheritance allows one class (subclass or child class) to inherit properties and methods from another class (superclass or parent class). This promotes code reuse and supports the "is-a" relationship.
Polymorphism: Polymorphism enables objects of different classes to be treated as instances of a common superclass. It allows for the flexibility of using different objects interchangeably.
Abstraction: Abstraction involves simplifying complex systems by breaking them down into manageable parts. In PHP, abstract classes and methods define a blueprint without providing a complete implementation, leaving specific details to subclasses.

How OOP in PHP Is Used:
OOP in PHP is used to create structured and modular code. It is particularly beneficial for building large-scale web applications and frameworks. Popular PHP frameworks like Laravel and Symfony heavily rely on OOP principles to provide robust and maintainable codebases.

OOP allows developers to organize code into reusable classes and objects, making it easier to manage and extend applications. It promotes code separation, making it simpler to identify and fix issues. OOP is also well-suited for collaborating on projects with multiple developers, as it offers clear guidelines for code organization and responsibilities.

Why Use OOP in PHP:
OOP enhances code reusability, maintainability, and scalability. It provides a structured and organized approach to software development, making it easier to understand and extend code over time. OOP is particularly valuable for complex web applications and projects where collaboration and long-term maintenance are priorities.

When to Use OOP in PHP:
OOP in PHP is beneficial for projects of various sizes and complexities, but it is especially valuable for medium to large-scale applications where code organization, extensibility, and maintainability are critical. Developers often use OOP when creating custom libraries, frameworks, content management systems, and enterprise-level web applications.


## BE 1.3 Säkerhet i PHP
Security is a critical aspect of web development, and PHP provides a range of features and best practices to help developers build secure web applications. Ensuring the security of PHP-based web applications is essential to protect user data, prevent unauthorized access, and mitigate security vulnerabilities.

Key Security Concepts:

Data Validation: Properly validating and sanitizing user inputs is crucial to prevent common security threats like SQL injection and Cross-Site Scripting (XSS) attacks. PHP offers functions and libraries to filter and sanitize user data.

Authentication: Implementing secure authentication mechanisms is vital to ensure that only authorized users can access certain parts of an application. PHP provides tools for password hashing and user authentication.

Authorization: Authorization controls what actions users are allowed to perform after they have been authenticated. Developers must implement robust authorization checks to ensure users cannot access unauthorized resources.

Secure File Handling: PHP applications often deal with file uploads and manipulation. Properly handling files, including validating file types, restricting access, and preventing file execution, is crucial for security.

Session Management: Secure session management is essential to prevent session hijacking and fixation attacks. PHP provides session handling functions, and developers should use secure session settings.

Cross-Site Request Forgery (CSRF) Protection: Implementing CSRF protection mechanisms helps prevent attackers from tricking users into performing unintended actions on a website. PHP offers tools to generate and validate CSRF tokens.

Input Validation: Always validate and sanitize data from all sources, including form submissions, URL parameters, and cookies. Input validation is essential to prevent various forms of attacks.

Error Handling: Avoid exposing sensitive information in error messages that could be useful to attackers. Implement custom error handling to display user-friendly error messages while logging detailed error information securely.

Why Security in PHP is Important:

Security in PHP is crucial to protect user data, maintain the integrity of web applications, and safeguard against threats and vulnerabilities. Failing to address security risks can lead to data breaches, unauthorized access, and compromised user trust.

When to Focus on Security in PHP:

Security considerations should be integrated into every stage of PHP web application development, from the initial design phase to deployment and ongoing maintenance. Security should be a top priority in all aspects of PHP development to ensure the protection of user data and the integrity of the application.

## BE 1.4 MVC
MVC is a software architectural pattern widely used in web development and other software engineering disciplines. It divides an application into three interconnected components to enhance code organization, maintainability, and scalability.

Key Concepts:

Model (M): The Model represents the application's core data and logic. It encapsulates the business rules, data storage, and interactions with the database. Models are responsible for retrieving, storing, and processing data. They do not have knowledge of how data is presented or displayed.

View (V): The View represents the user interface (UI) elements of the application. It handles the presentation and rendering of data to the user. Views are responsible for displaying data from the Model and capturing user input, but they do not handle data manipulation or business logic.

Controller (C): The Controller acts as an intermediary between the Model and the View. It processes user input from the View, interacts with the Model to retrieve or update data, and then updates the View to reflect the changes. Controllers contain application-specific logic and orchestrate the flow of data and user interactions.

How MVC Is Used:
MVC separates concerns within an application, making it easier to develop, maintain, and scale software. It encourages modularity and code reusability. Developers can work on different aspects of the application independently, allowing for collaborative development.

For web applications, the Model represents the data stored in the database, the View handles the HTML templates and user interfaces, and the Controller manages the routing and application logic.

Why MVC Is Important:
MVC promotes a clear separation of concerns, making it easier to manage complex applications. It enhances code maintainability, scalability, and testability. It also enables developers to reuse code components and adapt to changing requirements more efficiently.

When to Use MVC:
MVC is suitable for a wide range of software applications, especially those that require a well-structured architecture, such as web applications, mobile apps, and desktop applications. It is particularly useful when an application's data, presentation, and logic need to be organized and managed independently.


## BE 1.5 Wordpress
WordPress is a popular open-source content management system (CMS) and website-building platform. Originally designed for blogging, it has evolved into a versatile tool for creating a wide range of websites, from simple blogs to complex e-commerce sites and corporate web portals.

Key Concepts:

Themes: WordPress allows users to choose from a vast library of themes, which are templates that determine the website's design and layout. Themes can be customized or created from scratch to suit specific needs.

Plugins: Plugins are extensions that add functionality to a WordPress site. They can enhance SEO, provide security features, add contact forms, integrate social media, and much more. Thousands of free and premium plugins are available.

Content Management: WordPress provides an intuitive content management system, making it easy to create, edit, and organize text, images, videos, and other media. It also supports user roles and permissions for content control.

SEO-Friendly: WordPress is inherently SEO-friendly, with features like customizable permalinks, sitemaps, and easy integration with SEO plugins to optimize content for search engines.

Community and Support: A vast and active WordPress community offers support, documentation, forums, and resources to help users and developers troubleshoot issues and learn.

How WordPress Is Used:
WordPress is used to build websites of all types, including blogs, personal portfolios, corporate websites, e-commerce stores, forums, and more. Its flexibility and ease of use make it accessible to both beginners and experienced developers.

Why WordPress Is Important:
WordPress simplifies web development by providing a user-friendly platform for creating and managing websites. Its extensibility through themes and plugins allows users to customize their sites according to their unique requirements. It has a strong ecosystem of developers and designers, making it a reliable choice for many web projects.

When to Use WordPress:
WordPress is an excellent choice when you need to create a website quickly and efficiently, especially if you lack extensive coding skills. It's ideal for bloggers, small businesses, and organizations looking to establish a web presence without significant development overhead. However, it can also scale to handle more complex projects with the right customization and development expertise.


## BE 1.6 Heirarkiska databaser
A hierarchical database is a type of database model that represents data in a tree-like structure with a top-down, parent-child relationship between data elements. This model is one of the earliest database models and is still used in certain specialized applications today.

Key Concepts:
Tree Structure: In a hierarchical database, data is organized into a hierarchy, similar to a family tree. Each data element is called a "node" and is connected to other nodes in a parent-child relationship. A node can have multiple child nodes but only one parent node, except for the root node, which has no parent.

Parent-Child Relationships: Data elements are linked based on their relationships. Child nodes are subordinate to their parent nodes, and each node inherits properties or attributes from its parent.

Record Types: In a hierarchical database, different types of records or data elements are grouped together. Each record type may have its own set of attributes or fields.

Navigational Structure: Accessing data in a hierarchical database typically requires navigation from the top (root) of the hierarchy down to the desired data element. It follows a structured path to retrieve or manipulate data.

How Hierarchical Databases Are Used:
Hierarchical databases were historically used in applications where data naturally had a hierarchical structure, such as file systems or organizational charts. They are efficient for tasks like representing file directories or managing parts of an organization.

Why Hierarchical Databases Are Important:
Hierarchical databases offer efficient data retrieval for specific use cases with well-defined hierarchies. They provide a clear and intuitive way to represent structured data.

When to Use Hierarchical Databases:
Hierarchical databases are most appropriate when data naturally follows a hierarchical structure. They are less suitable for applications with complex and changing data relationships, such as modern transactional systems or data analytics. In such cases, relational databases or other database models are often preferred for their flexibility.


## BE 1.7 Relationsdatabaser, SQL och ER-modellering
Relational databases, SQL (Structured Query Language), and Entity-Relationship (ER) modeling are foundational concepts in the field of database management and design. They are essential for structuring and managing data in a way that ensures data integrity, retrieval efficiency, and ease of use.

Key Concepts:

Relational Databases:
What Are Relational Databases?: Relational databases are a type of database management system (DBMS) that organizes data into structured tables with rows and columns. Each table represents an entity, and relationships between tables are established using keys.
Key Concepts: Tables (relations), rows (tuples), columns (attributes), primary keys, foreign keys, and normalization are fundamental concepts in relational databases.
How Are They Used?: Relational databases are used to store, retrieve, and manage structured data efficiently. They provide a well-defined schema that enforces data consistency and integrity.

SQL (Structured Query Language):
What Is SQL?: SQL is a domain-specific language used for managing and querying relational databases. It provides a standardized way to interact with databases, allowing users to create, retrieve, update, and delete data.
Key Concepts: SQL includes commands like SELECT (for querying data), INSERT (for adding new data), UPDATE (for modifying existing data), and DELETE (for removing data).
How Is It Used?: SQL queries are used to extract specific data from databases, filter records, perform calculations, and join data from multiple tables.

ER Modeling (Entity-Relationship Modeling):
What Is ER Modeling?: ER modeling is a visual representation technique used to design the structure of a relational database. It helps define entities, attributes, and relationships between data elements.
Key Concepts: ER diagrams consist of entities (objects or concepts), attributes (properties of entities), and relationships (associations between entities).
How Is It Used?: ER modeling is a critical step in database design. It helps database designers create a blueprint for the database structure before implementation. ER diagrams are used to communicate and document the database's structure.

How They Are Used Together:
Database Design: ER modeling is used to plan the structure of the database, defining tables, their attributes, and the relationships between them.

Database Creation and Management: Relational databases are created and managed using SQL. SQL commands are used to create tables, insert data, query data, and perform various database operations.

Data Retrieval: SQL is used to query relational databases to retrieve specific data based on user requirements.

Data Integrity: Relational databases enforce data integrity constraints defined in the database schema. SQL is used to establish and manage these constraints.

Why They Are Important:
Relational databases, SQL, and ER modeling provide a structured and standardized approach to data management and database design. They are widely used in software development and data-driven applications to ensure data consistency, reliability, and accessibility.

When to Use Them:
Relational databases, SQL, and ER modeling are essential when dealing with structured data or when data relationships need to be clearly defined and maintained. They are suitable for a wide range of applications, including business systems, e-commerce platforms, content management systems, and more.


## BE 1.8 OAuth i backend
OAuth (Open Authorization) is a widely used authentication and authorization protocol that allows applications to securely access resources on behalf of a user without exposing the user's credentials. While OAuth often involves interactions between a frontend application, a user, and an OAuth provider, it is also important to consider OAuth from the backend perspective, especially when developing web services and APIs.

Key Concepts:

OAuth Flow: OAuth defines several authorization flows, such as the Authorization Code Flow, Implicit Flow, and Client Credentials Flow. The choice of flow depends on the use case and whether the application is a frontend or a backend service.

Client and Server Roles: In the context of OAuth, the backend service typically plays the role of the OAuth client, while the OAuth provider acts as the server. The backend client requests access tokens to access protected resources on behalf of users.

Access Tokens: Access tokens are short-lived, revocable credentials that authorize the backend service to access specific resources on behalf of a user. The backend service includes the access token in API requests to prove its identity and permissions.

Scopes: Scopes define the specific permissions or actions that an access token grants. Backend services request access tokens with the necessary scopes to perform authorized actions on the user's behalf.

How OAuth in the Backend Is Used:

OAuth in the backend is commonly used in scenarios where a backend service needs to access third-party APIs or protected resources on behalf of a user. For example, a backend service of a mobile app might use OAuth to access a user's Google Drive files or post on their social media account.

Why OAuth in the Backend Is Important:

Security: OAuth ensures that sensitive user credentials are not exposed to the backend service, enhancing security.

User Control: Users have control over which resources the backend service can access, as they grant and revoke permissions.

Third-Party Integration: OAuth enables seamless integration with third-party services and APIs, expanding the functionality of applications.

When to Use OAuth in the Backend:

OAuth in the backend is suitable when your application or service needs to access user data or perform actions on behalf of users without compromising security. It is especially valuable for applications that integrate with external services or APIs, such as social media platforms, cloud storage, or online marketplaces.


## BE 1.9 HTTP-protokollet
HTTP, which stands for Hypertext Transfer Protocol, is the foundation of data communication on the World Wide Web. It is an application layer protocol that defines how clients (typically web browsers) and web servers communicate with each other to request and deliver web content.

Key Concepts:
Client-Server Model: HTTP operates on a client-server model, where clients (user agents) make requests to web servers for resources like web pages, images, and documents.

Stateless Protocol: HTTP is inherently stateless, meaning that each request from a client to a server is independent and does not retain information about previous requests. To maintain session state, cookies and other mechanisms are often used.

Request-Response Cycle: An HTTP transaction follows a request-response cycle. The client sends an HTTP request to a server, and the server responds with the requested data or an error message.

Methods: HTTP defines several request methods, including GET (retrieve data), POST (submit data), PUT (update data), DELETE (remove data), and more. These methods indicate the desired action for the server to perform.

Headers: HTTP headers are metadata included in both requests and responses. They provide information about the message, such as content type, date, and server details.

Status Codes: HTTP responses include status codes that indicate the outcome of the request. Common status codes include 200 (OK), 404 (Not Found), and 500 (Internal Server Error).

How HTTP Is Used:
HTTP is used for various purposes on the web, including fetching web pages, submitting form data, downloading files, and interacting with web services and APIs. It forms the basis for the communication between web clients (browsers) and web servers.

Why HTTP Is Important:
Standardization: HTTP provides a standardized way for web clients and servers to communicate, enabling interoperability across different platforms and systems.

Web Development: Understanding HTTP is crucial for web developers, as it dictates how web applications interact with servers and how data is exchanged.

Web Browsing: Everyday web browsing relies on HTTP for fetching and rendering web pages, making it an integral part of the online experience.

When to Use HTTP:
HTTP is used whenever data needs to be exchanged between a client and a server over the internet. It is the fundamental protocol for web communication and is employed in web development, web services, and various internet-related applications.


## BE 1.10 cURL
cURL, short for "Client for URLs," is a command-line tool and library used for transferring data with URLs. It supports a wide range of protocols, including HTTP, HTTPS, FTP, FTPS, SCP, SFTP, LDAP, and more. cURL is highly versatile and is commonly used by developers, system administrators, and automation scripts to interact with web services, APIs, and other resources over the internet.

Key Concepts:
Command-Line Tool: cURL is primarily used as a command-line tool, where users can issue cURL commands in their terminal or command prompt. For example, you can use cURL to send HTTP requests to web servers and retrieve data.

Protocols: cURL supports numerous protocols, making it a valuable tool for various networking tasks. Users can specify the protocol in the URL they provide.

Options and Flags: cURL offers a wide range of command-line options and flags that allow users to customize their requests. These options can control headers, authentication, data payloads, and more.

Library: In addition to the command-line tool, cURL provides a library (libcurl) that can be integrated into applications. This library is available in multiple programming languages, making it accessible for developers to include network functionality in their software.

How cURL Is Used:
cURL is used for various purposes, including:

Sending HTTP requests to web servers to retrieve web pages and data.
Testing and debugging web services and APIs by inspecting the HTTP responses.
Automating tasks that involve downloading files from the internet or uploading data to remote servers.
Checking the availability and status of websites and web services.
Why cURL Is Important:

cURL simplifies data transfer and interaction with web resources from the command line, providing a versatile and scriptable way to work with URLs and various network protocols. It is a valuable tool for web developers, system administrators, and anyone needing to perform network-related tasks.

When to Use cURL:
cURL is used whenever there is a need to send HTTP requests, interact with web services, retrieve remote data, or automate network-related tasks from the command line or within scripts. It is especially useful for tasks that require customization and automation of data transfer over the internet.


## BE 1.11 REST
EST, which stands for Representational State Transfer, is an architectural style for designing networked applications. It was introduced by Roy Fielding in his doctoral dissertation in 2000 and has since become the predominant architectural style for designing web services and APIs.

Key Concepts:
Resources: In REST, everything is treated as a resource, which can be a physical object, a data entity, or an abstract concept. Resources are identified by URIs (Uniform Resource Identifiers), and each resource has a state.

HTTP Methods: REST relies on the standard HTTP methods (GET, POST, PUT, DELETE, etc.) to perform actions on resources. Each method has a specific purpose: GET for retrieving data, POST for creating new resources, PUT for updating resources, and DELETE for removing resources.

Stateless: REST is stateless, meaning that each request from a client to a server must contain all the information needed to understand and process the request. Servers do not store information about the client's state between requests.

Representation: Resources can have multiple representations, such as JSON, XML, HTML, or plain text. Clients interact with resources by exchanging representations.

Uniform Interface: REST promotes a uniform and consistent interface for interacting with resources. This includes using standard HTTP methods, employing meaningful URIs, and using hypermedia (HATEOAS) to provide links to related resources.

How REST Is Used:
REST is used for designing web services and APIs that are scalable, stateless, and easy to understand. It is widely employed in web and mobile application development for exposing data and functionalities over the internet.

Why REST Is Important:
Simplicity: RESTful APIs are straightforward to design, understand, and implement.
Scalability: REST's statelessness and uniform interface make it highly scalable, allowing for easy distribution and load balancing.
Interoperability: RESTful APIs are technology-agnostic and can be accessed from a wide range of clients and platforms.

When to Use REST:
REST is suitable for building APIs and services when the focus is on simplicity, scalability, and ease of use. It is commonly used in scenarios where data needs to be exposed and consumed over the internet, such as web and mobile applications, IoT devices, and microservices architectures.


## BE 1.12 XML och andra dataformat
XML (eXtensible Markup Language) is a versatile data format used for structuring and storing data in a hierarchical and human-readable manner. It is often used to exchange data between systems and to represent structured information like configuration files, documents, and more. Key features of XML include its extensibility, self-descriptiveness, and wide industry adoption.

In addition to XML, various other data formats serve different purposes in data exchange and storage:

JSON (JavaScript Object Notation): JSON is a lightweight, text-based data format known for its simplicity and ease of use. It is widely used in web APIs and web applications for data interchange due to its compatibility with JavaScript.

CSV (Comma-Separated Values): CSV is a plain-text format for representing tabular data. It is commonly used for spreadsheets and data import/export.

YAML (YAML Ain't Markup Language): YAML is a human-readable data serialization format used for configuration files and data exchange. It is known for its simplicity and readability.

Protobuf (Protocol Buffers): Protobuf is a binary serialization format used for efficient data storage and exchange. It is often used in scenarios where performance and efficiency are critical.

HTML (Hypertext Markup Language): HTML is a markup language used for structuring content on the web. While primarily intended for rendering web pages, it can also serve as a data format for web scraping and data extraction.

The choice of data format depends on the specific use case, requirements, and compatibility with the systems or applications involved. XML, JSON, and CSV are among the most commonly used formats due to their widespread support and versatility in different domains.

## BE 1.13 Webbservrar
A web server is software or hardware that serves as the foundation for websites and web applications. It handles client requests, processes them, and delivers web content to users' browsers over the internet. Web servers play a critical role in making websites accessible and responsive to user interactions.

Key Concepts:

Request-Response Model: Web servers follow a request-response model, where client devices (typically web browsers) send HTTP requests to the server, and the server responds with HTML, CSS, JavaScript, and other web resources.

HTTP Protocol: Web servers use the HTTP (Hypertext Transfer Protocol) to communicate with clients. HTTP defines how requests and responses are structured and transmitted.

Hosting Websites: Web servers store and serve web content, such as HTML files, images, videos, and databases, to users. They can host multiple websites or web applications on the same server, each with its own configuration and domain.

Processing Logic: Web servers can execute server-side code, such as PHP, Python, or Node.js scripts, to generate dynamic content or interact with databases. This allows for the creation of interactive web applications.

Load Balancing: In high-traffic scenarios, multiple web servers can be used in a load-balanced setup to distribute incoming requests evenly, ensuring better performance, redundancy, and fault tolerance.

How Web Servers Are Used:

Web servers are used to:
Host static websites by serving HTML, CSS, and JavaScript files.
Execute server-side scripts to generate dynamic web content.
Manage user sessions and authentication.
Serve as a reverse proxy to distribute requests to application servers.
Implement security measures, such as SSL/TLS encryption and firewalls, to protect data and users.
Why Web Servers Are Important:
Web servers are essential for making web content accessible to users worldwide. They ensure that web applications run smoothly, handle concurrent connections, and provide the necessary infrastructure for serving content securely and efficiently.

When to Use Web Servers:
Web servers are used whenever you need to make web content or web applications accessible over the internet. Whether you're hosting a simple static website or a complex web application, a web server is a fundamental component of web development and deployment.
