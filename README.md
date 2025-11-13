Exercise 5
Object Oriented


You can find excellent explanations about Object Oriented Programming in Python here:
https://pynative.com/python-classes-and-objects/

1.	Write Square and Rectangle classes which for the following main function:

if __name__ == "__main__":
    s = Square(5)
    r = Rectangle(8, 2)

    print(f"square area = {s.get_area()}")
    print(f"rectangle area = {r.get_area()}")

    print(f"aggregated area is: {s+r}")


The method get_area() should be implemented only once.

The following output will be given:

square area = 25
rectangle area = 16
aggregated area is: 41



---------------------------------------------------




1.	a) Implement the following classes hierarchy
Vehicle → Car → Truck
		→ Family
		→ Sport

	→ Bike → Mountain
		→ Road

Car and Bike inherit from Vehicle. 
Truck, Family and Sport inherit from Car. 
Mountain and Road inherit from Bike.

-	Each vehicle has color and track kilometrage 
-	Each car has vendor and marketing slogan
-	Each specific car type (truck, family and sport) has name of its model and max speed
-	Each specific bike type (mountain and road) has name of its model and max speed
-	Printing the string representation of each object will show its vendor, model, slogan, covered distance and color.


b) Implement functions for the following scenarios:
-	Write a function that will add random distance (between 1-500) to the given object. 

-	Each car needs to go through a routine check every 30,000 KM.
Bikes do not need routine checks.
Write a function that prints how much distance can be covered until the next check.

-	Mitsubishi decided to rename their “Outlander Ignite” model name to “Outlander Inspire”

-	Opel decided to change their slogan from “We Love Cars” to “The Future is Everyone”. All its cars should get the new slogan.

-	Some cars are imported to the US. From that point and on - their distances needed to be shown in miles.

-	Find the vehicle with the highest speed.


