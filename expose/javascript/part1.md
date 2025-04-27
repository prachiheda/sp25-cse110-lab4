1. values added: 20 
2. final result: 20 
3. We should not use var because it is function scoped. So even though the var was declared inside an if block, the whole function can access the var. This can be unexpected. 
4. values added: 20
5. The code will return an error because the let result variable was declared in the if statement, and variables declared with let is not defined outside its code block. 
6. line 9 will return an error because we are trying to modify a variable that has been declared to be constant
7. Similar to variables declared with let, the variable result declared with const is only scoped within its code block which is the if block. Therefore we will get an error trying to access the variable outside of its scope. 



