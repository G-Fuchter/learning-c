# Objects, Functions and Types

## Objects, Functions Types and Pointers
* An object is storage in which you can represent values
* Objects have types
* Functions are not objects but do have types (return types and types of its parameters)
* Pointers can be thought of as an address - a location in memory where an object or function is stored.
* C is a call-by-value A.K.A. pass-by-value.
	* When you provide an argument to a function, the value of that argument is copied into a distinct variablefor use within the function
* Variables inside a function have automatic storage duration, meaning that they exist until execution leave the block in which they are defined
* * operator (in the parameters of a function) dereferences the pointer to the object
```c
void swap(int *pa, int *pb){
// code
// swap now accepts pointers to object of type int as parameters
}
```
* The ampersand operator generates a pointer to its operand.
```c
swap(&a, &b);
```


