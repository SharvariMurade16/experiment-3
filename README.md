# Experiment-3
## Aim -
To study and implement operators in c++
## Theory -
Operators are essential symbols used to perform various operations on variables and values in programming. They are fundamental for calculations, assignments, decision-making, logical computations, and comparisons. Here’s a breakdown of the key types of operators and their uses:

### Arithmetic Operators :

+: Addition (e.g., a + b)

-: Subtraction (e.g., a - b)

*: Multiplication (e.g., a * b)

/: Division (e.g., a / b)

%: Modulus (remainder, e.g., a % b)

### Assignment Operators :

=: Assigns value (e.g., x = 5)

+=: Adds and assigns (e.g., x += 5)

-=: Subtracts and assigns (e.g., x -= 5)

*=: Multiplies and assigns (e.g., x *= 5)

/=: Divides and assigns (e.g., x /= 5)

%=: Modulus and assigns (e.g., x %= 5)

### Logical Operators :

&&: AND (true if both are true, e.g., a > 5 && b < 10)

||: OR (true if at least one is true, e.g., a > 5 || b < 10)

!: NOT (inverts boolean value, e.g., !(a > 5))

^: XOR (true if exactly one is true)

### Comparison Operators :

==: Equal to (e.g., a == b)

!=: Not equal to (e.g., a != b)

>: Greater than (e.g., a > b)

<: Less than (e.g., a < b)

>=: Greater than or equal to (e.g., a >= b)

<=: Less than or equal to (e.g., a <= b)

These operators are used to perform basic calculations, make decisions, and compare values in programming.

## Code-
1)-
```
//sharvari murade
//23070123088
//entc-b1

#include <iostream>
using namespace std;
int main(){
    int a,b;
    cout<<"Enter a number: ";
    cin>>a;
    cout<<"Enter second number: ";
    cin>>b;
    cout<<"Addition ("<<a<<"+"<<b<<"): "<<(a+b)<<endl;
    cout<<"Subtraction ("<<a<<"-"<<b<<"): "<<(a-b)<<endl;
    cout<<"Multiplication ("<<a<<"*"<<b<<"): "<<(a*b)<<endl;
    cout<<"Division ("<<a<<"/"<<b<<"): "<<(a/b)<<endl;
    cout<<"Modulas ("<<a<<"%"<<b<<"): "<<(a%b)<<endl;

    return 0;
}
```

2)-
```//sharvari murade
//23070123088
//entc-b1

#include <iostream>
using namespace std;
int main(){
    bool a,b;
    cout<<"Enter nature of a, 0 or 1: ";
    cin>>a;
    cout<<"Enter nature of b, 0 or 1: ";
    cin>>b;
    cout<<"a = "<<boolalpha<<a<<", b = "<<boolalpha<<b<<endl;
    cout<<"Logical AND ("<<a<<"&&"<<b<<"): "<<(a&&b)<<endl;
    cout<<"Logical OR ("<<a<<"||"<<b<<"): "<<(a||b)<<endl;
    cout<<"Logical NOT (!"<<a<<"): "<<(!a)<<endl;

    return 0;
}
```

3)-
```
//sharvari murade
//23070123088
//entc-b1

#include <iostream>
using namespace std;
int main(){
    int a,b;
    cout<<"Enter a number: ";
    cin>>a;
    cout<<"Enter second number: ";
    cin>>b;
    cout<<"Equal to ("<<a<<"=="<<b<<"): "<<(a==b)<<endl;
    cout<<"Not equal to ("<<a<<"!="<<b<<"): "<<(a!=b)<<endl;
    cout<<"Greater than ("<<a<<">"<<b<<"): "<<(a>b)<<endl;
    cout<<"Less than ("<<a<<"<"<<b<<"): "<<(a<b)<<endl;
    cout<<"Greater than or equal to ("<<a<<">="<<b<<"): "<<(a>=b)<<endl;
    cout<<"Less than or equal to ("<<a<<"<="<<b<<"): "<<(a<=b)<<endl;

    cout<<"Textual form: "<<endl;
    cout<<"Equal to ("<<a<<"=="<<b<<"): "<<boolalpha<<(a==b)<<endl;
    cout<<"Not equal to ("<<a<<"!="<<b<<"): "<<boolalpha<<(a!=b)<<endl;
    cout<<"Greater than ("<<a<<">"<<b<<"): "<<boolalpha<<(a>b)<<endl;
    cout<<"Less than ("<<a<<"<"<<b<<"): "<<boolalpha<<(a<b)<<endl;
    cout<<"Greater than or equal to ("<<a<<">="<<b<<"): "<<boolalpha<<(a>=b)<<endl;
    cout<<"Less than or equal to ("<<a<<"<="<<b<<"): "<<boolalpha<<(a<=b)<<endl;

    return 0;
}
```

### Output -
### 1.
![Image 12-08-24 at 9 33 PM](https://github.com/user-attachments/assets/06e502d3-8543-43dd-86bd-6d267f7c757f)
### 2.
![26A94F66-224B-4726-9954-593C6653CBB3](https://github.com/user-attachments/assets/e8bd6880-cdc9-430c-a668-93371297945f)
### 3.
![F2B11D94-63EC-4916-97F2-5B1A72542F0D](https://github.com/user-attachments/assets/7b6aa01c-e81b-4662-8c0b-03c96684ad82)

## Conclusion-
These programs provide a clear understanding of how to use various operators in C++. Mastery of operators is essential for performing mathematical calculations, making decisions, assigning values,comparing values and controlling the flow of a program.
