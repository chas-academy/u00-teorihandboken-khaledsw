# Teorihandboken - Programmeringsmetodik (PG)
Studerande: Khaled Ahmed

## PG 1.1 Versionshantering (Git)
Version control, particularly Git, is an indispensable tool in modern software development. It's a system that tracks changes to code and files over time, providing a historical record of every modification, who made it, and when. Here are the key aspects of Git and version control:

1. What is Version Control? Version control is a system that manages changes to files and directories, enabling multiple people to collaborate on projects efficiently and keeping a complete history of those changes.

2. Git as a Version Control System: Git is one of the most widely used distributed version control systems. Created by Linus Torvalds, it's renowned for its speed and efficiency in managing source code and other text-based files.

3. Key Concepts:
Repository (Repo): A Git repository is a directory that stores all the files, history, and metadata for a project.
Commit: Commits are snapshots of the project at specific points in time, recording changes made to the repository.
Branch: Branches in Git allow for the parallel development of different features or versions of a project, isolating changes until they are ready to be merged.
Merge: Merging combines the changes from one branch into another, often from a feature branch into the main branch (e.g., master).
Pull Request (PR): On platforms like GitHub, a pull request is a way to propose and discuss changes before merging them into the main branch.
Clone: Cloning is the process of creating a copy of a Git repository on your local machine.
Remote: A remote is a copy of a Git repository stored on a different server, commonly used for collaboration.

4. Benefits of Git:
History Tracking: Git maintains an exhaustive record of changes, facilitating tracking, auditing, and debugging.
Collaboration: Multiple team members can work on the same project simultaneously, and changes can be easily integrated.
Branching and Isolation: Feature branches allow developers to work on separate tasks without impacting the main codebase.
Reverting: It's straightforward to roll back to a previous version of your project if a new change causes issues.
Distribution: Git is distributed, meaning every collaborator has a full copy of the repository, ensuring work can continue even when disconnected from the internet.

5. Git Hosting Platforms: Git is often used in conjunction with platforms like GitHub, GitLab, and Bitbucket, which provide features for collaboration, issue tracking, and continuous integration.

6. Git Workflow: Git workflows, like Gitflow or GitHub Flow, provide rules and guidelines for managing branches, coordinating development, and releasing software.

Version control with Git is a foundational practice in software development, ensuring that code is well-organized, changes are tracked, and collaboration is efficient and transparent. It is considered an essential skill for developers and teams working on software projects of all sizes.


## PG 1.2 Benchmarking
Benchmarking is a strategic management and performance evaluation process used by organizations to assess and improve their own practices and results by comparing them to industry best practices and standards. It involves measuring the performance, processes, and outcomes of an organization against those of its peers, competitors, or leaders in the same field. Benchmarking can occur in various aspects of business, including operations, finances, customer service, and more. Here are some key points about benchmarking:

1. Types of Benchmarking:
Internal Benchmarking: This involves comparing a specific process or performance metric within different departments or divisions of the same organization to identify best practices and areas for improvement.
Competitive Benchmarking: Organizations compare their performance to that of direct competitors to gain insights into their relative strengths and weaknesses.
Functional Benchmarking: This involves looking at organizations outside your industry that excel in a particular function or process, even if it's unrelated to your core business.
Strategic Benchmarking: Involves evaluating the strategic direction and overall performance of similar organizations to identify best practices and potential areas for improvement.

2. Benefits of Benchmarking:
Performance Improvement: Identifying gaps in performance and adopting best practices can lead to tangible improvements.
Competitive Advantage: Understanding how your organization compares to competitors can help you gain a competitive edge.
Innovation: Benchmarking can inspire innovation and the adoption of new and effective strategies.
Efficiency: It can lead to streamlined processes and cost reduction.

3. The Benchmarking Process:
Planning: Define the objectives and scope of the benchmarking project.
Data Collection: Gather data on your organization's performance and the benchmark (best-in-class) organization's performance.
Analysis: Analyze the data to identify gaps and opportunities for improvement.
Implementation: Implement changes or best practices based on the analysis.
Monitoring and Review: Continuously monitor progress and make adjustments as necessary.
Benchmarking provides valuable insights and helps organizations set realistic goals for improvement. It is a dynamic process that can drive continuous improvement and excellence, keeping organizations competitive in their respective industries. However, it's essential to select appropriate benchmarks and use the insights to drive meaningful change effectively.

