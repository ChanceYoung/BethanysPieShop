# BethanysPieShop

The Purpose of this repository is to showcase my learning while following the Pluralsight Course: *Building Web Applications with ASP.NET core MVC*

## What did I learn?

09/28
---
The purpose of the Repository and Interface Repository within the Models folder is as part of the “domain” or usable data of the application.  
This also sets up Dependency Injection, which will make our testing easier and allows us to have decoupled dependencies. 
When injecting services in ASP.NET core, there are three types of “instances” you can use:
-AddScoped, which creates a new instance per request, and that instance will be reused for the lifetime of that request
-AddSingleton, which creates a single instance of the service and will reuse that instance
-AddTransient, which creates a new instance of the service every time you ask for one

A controller is the manager of user input. it will typically recieve some type of action from the user, make internal logic changes,  
and then return a new View that reflects these changes to the user.

A View can be considered as an HTML template, and in ASP.NET using "plain" or strongly-typed views, with a markup syntax called Razor  
that allows us to use C# code in our views. There is a difference between Razor and Razor Pages. 

09/29
---
