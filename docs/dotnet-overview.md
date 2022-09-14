# Dotnet Overview 
![Dotnet Overview](\assets\images\dotnet.excalidraw.svg)

## What is it?
It is a platform for writing and running software from Microsoft.

If first was released in 2002.

It was originally the antithesis of Java.

> ####NOTE
> What I mean is that Microsoft wanted .NET to run only Windows, Java was originally (and stull is) "cross platform"
> Microsoft had to switch their approach with the advent of cloud computing, thus .Net Core

## Dotnet Running

The **Common Language Runtime** is a managed runtime for your application. Your application is partially compiled to "Intermediate Language" and then "Just In Time (JIT) Compiled" to run at runtime.

.NET Applications compile to IL code.

.NET Applications compile to a format called an "Assembly"

Assembly has the compiled IL code
And a "database" of the types contained in that assembly.
(note: Assemblies are sort of like Jar files if you know Java).

Each **Project** in Visual Studio compiles to an Assembly.

A **Solution** is like a "workspace" and contain multiple projects.

## Terms you should memorize

> #### COMMON LANGUAGE RUNTIME
> The **CLR** - the program that runs your .NET programs. Versions for Windows, Mac and various Linux distrbutions are available 
...

> #### INTERMEDIATE LANGUAGE
> The Language that .NET applications compile to (think Java Bytecode)
...

> #### COMMON TYPE SYSTEM
> **CTS** - the type system in .NET that allows applications written in various languages (VB.NET, C#, *etc*) interact with one another. 
> 
> Two basic types:
> - Value Types
> - Reference Types
> Both Value Types and Reference Types are *user-definable*