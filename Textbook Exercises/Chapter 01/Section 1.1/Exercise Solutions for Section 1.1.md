Exercises for Section 1.1
=========================  

Exercise 1.1.1
--------------  
What is the difference between a `compiler` and an `interpreter`?  

#### Answer  

A `compiler` is a program that can read a program in one language - the `source` language - and translate it into an equivalent program in another language - the `target` language and report any errors in the source program that it detects during the translation process.  
`Interpreter` directly executes the operations specified in the source program on inputs supplied by the user.  
C is typically compiled.  
Scheme is typically interpreted.  
Java is compiled to bytecodes, which are then interpreted.  

Exercise 1.1.2  
--------------  
What are the advantages of:  
(a) a compiler over an interpreter  
(b) an interpreter over a compiler?  

#### Answer  
a) The machine-language target program produced by a compiler is usually much faster than an interpreter at mapping inputs to outputs.  
b) An interpreter can usually give better error diagnostics than a compiler, because it executes the source program statement by statement.  

Exercise 1.1.3  
--------------  
What advantages are there to a language-processing system in which the compiler produces assembly language rather than machine language?  

#### Answer  
The compiler may produce an assembly-language program as its output, because assembly language is easier to produce as output and is easier to debug.  

Exercise 1.1.4  
--------------  
A compiler that translates a high-level language into another high-level language is called a `source-to-source` translator. What advantages are there to using C as a target language for a compiler?  

#### Answer  
For the C language there are many compilers available that compile to almost every hardware.  

Exercise 1.1.5  
--------------  
Describe some of the tasks that an assembler needs to perform.  

#### Answer  
It translates from the assembly language to machine code. This machine code is relocatable.  