## PG 1.3 Testdriven utveckling
Test-driven development (TDD) is a software development approach in which developers write tests for a piece of code before they actually implement that code. TDD is a cycle that consists of three main steps: writing a failing test, writing the code to make the test pass, and then refactoring the code as needed while ensuring the test continues to pass. Here are some key aspects of TDD:

1. Red-Green-Refactor Cycle:
Red: Write a failing test case that defines the desired behavior of the code you are about to write.
Green: Implement the minimal amount of code necessary to make the test pass.
Refactor: After the test passes, refactor the code to improve its structure, readability, or efficiency while ensuring the test still passes.

2. Benefits of TDD:
Improved Code Quality: TDD promotes writing clean, maintainable code and ensures that code is thoroughly tested.
Faster Debugging: TDD often leads to finding and fixing issues earlier in the development process, reducing the time and effort spent on debugging.
Enhanced Design: TDD encourages developers to think about the interface and behavior of code before implementation, leading to better design decisions.
Confidence in Changes: TDD makes it easier to modify or extend existing code without introducing regressions.
Documentation: Test cases serve as documentation of the intended functionality of the code.
3. Common Testing Frameworks: TDD is often used in combination with testing frameworks and libraries, such as JUnit for Java, pytest for Python, and Jasmine for JavaScript, to automate the testing process.

4. TDD vs. Traditional Development: In traditional development, code is written first, and testing may be done afterward. In TDD, tests come first, which can help ensure that code is thoroughly tested and that the codebase remains stable and maintainable. 

5. Challenges: TDD can be challenging to implement, particularly for those new to the approach. It requires discipline and a shift in mindset to write tests before writing the actual code.

TDD is widely adopted in agile and iterative development processes and is considered a best practice for creating robust and reliable software. It helps ensure that code meets the specified requirements and that it can adapt to changing needs without introducing unexpected issues.


## PG 1.4 Deploy och staging
Deploying and staging are integral processes in software development, especially when releasing web applications or software. They involve preparing, testing, and transitioning code from development to a live production environment while minimizing disruptions and ensuring quality. Here are the key concepts:

Deployment:

Deployment is the process of releasing a software application, service, or website for public use. It involves making the code, databases, and related assets available to users. Deployment can be to various environments, including production (live), staging, and development.
Staging:

Staging is a pre-production environment that closely mimics the production environment. It serves as a testing ground for new code and features before they are deployed to the live production environment. Staging environments are meant to catch and resolve issues, ensuring a smooth and error-free deployment.
Key Aspects:

Testing: Staging is crucial for testing changes and new features to identify and address potential issues before they affect users in the live environment.

Data Synchronization: Staging environments should mirror production data as closely as possible, but without affecting real user data. Data synchronization is essential for accurate testing.

Quality Assurance: Staging environments often include quality assurance (QA) processes to ensure that the software functions correctly and meets established standards.

Rollback Planning: In case issues arise during deployment, a rollback plan should be in place to quickly revert to the previous version of the software to minimize disruption.

Version Control: Version control systems (e.g., Git) play a significant role in tracking code changes and ensuring that the correct version is deployed.

Automated Deployment: Automated deployment tools and scripts streamline the process, reducing the risk of human error.

User Acceptance Testing (UAT): Staging environments are often used for user acceptance testing, allowing stakeholders to verify that the software meets their requirements and expectations.

Load Testing: Staging environments may also be used to simulate user traffic and assess the system's performance and scalability.

Benefits:
Risk Mitigation: Staging minimizes the risk of deploying untested or flawed code to production, avoiding potential disruptions and damage to the user experience.
Quality Assurance: It ensures that the software is thoroughly tested and meets the required standards before being exposed to users.
Continuous Improvement: Staging allows for iterative development, with feedback and improvements made in a controlled environment.
In summary, the staging environment is a crucial step in the deployment process, helping ensure the stability and reliability of software before it goes live. It is an integral part of the software development lifecycle that safeguards the user experience and the reputation of the application or service.


