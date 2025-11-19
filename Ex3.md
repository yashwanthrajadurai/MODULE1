# Ex.No:3
# Ex.Name:Write a c++ program to Calculate the volume of a cylinder using class methods(declare members as private & methods define inside the class) 
## Date:
## Aim:
Write a c++ program to Calculate the volume of a cylinder using class methods(declare members as private & methods define inside the class) 

## Algorithm:




```
## Program:
#include <iostream>
using namespace std;
class cylinder
{
private:
float r,h;
public:
void input()
{
cin>>r>>h;
}
void result()
{
float v=3.14*r*r*h;
cout<<"The Volume of the Cyclinder is:"<<v<<endl;
}
};
int main()
{
cylinder s1;
s1.input();
s1.result();
}

```
## Output:
  <img width="1920" height="1080" alt="Screenshot (12)" src="https://github.com/user-attachments/assets/26940bb1-b571-4945-9f8c-4f31f3444461" />



## Result

The code is running Successfully.
