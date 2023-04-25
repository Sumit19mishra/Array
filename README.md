# Array
an array is a data structure consisting of a collection of elements (values or variables), of same memory size, each identified by at least one array index or key. An array is stored such that the position of each element can be computed from its index tuple by a mathematical formula.
By default the array is uninitialized, and no elements of the array are set to any value. However, for the proper working of the array, array initialization becomes important. Array initialization can be done by the following methods:

1. Passing no value within the initializer: One can initialize the array by defining the size of the array and passing no values within the initializer.

Syntax:

int arr[ 5 ] = {  };

2. By passing specific values within the initializer: One can initialize the array by defining the size of the array and passing specific values within the initializer. 

Syntax:

int arr[ 5 ] = { 1, 2, 3, 4, 5 };

Note: The count of elements within the “{ }”, must be less than or equals to the size of the array 
If the count of elements within the “{ }” is less than the size of the array, the remaining positions are considered to be ‘0’.

Syntax:

int arr[ 5 ] = { 1, 2, 3 } ;

3. By passing specific values within the initializer but not declaring the size: One can initialize the array by passing specific values within the initializer and not particularly mentioning the size, the size is interpreted by the compiler.

Syntax:

int arr[  ] = { 1, 2, 3, 4, 5 };

4. Universal Initialization: After the adoption of universal initialization in C++, one can avoid using the equals sign between the declaration and the initializer. 

Syntax:

int arr[ ]  { 1, 2, 3, 4, 5 };
