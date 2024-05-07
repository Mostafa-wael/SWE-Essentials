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

You should familairize yourself with

- **SOLID principles**: These are five principles that help you write clean, maintainable, and scalable code.
  - **Single Responsibility Principle**: A class should have only one responsibility.
  - **Open/Closed Principle**: A class should be open for extension but closed for modification.
  - **Liskov Substitution Principle**: Objects of a superclass should be replaceable with objects of a subclass without affecting the behavior of the program.
  - **Interface Segregation Principle**: A client should not be forced to implement an interface that it does not use.
  - **Dependency Injection Principle**: High-level modules should not depend on low-level modules. Both should depend on abstractions.
- **DRY (Don't Repeat Yourself) principle**: This principle states that you should not repeat the same code in multiple places in your codebase.
- **KISS (Keep It Simple, Stupid) principle**: This principle states that you should keep your code simple and easy to understand.
- **YAGNI (You Aren't Gonna Need It) principle**: This principle states that you should not add functionality to your codebase until you actually need it.

### Version Control & Code Registries

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

## Back-end

## How web works?

You should have a good understanding of how the web works and the OSI model. This includes understanding the client-server model, `HTTP protocol`, `RESTful APIs`, etc. You should be familiar with web technologies like HTML, CSS, JavaScript, and how they work together to build web applications. You should also be familiar with web servers, `DNS`, `hosting`, and `deployment`.

You should be familiar with common web development tools like `Chrome DevTools`, `Postman`, `VS Code`, etc. You need to understand the status codes of HTTP, the difference between the different types of requests (`GET`, `POST`, `PUT`, `DELETE`, etc.), and how cookies and sessions work.

## Networking

You should have a good understanding of networking concepts like IP addresses, `TCP/IP`, `DNS`, `HTTP`, etc. This is essential for building scalable and secure applications. You should be able to troubleshoot network issues, optimize network performance, and secure your applications against network attacks.

You should be familiar with common networking tools like `ping`, `traceroute`, `iptables`, etc. You should also be familiar with common network security concepts like firewalls, VPNs, encryption, etc.

## Communication Protocols

You should be familiar with common communication protocols like `REST`, `SOAP`, `gRPC`, `GraphQl`, etc. These protocols are used to define the rules that govern communication between different systems. You should be able to design and implement APIs that follow these protocols. You should also be familiar with tools like `Postman`, `Swagger`, etc. that help you test and document APIs.

## Web Servers

You should be familiar with common web servers like `Apache`, `Nginx`, `Tomcat`, etc. You should be able to configure these servers, optimize their performance, and secure them against attacks. You should also be familiar with concepts like load balancing, caching, etc. that help you scale your applications.

## Databases

You should be familiar with common databases like MySQL, PostgreSQL, MongoDB, etc. You should be able to design and implement database schemas, write efficient queries, and optimize database performance. You should also be familiar with concepts like normalization, indexing, transactions, etc.

You should be familiar with common database management tools like `phpMyAdmin`, `pgAdmin`, `adminer`, etc.

You may need to learn about stored procedures, triggers, views, etc. that help you implement complex database logic.

You may also need to dive deep in the query engine of the database you are using. For example, you may need to understand how the query engine of MySQL works, how query plans are generated, etc.

You may need to learn about ORM (Object Relational Mapping) tools like `SQLAlchemy`, `Hibernate`, etc. that help you interact with databases using an object-oriented approach.

## Linux

You should be familiar with the Linux operating system. Linux is widely used in the software industry for hosting web servers, databases, etc. You should be able to work with the Linux command line, install packages, configure services, etc. You should also be familiar with common Linux distributions like `Ubuntu`, `CentOS`, etc.

Understanding Linux will help you troubleshoot server issues, optimize server performance, and secure your applications.

You need to learn about common Linux commands like `ls`, `cd`, `pwd`, `cp`, `mv`, `rm`, `mkdir`, `rmdir`, `chmod`, `chown`, etc.

You should also be familiar with common Linux tools like `grep`, `sed`, `awk`, `top`, `htop`, `netstat`, `ifconfig`, etc.

You may need to learn about shell scripting that helps you automate common tasks on Linux. In addition, you may need to learn about system administration tasks like setting up users, groups, permissions, etc.

It would be great to learn about file systems, processes, memory management, monitoring, etc. in Linux.

## Parallel Programming

You should be familiar with parallel programming concepts. Parallel programming is essential for writing code that takes advantage of multi-core processors. You should be able to write code that runs multiple tasks concurrently and communicates between them. You should be familiar with common parallel programming models like threads, processes, locks, semaphores, etc.

You should be familiar with common parallel programming libraries like `OpenMP`, `MPI`, `Pthreads`, etc.

## Docker

Docker is a containerization platform that helps you build, ship, and run applications in a consistent environment. You should be familiar with Docker concepts like containers, images, volumes, networks, etc. You should be able to create Dockerfiles, build Docker images, run Docker containers, and manage Docker resources.

You should be familiar with common Docker commands like `docker build`, `docker run`, `docker ps`, `docker exec`, `docker stop`, `docker rm`, `docker rmi`, etc.

## Continuous Integration/Continuous Deployment (CI/CD)

CI/CD is a software development practice that helps you automate the process of building, testing, and deploying applications. You should be familiar with CI/CD tools like `Jenkins`, `Github Actions`, `CircleCI`, etc. You should be able to create pipelines that automate the process of building, testing, and deploying your applications.

## Testing

You should be familiar with common testing techniques like unit testing, integration testing, Test Driven Development, end-to-end testing, etc. You should be able to write test cases, run tests, and analyze test results. You should also be familiar with testing frameworks like `JUnit`, `Jest`, `Mocha`, `PyTest`, etc. that help you automate the testing process.

You may also be familiar with common testing tools like `Selenium`, `Cypress`, etc. that help you test web applications.

You should be familiar with common testing concepts like mocking, stubbing, spying, etc. that help you isolate the code you are testing.

## Linting

...

## Documentation

You should be able to write clear and concise documentation for your code. This includes writing comments, README files, API documentation, etc. You should be able to explain your code to other developers and users. You should also be familiar with documentation tools like `Swagger`, `Doxygen`, `Pydocs`, etc.

## System Design

You should be able to design scalable and maintainable systems. This includes understanding the requirements of the system, designing the architecture, and choosing the right technologies. You should be able to design systems that are fault-tolerant, scalable, and secure. You should be familiar with common system design concepts like load balancing, caching, sharding, replication, etc.

You need to learn about

- Architectural Design Patterns: layered architecture, microservices, monolithic, event-driven, microkernel, etc.
- Deployment Patterns: big bang deployment, blue-green deployment, canary deployment, rolling deployment, feature toggles, etc.
- Distributed Systems Patterns: ambassador, side car, circuit breaker, leader election, pub-sub, event sourcing, etc.
- Distributed Systems: CAP theorem, ACID, BASE, etc.
