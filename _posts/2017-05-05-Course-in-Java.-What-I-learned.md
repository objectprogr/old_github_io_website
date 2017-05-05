---
layout: post
title: "What I learned"
tags: java objects learning coding
---
## What give me a course?
To this time I have done 7 chapters in 57. 
The most important was chapter 6 Classes and objects. I managed to understand what are the diffrents between object and reference.
How thanks objects I can simplify my code. Code is more flexible. Introduction of some changes in my project is easier. 
Earlier I tried what are they objects, but I did can't. This course in very simple way explain me these issues.
{: .alert .alert-info .text-justify}
## Object and reference
```javascript
Car audi = new Car();
audi.doors = 4;
audi.color = "red";
```
**new Car()** - This is new object Car class.
and a reference is **audi**
The object is new Car() which holds all informations about object (car).
The reference is audi because it allows identify specified object (car).
Example:
Whe have a two objects Car class:

```javascript
Car opel = new Car();
opel.doors = 2;
Car bmw = new Car();
bmw.doors = 4;
```
And thanks the reference computer (compiler) can find the place where it is saved specific object (car) in computer memory. The object which we want use.
{: .alert .alert-info .text-justify}
Example:
```javascript
System.out.println(bmw.doors);
```
And computer know what Car class object to use. So in this case bmw. 

## Constructor
Constructor must have same name as class.
```javascript
class Car(){
	int doors;
	String color;
	
	//This is a constructor
	Car(int carDoors, String carColor){
		doors = carDoors;
		color = carColor;
	}
}
```
And, now we want create new object Car class:
```javascript
Car opel = new Car(4, "black");
```
Thnaks the constructor we can create new object using the less code. Great!
Now, when we have a constructor, creating object we must type in doors and color. If we dont do this IDE will indicate error and the code will not compile.
{: .alert .alert-info .text-justify}
And again managed to us cut our code. 

**Ok, I go back to leran :D**