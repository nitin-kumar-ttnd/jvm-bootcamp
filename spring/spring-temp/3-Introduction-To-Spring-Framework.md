# Introduction to Spring Framework

Udemy Course: https://www.udemy.com/course/spring-tutorial-for-beginners
Sections: 3,4 and 9

## A High-Level Overview
**Description:** This section provides a broad understanding of what the Spring Framework is, its core features, and its role in Java development.
- [Introduction to the Spring Framework](https://www.spring.io/projects/spring-framework) (Spring.io)

## Setting Up Java Spring Project Using Spring Starter
**Description:** Learn how to set up a new Spring Boot project using Spring Initializr, including creating the project structure and configuring dependencies.
- [Getting Started with Spring Boot](https://spring.io/guides/gs/spring-boot/) (Spring.io)

## Understanding Tight Coupling
**Description:** Understand what tight coupling is in software design, including its implications and drawbacks.
- [Tight Coupling vs. Loose Coupling](https://www.geeksforgeeks.org/coupling-in-java/) (GFG)

## Converting a Tightly Coupled Program to Loosely Coupled
**Description:** Explore techniques for refactoring tightly coupled code to achieve loose coupling, which improves maintainability and flexibility.
- [Converting a Tightly Coupled Program to Loosely Coupled](https://www.educative.io/courses/mastering-unit-testing-principles-with-nunit/convert-from-tightly-to-loosely-coupled-dependencies)


## Using Spring Framework to Manage Dependencies - `@Component`, `@Autowired`
**Description:** Learn about Spring’s dependency injection mechanism using annotations such as `@Component` and `@Autowired` to manage application components.
- [@Autowired](https://www.baeldung.com/spring-autowire) (Spring Documentation)

## Dynamic Autowiring and Troubleshooting - `@Primary`
**Description:** Understand how to manage multiple bean definitions using `@Primary` and troubleshoot common issues with dynamic autowiring in Spring.
- [Spring @Primary Annotation](https://www.baeldung.com/spring-primary) (Spring Documentation)

## Spring Injection Using Java, Constructor, and Setter Methods
**Description:** Explore different methods of dependency injection in Spring, including field injection, constructor injection, and setter injection.
- [Spring Dependency Injection](https://docs.spring.io/spring-framework/reference/core/beans/dependencies/factory-collaborators.html)
- [Spring Dependency Injection](https://www.baeldung.com/spring-dependency-injection)

## Spring Framework Modules
**Description:** Get an overview of the various modules provided by the Spring Framework and their respective functionalities.
- [Spring Modules Explained](https://www.edureka.co/blog/spring-framework-tutorial) (Edureka)


## Spring Projects
**Description:** Discover popular projects and extensions within the Spring ecosystem that enhance and complement the core framework like
Spring Batch, Spring Security, Spring Boot, Spring Cloud, Spring Data,Spring Integration Spring HATEOAS, etc.
- [Spring Projects Overview](https://spring.io/projects) (Spring.io)


## What Makes Spring Framework Popular in the Java World?
**Description:** Understand the reasons behind the popularity of the Spring Framework in the Java community, including its advantages and widespread adoption.
- [Why Use Spring Framework?](https://spring.io/why-spring) 
- [Why Use Spring Framework?](https://www.baeldung.com/spring-why-to-choose) 


## Examples of Dependency Injection
**Description:** Examine practical examples of dependency injection in Spring, showcasing various approaches and scenarios.
- [Spring Dependency Injection Examples](https://www.geeksforgeeks.org/spring-dependency-injection-with-example/) (GFG)


## Autowiring in Depth by Name and `@Primary`
**Description:** Dive deep into the concept of autowiring by name and how to use `@Primary` to resolve conflicts between multiple bean definitions.
- [@Autowired](https://www.baeldung.com/spring-autowire) (Baeldung)
- [@Primary](https://www.baeldung.com/spring-primary) (Baeldung)


## Scope of a Bean: Prototype and Singleton
**Description:** Understand the difference between prototype and singleton scopes in Spring beans and their impact on application behavior.
- [Spring Bean Scopes: Singleton vs. Prototype](https://www.baeldung.com/spring-bean-scopes) (Baeldung)


## Difference Between Spring Singleton and GOF Singleton
**Description:** Explore the distinctions between Spring's singleton scope and the Singleton pattern from the Gang of Four (GOF) design patterns.
- [Spring Singleton vs. GOF Singleton](https://www.javadevjournal.com/spring/spring-singleton-vs-singleton-pattern/) (JournalDev)


## Context and Dependency Injection - `@Named`, `@Inject`
**Description:** Learn about additional annotations such as `@Named` and `@Inject` for dependency injection and their usage within the Spring context.
- [Context and Dependency Injection with @Named and @Inject](https://www.baeldung.com/java-ee-cdi)


## IOC Container versus Application Context versus Bean Factory
**Description:** Differentiate between the IOC Container, Application Context, and Bean Factory in Spring and understand their roles.
- [Spring IOC Container vs Application Context vs Bean Factory](https://jstobigdata.com/spring/ioc-containers-in-spring-application-context-vs-bean-factory/)


## `@Component` vs `@Service` vs `@Repository` vs `@Controller`
**Description:** Understand the differences between these key Spring annotations and their specific use cases in the application layer.
- [Difference Between @Component, @Service, @Repository, and @Controller](https://www.baeldung.com/spring-component-service-repository-controller) (Baeldung)


## Reading Values from External Properties File
**Description:** Learn how to configure and read external properties files in a Spring application to manage configuration values.
- [Spring External Properties File](https://www.baeldung.com/properties-with-spring) (Baeldung)


## Spring AOP
**Description:** Get an overview of Aspect-Oriented Programming (AOP) in Spring, including its key concepts and how it enhances modularity.
- [Introduction to Spring AOP](https://www.baeldung.com/spring-aop) (Baeldung)


## Defining `@Before` Advice
**Description:** Learn how to use `@Before` advice in Spring AOP to execute code before the join points in your application.
- [Spring AOP @Before Advice](https://www.baeldung.com/spring-aop-advice-tutorial) (Baeldung)


## Understand AOP Terminology - Pointcut, Advice, Aspect, and Join Point
**Description:** Understand the fundamental AOP terminology, including pointcut, advice, aspect, and join point, and their roles in aspect-oriented programming.
- [AOP Terminology Explained](https://www.baeldung.com/spring-aop) (Baeldung)


## Using `@After`, `@AfterReturning`, `@AfterThrowing` Advices
**Description:** Explore how to use `@After`, `@AfterReturning`, and `@AfterThrowing` advices to handle different scenarios after method execution.
- [Spring AOP Advices: @After, @AfterReturning, @AfterThrowing](https://www.baeldung.com/spring-aop-advice-tutorial) (Baeldung)


## Using `@Around` Advice to Implement Performance Tracing
**Description:** Learn how to use `@Around` advice to implement performance tracing and other cross-cutting concerns in Spring AOP.
- [Spring AOP @Around Advice](https://www.baeldung.com/spring-aop-around-advice) (Baeldung)


## Best Practice: Use Common Pointcut Configuration
**Description:** Discover best practices for configuring common pointcuts in Spring AOP to improve code maintainability and consistency.
-


## Quick Summary of Other Pointcuts
**Description:** Get a quick summary of various pointcut types in Spring AOP and their uses.
- [Summary of AOP Pointcuts](https://www.baeldung.com/spring-aop-pointcut-tutorial) (Baeldung)


## Creating Custom Annotation and an Aspect for Tracking Time
**Description:** Learn how to create a custom annotation and define an aspect to track the execution time of methods.
- [Creating Custom Annotations and Aspects](https://www.baeldung.com/spring-aop-annotation) (Baeldung)



# Resources?
* Spring Basics: https://www.youtube.com/watch?v=f6DHAgL7FWc
* Spring AOP: https://www.youtube.com/watch?v=Og9Fyew8ltQ