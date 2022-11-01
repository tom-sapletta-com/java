# java
Notes abouts java language


[Spring Initializr](https://start.spring.io/)


[Convention over configuration - Wikipedia](https://en.wikipedia.org/wiki/Convention_over_configuration)

> # Convention over configuration
> 
> From Wikipedia, the free encyclopedia
> 
> [Jump to navigation](https://en.wikipedia.org/wiki/Convention_over_configuration#mw-head) [Jump to search](https://en.wikipedia.org/wiki/Convention_over_configuration#searchInput)
> 
> Software design paradigm
> 
> **Convention over configuration** (also known as **coding by convention**) is a software [design paradigm](https://en.wikipedia.org/wiki/Design_paradigm "Design paradigm") used by [software frameworks](https://en.wikipedia.org/wiki/Software_framework "Software framework") that attempts to decrease the number of decisions that a [developer](https://en.wikipedia.org/wiki/Software_developer "Software developer") using the framework is required to make without necessarily losing flexibility and [don't repeat yourself](https://en.wikipedia.org/wiki/Don%27t_repeat_yourself "Don't repeat yourself") (DRY) principles.[\[1\]](https://en.wikipedia.org/wiki/Convention_over_configuration#cite_note-1)
> 
> The concept was introduced by [David Heinemeier Hansson](https://en.wikipedia.org/wiki/David_Heinemeier_Hansson "David Heinemeier Hansson") to describe the philosophy of the [Ruby on Rails](https://en.wikipedia.org/wiki/Ruby_on_Rails "Ruby on Rails") [web framework](https://en.wikipedia.org/wiki/Web_framework "Web framework"), but is related to earlier ideas like the concept of "sensible [defaults](https://en.wikipedia.org/wiki/Default_(computer_science) "Default (computer science)")" and the [principle of least astonishment](https://en.wikipedia.org/wiki/Principle_of_least_astonishment "Principle of least astonishment") in [user interface design](https://en.wikipedia.org/wiki/User_interface_design "User interface design").


[Patterns in Practice - Convention Over Configuration | Microsoft Learn](https://learn.microsoft.com/en-us/archive/msdn-magazine/2009/february/patterns-in-practice-convention-over-configuration)

> # Patterns in Practice - Convention Over Configuration
> 
> By [Jeremy Miller](https://learn.microsoft.com/en-us/archive/msdn-magazine/2009/february/%5Carchive%5Cmsdn-magazine%5Cauthors%5CJeremy_Miller) | February 2009
> 
> ## [](https://learn.microsoft.com/en-us/archive/msdn-magazine/2009/february/patterns-in-practice-convention-over-configuration#contents)Contents
> 
> The Impact of Language Innovation  
> Say It Once and Only Once  
> Sensible Defaults  
> Convention over Configuration  
> Next Steps
> 
> Have you ever thought about how much time on your project is spent on the core problems versus the time you spend wrestling with purely technical concerns? Some may say that the most important goal of all new software technologies and techniques is to reduce the distance between the developer's intent for the software and the realization of that intent in code. And the industry has continuously raised the level of abstraction to allow developers to spend more time delivering functionality and less time writing low-level infrastructure—but there's still a long way to go.
> 
> Think about this for a minute. If you were to show your code to your business representatives—assuming that they were actually willing to read the code with you—how much of that code would they care about? Those business representatives will probably only care about the code that expresses the business functionality of the system. That code is the "essence" of the system. On the other hand, they probably wouldn't have the slightest interest in code such as type declarations, configuration settings, try/catch blocks, and generic constraints. That code is the infrastructure, or "ceremony," that you, the developer, have to go through just to ship code.
> 
> In previous installments of this column I've largely explored fundamental design concepts and principles, most of which have been part of the design canon for quite some time. This time around, I'd like to look at some newer techniques that you can adopt to reduce the amount of ceremony in your code. Some of these concepts may be new to you, but I believe that all of this will be part of the .NET mainstream within a few years.
> 
> The Impact of Language Innovation
> 
> The first factor I'd like to consider is the choice of programming language and how you use programming languages. To illustrate the impact of a programming language on the amount of ceremony in the code, let's take a little detour into the musty pages of history.
> 
> Earlier in this decade I was building a large system in Visual Basic 6.0. Each method would look something like what you see in **Figure 1**. Every single bit of that code was ceremony.

[OpenAPI 3 Library for spring-boot](https://springdoc.org/)

> `springdoc-openapi` java library helps to automate the generation of API documentation using spring boot projects. `springdoc-openapi` works by examining an application at runtime to infer API semantics based on spring configurations, class structure and various annotations.
> 
> Automatically generates documentation in JSON/YAML and HTML format APIs. This documentation can be completed by comments using swagger-api annotations.
> 
> This library supports:
> 
> -   OpenAPI 3
>     
> -   Spring-boot (v1 and v2)
>     
> -   JSR-303, specifically for @NotNull, @Min, @Max, and @Size.
>     
> -   Swagger-ui
>     
> -   OAuth 2
>     
> -   GraalVM native images
