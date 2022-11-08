Use this file to record your reflection on this assignment.

***I worked with Nathalie Trouba and Liberty Lehr on this assignment***

Which methods did you decide to overload, and why?

    In the Cafe class, I first decided to overload sellCoffee(...) to make a method for selling a black coffee (a very popular order which does not require cream or sugar as parameters). I then overloaded restock(...) to make a method for restocking just coffee, as coffee--in my experience--may run out more frequently than other ingredients. I additionally overloaded the Cafe constructor so that you do not need to put in the number of floors since it is not very useful. 
    
    In the Library class, I overloaded addBook(...) and removeBook(...) so that two books can be added/removed at the same time. 
    
    In the House class, I overloaded the moveIn(...) method twice so that people can be added to a House in groups of 2 and 3. (I was thinking of how people request doubles/triples with their friends.) 

What worked, what didn't, what advice would you give someone taking this course in the future?
    
    It was really helpful to use super() to minimize the amount of code I had to repeat, and I would recommend someone taking this course in the future to keep that in mind. 
    
    I was confused because on the rubric it says: "The `Library` class has a `goToFloor(...)` method that allows movement between non-adjacent floors"; however, not all libraries necessarily have elevators and I probably would not need to override the goToFloor(...) method if they did. As such, I used the same goToFloor(...) method in both House and Library--despite what the rubric said. I hope that's okay!