# ComplexNumbers
An example class for complex numbers using operator overloading
# Notes:
1. Complex Class:

  - The Complex class represents a complex number with real (real) and imaginary (imag) parts.
  - It includes a constructor to initialize these parts.
2. Operator Overloading:

  - **+ Operator**: Adds two complex numbers by adding their real parts and their imaginary parts.
  - **- Operator**: Subtracts one complex number from another.
  - <b>* Operator</b>: Multiplies two complex numbers using the formula for complex multiplication.
  - **<< Operator**: Overloads the << operator to allow complex numbers to be printed using `std::cout`. It is implemented as a friend function so that it can access the private members of Complex.
3. Main Function:

Creates two `Complex` objects, `c1` and `c2`.
Demonstrates the use of the overloaded operators by performing addition, subtraction, and multiplication on these objects.
Prints the results using the overloaded << operator.
