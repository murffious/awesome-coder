Debugging

Know where the code is stopping
Read VERY carfeully teh ENITRE error message. Multiple times. - looking for a file path to where the code broke 
If node code - hit the route with postman and hard code an object console log in the route , conoslel.og req. Body and req.params 


console.log(“file loaded”)
console.log(“above function or if statement or for loop”)
console.log(“inside function or if statement or for loop”)

File path to connect files is broken (esp if front end javascript ro css) 
Function is not being called
For loop condition or if statemetn condition is not really true so not running usually due to some typo or variable being undefiend 

console.log(“variable name”, variable) to see what the computer sees
