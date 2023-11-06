#include <iostream>

using namespace std;
//1 
int main()
{
    int a, b, c, d, e;
    cin >> a >> b;
    d = (a+b)/2;
    e = a*b;
    cout<< "The result of avarage is "<<d<<endl;
    cout<<"the result of product is "<<e<<endl;
    
//2
    float l, h, A; //length and height and Area
    cin>>l>>h;
    A = 0.5*l*h;
    cout<<"The Area of triangle is "<<A<<endl;
    
//3 
    float p;
   cin >> p;
   float f = (9 * p) / 5; // calculating the first part of the formula
   f += 32; // calculating the remaining part
   cout << "Temperature in Fahrenheit: " << f<<endl; // printing the calculated temperature
   
//4
   int numberofStudents, freeComputers;
   cin>>numberofStudents;
   if(numberofStudents>=50){
       freeComputers = numberofStudents % 50;
       cout<<"The number of free compters in the last group is equal to "<<freeComputers<<endl;
   }else{
       freeComputers = 50 % numberofStudents;
       cout<< "The number of free computer in the last group is equal to "<<freeComputers<<endl;
   }
   
//5
    cout << "Size of char: " << sizeof(char) << " byte" << endl;
    cout << "Size of int: " << sizeof(int) << " bytes" << endl;
    cout << "Size of float: " << sizeof(float) << " bytes" << endl;
    cout << "Size of double: " << sizeof(double) << " bytes" << endl;


    return 0;
}
