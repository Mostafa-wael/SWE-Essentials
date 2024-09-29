# What you should know as a software engineer?

## Introduction

Welcome to the ever-evolving world of software engineering! In this dynamic field, staying updated with the latest trends and technologies is key to maintaining your competitive edge. Nevertheless, there are foundational principles that every software engineer must grasp, regardless of their specialization. While this article may lean towards backend development, rest assured, these concepts are universally applicable across all software engineering domains. So, let's start!

## Basics

### Programming Language

As software engineers, our primary tool and asset is the programming language. Proficiency in at least one programming language is a fundamental requirement for success in this field. Your goal should be to write code that is not only functional but also clean, efficient, and easily maintainable. It's crucial to familiarize yourself with the best practices of your chosen language and adhere to them. Additionally, having a solid understanding of common data structures and algorithms in your language of choice is essential.

Consider the following languages and their respective advantages:

- **Cpp/Golang**: Ideal for high-performance computing and systems programming. C++ is commonly used in game development and system-level programming, while Golang excels in building scalable, concurrent systems.

- **Python**: Simple and beginner friendly, and is widely used in various domains such as web development, data science, machine learning, and automation.

- **JavaScript/Typescript**: JavaScript is the backbone of web development, enabling dynamic and interactive web applications. Typescript, a superset of JavaScript -For now-, adds static typing and other features for building robust web applications.

- **Java/C#**: Both Java and C# are powerful object-oriented languages used for building enterprise-level applications, desktop software, and Android (Java) and Windows (C#) applications.

Once you've mastered one language, you'll find it easier to pick up new ones quickly. This adaptability is crucial for staying abreast of emerging technologies and remaining competitive in the ever-evolving job market.

### Object-Oriented Programming

Once you've gained proficiency in a programming language, diving into object-oriented programming (OOP) concepts becomes essential. Understanding OOP is important for crafting code that is modular, extensible, and easy to maintain. OOP involves designing classes and objects that emulate real-world entities, facilitating a structured and intuitive approach to software development.

Key concepts in OOP include:

- **Abstraction**: Keeping complex implementation details within a class and just giving relevant information to external entities.
- **Encapsulation**: Cohesively bundling data and methods within a class, shielding internal complexities from external interference.
- **Inheritance**: Building upon existing class code to create new classes, fostering code reuse and establishing hierarchy within the codebase.
- **Polymorphism**: Granting objects the capability to exhibit multiple forms, facilitating dynamic behaviour and enhancing code flexibility.

It's important to note that while OOP is a widespread paradigm, it's not the only approach to software development. Other paradigms like functional programming and declarative programming also exist, each with its own set of advantages and use cases. The choice of paradigm depends on the specific requirements of the project. Always remember the adage: "*To the man with only a hammer, every problem looks like a nail.*" Accept variety in your approach to coding, tailoring your techniques to the needs of each project.

### Data Structures and Algorithms

Now that you've developed your programming skills and explored the world of object-oriented programming, along the way, you've likely encountered built-in classes that aid in your coding endeavours. These, fall under the umbrella of data structures.

Data structures and algorithms serve as the backbone of efficient code. Imagine them as the tools in your toolbox, each serving a specific purpose. Your goal? To wield these tools adeptly, selecting the right one for the job and implementing algorithms that crack problems with finesse.

Essential data structures include:

- **Arrays**: Simple yet powerful, arrays provide a foundation for storing and accessing data efficiently.
- **Linked Lists**: Dynamic and versatile, linked lists excel in scenarios requiring frequent insertions and deletions.
- **Stacks and Queues**: These fundamental structures facilitate orderly data manipulation, be it through last-in-first-out (LIFO) or first-in-first-out (FIFO) operations.
- **Trees**: Hierarchical structures that lay the groundwork for complex data organization and manipulation.
- **Hash Tables**: The cornerstone of efficient data retrieval, hash tables offer lightning-fast access to stored information.
- **Graphs**: Networks of interconnected nodes that open doors to a myriad of problem-solving possibilities.

Core algorithms encompass:

