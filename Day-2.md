# DAY2
### (1)Diffrence Between Imperative And Procedure And Examples:
Imperative programming: This is a programming paradigm where the programmer specifies how the program should accomplish a task by giving step-by-step instructions.
Imperative programming focuses on the control flow and mutable state of a program. Examples of imperative programming languages include C, Java, and Python.

Declarative programming: This is a programming paradigm where the programmer specifies what the program should accomplish without specifying how to do it. 
Declarative programming focuses on the logic of the program and is often used in data processing and querying tasks. Examples of declarative programming languages
include SQL, Prolog, and Haskell.

Procedural programming: This is a programming paradigm where the program is structured around procedures or subroutines, which are a set of instructions that 
perform a specific task. Procedural programming languages are usually imperative and focus on the sequence of actions that must be taken to achieve a specific result.
Examples of procedural programming languages include C, Pascal, and Fortran.
##
### (2)How Can Python Work With Large Numbers (14 BYTES):
Python supports a “bignum” integer type which can work with arbitrarily large numbers. In python 2.5+,this type is called long and its separate from int type,
but the interpreter will automatically use whichever is more appropriate. In python 3.0+, the int  type has been dropped completely
##
### (3)Null Pointer Exception:
"Null pointer exception" (NPE) is an error that occurs in programming languages, such as Java, C++, and others when an attempt is made to use an object or variable
that has a "null" (or "nil") value, which means that it does not point to any memory location or object in the program. This error occurs when the program tries to
access a member of a null object, or when a null value is passed to a method or function that expects a non-null value.
##
### (4)What's Not Case Sensitive Languages And Its Kinds:
Case-insensitive languages are programming languages that do not distinguish between uppercase and lowercase letters, meaning that a capitalized letter and its 
corresponding lowercase letter are considered the same. This does not affect the translation or execution of the code. Examples of such languages include HTML, CSS, and XML.
##
### (5)Diffrence Between Heap And Stack:
The difference between the heap and the stack is that the heap is a region of memory used for dynamic memory allocation, while the stack is a region of memory used 
for storing variables created within a function.In more detail, the heap is an area of memory that is used to store dynamically allocated data. This means that the size
of the memory block can be determined at run-time, and the memory is allocated and de-allocated using the "new" and "delete" operators in C++ or the "malloc" and "free" 
functions in C. The heap can be used to allocate large blocks of memory, but is slower than the stack because the memory allocation is not done statically.On the other
hand, the stack is a region of memory that is used for local variables and function calls. The stack is a LIFO (last-in-first-out) data structure, where the last item 
pushed onto the stack is the first item to be popped off. The stack is faster than the heap because the memory allocation and deallocation is done statically.In summary,
the heap and the stack are both regions of memory that are used for different purposes. The heap is used for dynamic memory allocation, while the stack is used for storing 
local variables and function calls.
##
### (6)What are the programming languages that support auto garbage collection and which ones do not?
Programming languages that support automatic garbage collection include Java, Python, Ruby, JavaScript, C#, and Kotlin, among others. On the other hand, 
programming languages that do not support automatic garbage collection include C and C++, among others. In these languages, the programmer is responsible for 
managing memory allocation and deallocation manually.









