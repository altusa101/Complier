# 🚀 MyCompiler — A Real x86-64 Compiler Written in C  
A personal project where I learn, document, and build a **real compiler** targeting **x86-64 machine code**.  
This is a complete engineering log of my journey into compiler development.

---

## 🎯 Project Vision
**My goal:**  
Build a real, native compiler that transforms a custom programming language into **x86-64 assembly**, then into an **executable binary** — just like GCC or Clang (but far simpler).

Not a toy interpreter. Not a VM.  
A true compiler pipeline:

// Source Code → Lexer → Parser → AST → Code Generator → Assembly → Object → Executable


---

## 🛠️ Tech Stack

- **Implementation Language:** C  
- **Target Architecture:** x86-64 (System V ABI)  
- **Assembler:** NASM  
- **Linker:** LD or GCC  
- **Build System:** Make  
- **OS:** Linux or Windows (cross-compiling possible)

---

## 📘 Language Features (Initial Version)

The first stage of the language will support:

- Integer variables  
- Assignments  
- Arithmetic (`+ - * /`)  
- Print statements  
- Expression evaluation  
- Code generation to NASM  
- Producing native executables  

**The project struct

mycompiler/
│
├── src/
│   ├── lexer.c
│   ├── parser.c
│   ├── ast.c
│   ├── codegen.c
│   ├── emitter.c
│   └── main.c
│
├── include/
├── examples/
├── build/
└── README.md


> note - all the files and images of flowcharts are in source plan folder


