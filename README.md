# Exception

### **Objective**
The purpose of this project is to validate your understanding of exception handling in C++.



### **Problem**
Throw an exception if the name variable is empty.

### **Implementation**
Handle the code to throw an exception if the name is empty, by using custom exception. 
If the name is empty print the exception message, and if it's not empty print the name.

> You can use the string function **.empty** to check if the string is empty or not.

```cpp
#include <iostream>
#include <string>
using namespace std;

int main() {
    // warp name initialization with try keyword
    string name = "";
    // if the name is empty throw an error with the message "Name can't be empty"
   
    // catch the exception and print the exception message
  
  return 0;
}
```

