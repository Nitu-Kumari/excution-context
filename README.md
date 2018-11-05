# Execution contex
~~~
Execution context is defined as the environment in which JavaScript code is executed.
 By environment I mean the value of this, variables, objects, and functions JavaScript code has access to, constitutes it’s environment.

Execution context in JavaScript are of three types:
1 Global execution context 

2 Functional execution context

3 EVAL
~~~

 # 1 Global execution context 
 ~~~
 This is the default execution context in aJavascript code .
  when the file first loads in the browser.
   All the global code are executed inside global execution context. 
   ~~~

   # Functional execution context
   ~~~
   Functional execution context is defined as the context created by the execution of code inside a function.
  Each function has it’s own execution context.
   It can be more than one.
Functional execution context have access to all the code of global execution context. 
~~~


# Eval: Execution context inside eval function.
~~~
Execution context stack is a stack data structure to store all the execution stacks created while executing the JS code.
 Global execution context is present by default in execution context stack and it is at the bottom of the stack.
 JS engines pops out that functions execution context and starts executing the function
 ~~~

 
# JavaScript engine creates the execution context in the following two stages:
1 Creation phase
2 Execution phase
