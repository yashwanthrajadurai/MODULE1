# Ex.No:5
# Ex.Name:Write a C++ program using friend function to find the minimum integer value  among the member of both the classes.
## Date:7/8/25
## Aim:
Write a C++ program using friend function to find the minimum integer value  among the member of both the classes.


## Algorithm:
Start the program.

Create two classes, each containing:

A private integer data member.

A constructor or method to initialize the data member.

A friend function declaration to compare values.

Define the friend function outside both classes:

Access the private members of both class objects.

Compare the two integer values.

Determine and display the minimum value.

In main():

Create one object for each class and initialize their integer values.

Call the friend function, passing both objects.

End the program.




## Program:
#include<iostream>
using namespace std;

class Minimum{
  public:
  void findMinimum(int a,int b)
  {
      if(a>b)
      {
          cout << "Minimum value is " << b;
      }
      else{
          cout << "Minimum value is " << a;
      }
  }
};

int main()
{
    int a,b;
    cin >> a >> b;
    Minimum m;
    m.findMinimum(a,b);
    return 0;
}


## Output:
<img width="1036" height="499" alt="image" src="https://github.com/user-attachments/assets/15b03ddd-ebe6-4529-bd70-c69ab3e974de" />

## Result:
Hence the program is executed successfully.

