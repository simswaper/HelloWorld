# Introduction

Hello, thank you for wanting to learn about one sentence in all programming languages. What is this sentence? Well, that's the phrase [Hello World](https://pl.wikipedia.org/wiki/Hello_world). If a language is missing, please contact us by [reporting a problem to the repository](https://github.com/simswaper/HelloWorld/issues).

# List of Programming Languages from A to Z

- **[Assembly](#assembly) (credit to [Pablo Corbalán](https://gist.github.com/pablocorbalann))**
- **Bash**
- **C**
- **C++**
- **C#**
- **Clojure**
- **COBOL**
- **Dart**
- **Elixir**
- **Elm**
- **Erlang**
- **F#**
- **Fortran**
- **Go**
- **Groovy**
- **Haskell**
- **HTML/CSS** (although not traditional programming languages)
- **Java**
- **JavaScript**
- **Julia**
- **Kotlin**
- **Lisp**
- **Lua**
- **MATLAB**
- **Objective-C**
- **Pascal**
- **Perl**
- **PHP**
- **Prolog**
- **Python**
- **R**
- **Ruby**
- **Rust**
- **Scala**
- **Shell**
- **SQL**
- **Swift**
- **TypeScript**
- **VBScript**
- **VHDL**
- **Verilog**

# Assembly
This is a simple "Hello World" program written in Assembly language using NASM.

## Installation

1. **Install NASM:**
   - On Debian/Ubuntu:
     ```bash
     sudo apt-get update
     sudo apt-get install nasm
     ```
   - On Fedora:
     ```bash
     sudo dnf install nasm
     ```

2. **Download a file:**
   ```bash
   curl -o main.asm https://raw.githubusercontent.com/simswaper/HelloWorld/main/Assembly/main.asm
   ```

# Compile and run the project
nasm -f elf32 -o main.o main.asm
ld -m elf_i386 -o main main.o
./hello
./hello
