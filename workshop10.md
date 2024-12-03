# Workshop 10 - Object Orientated Programming

### Navigate to : 

**Task 1: Create a Student Class**Create a Python class called `Student` with the following specifications:

1.  The class should have attributes for `name`, `degree`, and `student_id`.
2.  Implement a constructor (**init** method) that initializes these attributes.
3.  Add input validation in the constructor:
    
    -   `name` should not be empty
    -   `degree` should be one of ["ECE", "BIO", "MECH", "EEE"]
    -   `student_id` should be a unique 6-digit number
    
4.  Implement a **str** method that returns a string representation of the student.

**Task 2: Implement Getter and Setter Methods**

1.  Create a getter and setter for the `degree` attribute using the `@property` decorator.
2.  In the setter, implement the same validation as in the constructor.

**Task 3: Create a Course Class**

1.  Create a `Course` class with attributes for `course_name`, `course_code`, and a list of enrolled students.
2.  Implement methods to add and remove students from the course.
3.  Implement a method to print all students enrolled in the course.

**Task 4: Inheritance**

1.  Create a `GraduateStudent` class that inherits from the `Student` class.
2.  Add an additional attribute for `research_topic`.
3.  Create a `UndergraduateStudent` class that inherits from the `Student` class. 
4. Add an additional attribute for `year_in_industry`, `foundation` and `repeater`


**Task 5: Main Program**

Write a main program that demonstrates the use of these classes:

1.  Create several `Student` `GraduateStudent` and `UndergraduateStudent`objects.
2.  Create a `Course` object and add some students to it.
3.  Print out the course details, including the list of enrolled students.
4.  Demonstrate the use of getter and setter methods for the `degree` attribute.

**Bonus Task: Operator Overloading**

Implement the `__add__` method for the `Course` class that allows two courses to be combined, merging their student lists (without duplicates).

