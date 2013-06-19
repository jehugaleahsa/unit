# Unit

Research for the Unit programming language.

## Purpose
This project aims at investigating the Python source code, with the ultimate aim of developing a new programming language called Unit. This project will hold any notes describing the layout and structure of the C source code. Eventually, it will house any code (C++) as the starting point of the new Unit programming language.

To be clear, this is intended to be an **educational** project. The goal is to learn how to develop a dynamic, interpreted language. There is a great potential for learning on this project. Not only will I learn a lot about C++ and Python, I will gain a deeper understanding of interpreters and programming languages.

Unit will have limited runtime support. I will not be trying to port Python standard libraries to Unit. This would be a herculean task - and I am not a big fan of the standard libraries anyway. For the same reason, I will not be trying to implement many of the built-ins. Instead, I will focus on the core language.

This will be an interesting progression. Initially, it will appear as though I am just rewriting Python core code in C++. However, I will eventually be making code changes to the syntax itself (with some minor semantics differences). The final Unit language will hopefully be 90% Python, 8% Ruby, 1% Haskell and 1% Scala. Developers familiar with Python should be able to almost immediately start programming in Unit. However, the goal is to have better functional programming support (beyond comprehensions and built-in functions), class-level scoping, easier runtime decoration/extension and the use of companion objects to replace statics.
