# Mini-C Compiler - Lexical Analyzer

- **NAME:** Mai Jock (153-793)
- **Course:** Compiler Design
- **University:** Cavendish University Uganda

## Project Overview
A complete lexical analyzer for a subset of the C programming language, implementing a **15-state DFA** with **2-character lookahead** for accurate token recognition.

## Features
- ✅ 12 Token Categories (keywords, identifiers, literals, operators, separators, comments)
- ✅ 15-State DFA for Token Recognition
- ✅ 2-Character Lookahead Buffer for Operators
- ✅ Symbol Table with Scope Management
- ✅ Error Detection and Reporting
- ✅ Comprehensive Statistics Collection

## How to Run
```bash
g++ -std=c++17 lexer.cpp -o lexer.exe
