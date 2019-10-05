topics:  

1. Relationship(saving sub entities)  
    a. one to one  
    b. one to many  
    c. many to one  
2. Embeded objects(saving sub object which are not entities)    
3. Inheritance  
    a. single table
    b. table per class
    c. join table
4. Caching  
    a. level one  
    b. level two  
    
    
    
    
**have a look:**  
 
class User with data member:

1. ArrayList<String>  
2. ArrayList<Address> - called embedded objects iff Address is not an Entity  
3. Address (Address is not an Entity) - called embedded object  
4. Address home, Address office (where address is not ant Entity. its an Embedded object and we have two such objects then how would a table structure be) - called embedded object  
5. Vehicle (its an Entity one object only) - often called one to one mapping  
6. ArrayList<Vehicle> - called one to many mapping  

----
1. @Embedded
2. @Embeddeble
3. @Entity
4. @ElementCollection
5. @CollectionId
