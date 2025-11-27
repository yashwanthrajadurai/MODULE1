# Ex.No:3
# Ex.Name:Write a C++ Program to generate Fibonacci series using Class?
## Date:7/8/25
## Aim:
Write a C++ Program to generate Fibonacci series using Class?
## Algorithm:
Start the program.

Create a class named Fibonacci.

Inside the class:

Declare a private variable to store the number of terms.

Create a constructor to initialize this value.

Create a member function to generate the Fibonacci series.

In the member function:

Initialize the first two Fibonacci numbers (a = 0, b = 1).

Display them based on the required number of terms.

Use a loop to generate and display the remaining terms:

Compute next term as c = a + b.

Update values: a = b, b = c.

In main():

Read the number of terms from the user.

Create an object of the class using the input.

Call the member function to display the Fibonacci series.

End the program.

## Program:
#include<iostream>
using namespace std;

void fib(int n){
    int s=0,t1=0,t2=1;
    for(int i=2;i<n;i++){
        s=t1+t2;
        t1=t2;
        t2=s;
        cout << s << " ";
    }
}

int main(){
    int a;
    cin >> a;
    cout << "Fibonacci Series are:";
    cout << "0 1 ";
    fib(a);
}

## Output:
<img width="1037" height="449" alt="image" src="https://github.com/user-attachments/assets/50f8c3d5-e203-4e92-996e-39077074d67f" />

## Result:
Hence the program is executed successfully.

