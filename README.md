# EXP-15

## Aim:
**To study and implement Recursion.**

## Software:
`Microsoft VSCode`

## Theory:
Recursion in C++, is a technique in which a function calls itself repeatedly until a given condition is satisfied.
Syntax Structure of Recursion
return_type recursive_func {
....
// Base Condition
// Recursive Case
....
}
## Code: 15A
```cpp
// NAME - Kanwaljeet singh
// PRN- 23070123124
// EXPERIMENT - 15(A) 

#include<iostream> 
using namespace std;

// Creating a function. 

int fact(int n){
    if(n<=1){
        return 1;
    }
    else{
        return(n*fact(n-1));  // Recursion 
    }
}

int main(){
    int X,n;
    cout<<"Enter a number: ";
    cin>>n;
    X=fact(n);
    cout<<X;
    return 0;
}
```
## Output:
![Uploading image.png…]()








## Code: 15B
```cpp
// NAME - Kanwaljeet singh
// PRN - 23070123124
// EXPERIMENT - 15(B)
#include<iostream> 
using namespace std;

int add(int n){
    if(n<=1){
        return 1;
    }
    else{
        return(n+add(n-1));
    }
}

int main(){
    int X,n;
    cout<<"Enter a number: ";
    cin>>n;
    X=add(n);
    cout<<X;
    return 0;
}
```
## Output:
![Uploading image.png…]()






## Code: 15C
```cpp
// NAME - Kanwaljeet singh
// PRN - 23070123124
// EXPERIMENT - 15(C)
#include<iostream>
using namespace std;      

// Creating function. 
void reverse(char *str)
{
    if(*str)  // Base Condition 
    {
        reverse(str+1);  // Recursion 
        cout<<("%c",*str);
    }
}

int main() 
{
    char a[50];
    cout<<"Enter a string: ";
    cin>>a;
    reverse(a);  // Function calling 
    return 0; 
}       
```
## Output:
![image](https://github.com/user-attachments/assets/f4560189-5057-4d13-984f-a286c27dfbbd)



## Code: 15D
```cpp
// NAME - Kanwaljeet singh
// PRN - 23070123124
// EXPERIMENT - 14(D)

#include<iostream> 
using namespace std;

// Creating a function 

void print_rev(int i){
    if(i>0)          // Base Condition  
    {
        cout<<(i%10);
        print_rev(i/10);   // Recursion 
    }
}

int main()
{
    int i;
    cout<<"Enter the number: ";
    cin>>i;
    print_rev(i);  // Function Calling   
    return 0;
}           
```                  
## Output:
![image](https://github.com/user-attachments/assets/31f30dd0-ee45-4c5d-8bcd-118cd2145e45)




### Conclusion:
I learnt about recursion in C++ and performed programs based on that.
