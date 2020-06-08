# What I learned in week 3
## Github
1. branch & merge
   - Create new branch to work on your own version of solution by git branch.
   - switch master branch and new branch via git checkout
   - merge new branch to master branch via git merge
   - multiple branches works on the same part can cause conflict. git status can show unmerged part and users can work on it.
## Javascript
1.data type
    
    - string
    - numbers
    - booleans
    - nan, null and undefined
### Sting

- Surrounded by '';
- If string contains ',surround string with "",or use/ before the '.
- The operation '+' for sting is concatenation. For easy-reading, +' ' to create space between words.
  
### number
- basic operation: +, -, *, /
- remainder: %
- exponentiation: **

2. variable
    - create variable by let/const/var(outdated)
    - operation on variable will work on the original value and assign the new one to the variable. e.g. let a = 1; a = a + 1; a = 2.

3. Function 
    - create function by function function-name(parameter){};
    - make function work need to call the function.
    - variable out side the function is global.Function can use global variable; variable inside function cannot used outside of the function.
    - to use global variables without changing their value need to use return.

4. Tool for javascript
### RunJS
Working on short command.

### Debug
set break point, JS will stop executing at breakpoint, user can examine JavaScript values.

### Quokka
cannot work with debug at the same time. quokka can show which function is called, the value of variables and the value of return after calling the return.


