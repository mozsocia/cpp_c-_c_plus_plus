https://www.geeksforgeeks.org/vector-in-cpp-stl/

https://www.programiz.com/cpp-programming/vectors

```cpp

#include <iostream>
#include <vector>
#include <bits/stdc++.h>
  
using namespace std;
  
int main()
{
  
    // initializer list
    vector<int> vector1 = {1, 2, 3, 4, 5};

    // uniform initialization
    vector<int> vector2{6, 7, 8, 9, 10};

    vector<int> g1;
  
    for (int i = 1; i <= 5; i++)
        g1.push_back(i);
  
  
    for (auto i = g1.begin(); i != g1.end(); ++i){
      cout << *i << " ";
    }
    
    
    
    
     for (auto i : g1) {
        cout << i << "  ";
    }
  
     for (int i : g1) {
        cout << i << "  ";
    }
    
    
    
  
    for (const int& i : vector2) {
      cout << i << "  ";
    }    
   
    for (const auto& i : vector2) {
      cout << i << "  ";
    }
  
  
  
  
  
  
  
    cout << "Size : " << g1.size();
    cout << "\nCapacity : " << g1.capacity();
    cout << "\nMax_Size : " << g1.max_size();
  
    // resizes the vector size to 4
    g1.resize(4);
  
    // prints the vector size after resize()
    cout << "\nSize : " << g1.size();
  
    // checks if the vector is empty or not
    if (g1.empty() == false)
        cout << "\nVector is not empty";
    else
        cout << "\nVector is empty";
  
    // Shrinks the vector
    g1.shrink_to_fit();
    cout << "\nVector elements are: ";
    for (auto it = g1.begin(); it != g1.end(); it++)
        cout << *it << " ";
  
    return 0;
}
```
