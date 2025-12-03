Exercise B1
Object Oriented


You can find excellent explanations about Object Oriented Programming in Python here:
https://pynative.com/python-classes-and-objects/

Explanations on operators overloading: 
https://www.geeksforgeeks.org/operator-overloading-in-python/ 

Write Square and Rectangle classes which for the following main function:

if __name__ == "__main__":
    s = Square(5)
    r = Rectangle(8, 2)

    print(f"square area = {s.get_area()}")
    print(f"rectangle area = {r.get_area()}")

    print(f"aggregated area is: {s+r}")


The method get_area() should be implemented only once.

The following output will be printed:

square area = 25
rectangle area = 16
aggregated area is: 41



