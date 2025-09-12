Project: number-display
Authors: Michael Kölling and David J. Barnes

This project is part of the material for the book

   Objects First with Java - A Practical Introduction using BlueJ
   Seventh edition
   David J. Barnes and Michael Kölling

It is discussed in chapter 3.

To use this project, create an instance of class NumberDisplay. Then inspect this 
instance and leave the inspector window open. With the inspector window open, 
call the object's methods, such as increment and setValue.

PART I
1. The class diagram simply shows the 2 classes in the project(graphical representation of the project), it's persistent because they're saved on file. The Object diagram shows the relation between the LabClass object and the Student objects, objects aren't persistent because they arent saved in file. FIX THE SYNTAX

2. If another class is added or deleted or if the relationship between classes are changed.
3. If an object is added or deleted or if the relationship between objects are changed.
4. private Instructor tutor;
5. Hours.increment();.

6.minutes.increment(); ...

8. For the first one, I wrote display.setValue(2); and the value changed to 2. For the second one, I wrote display.setValue(10); and the value remained to 2. That's because the code doesn't allow the value inserted to be higher than the rollOverLimit.

9.The value will be 0. ...

10.Error: non-static method getValue() cannot be referenced from a static context.
11.Error: '.class' expected. There shouldn't be an "int" before the value. It should be display.setValue(5);.

13. ...

14. If the setValue value surpasses the rollOverLimit(e.g. limit is 10 and setValue is 11), when getValue is called, it will return 11(usually, it's supposed to go back to 0).
15. "!false" and "(34 != 33) && ! false".

16. ...

17. ...

18. The returned value is 0.
19. There is no difference.
20. 12cat and cat12. I was right for the first one, but the second one was cat39. I'm guessing that any numbers after a string don't get added together.

