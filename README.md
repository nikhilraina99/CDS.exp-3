# Experiment 3
## Aim
To learn about arithmetic, logical, miscelleaneous and assignment operators on c++.
# Software Used
VS Code

# Problem Statements
1. Boolean Operators: Demonstrate the use of boolean operators in C++.
2. Equality Check: Write a program to check if two values are equal.
3.Inequality Check: Write a program to check if two values are not equal.

# Theory
Boolalpha Manipulator: The boolalpha manipulator in C++ allows boolean values to be displayed as true or false instead of 1 or 0.
Equality Operator (==): Returns true if both operands are equal, otherwise returns false.
Inequality Operator (!=): Returns true if the operands are not equal, otherwise returns false.

# Program codes
1.
```javascript
//Bool
#include<iostream>
using namespace std;
int main(){
    bool a= true;
    bool b= true;
    cout<<boolalpha;
    cout<<"A&&B: "<<(a&&b)<<endl;
    return 0;
}
```
2.
```
//Equality Operator
#include<iostream>
using namespace std;
int main(){
    int a,b;
    cout<<"Enter first number: ";
    cin>>a;
    cout<<"Enter second number: ";
    cin>>b;
    cout<<"a==b: "<<(a==b)<<endl;
    return 0;
}
```
3.
``` 
//Inequality Operator
#include<iostream>
 using namespace std;
 int main()
{
    int a,b;
    cout<<"enter first number: ";
    cin>>a;
    cout<<"enter second number: ";
    cin>>b;
    cout<<"a!=b: "<<(a!=b)<<endl;
    return 0;
}
```
4.
```
 #include<iostream>
 using namespace std;
 int main()
{ int a,b;
    
    a = 1;
    b = 1;
    cout<<"a&b: "<<(a&b)<<endl;
    cout<<"a|b: "<<(a|b)<<endl;
    cout<<"a^b: "<<(a^b)<<endl;
    cout<<"a: "<<(~a)<<endl;
    cout<<"a<<b: "<<(a<<b)<<endl;
    cout<<"a>>b: "<<(a>>b)<<endl;
    
    return 0;
}
```
# Output:
1.![Screenshot 2024-08-16 003434](https://github.com/user-attachments/assets/d9416b23-4de2-4336-b134-9d22a4c35e7f)

2.

3.![Screenshot 2024-08-16 003552](https://github.com/user-attachments/assets/095303bc-8e64-4905-a783-5c982943a639)

4.![Screenshot 2024-08-16 003617](https://github.com/user-attachments/assets/09a498eb-44ef-4e77-b279-456bf46e6c61)

# Conclusion
This repository provides a practical understanding of different operators in C++. By experimenting with these examples, users can gain insight into how each operator functions in C++ programming.





















