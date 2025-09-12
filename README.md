# Number-Dislay project
Vanier Programming 01 course - Lab 03

Q1: The class diagram shows all the classes in the project, allowing us to get an overview of the project. It is persistent as classes are stored as .java files on the computers storage.
    The object diagram shows all instansiated objects, this allows us to get an idea of what exists and allows us to know what methods we can use, as well as visualize the relationship between objects. It is volatile, as objects exist only in the computers memory and will be overwritten when the program closes or disapear when the power to the RAM is cut.
    
Q2: The class diagram can change for several reasons, including:
        * A change to the name of the class                         => Change the class's box to display a new name  
        * A change in the relationships between classes             => Change the arrows that show the relationships  
        * A creation or deletion of classes                         => Change the number of classes boxes  

Q3: The object diagram can change for several reason, such as:
        * Creation or deletion of objects %n
        * A change in the relationship betweem objects %n
        * In the case that the object diagram shows the values of the fields of individuals objects, a change to the internal values would also change the object diagram

``` java
// Question 4
private Instructor tutor
```

Q6: We should look if the value of minutes is zero. 

Q8: display.setValue(10); did not affect the value.  The code for setValue() only executes when the new value < the limit

Q10: Error: non-static method getValue() cannot be referenced from a static context

Q11: Error: '.class' expected
``` java
display.setValue(5);
```

Q13: 0

Q14: Every integer

Q15: 
    * !false  
    * (34 != 33) && !false