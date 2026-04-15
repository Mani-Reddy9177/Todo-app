Todo
This is a simple Todo application built using React. It demonstrates basic CRUD operations (Create, Read, Update, Delete) using the useState hook.

**What is this project?**

This Todo app allows users to:

Add new tasks
View all tasks
Edit existing tasks
Delete tasks

All operations are handled using React’s useState hook for state management.
Create:
How it works:
Take old data from todos
todos → copy old data
Add new input
setTodos() → update state
(“We are adding a new todo into the state using useState”)



Read:
How it works:
Take todos array
Use map() to loop
Show each item on screen
(“We are displaying todos using map function”)


Update:
How it works:
Copy old todos
Change one item using index
Update state using setTodos()
(“We update a specific todo using its index”)


delete:
How it works:
Loop using filter()
Remove selected index
Keep remaining items
Update state
(“We delete a todo using filter method”)






