// Temprature Conversion 
// Take input in the form of Celcius and convert it into fahrenheit...

#include<iostream>
using namespace std;

int main(){
    
    double celcius;
    double fahrenheit;
    cin >> celcius;
    fahrenheit = (celcius * 9.0 / 5.0) + 32.0;
    cout << fahrenheit << endl;
    
    return 0;
    
}


// GLOBAL VS LOCAL VARIABLE

#include<iostream>
using namespace std;
// global variable
int globalVaribale = 100;
int main(){
    // local variable
    int userInput;
    float result;
    
    cin >> userInput;
    result = (double)globalVaribale / userInput;
    
    cout << result << endl;
    return 0;
    
}

// Problem 3
// Logical and relational Operators 

#include<iostream>
using namespace std;

int main() {
    int side1, side2, side3;
    cin >> side1 >> side2 >> side3;
    
    bool isEqui = (side1 > 0) && (side1 == side2) && (side2 == side3);
    cout << isEqui << endl;
    return 0;
    
}

// Problem 4
// Swap values of 2 variables using 3rd variable

#include<iostream>
using namespace std;

int main() {
    int a;
    int b;
    
    cin >> a >> b;
    // swapping Logic
    int temp = a;
    a = b;
    b = temp;
    
    cout << a << "\n" << b << endl;
    return 0;
}


// Area of Shapes
// 1 -- circle, 2 == rectangle, 3-- triangle
#include<iostream>
using namespace std;

int main() {
    int choice;
    cin >> choice;
    
    if(choice == 1){
        double radius;
        cin >> radius;
        cout << 3.14 * radius * radius << endl;
    } else if (choice == 2) {
        double length, width;
        cin >> length >> width;
        cout << length * width<< endl;
    } else if (choice == 3) {
        double base, height;
        cin >> base >> height;
        cout << 0.5 * base * height << endl;
    } else {
        cout << "invalid Choice" << endl;
    }
    return 0;
    
}