## PG 1.5 Debugging
Debugging is a systematic process of identifying, analyzing, and fixing errors or issues in computer programs, scripts, or software applications. It is an essential part of software development and maintenance, as all complex code can potentially contain bugs. Here are key aspects of debugging:

1. Error Types:
Syntax Errors: These are typically caught by the compiler or interpreter and prevent the program from running. They involve issues like missing semicolons, typos, or incorrect variable names.
Runtime Errors: These occur while the program is executing and can lead to crashes or unexpected behavior. Common examples include null pointer exceptions and division by zero.
Logical Errors: These are the trickiest to identify because the code runs without errors, but the output doesn't meet the intended logic or requirements.

2. Debugging Tools:
Print Statements: Adding print or log statements to your code is one of the simplest and effective debugging techniques. It helps you inspect variable values and program flow.
Integrated Development Environments (IDEs): IDEs often include debugging tools that allow you to set breakpoints, step through code, and inspect variables.
Debugging Libraries: Many programming languages provide debugging libraries or tools to assist in diagnosing issues.
Profiling Tools: Profilers help identify performance bottlenecks and resource usage problems.

3. Debugging Techniques:
Bisection Method: If you're dealing with large codebases, you can use a binary search-like approach by commenting out half of the code and checking if the issue still exists, narrowing down the problematic section.
Rubber Duck Debugging: Explaining your code or problem to someone (or something, like a rubber duck) can help you see the issue from a different perspective.
Pair Programming: Collaborating with another developer can bring fresh insights and help identify issues more efficiently.
Code Reviews: Having peers review your code can uncover errors and provide valuable feedback.

4. Reproducing the Issue:
The first step in debugging is being able to consistently reproduce the issue. Knowing the conditions under which the error occurs is crucial.

5. Systematic Approach:
Debugging often involves a systematic approach, moving step by step through the code to identify the point where the error occurs.

6. Documenting and Learning:
Keep a record of the issues you encounter, the solutions you find, and the debugging techniques that work best for you. This can serve as a valuable resource for future troubleshooting.
Debugging is an integral skill for developers, as it helps maintain code quality, identify vulnerabilities, and ensure software functions as intended. It requires patience, problem-solving skills, and a systematic approach to uncover and fix issues effectively.


## PG 1.6 Dokumentation
Documentation of a project is a vital process in software development and project management. It involves creating a comprehensive set of written materials that provide information about the project's objectives, scope, design, functionality, and implementation details. Proper documentation is essential for a project's success, as it facilitates communication, collaboration, and the long-term maintenance of the project. Here are key aspects of project documentation:

Project Objectives: Begin by clearly defining the project's goals, including the problem it aims to solve and the expected outcomes.

Scope: Document the project's boundaries, specifying what is included and what is not. This ensures that everyone has a shared understanding of the project's limitations.

Requirements: Detail the functional and non-functional requirements of the project, describing what the system should do and any performance or security considerations.

Design: Document the architectural design, data flow, user interface design, and any relevant diagrams to provide a clear picture of the project's structure.

Implementation: Describe the coding standards, technologies, and methodologies used in the development process. Include code comments and explanations for easier understanding and maintenance.

User Manuals: Create user manuals or guides that explain how to use the system. These can be invaluable for end-users, administrators, or support staff.

Testing: Document the testing procedures, test cases, and the results of testing to ensure that the project meets its requirements and performs reliably.

Troubleshooting and Support: Include documentation on common issues and their solutions, as well as contact information for support or maintenance.

Version Control: Explain the version control system and the process for tracking and managing code changes.

Project Timeline: Document the project's timeline, milestones, and deliverables to keep everyone informed about progress.

Dependencies: List any external libraries, tools, or resources used in the project, along with instructions for setting them up.

Security: Describe any security measures or considerations in place to protect the project and its data.

Legal and Compliance: Address any legal or compliance issues, including licenses, copyrights, or regulatory requirements.

Proper documentation simplifies knowledge sharing, onboarding of new team members, and ongoing maintenance. It also improves collaboration and helps to avoid misunderstandings or misinterpretations. Documentation is an investment in the project's long-term success, as it ensures that the project can be maintained and extended in the future.


## PG 1.7 Struktur av kod i projekt
The structure of code in projects is a critical aspect of software development that greatly influences code maintainability, collaboration, and scalability. A well-structured codebase is organized, easy to understand, and efficient. Here are key principles for structuring code in projects:

