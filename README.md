# OOP-Lab-3

## School Simulation 2.0

For this laboratory work,I extended my already existing classes using inheritance and created a logical hierarchy of entities. I experimented with acces modifiers to see and understand how visibility works,I defined abstract classes,as well as overrid attributes/methods. 

In my simulation, you can create a certain School,with its own name,surface(area in square meters),city,address,annual funds. Going into more detailed simulated elements, you can create multiple floors with their own attributes,multiple classrooms,canteens or sports halls. Human beings can be simulated as well and they are of two types: Staff and Student. Each has their own characteristics, like name,grade,presence(Student), salary(Staff). Staff is divided into 3 main categories: teacher(has attribute subject), adjunct ( has attribute task), AuxiliaryWorker( has attribute job, which can be nurse, cook, janitor and so on).

As it can be seen in the diagram,my school simulation has root superclass "Entity",which has attribute ID and method exist(). The concrete class School and the abstract class Person  inherit superclass Entity,each with their own attributes and methods. Next there are subclasses Staff and Student of abstract class Person,which inherit the attribute name and method doSomething(). Classes Teacher, Adjunct and AuxiliaryWorker inherit class Staff. The classes Floor and Location inherit from parent-class School. Next up, classes Classroom,Canteen and SportsHall inherit from Floor.
