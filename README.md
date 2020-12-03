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
 
                                          #include <algorithm>
                                          #include <iostream>
 
                                          using namespace std;
 
                                          void show(int a[], int array_size)
                                          {
                                          for (int i = 0; i < array_size; ++i)
                                                 cout << a[i] << " ";
                                          }
 
                                         // Driver code
                                         int main()
                                         {
                                         int a[] = { 1, 5, 8, 9, 6, 7, 3, 4, 2, 0 };
   
                                         // size of the array
                                         int asize = sizeof(a) / sizeof(a[0]);
                                         cout << "The array before sorting is : \n";
   
                                         // print the array
                                         show(a, asize);
 
                                         // sort the array
                                         sort(a, a + asize);
 
                                         cout << "\n\nThe array after sorting is :\n";
   
                                         // print the array after sorting
                                         show(a, asize);
 
                                         return 0;
                                        }
 