Modularity: Divide the code into small, reusable modules or components. This promotes a clean separation of concerns and allows developers to work on individual parts without affecting the entire codebase.

Directory Structure: Create a well-organized directory structure that reflects the project's architecture. Group related files and folders, making it easy to locate and navigate through code.

Naming Conventions: Use clear and consistent naming conventions for variables, functions, classes, and files. This promotes readability and makes it easier for team members to understand the code.

Documentation: Include comments and documentation within the code to explain complex logic, usage instructions, and any external dependencies. Documentation helps other developers understand the purpose and usage of each component.

Separation of Concerns: Isolate different aspects of the application, such as data access, business logic, and user interface, into separate layers or modules. This separation enhances maintainability and allows for changes in one area without affecting others.

Code Patterns and Best Practices: Follow established coding patterns and best practices for the programming language or framework being used. Consistency in code style and structure is essential for readability and maintainability.

Version Control: Use a version control system, like Git, to manage code changes, track history, and collaborate with others effectively. Version control helps maintain the integrity of the codebase.

Testing: Integrate testing into the codebase. Create unit tests, integration tests, and end-to-end tests to verify that the code functions correctly and continues to do so as changes are made.

Error Handling: Implement robust error-handling mechanisms to provide meaningful error messages and gracefully handle exceptions.

Configuration Management: Store configuration settings separately from the code to allow for easy configuration changes without modifying the code.

Dependencies: Manage external dependencies with package managers or dependency management tools. This simplifies the process of adding, updating, and removing libraries or frameworks.

Build and Deployment Scripts: Include automation scripts for building and deploying the project. This ensures consistency and simplifies the release process.

Security: Implement security best practices, such as input validation, authentication, and authorization, within the code to protect against vulnerabilities.

A well-structured codebase promotes code quality, simplifies maintenance, and eases collaboration among developers. It allows the project to scale effectively and adapt to changing requirements over time. Consistently following these principles in code structuring ensures that the project remains efficient and manageable throughout its lifecycle.


## PG 1.8 Automatisering av arbetsflöde
Workflow automation refers to the use of technology to streamline, optimize, and automate various business processes and tasks. This approach replaces manual, time-consuming, and often error-prone processes with efficient, automated solutions. Here are key aspects of workflow automation:

1. Process Automation: Workflow automation targets repetitive and rule-based tasks within an organization. This can include data entry, document routing, approvals, notifications, and more.

2. Benefits:
Efficiency: Automation reduces the time and effort required to complete tasks, leading to faster and more consistent results.
Error Reduction: Automation minimizes human errors, improving data accuracy and the quality of outcomes.
Resource Allocation: Employees can focus on more strategic and creative tasks while automation handles routine activities.
Compliance: Automation ensures that processes adhere to predefined rules and standards.
Visibility: Automated workflows often provide real-time insights into the status of tasks, which can help in decision-making and monitoring.
3. Tools and Platforms: Workflow automation relies on software tools and platforms designed for this purpose. Examples include:

Business Process Management (BPM) Software: BPM tools provide a framework for designing, executing, monitoring, and optimizing workflows.
Robotic Process Automation (RPA): RPA software automates repetitive and rule-based tasks, often interacting with existing applications.
Workflow Management Software: Workflow management systems facilitate the creation and tracking of workflow processes.
No-Code/Low-Code Platforms: These platforms allow non-technical users to design and deploy workflows with minimal coding.
4. Use Cases: Workflow automation can be applied across various industries and departments, including finance (e.g., invoice processing), human resources (e.g., onboarding), customer service (e.g., ticket routing), and manufacturing (e.g., supply chain management).

5. Implementation: Successful implementation involves defining the workflow, integrating with relevant systems, testing, and ongoing monitoring and improvement.

6. Challenges: Challenges include selecting the right tools, adapting existing processes, and ensuring data security.

7. Scalability: Workflow automation can scale to accommodate growing workloads and evolving business needs.

Workflow automation is a powerful strategy for organizations seeking to enhance efficiency, reduce operational costs, and improve the quality of their processes. By automating routine tasks, companies can free up their workforce to focus on higher-value activities and remain competitive in an increasingly digital and fast-paced business environment.


