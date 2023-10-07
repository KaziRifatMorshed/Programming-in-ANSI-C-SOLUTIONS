 
# Multiple Choice Questions

1. 25
2. 9
3. Static Memory Allocation
4. Garbage Value (array indexing starts from zero)
5. 5 x 30 (row x column)
6. 100

# Review Questions

1. 
(a)- False. Arrays have a fixed size that is determined at the time of declaration. They can store a finite number of elements of the same type.

(b)- True. You can declare an array with a constant size, a variable size, or an expression that evaluates to an integer, as long as the size is known at compile time.

(c)- True. The size of the array is specified as 2, but you are trying to initialize it with three elements. This is illegal in C.

(d)- False. In C, if you don't explicitly initialize an array, its elements will contain garbage values, not necessarily zero.(NOTE: NOT INDEXING)

(e- True. You can use an integral expression as a subscript to access elements in an array.

(f)- True. In C, array indices are zero-based, which means the first element of an array has an index of 0.

(g)- True. When initializing a multidimensional array, you should specify all dimensions except for the leftmost dimension (the number of rows) explicitly. The leftmost dimension can be inferred from the initialization.

(h)- False. The subscript expression should evaluate to a non-negative integer, but it can be zero.

(i)- False. C does not impose a strict limit on the number of dimensions in an array. The practical limit may depend on the compiler and system, but you can have arrays with more than 4 dimensions.

(j)- False. Accessing an array outside its valid range is typically not a compile-time error. It may lead to undefined behavior at runtime, but the compiler may not always catch this error.

(k)- False. A char type variable can be used as a subscript in an array. In fact, any integral type (char, int, etc.) can be used as a subscript.

(l)- True. An unsigned long int type can be used as a subscript in an array, as long as it evaluates to a valid array index.
    
2. 
(a) index  
(b) multidimentiional  
(c) shorting  
(d) runtime  
(e) Dynamic  
(f) Garbage  
(g) null terminator  

3.   
```c
bla bla bla...
