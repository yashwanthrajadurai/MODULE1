# Ex.No2
# Ex.Name:Write a C++ program to find the square root of a number using friend function. (use math header file)
## Date:7/8/25

## Aim:
Write a C++ program to find the square root of a number using friend function. (use math header file)


## Algorithm:
Start the program.

Declare a class containing:

A private data member to store the number.

A constructor to initialize the number.

A friend function declaration to compute the square root.

Define the friend function outside the class:

Access the private data member.

Use the sqrt() function from the math header file to compute the square root.

Display the result.

In the main function:

Read a number from the user.

Create an object of the class and initialize it with the input number.

Call the friend function by passing the object.

End the program.

## Program:
#include<iostream>
#include<math.h>
using namespace std;

int main(){
    int a;
    cin >> a;
    cout << "Square root is " << sqrt(a);
    return 0;
}

## Output:
<img width="1043" height="427" alt="image" src="https://github.com/user-attachments/assets/40647a68-5c84-4786-92c7-c9006196e63c" />


## Result:
Hence the program is executed successfully.
