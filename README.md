# Codekrypt Compiler
This repo contains sub modules which helped me understand compilers better.

## Project Modules

### Compiler Examples

#### SVG Compiler
1. [Web App](https://kosamari.github.io/sbn/)
2. [Medium Article](https://medium.com/@kosamari/how-to-be-a-compiler-make-a-compiler-with-javascript-4a8a13d473b4)

#### LISP Compiler (on hold)
1. [Github](https://github.com/jamiebuilds/the-super-tiny-compiler/blob/master/the-super-tiny-compiler.js)

#### CK(Codekrypt) Compiler
This compiler was developed ground up as a part of learning. This is adapted from `ANLR Examples` module.
```text
1. Lexical Analysis [Done]
2. Parsing [Done]
3. Semantic Analyser [TODO]
4. Optimization [Optional]
5. Code Generation [Done]
```
1. [ASM Code Generation](https://github.com/arjunsk/java-bytecode/tree/master/java-asm/ow2-asm-example/src/main/java/com/arjunsk/asm/asmifier) 

### Parser Examples

#### ANTLR Examples
1. [Visitor](https://www.javahelps.com/2019/04/antlr-hello-world-arithmetic-expression.html)
2. [Listener](https://shalithasuranga.medium.com/build-your-own-programming-language-with-antlr-5201955537a5)

#### Javaparser Example
1. [StackOverflow](https://stackoverflow.com/questions/58611706/javaparser-parsing-and-generating-java-code)

#### JDT Example
1. [ProgramCreek](https://www.programcreek.com/2011/01/best-java-development-tooling-jdt-and-astparser-tutorials/)


## Trouble Shooting
1. If the project is failing in the `ANTLR Examples` submodules, please build the project first using. 
```shell script
mvn clean install
```