## PG 1.9 Virtualisering av utvecklingsmiljö
The virtualization of a development environment involves creating a self-contained, isolated virtualized system that replicates the tools, configurations, and dependencies required for software development. This technology enables developers to work in a consistent and controlled environment without the need for physical hardware. Here are key points about the virtualization of development environments:

1. Virtual Machines (VMs): Developers use virtualization software like VMware, VirtualBox, or Hyper-V to create virtual machines that run within their physical computers. These VMs act as self-contained development environments.

2. Benefits:
Isolation: VMs are isolated from the host system, preventing conflicts between development tools and the host's configuration.
Portability: Virtualized development environments can be easily moved between systems, ensuring consistency across team members.
Replication: Developers can create VM templates that include specific software configurations, making it easy to replicate the same development environment for different projects.
Resource Efficiency: VMs can be tailored to the specific resource requirements of a project, optimizing CPU, memory, and storage usage.
3. Containerization (Docker): Containerization, popularized by Docker, is another form of virtualization that uses containers to package applications and their dependencies. This approach is lightweight and more focused on application portability.

4. Use Cases:
Cross-Platform Development: Virtualization allows developers to work on different platforms (e.g., Windows, Linux, macOS) within the same environment.
Project Isolation: Each project can have its isolated development environment, preventing interference between projects.
Testing Environments: Virtualized environments facilitate testing on multiple configurations and environments, including different OS versions and browser types.
Collaboration: Teams can share development environments to ensure consistency and collaboration.
5. DevOps Integration: Virtualized development environments align well with DevOps practices, as they enable the creation of consistent and reproducible development, testing, and production environments.

6. Cloud-Based Development: Cloud providers offer virtualized development environments in the form of cloud-based development platforms (Platform as a Service - PaaS) or Infrastructure as a Service (IaaS) offerings that support VMs and containers.

7. Challenges: Managing and maintaining virtualized development environments, especially in complex projects with multiple dependencies, can be challenging. Version control of environment configurations is crucial.

Virtualization of development environments enhances the efficiency and consistency of the development process, making it easier to manage dependencies and ensure that software works reliably across different systems. Whether using VMs or containers, virtualization is a valuable practice for developers and DevOps teams.

## PG 1.10 Bundeling-verktyg
Beskriv rubriken här

## PG 1.11 Terminalinterface
A terminal interface, often referred to as a command-line interface (CLI) or text-based interface, is a means of interacting with a computer or software through text commands rather than a graphical user interface (GUI). It provides a direct and efficient way to control and manage a computer, operating system, or software application. Here are key points about terminal interfaces:

Text Commands: Users interact with the system by typing text-based commands into a terminal or console. These commands are typically issued in a specific syntax to perform tasks, configure settings, or access information.

Efficiency: Terminal interfaces are known for their efficiency, as they allow experienced users to perform tasks quickly without the overhead of graphical elements.

Scripting: Terminal interfaces are scriptable, enabling users to create and automate complex tasks through scripts or batch files. This is valuable for repetitive or system administration tasks.

Server Administration: Terminal interfaces are commonly used for server administration, allowing remote control and management of servers over networks.

Operating System Control: Users can interact with the core functions of an operating system using terminal commands. This includes file management, user account control, and software installation.

Software Development: Developers often use terminal interfaces for programming, version control (e.g., Git), compiling code, and running tests.

Debugging and Troubleshooting: Terminal interfaces provide extensive diagnostic tools for debugging and troubleshooting system or application issues.

Customization: Users can customize their terminal environment by modifying configurations, installing plugins, and choosing color schemes and fonts.

Cross-Platform: Terminal interfaces are available on various operating systems, including Linux, macOS, and Windows (using tools like PowerShell).

Accessibility: For users with visual impairments, terminal interfaces can be more accessible and screen-reader-friendly than GUIs.

Learning Curve: While efficient, terminal interfaces can have a steeper learning curve, as users need to learn specific commands and syntax.

Terminal interfaces have enduring popularity, especially among power users, system administrators, developers, and those who value the precision and control they offer. They remain a fundamental tool in computer technology, alongside graphical user interfaces, and are often used in combination with them to provide a versatile computing experience


