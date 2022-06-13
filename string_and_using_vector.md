
```cpp


// Online C++ compiler to run C++ program online
#include <iostream>
#include <bits/stdc++.h>

using namespace std;

int main() {
    // Write C++ code here
    string mystr;
    getline (cin, mystr);
    cout << mystr;
    
    for(auto i = mystr.begin();i != mystr.end();++i){
        cout << *i << " ";
    }
    for (char j : mystr){
        cout << j << " ";
    }
    cout << "Hello world!";

    return 0;
}

```

### taking a string and store it in a vector

```cpp

    string mystr;   
    
    getline (cin, mystr);

    vector<char> v4(mystr.begin(),mystr.end());
    
 ```
 
 
 ```cpp
 
 
 #include<iostream>
#include <bits/stdc++.h>
using namespace std;

int main()
{
      
    string mystr;   
    
    string s3 = "mozdalif";
    
    getline (cin, mystr);

    vector<char> v4;
    v4.insert(v4.end(),mystr.begin(),mystr.end()); 
    
    v4.insert(v4.end(),s3.begin(),s3.end());
    
    for(auto x: v4){
        cout << x << " ";
    }
               
    
    return 0;
}
```
