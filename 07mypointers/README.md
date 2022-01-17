# Memory Management in GO

Memory allocation and Deallocation happen automatically 

we will be using two methods 

1. new()

  - Allocate memory but no INITIALIZED
  - you will get a memory address
  - zeroed storage

2. make()

  - Allocate memory and INITIALIZED
  - you will get a memory address
  - non zeroed storage


Most of time make() is used.


Garbage collection happpens automatically

pkg - runtime is a package for the Garbage collector 



By default pointers have value nil



 
