# Ex.No:4
# Ex.Name:Write a program in C++ to convert temperature in Fahrenheit to Celsius using class methods(define member as private & define methods within class)
## Date:7/8/25
## Aim:
Write a program in C++ to convert temperature in Fahrenheit to Celsius using class methods(define member as private & define methods within class)


## Algorithm:
Start the program.

Create a class named Temperature.

Inside the class:

Declare a private data member to store the Fahrenheit value.

Define a public method to read the Fahrenheit temperature from the user.

Define another public method to convert Fahrenheit to Celsius using the formula:

Celsius=(Fahrenheit−32)×59Celsius=(Fahrenheit−32)×95
	​
Define a method to display the Celsius result.

In main():

Create an object of the class.

Call the method to input Fahrenheit.

Call the method to convert temperature.

Call the method to display the Celsius value.

End the program.




## Program:
#include<iostream>
using namespace std;

class Temperature {
  private:
  float celsius;
  float fahrenheit;
  public:
  void setfahrenheit(float f){
      fahrenheit = f;
  }
  void convert(){
      celsius = (fahrenheit - 32) * 5/9;
  }
  void printCelcius(){
      cout << "The temperature in Celsius:" << celsius << endl;
  }
  void printFahrenheit(){
      cout << "The temperature in Fahrenheit:" << fahrenheit << endl;
  }
};

int main(){
    float fah;
    cin >> fah;
    Temperature t;
    t.setfahrenheit(fah);
    t.convert();
    t.printFahrenheit();
    t.printCelcius();
    return 0;
}

## Output:

<img width="1045" height="527" alt="image" src="https://github.com/user-attachments/assets/4697095f-0fb5-45b8-9955-7bf71971657f" />

## Result:
Hence the program is executed successfully.
