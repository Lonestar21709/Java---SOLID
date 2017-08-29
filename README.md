# Java - SOLID
SOLID - OO Design Principles 
Single Responsibility Principle - class should only have single reason to change, only know one thing

Open Closed Principle - open for extension, closed for modification. New changes should cause minimal changes to working and testing code.  Focus on changing environment around the module rather than the module itself.

Liskov Substitution Principle - subtypes must be substitutable for their basetypes. Pay attention to if a method should not be called on a sub-class -> violation of LSP.

Interface Segregation Principle - no clients should depend on methods they do not use.  If for example a class has two subclasses that use different methods within the parent class.  Then you should create interfaces for each sub-class so they don’t have to depend on the methods they don’t use.  

Dependency Inversion Process - VIOLATION when higher level modules depend on lower level ones susceptible to change.  High level should not depend on low level, BOTH should depend on abstraction.  Details depend on abstraction, abstraction should not depend on details.  

