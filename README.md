# 2. EXPERIMENT 2



## Aim:
To use the sizeof operator to display the sizes of fundamental data types in C++. This helps us gain further knowledge about the memory allocation for different data types in C++.


## Apparatus:
VS Code, Github


## Theory:
The sizeof operator is used to determine the size of a data types in bytes. Understanding this is important for optimizing the program with better memory management. Here are some common data types of C++ and their sizes:

### char:
Represents a single character and occupies 1 byte of memory.

### int:
A standard integer type the size of which can vary but it mostly occupies 4 bytes of memory.

### short int:
A short integer type occupies 2 bytes of memory.

### long:
A long integer type can occupy 4 or 8 bytes of memory.

### long long:
A long long integer type occupies 8 bytes of memory.

### float:
A float type occupies 4 bytes of memory.

### double:
A double type occupies 8 bytes of memory.

### long double:
A long double type can vary in size, it can occupy 8,12 or 16 bytes of memory.

### bool:
Represents a Boolean value which is either true or false, it occupies 1 byte. 

The sizes of these data types can differ depending on the compiler. This program shows code that prints the size of each data type using sizeof operator, allowing users to see the actual sizes of the various data types.

## Explanation:

### sizeof operator:
In this program we input values in various different datatypes such as int, short int, unsigned short int, long long int, char, wchar_t, float, double, long double, unsigned long long int. We then use the sizeof operator to print the ammount of memory that each data type occupies. We also use input values into different storage types such as static int, register int and extern double.

## Code:

### Size of various data types:
```
#include<iostream> 
//Yaman Hasan Ansari 
// PRN: 23070123155 
using namespace std; 
int main() 
{ 
   int a = 10; 
   short int a1 = 15; 
   unsigned short  int a2 = 20; 
   long long int a3; 
   char b = 'B'; 
   wchar_t b1; 
   float c = 3.14; 
   double d; 
   long double d1; 
   unsigned long long int d2; 


  static int e1; 
  register int e2 = 100; 
  extern float e3 ; 
  
   cout<<endl<<sizeof(a); 
   cout<<endl<<sizeof(a1); 
   cout<<endl<<sizeof(a2); 
   cout<<endl<<sizeof(a3); 
   cout<<endl<<sizeof(b); 
   cout<<endl<<sizeof(b1); 
   cout<<endl<<sizeof(c); 
   cout<<endl<<sizeof(d); 
   cout<<endl<<sizeof(d1); 
   cout<<endl<<sizeof(d2); 
   cout<<endl<<sizeof(e1); 
   cout<<endl<<sizeof(e2); 
   cout<<endl<<sizeof(e3); 
    return 0; 
} 
```
### Output:
![Screenshot 2024-07-30 101642](https://github.com/user-attachments/assets/16b3faed-a6b2-407d-9e64-995822d63af1)


## Conclusion:
This program demonstrates the use of sizeof operator to help determine the size of various data types in C++. Understanding the sizes of these data types helps us to make better memory management decisions and optimizing our programs.
