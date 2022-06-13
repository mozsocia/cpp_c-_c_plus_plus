
### normal addition
```cpp


#include<iostream>
using namespace std;

template <class Test>

Test addition(Test num1, Test num2)  //Created generic template
{
        return (num1+num2);
}
int main()
{
      
        cout<<"\n Addition of Integer Parameters : "<<addition(10, 10);  
           
        cout<<"\n Addition of Float Parameters : "<<addition(15.5, 20.10);    
               
        return 0;
}

```

### High level 

```cpp
#include <iostream>
#include <bits/stdc++.h>

using namespace std;

template <class Dt>

int mycount(vector<Dt>& vp, Dt z){
	int num_count = 0;

	for(auto x : vp){
		if (x == z){
			num_count++;
		}
	}
	return num_count;
}

int main() {
    // Write C++ code here
    string mystr;
    vector<char> v1 = {'y','y','y','z','t','i','i'};    

	  cout << mycount(v1,'p');
    
    vector<int> v2 = {2,4,6,7,8,4,6};
	
  	cout << mycount(v2, 4) << endl;

  return 0
 }
	

```
