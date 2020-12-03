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
 
                                          #include <iostream>
                                          #include <bits/stdc++.h>
                                          
                                          using namespace std;
                                          
                                          int main()
                                          {
                                             int i;
                                             vector<int> arr1{"5" , "8" , "4" , "2" , "9"};
                                             cout << "Intial Array.....Not sorted:" << endl;
                                             for(i = 0 ; i <= arr1.size() ; i++)
                                             {
                                                cout << arr1[i] << " ";
                                             }
                                             cout << "Sorted Array:"
                                             sort(arr1.begin() , arr1.end()); // To sort arr1
                                             for(i = 0; i < arr1.size() ; i++)
                                             {
                                                cout << arr1[i] << " ";
                                             }
                                          }
 
