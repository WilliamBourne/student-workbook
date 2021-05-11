  # Var, let and const

## What is Scope?
 Scope is where variables are available for use. var is globally scoped or function scope. It is globally scoped when it is outside of a function and function scoped when inside a function. When function scoped the variable can only be used in that function. When globally scoped the variable is available for the whole window. 


 ## What is Hoisting?
 A javascript mechanism where variables and variable declorations are moved to the top before code execution. 

 ## var vs const vs let.
 Right now let is the preferred varibale declaration. Using let you don't have to worry about if you have used a name for a variable before as a variable exists only within it's scope. 
 Var declarations are function and globally scoped while let and const are block scoped. Var and let can be declared without being initialized while const must be initialized during declaration. 