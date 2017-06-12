## Scope, hoisting and compartmentalization

### Answer the following:
In you own words, explain the concepts of scope, hoisting, compartmentalization.
Scope is used to define the access level(permissions) of the variable.  Hoisting is elevating the global variable and functions to the top of the page(this is the way javascript organizes these objects.).  Compartmentalization is breaking things into components to easily manage the smaller functions.

### Provide examples for all three, below:

#### Scope:
var name = 'John';
function what(){
    var name = 'Justin';
    return name;
}
The name = 'Justin' is a local variable and does not live as 'Justin' outside of the function.  Everywhere else name = 'John';
#### Hoisting:
Variables and functions are brought to the top of the javascript space and held in memory.  Initialization of variables does not happen in this area.  Variables have to be initialized prior to calling a function that uses them.

#### Compartmentalization:
Breaking large pieces of code into smaller pieces to allow for easier functionality. 

Like a car would have multiple components to allow for different functions.  

Function right_pedal(){
    makes the car go faster;
}
Function left_pedal(){
    stops the car
}