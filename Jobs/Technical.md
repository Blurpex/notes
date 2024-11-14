## software development cycle
#### steps
1. **planning**: project scope, objectives, and feasibility
2. **requirement analysis**: gather and analyze business requirements and file them into a Software Requirement Specification document
3. **design**: translate requirements into a detailed design which might include data models, UI, and system architecture
4. **implementation**: convert the design into functional software
5. **testing**: ensure the software is free of defects and meets requirements. Some types of testing are unit testing, integration testing, and user acceptance testing.
6. **deployment & maintenance**: release the software to production environment and provide ongoing support and enhancements.
#### methods
- **waterfall model**: a sequential approach where each phase must be completed before the next begins; although its easy to follow its not very flexible and has a lot of downtime
- **agile model**: when you break project into smaller parts called sprints and at the end of that sprint, the team delivers a working piece of the software. it emphasizes flexibility, customer collaboration and rapid delivery
---
## database
#### normalization
1. **first normal form**: 
	- a single cell must not hold more than one value
	- there must be a primary key
	- no duplicated rows or columns
2. **second normal form**:
	- attributes that are not primary key must depend on the whole primary key
	- there should not be partial dependency
3. **third normal form**: 
	- should not have transitive partial dependency which happens when a non-key column depends on another non-key column instead of depending on the primary key
4. **forth normal form**:
	- stricter version of third normal form
	- aka Boyce-Codd normal form
	- no multi-valued dependencies
	- ensure that sets of values that are independent of each other are stored in separate tables
5. **fifth normal form**: 
	- 
---
## object oriented programming
- **class**: a blueprint got creating objects
- **object**: an instance of a class
- **encapsulation**:
	- the practice of keep fields within a class private
	- provide access to them via getter methods and setter methods
	- prevents accidental modification of data
- **inheritance**: 
	- a mechanism by which one class (child class) can inherit the properties and methods of another class (parent class)
	- allows for code reuse and the creation of hierarchical relationships between classes.
- **polymorphism**:
	- the ability to present the same interface for different underlying data types
	- allows methods to do different things based on the object is it acting upon
- **abstraction**: 
	- the concept of hiding complex implementation details and showing only the necessary features of an object.
- **abstract class**:
	- a class that cannot be instantiated on its own
	- can have both abstract methods (methods with no body) and non-abstract methods
	- a class can only inherit one abstract class
	- can have instance variables
	- you `extend` abstract class
	- methods can be public, protected, or private
- **interface**:
	- can have only abstract methods
	- a class can inherit multiple interfaces
	- cannot have instance variables
	- you `implement` abstract class
	- methods are public
---
## application programming interface (API)
- interface that allows different software applications to communicate with each other
#### API protocols
- **REST**: 
	- relies on client/server approach what works over http
	- uses standard HTTP methods like GET, POST, PUT, PATCH, and DELETE
	- stateless and usually return data in either JSON or XML format
- **GraphQL**: 
	- developer by Meta
	- allows clients to request exactly the data that they need
- **Websockets**: 
	- bidirectional communication over a single TCP connection
	- ideal for real-time data communication
- **gRPC**: 
	- developed by Google
	- ideal for communication between servers especially in a microservices architecture
- **message queues**:
	- provides asynchronous communication
	- ideal for event driver architecture
	- the protocol varies, some of them include AMQP and Kafka
--- 
## AI
#### large language models (LLM)
- advanced AI models designed to process and generate human like text
- based on deep learning architectures like transformers
---
## algorithms
#### data structure time complexity
![[Pasted image 20241113183808.png]]
#### array time complexity
![[Pasted image 20241113183831.png]]
#### algorithms
-  
---
## testing
- **unit testing**
	- testing individual components or modules of a software application
	- JUnit
- **integration testing**
	- testing the interactions between integrated units or components
	- JUnit
- **system testing**
	- testing the complete and integrated system as a whole
	- selenium
- **user acceptance testing**
	- test performed at the final phase of the software testing process where software is tested in the real-world by the end users to ensure it meets their requirements and works as intended

## manipulate data on a web page (dom, mvc)

difference Scrum and waterfall mode/development;advantage and disadvantage of cloud;difference between primary key and foreign key
What are the assumptions of linear regression?
The processes of technology implementation.
how do you build an object. What are the different operators you can use in functions. What are self-invoking functions
abstract class
	var and contraint in js
	purpose of error handling
	What is trigger order of executions?