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
 
                                          void show(int array[], int arraysize)
                                          {
                                          for (int i = 0; i < arraysize; ++i)
                                                cout << array[i] << " ";
                                          }
 
                                          int main()
                                          {
                                          int array[10] = { 1, 5, 8, 9, 6, 7, 3, 4, 2, 0 };
   
                                          int ArraySize = sizeof(array) / sizeof(array[0]);// size of the array
                                          cout << "The array before sorting is : \n";
   
                                          show(array, ArraySize);// print the array
 
                                          sort(array, array + ArraySize);// sort the array
 
                                          cout << "\n\nThe array after sorting is :\n";
   
                                          show(array, ArraySize); // print the array after sorting
                                                                  //outputs 0 1 2 3 4 5 6 7 8 9 
                                          return 0;
                                          }
 
                                          /*So, now, we know sort function sorts 
                                          the elements of the array in a ascending 
                                          or descending order*/
C++ Binary Search:
         
Now, What does Binary Search Algorithm work? See this code below to understand it clearly:

                                          #include <bits/stdc++.h>
                                          #include <iostream>
                                          
                                          using namespace std;
                                          
                                          int main()
                                          {
                                             int arr1[10] = {5 , 3 , 4 , 1 , 2 , 0 , 8 , 9 , 6 , 7};
                                             //First let us  sort this array
                                             sort(arr1 , arr1 + 10);
                                             //let us see if it is sorted
                                             int i;
                                             for(i = 0 ; i < 10 ; i++)
                                             {
                                                cout << arr1[i] << " "; //outputs 0 1 2 3 4 5 6 7 8 9
                                             }
                                             //Let us check if 5 is in this array
                                             if(binary_search(arr1 , arr1 + 10 , 5))
                                             {
                                                cout << "Great! 5 is there in the list!" << endl;
                                             }
                                             else
                                             {
                                                cout << "Uh oh....5 is not there in the list" << endl;
                                             } 
                                             //outputs Great! 5 is there in the list!
                                             //Let us see if 11 is there in the list
                                             if(binary_search(arr1 , arr1 + 10 , 11))
                                             {
                                                cout << "Great! 11 is there in the list" << endl;
                                             }
                                             else
                                             {
                                                cout << "Uh oh....there is no 11 in the list" << endl;
                                             }
                                             //outputs Uh oh....there is no 11 in the list
                                          }
