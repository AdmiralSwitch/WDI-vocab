WDI Vocab
=========


## Dynamic Dispatch

* The process of selecting which implementation of a polymorphic operation (method or function) to call at runtime.
* Dynamic dispatch contrasts with static dispatch in which the implementation of a polymorphic operation is selected at compile-time.
* The purpose of dynamic dispatch is to support cases where the appropriate implementation of a polymorphic operation can't be determined at compile time because it depends on the runtime type of one or more actual parameters to the operation.

[Wikipedia: Dynamic Dispatch](http://en.wikipedia.org/wiki/Dynamic_dispatch)


## Protocols

* In object-oriented programming, a **protocol or interface** is a common means for unrelated objects to communicate with each other. These are definitions of methods and values which the objects agree upon in order to cooperate.

[Wikipedia: Protocol (Object-Oriented Programming)](http://en.wikipedia.org/wiki/Protocol_(object-oriented_programming))

* A **routing protocol** specifies how routers communicate with each other, disseminating information that enables them to select routes between any two nodes on a computer network.

[Wikipedia: Routing Protocol](http://en.wikipedia.org/wiki/Routing_protocol)


## NoSQL

* A NoSQL or **Not Only SQL** database is a non-relational database. Motivations for this approach include simplicity of design, horizontal scaling and finer control over availability.
* Examples of NoSQL data structures include key-value, graph, or document. Depending on the problem, some operations are faster in NoSQL than in a relational database.

[Wikipedia: NoSQL](http://en.wikipedia.org/wiki/NoSQL)

[List of NoSQL Databases](http://nosql-database.org/)


## Heap Memory

* The portion of memory where dynamically allocated memory resides (i.e. memory allocated via [malloc](http://stackoverflow.com/questions/1213403/what-is-malloc-doing-in-this-code)).
* Memory allocated from the heap will remain allocated until one of the following occurs:
	* The memory is free'd
	* The program terminates
	
[Stack Overflow: What is a memory heap?](http://stackoverflow.com/questions/2308751/what-is-a-memory-heap)


## Prototype-Based Programming

* A style of object-oriented programming in which behaviour reuse (known as inheritance) is performed via a process of cloning existing objects that serve as prototypes.

[Wikipedia: Prototype-Based Programming](http://en.wikipedia.org/wiki/Prototype-based_programming)


## Law of Demeter (LoD)

* The Law of Demeter (LoD) or **principle of least knowledge** is a design guideline for developing software, particularly object-oriented programs. It can be succinctly summarized by the following: *Each unit should have only limited knowledge about other units: only units "closely" related to the current unit.*
* The fundamental notion is that a given object should assume as little as possible about the structure or properties of anything else (including its subcomponents), in accordance with the principle of ["information hiding"](http://en.wikipedia.org/wiki/Information_hiding).

[Wikipedia: Law of Demeter](http://en.wikipedia.org/wiki/Law_of_Demeter)


## Kleene Plus (the plus sign)

* In regular expressions, the Kleene Plus (+) means "in any length, larger than zero."

[Udacity: Difference between * and +](http://forums.udacity.com/questions/7009162/can-anyone-explain-difference-between-and-in-regular-expression)


## Node

* In general, a node is a **device or data point on a larger network**. On the internet, a node is anything with an IP address. In reference to data structures, a node is an individual part of a larger data structure.

[Wikipedia: Node (Computer Science)](http://en.wikipedia.org/wiki/Node_(computer_science))

* Node.js is a cross-platform runtime environment for server-side and networking applications. Node.js applications are written in JavaScript.
* Node.js applications are designed to maximize throughput and efficiency, using non-blocking I/O and asynchronous events. It is commonly used for real-time applications due to its asynchronous nature.

[Wikipedia: Node.js](http://en.wikipedia.org/wiki/Node.js)


##Primitive Data Types

* In computer science, a **primitive data type** can mean either of the following:
	* A **basic type** is a data type provided by a programming language as a basic building block. Most languages allow more complicated composite types to be recursively constructed starting from basic types.
	* A **built-in type** is a data type for which the programming language provides built-in support.
	
[Wikipedia: Primitive Data Type](http://en.wikipedia.org/wiki/Primitive_data_type)


##Headers

* Supplemental data placed at the beginning of a block of data being stored or transmitted.

[Wikipedia: Header (Computing)](http://en.wikipedia.org/wiki/Header_(computing))


##Groupings

* In computer science, the term group generally refers to a grouping of users. In principle, users may belong to none, one, or many groups (although in practice some systems place limits on this).
* The primary purpose of user groups is to simplify access control to computer systems.

[Wikipedia: Group (Computing)](http://en.wikipedia.org/wiki/Group_(computing))


##SSH

* **Secure Shell (SSH)** is a cryptographic network protocol for secure data communication, remote command-line login, remote command execution, and other secure network services between two networked computers.

[Wikipedia: Secure Shell](http://en.wikipedia.org/wiki/Secure_Shell)


## Subtype

* A datatype that is related to another datatype (the supertype). Program elements written to operate on elements of the supertype can also operate on elements of the subtype.

[Wikipedia: Subtyping](http://en.wikipedia.org/wiki/Subtyping)


## Status Codes
[List_of_HTTP_status_codes](http://en.wikipedia.org/wiki/List_of_HTTP_status_codes)

100 - Continue. 

200  -  Success

201 - Successful POST

202 - Request being processed
 
206 - Partial Information returned
300  -  Redirect
301 - Moved Permanently
     307 - Temporary Redirect
     308 - Permanent Redirect
400  -  Client error
     403 - Forbidden, unauthorized
     404 - Not Found
     410 - File removed.
     429 -  Use has sent too many requests
500  -  Server error
     502 - Bad gateway
     503 - Service Unavailable
     508 -  Infinite loop

## Associative Array
An abstract data type composed of a collection of  pairs, such that each possible key appears at most once in the collection.
Arrays with named indexes are called associative arrays (or hashes)

[Hashes](http://ruby-doc.org/core-2.1.2/Hash.html)

[Javascript Associative Arrays Demystified](http://blog.xkoder.com/2008/07/10/javascript-associative-arrays-demystified/)

##Query String
In the World Wide Web, a query string is the part of a uniform resource locator (URL) containing data that does not fit conveniently into a hierarchical path structure.



## Abstraction Principle
Reduce duplication of code in a program whenever practical by making use of abstractions provided by the programming language or software libraries. DRY

##SMTP
Simple Mail Transfer Protocol is the internet standard for email.

##Self Reference
Self referencing is in the context of data -- you have a data type that contains a reference to something of the same type.

##Boolean ||
Means OR

##Port 80
Port that a web server is typically available through. (Hypertext protocol)
[List of Port Numbers](http://en.wikipedia.org/wiki/List_of_TCP_and_UDP_port_numbers)


## Dictionary
Dictionary isn’t in Javascript but you can use object notation
```
states_dictionary={"CT":["alex","harry"],"AK":["liza","alex"],"TX":["fred","harry"]};
```
In Ruby a dictionary is a hash: [Hashes](http://www.ruby-doc.org/core-2.1.1/Hash.html)

##Session Store
An application has a session for each user in which you can store small amounts of data that will be persisted between requests. All session stores use a cookie to store a unique ID for each session (you must use a cookie, Rails will not allow you to pass the session ID in the URL as this is less secure).

[Session](http://guides.rubyonrails.org/action_controller_overview.html#session)

##Event Queue

Most events are asynchronous. When an asynchronous event occurs, it gets into the Event queue. The browser has inner loop, called Event Loop, which checks the queue and processes events, executes functions etc.
For example, if the browser is busy processing your onclick, and another event happened in the background (like script onload), it appends to the queue. When the onclick handler is complete, the queue is checked and the script is executed. 
http://javascript.info/tutorial/events-and-timing-depth
Static Method
Static methods neither require an instance of the class nor can they implicitly access the data (or this, self etc.) of such an instance.
http://en.wikipedia.org/wiki/Method_(computer_programming)#Static_methods

In Ruby:
```
def
	self.checkPings
end
```

http://stackoverflow.com/questions/5231534/ruby-on-rails-static-method

##Variable Instantiation

An object instance is created from a class through the a process called instantiation. In Ruby this takes place through the Class method new.

```
  anObject = MyClass.new(parameters)

``` 
[Classes](http://en.wikibooks.org/wiki/Ruby_Programming/Syntax/Classes)

##Pass By Value