- **Sorting algorithms**: From the classic Bubble Sort to the efficient Merge Sort, mastering sorting techniques is crucial for maintaining order in your data.
- **Searching algorithms**: Whether you're traversing sorted arrays with Binary Search or scanning unsorted lists with Linear Search, efficient searching is a skill every programmer must possess.
- **Dynamic Programming**: Tackling complex problems by breaking them down into simpler subproblems and storing their solutions for efficiency.
- **Recursion**: Embracing the beauty of self-referential functions to solve problems in a succinct and elegant manner.
- **Divide and Conquer**: Conquering complexity by breaking it down into smaller, more manageable chunks.
- **Graph algorithms**: Traversing the intricate pathways of BFS, the depth of DFS, or finding the shortest path with Dijkstra's algorithm, your journey through graphs is well-guided.
- **Greedy Algorithms**: Making optimal choices at each step to achieve the best overall solution.
- **Backtracking**: Exploring all possible paths to find solutions, even if it means backtracking from dead ends.
- **Bit Manipulation**: Unleashing the power of individual bits for efficient storage and manipulation.
- **String algorithms**: Harnessing the magic of characters to manipulate and analyze textual data with finesse.

But wait, there's more! Understanding the time and space complexity of your algorithms is crucial. It's like understanding the fuel efficiency of your car—it helps you optimize performance when the road gets rough.

Lastly, don't forget to forge connections between theory and practice. Understand that the dictionary data structure in Python is essentially a hash table, while a list behaves like an array. These connections will not only deepen your understanding but also enhance your ability to wield your chosen programming language with finesse.

As you embark on this journey, remember that every concept you grasp, every algorithm you master, brings you one step closer to unlocking the true potential of your craft. So, brace yourself, adventurer, for the world of data structures and algorithms awaits—full of challenges, discoveries, and endless possibilities.

### Design Patterns

Ah, as you journey continues, you begin to notice recurring themes and challenges in your projects. But fear not, for where there are problems, there are also solutions—design patterns, to be precise.

Consider design patterns to be time-tested blueprints that will lead you to elegant and efficient solutions to typical software design challenges. With their help, you may create code that is not only easier to maintain, but also more adaptable and scalable.

Let's delve into the three realms of design patterns:

- **Creational Patterns**: Think of these as blueprints for object creation, tailored to suit different scenarios.
  - **Singleton**: Ensuring a class has only one instance and providing a global point of access to it.
  - **Factory**: Creating objects without specifying the exact class of object to be created, allowing for flexibility and decoupling.
  - ...

- **Structural Patterns**: Here, we're concerned with how objects are composed and connected.
  - **Adapter**: Bridging the gap between incompatible interfaces, allowing them to work together seamlessly.
  - **Facade**: Providing a simplified interface to a complex system, shielding clients from its intricacies.
  - **Proxy**: Acting as a surrogate or placeholder for another object, controlling access to it.
  - ...

- **Behavioral Patterns**: Dive into algorithms and object interactions with these patterns.
  - **Observer**: Establishing a one-to-many dependency between objects, ensuring that when one object changes state, all its dependents are notified and updated automatically.
  - **Strategy**: Encapsulating a family of algorithms and making them interchangeable, allowing clients to choose algorithms dynamically at runtime.
  - **Chain of Responsibility**: Passing a request along a chain of handlers, with each handler having the option to process the request or pass it to the next handler in the chain.
  - ...

But here's the beauty of design patterns—they're not holy books! Feel free to tweak and tailor them to fit your unique needs. In fact, you might find that combining multiple patterns yields the perfect solution to your problem.

Let design patterns serve as your compass as you navigate the broad world of software design. With their guidance, you'll create solutions that not only tackle problems but also take your code to new heights of elegance and efficiency. 

### Clean Code

You aren't working alone on your projects anymore, your code must be  clean, readable, and maintainable so that others -including you future self- can continue developing and maintaining it. This is essential for working in a team environment where multiple developers are working on the same codebase. You should follow best practices like writing self-explanatory code, using meaningful variable names, writing comments, and following coding conventions.

You should familiarize yourself with

- **SOLID principles**: These are five principles that help you write clean, maintainable, and scalable code.
  - **Single Responsibility Principle**: A class should have only one responsibility.
  - **Open/Closed Principle**: A class should be open for extension but closed for modification.
  - **Liskov Substitution Principle**: Objects of a superclass should be replaceable with objects of a subclass without affecting the behavior of the program.
  - **Interface Segregation Principle**: A client should not be forced to implement an interface that it does not use.
  - **Dependency Injection Principle**: High-level modules should not depend on low-level modules. Both should depend on abstractions.
