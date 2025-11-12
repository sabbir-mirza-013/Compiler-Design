This project implements a mini C-like compiler built using Flex and Bison. It performs lexical, syntactic, and semantic analysis of source code, integrated with a symbol table and scope table system for managing identifiers and nested scopes.

**🔹 Key Features**

Lexical Analysis:
Implemented in scanner.l using Flex. Recognizes keywords, identifiers, constants, operators, and delimiters while logging tokens and lexical errors.

Syntax Analysis:
Implemented in parser.y using Bison. Validates program structure based on grammar rules for declarations, expressions, loops, and conditionals.

Symbol Table & Scope Table:
Custom C++ classes manage identifiers, data types, and scopes.

The symbol table stores variable and function information.

The scope table tracks nested scopes (global, function, block).

Supports insertion, lookup, shadowing, and scope entry/exit operations.

Error Handling:
Detects and reports lexical, syntax, and semantic errors with line numbers.
