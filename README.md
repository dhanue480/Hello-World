# Hello-World

Purpose: Write a Hello World program

Requirements:

The program has 1 current business requirement a write Hello World to the console/screen.

The program should have an API that is separated from the program logic to eventually support mobile applications, web applications, console applications or windows services.

The program should support future enhancements for writing to a database, console application, etc.

a. Use common design patterns (inheritance, e.g.) to account for these future concerns.

b. Use configuration files or another industry standard mechanism for determining where to write the information to.

Write unit tests to support the API

The Hello World Application consists of:

ConsoleApp - A Console Application that will write to the Console

HelloWorldAPI - A Web API for the Console Application to communicate with

HelloWorldInfrastructure - A Class library containing reusable code

HelloWorldAPI.Tests - A Test project containing unit tests for the application

To run the application:

Build the solution (all of the projects)

Set the HelloWorldAPI project as the 'Startup Project'

Debug/run the HelloWorldAPI project

Open a cmd window

Run the ConsoleApp binary in the cmd window (HelloWorld\ConsoleApp\bin\Debug\ConsoleApp.exe)
