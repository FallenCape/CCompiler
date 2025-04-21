# 🛠️ C-Compiler in C++

A simple C compiler written in C++. This is a learning project aimed at building a minimal compiler for a subset of the C language, from source code to assembly.

## 🚀 Features (Planned)

- [x] Lexical analysis (lexer/tokenizer)
- [x] Syntax analysis (recursive descent parser)
- [ ] Semantic analysis (type checking, scope)
- [ ] Intermediate representation (IR)
- [ ] x86-64 code generation (or LLVM IR)
- [ ] Function definitions and calls
- [ ] Control flow (if, while, for)
- [ ] Error handling and diagnostics
- [ ] (Optional) Optimizations (constant folding, dead code elimination)

## 📁 Project Structure
CCompiler/ ├── include/ # Header files │ ├── Lexer.hpp │ ├── Parser.hpp │ ├── Token.hpp │ └── ... ├── src/ # Source files │ ├── main.cpp │ ├── Lexer.cpp │ ├── Parser.cpp │ └── ... ├── tests/ # Test C programs │ ├── test1.c │ └── ... ├── build/ # Build artifacts ├── CMakeLists.txt # Build configuration └── README.md #

