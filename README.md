- What is the difference between ***var*** and ***let***?
    var can be reassigned and redeclared. There can be mulitple of var x = "some text or number", while let cannot be redeclared.
- What is the difference between **var** and ***const***?
    const can neither be reassigned nor redclared.
- What is the difference between **let** and **const**?
    let can be reassigned and mutated, while const can only be mutated.
- What is hoisting?
    Hoisting is calling a variable before it is declared; they are often put at the top of the code, before being used in a function.


**** from the solutions section:
- What is the difference between ***var*** and ***let***?
    
    You can reassign and redeclare with ***var***, but you can not redeclare using the ***let*** keyword. You can access a hoisted variable with var. Let creates block scope.
    
- What is the difference between ***var*** and ***const***?
    
    You can reassign and redeclare with ***var***, but you can not redeclare or reassign using the ***const*** keyword. You can access a hoisted variable with var. Const creates block scope.
    
- What is the difference between ***let*** and ***const***?
    
    You can reassign with ***let***, but you can not redeclare or reassign using the ***const*** keyword.
    
- What is hoisting?
    
    It’s the way that we explain how the JS compiler works. Variables are lifting or “hoisted” to the top of the scope they are declared in. When using ***var***, you can access the variable name and it’s undefined value before it is used later on.
    
    Function declarations are also hoisted and can be invoked “before” they are defined in a codebase.