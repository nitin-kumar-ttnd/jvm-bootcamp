# Spring Data JPA with Hibernate

## Lecture Pre-Requisites or Installations
* Install Java
* Install STS or Intellij
* Install MySql and MySql Workbench
* Launch MySql workbench and create a database
* Spring Data JPA reference documentation

---

## Java EE Application Layers
### Description
Java EE (Enterprise Edition) applications are typically divided into three layers: the Presentation Layer, the Business Layer, and the Data Layer. Understanding these layers helps in designing scalable and maintainable enterprise applications.

- **Presentation Layer**: Deals with the user interface and user interaction.
- **Business Layer**: Contains business logic and application rules.
- **Data Layer**: Manages data persistence and retrieval.

### Learning Resources
- **Video**: [Java EE Architecture - Layers & Components](https://www.youtube.com/watch?v=VMDfSsd7YFU)
- **Blog**: [Java EE Architecture Explained](https://subscription.packtpub.com/book/programming/9781847195609/1/ch01lvl1sec01/introduction-to-the-java-ee-architecture)

---

## ORM (Object-Relational Mapping)
### Description
ORM is a programming technique that allows developers to map Java objects to database tables, making database operations easier and less error-prone.

### Learning Resources
- **Video**: [ORM Explained](https://www.youtube.com/watch?v=KthQ0UmBmxE)
- **Blog**: [Introduction to ORM](https://www.freecodecamp.org/news/what-is-an-orm-the-meaning-of-object-relational-mapping-database-tools/)

---

## What is JPA?
### Description
Java Persistence API (JPA) is a specification that provides a standardized way to manage relational data in Java applications using ORM.

### Learning Resources
- **Video**: [JPA in28minutes](https://www.youtube.com/watch?v=MaI0_XdpdP8)
- **Blog**: [Introduction to JPA](https://www.javatpoint.com/jpa-introduction)

---

## What and Why Spring Data?
### Description
Spring Data is a part of the larger Spring framework. It simplifies database operations by reducing the amount of boilerplate code needed for data access and manipulation.

### Learning Resources
- **Video**: [Introduction to Spring Data]()
- **Blog**: [Why Use Spring Data?](https://www.baeldung.com/the-persistence-layer-with-spring-data-jpa)

---

## Simple CRUD Operations
### Description
CRUD stands for Create, Read, Update, and Delete. These are the basic operations performed on a database.

### Learning Resources
- **Video**: [Spring Data JPA - CRUD Operations]()
- **Blog**: [CRUD Operations with Spring Data JPA](https://www.baeldung.com/spring-data-jpa-crud)

---

## Generators
### Description
Generators in JPA are used to automatically generate primary key values for entities.

### Learning Resources
- **Video**: [JPA Primary Key Generators]()
- **Blog**: [JPA Primary Key Generation Strategies](https://www.baeldung.com/hibernate-identifiers)

---

## Spring Data Finder Methods
### Description
Finder methods in Spring Data allow you to define query methods simply by following a naming convention.

### Learning Resources
- **Video**: [Spring Data JPA Finder Methods]()
- **Blog**: [Spring Data JPA Query Methods](https://www.baeldung.com/spring-data-derived-queries)

---

## Paging and Sorting
### Description
Paging and Sorting in Spring Data allow you to handle large datasets by retrieving data in chunks (pages) and sorting it as per your requirements.

### Learning Resources
- **Video**: [Spring Data JPA - Paging and Sorting]()
- **Blog**: [Pagination and Sorting with Spring Data JPA](https://www.baeldung.com/spring-data-jpa-pagination-sorting)

---

## JPQL
### Description
Java Persistence Query Language (JPQL) is a powerful query language that is similar to SQL but operates on JPA entities rather than tables.

### Learning Resources
- **Video**: [JPQL Tutorial]()
- **Blog**: [Introduction to JPQL](https://www.baeldung.com/jpa-queries)

---

## Native Query
### Description
Native queries allow you to write SQL queries directly when JPQL is not sufficient.

### Learning Resources
- **Video**: [JPA Native Query Tutorial]()
- **Blog**: [Using Native Queries in JPA](https://www.baeldung.com/jpa-native-queries)

---

## When to use Native Query?
### Description
Use native queries when you need database-specific features or when JPQL cannot express a query.

### Learning Resources
- **Video**: [When to Use Native Queries]()
- **Blog**: [Choosing Between JPQL and Native SQL](https://www.baeldung.com/jpa-native-query)

---

## Inheritance Mapping
### Description
Inheritance mapping in JPA allows you to map Java inheritance hierarchies to database tables.

### Learning Resources
- **Video**: [JPA Inheritance Mapping]()
- **Blog**: [JPA Inheritance Mapping Strategies](https://www.baeldung.com/hibernate-inheritance)

---

## Component Mapping
### Description
Component mapping in JPA refers to embedding value objects inside entities.

### Learning Resources
- **Video**: [JPA Component Mapping]()
- **Blog**: [Embeddable Types in JPA](https://www.baeldung.com/hibernate-embeddable)

---

## Relationships in Hibernate
### Description
Understanding relationships like One-to-One, One-to-Many, and Many-to-Many in Hibernate is essential for effective database design.

### Learning Resources
- **Video**: [Hibernate Relationships]()
- **Blog**: [Mapping Relationships with JPA and Hibernate](https://www.baeldung.com/hibernate-one-to-many)

---

## Transaction Management

### Introduction to Transaction Management
### Description
Transaction management ensures data integrity and consistency by treating multiple database operations as a single unit of work.

### Learning Resources
- **Video**: [Transaction Management Basics]()
- **Blog**: [Introduction to Transaction Management](https://www.baeldung.com/spring-transactional-propagation-isolation)

---

### Transaction Management - ACID Properties
### Description
ACID (Atomicity, Consistency, Isolation, Durability) properties are fundamental to transaction management.

### Learning Resources
- **Video**: [ACID Properties Explained]()
- **Blog**: [Understanding ACID Properties](https://www.geeksforgeeks.org/acid-properties-in-dbms/)

---

### Understanding Dirty, Phantom, and Non-Repeatable Reads
### Description
These are types of inconsistencies that can occur in database transactions due to concurrency issues.

### Learning Resources
- **Video**: [Dirty, Phantom, and Non-Repeatable Reads]()
- **Blog**: [Database Read Phenomena](https://www.baeldung.com/read-committed-repeatable-read-phantom-read)

---

### Understand 4 Isolation Levels
### Description
Isolation levels define the degree to which the operations in one transaction are isolated from those in other transactions.

### Learning Resources
- **Video**: [Isolation Levels Explained]()
- **Blog**: [Isolation Levels in Transaction Management](https://www.baeldung.com/spring-transaction-isolation-levels)

---

### Choosing Between Isolation Levels
### Description
Choosing the right isolation level is crucial for balancing consistency and performance in database transactions.

### Learning Resources
- **Video**: [Choosing the Right Isolation Level]()
- **Blog**: [Guide to Choosing Isolation Levels](https://www.baeldung.com/transaction-isolation-levels)

---

### Implementing Transaction Management - 3 Things to Decide
### Description
When implementing transaction management, you need to decide on transaction boundaries, isolation levels, and propagation behavior.

### Learning Resources
- **Video**: [Implementing Transaction Management]()
- **Blog**: [Decisions in Transaction Management](https://www.baeldung.com/spring-transaction-management)

---

## Caching with Hibernate & JPA

### Introduction to Caching
### Description
Caching is a technique used to improve the performance of data retrieval by storing frequently accessed data in memory.

### Learning Resources
- **Video**: [Introduction to Caching]()
- **Blog**: [Introduction to Caching in Hibernate](https://www.baeldung.com/hibernate-second-level-cache)

---

### Hibernate and JPA Caching - First Level Cache
### Description
First-level cache in Hibernate is associated with the session and is enabled by default. It caches objects within the session.

### Learning Resources
- **Video**: [First Level Cache in Hibernate]()
- **Blog**: [Hibernate First Level Cache Explained](https://www.baeldung.com/hibernate-1st-2nd-level-cache)

---

### Hibernate and JPA Caching - Basics of Second Level Cache with EhCache
### Description
The second-level cache in Hibernate is a global cache and can be shared across sessions. EhCache is a popular implementation.

### Learning Resources
- **Video**: [Second Level Cache with EhCache]()
- **Blog**: [Second Level Caching with EhCache](https://www.baeldung.com/hibernate-second-level-cache)

---

### Hibernate and JPA Caching - Second Level Cache Part 2
### Description
This section dives deeper into configuring and using the second-level cache effectively in Hibernate.

### Learning Resources
- **Video**: [Advanced Second Level Caching]()
- **Blog**: [Advanced Guide to Second Level Caching](https://www.baeldung.com/spring-cache-tutorial)

---

## Performance Tuning Tips with Hibernate and JPA

### Performance Tuning - Measure before Tuning
### Description
Before tuning, it's important to measure the current performance to understand where bottlenecks exist.

### Learning Resources
- **Video**: [Performance Tuning in Hibernate]()
- **Blog**: [Measure Before You Tune](https://www.baeldung.com/performance-tuning-hibernate-jpa)

---

### Performance Tuning - Indexes
### Description
Indexes can significantly improve the performance of database queries but must be used judiciously.

### Learning Resources
- **Video**: [Understanding Indexes]()
- **Blog**: [Using Indexes in Hibernate](https://www.baeldung.com/spring-data-jpa-index-annotation)

---

### Performance Tuning - Use Appropriate Caching
### Description
Using the right caching strategy is crucial for improving application performance.

### Learning Resources
- **Video**: [Caching Strategies in Hibernate]()
- **Blog**: [Effective Caching in Hibernate](https://www.baeldung.com/spring-boot-ehcache)

---

### Performance Tuning - Eager vs Lazy Fetch
### Description
Choosing between eager and lazy fetching affects both performance and memory usage in Hibernate.

### Learning Resources
- **Video**: [Eager vs Lazy Fetching]()
- **Blog**: [Eager and Lazy Loading in Hibernate](https://www.baeldung.com/hibernate-lazy-eager-loading)

---

### Performance Tuning - Avoid N+1 Problems
### Description
The N+1 query problem occurs when a system executes one query to retrieve parent entities and another N queries to retrieve child entities. It can severely impact performance.

### Learning Resources
- **Video**: [N+1 Query Problem]()
- **Blog**: [Avoiding N+1 Problem in Hibernate](https://www.baeldung.com/hibernate-n-plus-one-problem)

