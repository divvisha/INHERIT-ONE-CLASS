# EXPERIMENT-8 JAVA PROGRAM TO ACQUIRE THE PROPERTIES OF OTHERS USING INHERITANCE.

## AIM:
To write a Java program using inheritance one class can acquire the properties of others.

## Algorithm:
1. Open Intelli J application or any other code editor.

2. Create a class called "Animal" and create required statements.

3. Create a another class called "Bird" and create required statements.

4. Create another class,called the Solution Class.

5. Using the 'extends' keyword you can inherit classes, do the same with above created class.

6. Display the statements from the first and secomd Class using Solution Class in the terminal.

## PROGRAM:

class Animal<br>
{<br>
void walk()<br>
{<br>
System.out.println("I am walking");<br>
  }<br>
}<br>

class Bird extends Animal<br>
{<br>
void fly()<br>
{<br>
System.out.println("I am flying");<br>
  }<br>
}<br><br>

public class Solution<br>
{<br>
public static void main(String args[])<br>
{<br>
Bird bird = new Bird();<br>
bird.walk();<br>
bird.fly();<br>
  }<br>
}

## OUTPUT:
<img width="179" alt="java ex9 op" src="https://github.com/divvisha/INHERIT-ONE-CLASS/assets/127508123/8f4eccaf-9f59-4925-847a-67172f0f5423">

## RESULT:
Thus the program to acquire the properties of others using Inheritance has been created and executed successfully.
