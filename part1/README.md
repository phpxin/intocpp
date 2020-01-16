# Grammar

```c++
#include <iostream>

using namespace std;

int main(int argc, char* argv[]) {
    for (int i=0; i<argc; i++) {
        cout << argv[i] << endl;
    }

    return 0;
}
```

This is a sample CPP program. 
First we use `include` to include the package `iostream`. It includes some basic functions for operating IO.  
Then we use `using` to declare that the program is using the namespace `std`. *namespace is use to isolate the two different functions that have the same names*  
Like C program, the CPP program is also need the function `main` to be a entry of the program.  
Usually, we declare the `int` as its return value, and two parameters as the the input of the function: One parameter is an integer, it means how many parameters of input the execution has; The other is an array of pointer of char, it represent the parameters of input.  
You see, the CPP is a strict typed programming language. It needs the type in front of the variable, so the compiler knows what type the variable is and how many bytes of the memory does the variable need.  

