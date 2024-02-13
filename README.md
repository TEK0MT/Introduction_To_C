"# Introduction_To_C" 
* Computing systems consists of three thing :
1- processor
2 - Memory
3- I/O
*the processor reads from the memmory using 3 things called Buses
1- Data bus : That's what transfer the data from memmory to processor or in reverse
2-Address bus : To send address of the data in the memmory that we want to read or write
3-Control Bus : to specify whether we want to read or write in the memmory
* The processor only understands machine language which depend on only 2 digits (0,1) but it was hard to write a code in only 
(0,1) so they created assembly but it hast some disadvantage
1-Micro procerssor dependent
2-Hard to write and understand
Advantage 
1-optimized size and excution time
2-No need for combiler
* 1972 C language was released by Dennis Ritchi 
it was first work only on UNIX then it worked on cross and native compilers and WINDOWS and it had many versions untill
in 1989 ANSI granteed a C version called C89
## Why we use C in Embedded system
1- C is easier and fast for the developer
2- simple more than assembly 
3- Poratble platform
4- Can access memmory and buses
* The code we wrote (.c) passes through (Tool chain) to become an excutable file (.exe)
the tool chain we will use is GCC compiler
### There is two types of Tool chain
1-Native compiler : the output of the code run on the same platform
2-Cross compiler : the output of the code run on another platform
#### The process the code passes to tuern into excutable file 
code(.exe) --> preprocessing (.i) : this process replace all # to the code itself form the libraries
(.i) --> compiler(.s) : the compilation process turn the code into assembly
(.s) --> Assembler(.o) : turn the assembly file into machine code
(.o) --> Linker (.exe) : turn the code into excutable file 