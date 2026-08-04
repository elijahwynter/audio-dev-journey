# C++ Notes

## Basic Syntax Rules

- C++ ignores whitespace (e.g., spaces, tabs, line breaks), but we use it to make code more readable.
- C++ is case-sensitive, so be careful.
- C++ statements must end in a semicolon `;`

## Initializing a Program

Almost all C++ programs start with these two lines:

```cpp
#include <iostream>        // Gives access to input and output tools
using namespace std;       // Makes typing commands easier (i.e., cout instead of std::cout)
```

## Executing the Program

Every C++ program needs a `main()` function. It is where the program truly starts.

The basic structure looks like this:

```cpp
int main() {           
    // Enter your code
    return 0;
}
```

### Breaking it down
`int` - Means that the function returns an integer value when it finishes.

`main()` - The OS looks for this specific function name to know where to start running the program.

`return 0;` - Ends the program and returns the value `0` to indicate that the program completed successfully

Your code runs within the curly brackets `{}`



