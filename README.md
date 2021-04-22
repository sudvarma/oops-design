# oops-design


###### Ask for things - don't look up (use dependency injection instead)

###### Avoid global state. (eg: Avoid Singleton)

###### Prefer composition - avoid inheritance (eg: Bridge Pattern)

## SOLID

###### S	
	Single Responsibility ( a class should be modified only for a single purpose)
###### O
	Open for extension closed for modification (a functionality could be extended with out modifying the class)
###### L
	Liskov's Subsitiution principle (an interface should be substitutatble for any of the implementation class)
###### I
	Interface seggregation principle (interfaces should be thin and not fat,
					    classes should not be forced to implement methids that it doesn't need)
###### D
	Dependency Inversion Principle (the high level module should not be dependent on low level module - 
	instead all dependency should happend through an abstraction.
	For eg: "Print" module should not include printer specific details, there by making it difficult print
                using a different printer. Instead the print should depend only on a printer abstraction.


## Design Patterns
Three main categories
###### Creational Patterns
    To do with creation of class instance. To avoid usage of new instance along with the business objects and to create them separately, say using a factory.
    
###### Structural Patterns
    To do with relation between class instances
    
###### Behavioural Patterns
    To do with communication between class instances
