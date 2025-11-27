# Ex.No:1
# Ex.Name:Write a C++ program to find the minimum of two and three numbers using construction overloading, pass values during compile time.
## Date:7/8/25
## Aim:
Write a C++ program to find the minimum of two and three numbers using construction overloading, pass values during compile time.

## Algorithm:
Step 1: Start the program.
Step 2: Create a class Minimum.
Step 3: Inside the class, define:

Two data members for two numbers.

Three data members for three numbers.

Two constructors:

Constructor 1: Accepts two numbers.

Constructor 2: Accepts three numbers.

Step 4: In Constructor 1:

Compare the two numbers.

Store or display the minimum.

Step 5: In Constructor 2:

Compare the three numbers.

Store or display the minimum.

Step 6: In main():

Create an object of Minimum with two values (compile-time initialization).

Create another object of Minimum with three values.

Step 7: End the program.

## Program:
#include<iostream>
using namespace std;
class Arithmetic{
  public:
  Arithmetic(int a,int b){
      if(a>b){
          cout << b << " is lesser" << endl;
      }
  }
  Arithmetic(int a,int b,int c){
      if(a>b && c>b){
          cout << b << " is lesser" << endl;
      }
      else if(b>a && c>a){
          cout << a << " is lesser" << endl;
      }
      else {
          cout << c << " is lesser" <<  endl;
      }
  }
};

int main(){
    Arithmetic ar(95,64);
    Arithmetic ar1(22,28,21);
    return 0;
}

## Output:
<img width="1037" height="349" alt="image" src="https://github.com/user-attachments/assets/1769d4fd-bf84-4f1c-b836-798314a15444" />
## Result:
Hence the program is executed successfully.


