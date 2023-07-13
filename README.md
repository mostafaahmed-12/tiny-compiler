# Tiny-Compiler
Tiny Programming Language Compiler
An implementation of Scanner and Parser for Tiny programming language,

Langage's NFA constructed from Regex using Thompson Construction method and converted to DFA using Subset / Powerset Construction method and then minimized the DFA

Lexer "Scanner"
Implemented in Scanner.cs
Based on the following Regular Expressions (Regex) and Deterministic Finite Automata (DFA)
Scans the code to identify Lexemes
Produces a list of Tokens
Checks for unrecognized Tokens and outputs them in errors list
Parser
Implemented in Parser.cs
Based on the following Context Free Grammer (CFG) rules
Uses the token stream produced by Scanner to Build an abstract syntax tree
Checks for syntax errors and outputs them in errors list
