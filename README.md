Lexical Analyzer


Introduction
In computer science, Lexical Analysis is the process of converting a sequence of characters into a sequence of tokens. A program that performs lexical analysis is called a lexical analyzer or lexer. Lexers are typically the first step in the compilation process, recognizing keywords, operators, identifiers, numbers, and other fundamental language elements from the source code.

This project is a simple Lexical Analyzer written in C, specifically for a subset of the C programming language. It reads a C source file and produces a sequence of tokens to be used in the next stage of compilation.



Purpose of the Project
The main goal of this project is to build a lexical analyzer that takes a .c file as input, processes it, and outputs the tokens from the source code. It helps demonstrate the concept of lexical analysis in the compiler design process.



Features
Tokenizes C source code into keywords, identifiers, operators, constants, and special symbols.
Supports recognition of integers, floating-point numbers, character strings, and other literals.
Processes and identifies arrays and control structures like if, while, and for.
Simple error detection for invalid tokens.


Scope of the Project
Designed to work with a subset of the C language.
Assumes the source program is stored in a file and the input is from the output of a preprocessor.
Recognizes basic C elements, including:

Keywords: e.g., if, else, for, while, etc.

Identifiers: e.g., variable names.

Literals: integers, floating-point numbers, strings, and characters.

Operators: arithmetic, relational, and logical operators.

Special Symbols: braces, parentheses, commas, etc.

Note: This project is not optimized for performance and is limited to basic C syntax handling.

Phases of Compilation
The Lexical Analyzer is a key phase in the compilation process. It processes the input source code and generates tokens, which are later used by the parser. The key phases include:

Lexical Analysis: Tokenizes the input stream.

Syntax Analysis: Ensures the tokens follow the syntax rules of the language.

Semantic Analysis: Ensures the meaning of the code is valid.

Intermediate Code Generation
Code Optimization
Target Code Generation
Lexical Analysis Overview
Lexical analysis reads a stream of characters and groups them into tokens. A token is the smallest unit in the source code, and can represent keywords, operators, identifiers, literals, and more.

For example, consider the following C code:

c
Copy code
sum = 3 + 2;
The Lexical Analyzer would break it down into the following tokens:

Lexeme	Token Type
sum	Identifier
=	Assignment Operator
3	Integer Literal
+	Addition Operator
2	Integer Literal
;	End of Statement


How to run project :- edit test.c 

then ./a.out


Author

Pritesh Suryawanshi

Batch: ECEP (24002_030), Emertxe.

Guidance: Emertxe
