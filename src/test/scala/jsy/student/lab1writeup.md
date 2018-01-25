# Lab 1 write up
Author: Chris Scarola  
Partner: Russell Decker

# Question 2.a.
pi at line 4 is bound to line 3 since in the circumference scope it is redefined.  
pi at line 7 is bound to the pi defined in the global scope on line 1

# Question 2.b.
The x at line 3 is bound to the x in the function f parameter list on line 2.  
The x in line 6 is bound to the case x in line 5 which will be the x from the f() argument given.  
The x at line 10 is also bound to the case x at line 5 since the x at line 8 is inside a different scope.  
The x at line 13 is bound to the x defined at line 1 since it is outside of the function.  

# Question 3.
g is well typed.  
    
    g: Int because
        a: Int from tuple declaration, a = 1
            After the if statment a = 1 or a = 3, both Ints
        b: Int because
            x: Int from function parameter, and 3 is an Int
                After the if statement b = (0, 3) which is (Int, Int)
                  