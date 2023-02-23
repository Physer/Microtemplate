# Microtemplate

A Visual Studio solution template for microservices in .NET/C#

## Introduction

This is a multi-project solution template for Visual Studio to quickly scaffold a microservice based on [Clean Architecture](https://jasontaylor.dev/clean-architecture-getting-started/).

You can add this template to your Visual Studio templates and use it as a starting point for creating a new Microservice without repeating yourself.

## How to use

1. Download the latest `Microtemplate.zip` file from the [Releases page](https://github.com/Physer/Microtemplate/releases)
2. Place the ZIP file in your Visual Studio user data location: `%USERPROFILE%\Documents\Visual Studio 2022\Templates` 
3. If Visual Studio was open, restart it
4. You can now create a new project using the `Microtemplate` project template

## Architecture overview

This template uses Clean Architecture for its solution and project structure.
There are 5 projects created with this solution:
1. Application (Core)
2. Domain (Core)
3. Persistence (Infrastructure)
4. Tests (Tests)
5. Web (Presentation)

![Clean Architecture diagram](https://i0.wp.com/jasontaylor.dev/wp-content/uploads/2020/01/Figure-01-2.png?w=531&ssl=1)
© Jason Taylor

## References

* https://learn.microsoft.com/en-us/visualstudio/ide/creating-project-and-item-templates?view=vs-2022
* https://jasontaylor.dev/clean-architecture-getting-started/