- **DRY (Don't Repeat Yourself) principle**: This principle states that you should not repeat the same code in multiple places in your codebase.
- **KISS (Keep It Simple, Stupid) principle**: This principle states that you should keep your code simple and easy to understand.
- **YAGNI (You Aren't Gonna Need It) principle**: This principle states that you should not add functionality to your codebase until you actually need it.

### Version Control(Git)

Now that you've honed your coding skills, you can agree that making wrong turns and removing files unintentionally, is one of our worst nightmares. But, fear nor, version control is your faithful friend that have your back.

Here's your compass:

- **Version Control**: You should be familiar with version control systems like Git. Version control is essential for tracking changes in your codebase and collaborating with other developers. You should be able to create branches, merge changes, resolve conflicts, and work with remote repositories. You should also be familiar with common Git commands like `git clone`, `git pull`, `git push`, `git commit`, `git checkout`, etc.
- **Code Registries**: After becoming familiar with version control, you may need to learn more about code registries like `Github`, `Bitbucket`, `Gitlab`, etc. This will help you share your code with other and collaboratively develop your projects with your team. 

### Frameworks and Libraries

Finally, you are ready to learn more about frameworks and libraries in your programming language. Frameworks and libraries help you build applications faster by providing pre-written code for common tasks. You should be able to use these frameworks and libraries effectively to build scalable and maintainable applications.

For example:

- **Python developers**: You may be familiar with frameworks like **Django**, **Flask**, etc. In addition to libraries like **NumPy**, **Pandas**, etc. 
- **JavaScript developers**: You may be familiar with **Node.js**, **Express**, etc.
- **Java developers**: You may be familiar with **Spring boot**, etc.
- **C# developers**: You may be familiar with **.NET Core**, **ASP.NET**, etc.

## Three Important Pillars

### Testing: The Key to Reliable Software
Testing is essential for maintaining code quality and preventing bugs.

- **Unit Testing**, **Integration Testing**: Write tests for individual components and how they interact. You may need to use tools like: `JUnit`, `Jest`, `Mocha`, and `PyTest`.
- **E2E Testing Tools**: Familiarize yourself with E2E testing tools, it may save you a lot of time and effort like `Selenium`, and `Cypress`,.
- **Mocking & Stubbing**: Learn these concepts to isolate the parts of your code you want to test.

Good testing practices lead to more reliable software and fewer bugs in production.

### Linting: Keeping Your Code Consistent
Linting helps enforce coding standards across your project. Tools like `Pylint`, `ESLint`, and `Checkstyle` ensure that your code is clean, readable, and maintainable.

- **Code Styling**: Establish consistent rules for your project’s code style, like naming conventions and code formatting.
Linting is crucial when working in teams to keep the codebase clean and avoid inconsistencies.

### Documentation: Explaining Your Work to the World
Clear documentation is vital for helping others (and your future self) understand your code.

- **Documentation Tools**: Tools like `Doxygen`, and `Pydocs` can help you generate code documentation. Tools like `Swagger` helps you generate API documentation. 
- **READMEs**: A well-written README file provides essential details about how your project works.
- **CHANGELOGs**: A well-written CHANGELOG file provides essential details about how your project evolves and makes it easier to keep track with the changes and why we needed them.

Good documentation improves the usability of your code and enhances team collaboration.

## Essentials to become a hero!

### How the Web Works: Your First Stop on the Journey
Before we dive into building systems, it's essential to understand how the web works. Picture the web as a vast communication network between clients and servers, using the OSI model as a framework for interactions.

- **Client-Server Model**: At the heart of the web, you’ll find this model. Your browser (the client) sends requests to a web server, and the server responds with data (like a web page).
- **HTTP Protocol**: The lifeblood of the web, HTTP governs how clients and servers communicate.
- **APIs**: These define how systems should interact over the web, providing a clear set of guidelines for communication.

To succeed as a back-end engineer, you must also know the tools that streamline this process, such as `Chrome DevTools`, `Postman`, `VS Code`. Understanding HTTP status codes and methods (GET, POST, PUT, DELETE) is crucial, along with knowing how cookies and sessions manage user data. These are your tools for creating interactive web experiences.

### Networking: The Web’s Backbone
The backbone of the internet is networking. As a back-end engineer, you need a solid grasp of networking concepts.

- **IP Addresses, DNS, and TCP/IP**: These allow your applications to communicate over the web. Understanding them is key to building scalable and secure apps.
- **Network Troubleshooting & Security**: Learn tools like `ping`, `traceroute`, `iptables`. Dive into network security concepts like firewalls, VPNs, and encryption to secure your systems.
In the end, good networking knowledge will not only help you resolve connectivity issues but also ensure your applications perform smoothly under different conditions.

### Communication Protocols: Establishing Clear Rules for Interaction
Communication protocols define how systems talk to each other. As a back-end engineer, you should be comfortable with common protocols like:

- **REST**: Simple and stateless, used widely in web development.
- **SOAP**: A more rigid, protocol-based communication system.
- **gRPC**: Modern, efficient, and often used for microservices.
- **GraphQL**: Offers more flexible data querying, which is popular in modern APIs.
Tools like `Postman` and `Swagger` are essential for designing, testing, and documenting these APIs. Mastering these protocols ensures you can build/choose APIs that communicate effectively across systems.

### Web Servers: The Gatekeepers of Your Applications
Your back-end code runs on web servers. It’s essential to get acquainted with popular servers like `Apache`, `Nginx`, and `Tomcat`.

- **Configuration**: Learn how to configure these servers to host your applications.
- **Performance Optimization**: Techniques like load balancing and caching ensure that your applications can handle high traffic without crashing.
- **Security**: Securing web servers is crucial to prevent attacks.
Whether you're hosting a simple website or a complex application, understanding web servers is key to delivering a reliable and secure experience to users.

### Linux: The Foundation of the Modern Web
Most back-end systems run on Linux. To become an effective back-end engineer, you must be comfortable with Linux commands and administration. You should be able to work with the Linux command line, install packages, configure services, etc. You should also be familiar with common Linux distributions like `Ubuntu`, `CentOS`, etc.

- **Basic Commands**: Familiarize yourself with basic commands (`ls`, `cd`, `pwd`, `cp`, `mv`, `rm`, `mkdir`, `rmdir`, `chmod`, `chown`).
- **Common handy tools**:  Familiarize yourself with (`grep`, `sed`, `awk`, `top`, `htop`, `netstat`, `ifconfig`) and how to use them. 
- **System Administration**: Set up users, configure services, and manage permissions.
- **Scripting**: Shell scripts allow you to automate tasks like backups, deployments, and system monitoring.
 
A solid understanding of Linux ensures that you can manage servers and applications with confidence

### Parallel Programming: Unlocking Multi-Core Power
Modern systems often require concurrent execution of tasks. Understanding parallel programming is essential for improving efficiency and performance.

- **Threads**, **Processes**, **Locks**: Learn how to write concurrent programs using these concepts.
- **Libraries**: Explore libraries like `OpenMP`, `MPI`, and `Pthreads` to help you in parallel processing.

With parallel programming, you can build systems that take full advantage of modern multi-core processors.

### Docker: Containerizing Your Applications
In the world of modern software, Docker has become essential. Docker allows you to package your application and its dependencies into a container, ensuring it runs consistently across environments.

- **Containers**, **Networking**, and **Volumes**: Master these concepts to package your application.
- **Docker Commands**: Learn essential commands like `docker build`, `docker run`, `docker ps`, `docker exec`, `docker stop`, `docker rm`, and `docker rmi`.
- **Docker-Compose**: A more organized way to handle multiple docker containers/resources and their configurations.

Understanding Docker is crucial for deploying scalable and reliable applications in any environment.

### Databases: Where Your Data Lives
Databases store and manage the data your applications rely on. As a back-end engineer, you should be comfortable with both SQL databases (like MySQL, and PostgreSQL) and NoSQL databases (like MongoDB).

- **Schema Design & Optimization**: Designing efficient database schemas and optimizing performance through **indexing**, **normalization**, and **query optimization** are must-have skills. You can achieve this by diving deeper into the query engine and understand how things work behind the hood e.g. how query plans are generated, how redo/undo works and so on. 
- **ORMs(Object Relational Mapping)**: Tools like `SQLAlchemy`, and `Hibernate` help you interact with databases using object-oriented paradigms i.e. programming languages.
- **Stored Procedures**, **Triggers**, **Views**: Learn about these to implement complex database logic.
- **Management Tools**: You should be familiar with common database management tools like `phpMyAdmin`, `pgAdmin`, or `adminer`.
- **Distributed Database Concepts**: understand concepts like **CAP** theorem, **ACID**, **BASE**, database **sharding**, database **replication**, etc.

A solid database foundation ensures your applications handle data efficiently and scale well.

### Continuous Integration/Continuous Deployment (CI/CD): Automating Your Workflow
CI/CD tools like `Jenkins`, `Github Actions`, `CircleCI`, and `Bitbucket Pipeline` automate the process of building, testing, and deploying applications.

- **Deployment**: Learn how to create pipelines that automate your deployment process.
- **Testing Integration**: Integrate unit tests into your CI/CD pipelines to ensure code quality.
- 
Mastering CI/CD ensures your applications are deployed faster and with fewer errors.

## Monster Level

### Security: Protecting Your Applications and Data
Security is a fundamental aspect of any software development process. As a back-end engineer, you need to ensure that your applications are secure and resistant to various types of attacks. 

- **Storing Passwords**: Storing passwords securely is critical to protecting user data. Learn about:
  - Hashing: Instead of storing passwords in plaintext, you should hash them using algorithms like bcrypt, Argon2, or PBKDF2. These algorithms are designed to be slow, making brute-force attacks harder.
  - Salting: Add a unique salt to each password before hashing. This prevents attackers from using precomputed hash tables (rainbow tables) to crack passwords.
- **Authentication**: This is the process of verifying the identity of a user. Learn about:
  - Username & Password: The most common form of authentication.
  - Multi-Factor Authentication (MFA): Adds a second layer of authentication, typically using a code sent to the user’s phone or an authentication app.
  - OAuth2: A popular protocol for third-party authentication (e.g., logging in with Google, or Facebook).
- **Authorization**: This process determines what an authenticated user is allowed to do. Learn about:
  - Role-Based Access Control (RBAC): Users are assigned roles that define their permissions.
  - Access Control Lists (ACL): A more fine-grained approach where specific permissions are assigned to individual resources.
- **Cookies**, **Tokens**, and **Sessions**: Managing User State:
  - Cookies: Small pieces of data stored in the user's browser, often used for session management, authentication, and personalization. Cookies should be HttpOnly and Secure to prevent attacks like `XSS` (Cross-Site Scripting).
  - Sessions: Server-side storage that tracks user data during their interaction with an application. Sessions are often linked to a cookie.
  - Tokens: Commonly used in stateless authentication (e.g., `JWT`). Tokens are signed data that can be verified by the server to authenticate users.
- **Security in the Development Lifecycle**: Integrate Security Early
  - Security Testing: Incorporate security testing into your development lifecycle through tools like `OWASP ZAP`, `Burp Suite`, or `Snyk`.
  - Static Application Security Testing (SAST): Use automated tools to scan your codebase for security issues.
- **Common Security Threats**: Recognize and Defend
  - **SQL Injection**: Attackers insert malicious SQL code into your queries, allowing them to view or manipulate your database. Prevention strategies:
    - Use prepared statements and parameterized queries.
    - Always validate and sanitize user inputs.
  - **Cross-Site Scripting (XSS)**: Attackers inject malicious scripts into web pages viewed by other users. To prevent XSS:
    - Escape all user input before rendering it in HTML.
    - Use libraries like DOMPurify to sanitize HTML inputs.
  - **Cross-Site Request Forgery (CSRF)**: Attackers trick users into performing actions they didn't intend to. To prevent CSRF:
    - Use CSRF tokens in forms and requests.
    - Validate the Origin or Referer headers.
  - **Man-in-the-Middle (MitM) Attacks**: Attackers intercept and possibly alter the communication between two parties. To prevent this:
    - Always use HTTPS to encrypt traffic.
    - Implement SSL/TLS for secure communication.
  - **Brute Force Attacks**: Attackers try multiple combinations of passwords until they find the correct one. Mitigations include:
    - Implement rate limiting to slow down repeated login attempts.
    - Use CAPTCHAs to detect and block automated login attempts.

### System Design: Crafting Large-Scale Solutions
You should be able to design scalable and maintainable systems. This includes understanding the requirements of the system, designing the architecture, and choosing the right technologies. You should be able to design systems that are fault-tolerant, scalable, and secure. You should be familiar with common system design concepts like load balancing, caching, sharding, replication, etc.

- **Architectural Patterns**: Learn patterns like layered architecture, microservices, monolithic, event-driven, microkernel, etc.
- **Deployment Patterns**: Learn Techniques like big bang deployment, blue-green deployment, canary deployment, rolling deployment, feature toggles, etc. 
- **Distributed Systems Patterns**: Understand patterns for building large-scale systems, such as leader election, circuit breaker, event sourcing, ambassador, sidecar, pub-sub, etc.
- **Distributed Systems Components/Concepts**: Load balancers, proxies, caches, SSL termination, DNS propagation, etc.


