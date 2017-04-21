1.Use nm to list symbols of the function_overloading

  The encoded identifiers used for the functions are
  0000000000400504 T _Z7averageif
  00000000004004d6 T _Z7averagePdRd
  
  On the first line, 7 is the number of the characters in function name, 
  i is the type of the first parameter(int), f is the type of the second parameter(float).
  On the second line, 7 is the number of the characters in function name, 
  Pd is the type of the first parameter(a pointer to a double), Rd is the type of the second parameter(a reference to a double).

2.The output of the sizeof.cpp is:
  1 8
  4 8
  4 8
  8 8
  
  The size of a character is 1, the size of integer is 4,the size of float is 4, and the size of double is 8.
  The value of pointer is an address of another variable,so the size of pointer is 8 for 64-bit machine.
  If the machine is 32-bit, the size of pointer is 4.
