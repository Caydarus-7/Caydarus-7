#include <iostream>
using namespace std;

// Define the Rectangle class
class Rectangle {
public:
    // Public member variables
    double length;
    double width;

    double getArea() {
        return length * width;
    }

    
    double getPerimeter() {
        return 2 * (length + width);
    }

    
    void display() {
        cout << "Area: " << getArea() << endl;
        cout << "Perimeter: " << getPerimeter() << endl;
    }
};

int main() {
    
    Rectangle rect1, rect2;

    // Assign values to the member variables of rect1
    rect1.length = 8.0;
    rect1.width = 5.0;

    // Assign values to the member variables of rect2
    rect2.length = 8.0;
    rect2.width = 7.0;

    
    cout << "Rectangle 1:" << endl;
    rect1.display();

    
    cout << "\nRectangle 2:" << endl;
    rect2.display();

    return 0;
}

