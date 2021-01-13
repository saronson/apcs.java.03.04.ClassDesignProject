# Class Design Project

1. Pick some topic that holds interest for you.
2. Add a file for that class (for example, if I am designing a Dog class, I would add a file named Dog.java).
3. Design and write the Java class that represents this topic. The class should have:

- instance variables (at least two)
- constants (at least one)
- constructors (at least two, one of which is a default constructor)
- accessor and mutator methods (gets and sets for each instance variable)
- ```public String toString()``` method
- ```public boolean equals(Object obj)``` method 

4. Add code to the ```main``` in the Test class to make some objects from your class and do something interesting with them

If you want to get input from a user in your test program,  here is code to do that:

  ```java.util.Scanner scan = new java.util.Scanner(System.in);```
  
  ```scan.next()``` will have user enter a String
  
  ```scan.nextInt()``` will have user enter an integer
  
  ```scan.nextDouble()``` will have user enter a double
