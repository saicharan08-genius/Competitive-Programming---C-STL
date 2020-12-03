# Competitive Programming - C++ STL 

Disclaimer: This is Competitive programming contest related and not software development related

C++ STL Programming prerequisites:
    
                               1.Basic Programming in C++(structures, loops, conditions, data types)
                               2.Class Templates and Generic Programming in C++
                               
C++ STL Programming Conisist of:
  
                               1.Containers
                               2.Algorithms
                               3.Functions
                               4.Iterators
                               
# C++ Algorithms:

C++ Sorting: 

What does Sort function in C++ do? You will understand it in the C++ code below:
 
                                          #include <bits/stdc++.h>
                                          #include <iostream>
 
                                          using namespace std;
 
                                          void show(int num[], int arraySize)
                                          {
                                          for (int i = 0; i < arraySize; i++)
                                                 {
                                                 cout << a[i] << " ";
                                                 }
                                          }
 
                                         int main()
                                         {
                                         int num[10] = { 1, 5, 8, 9, 6, 7, 3, 4, 2, 0 };
   
                                         int arraysize = sizeof(a) / sizeof(a[0]); // size of the array
                                         cout << "The array before sorting is : \n";
   
                                         // print the array
                                         show(a, arraysize);
 
                                         // sort the array
                                         sort(a, a + arraysize);
 
                                         cout << "\n\nThe array after sorting is :\n";
   
                                         // print the array after sorting
                                         show(a, arraysize);
 
                                         return 0;
                                        }
 
