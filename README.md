# learningpython
My python learning journey
A while loop runs a set of statements, known as the loop body, while a given condition, known as the loop expression, is true.  

• A for loop can be used to iterate over elements of a container object.  

• A range()function generates a sequence of integers between the two numbers given a step size.  

• A nested loop has one or more loops within the body of another loop.  

• A break statement is used within a for or a while loop to allow the program execution to exit the loop once a given condition is triggered.  

• A continue statement allows for skipping the execution of the remainder of the loop without exiting the loop entirely.  

• A loop else statement runs after the loop's execution is completed without being interrupted by a break statement. 

 

 

 

 range(end)  Generates a sequence beginning at 0 until end with step size of 1.  

range(start, end) Generates a sequence beginning at start until end with step size of 1.  

range(start, end, s) Generates a sequence beginning at start until end with the step size of s 

 

While Loop 

 

 

  A while loop is a code construct that runs a set statement.  

It runs until the condition becomes false.  

Use while when iterations depend on conditions or events, not fixed-size data.   

 

 # initialization 

while expression:  

# loop body  

 

# statements after the loop  

 

 

For Loop 

 

 

 

 In Python, a container can be a range of numbers, a string of characters, or a list of values.  

 A for loop iterates over all elements in a container. 

For loop iterates over an iterable—such as a list, tuple, string, dictionary, set, or anything that yields element. 

 

 

# initialization  

for loop_variable in container:  

 

# loop body  

 

# statements after the loop 

 

 

 Nested While Loop 

 

 

A nested while loop means having a while loop inside another while loop. The inner loop runs completely for each iteration of the outer loop. 

 

 

while outer_loop_expression:  

# outer loop body (1) while inner_loop_expression:  

# inner loop body  

# outer loop body (2)  

 

# statements after the loop 

 

 

 

Break Statement 

 

 

A break statement is used within a for or a while loop. 

 A break statement can be used to improve runtime efficiency.  

 A break statement is an essential part of a loop that does not have a termination condition. 

 A loop without a termination condition is known as an infinite loop.  

 

 

 

# initialization  

while loop_expression:  

# loop body  

if break_condition:  

break  

# remaining body of loop  

 

# statements after the loop 

 

 

 

Continue Statement 

 

 A continue statement allows for skipping the execution of the remainder of the loop without exiting the loop entirely. 

A continue statement can be used in a for or a while loop.  

 After the continue statement's execution, the loop expression will be evaluated again and the loop will continue from the loop's expression.  

 A continue statement facilitates the loop's control and readability. 

 

 

 

# initialization  

while loop_expression:  

# loop body  

if continue_condition:  

continue  

# remaining body of loop  

 

# statements after the loop 

 

 

 

Loop else statement 

 

 A loop else statement runs after the loop's execution is completed without being interrupted by a break statement.  

 A loop else is used to identify if the loop is terminated normally without being interrupted by a break statement.  

 

 

 

# initialization  

for loop_expression:  

# loop body  

if break_condition:  

break  

# remaining body of loop else:  

# loop else statement  

 

 

# statements after the loop 
