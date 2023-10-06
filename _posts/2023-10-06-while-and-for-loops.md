Ze second blog post. During time between first and second blog post I was learning for loop and while loop in python. Most recant assements I did in class were "Rootin Tootin Ranges" and "TODO Tracker".

In "Rootin Tootin Ranges" I was using for loops to count and to do math here are some of parts of the code.

  
    for x in range(11):
    print(x)

~~~~~~~
    a=0
    for x in range(1,11): 
      a+=x
      print(x) 
    print(a)
~~~~~~~
First line of code is telling python to print 1 throught 10 on separet lines and second code is counting 1 throught 10 and adding all of numbers from 1 to 10 and printing total on separet line.

In todo.py" I was using for while loop to create todo list for user to put his todo in and delete it. Here are some of parts of the code.

    todos=[]
    todos.append(input("Enter your first todo: "))
    while 1:

    print("-----------------------------------------------------")
    print(todos)
    print("-----------------------------------------------------")
    q=input("do you want to add one more todo to your todos? Y/N ")#this part of code allows user to choose action which they will do 
    if q=="Y"or q=="y":
        todos.append(input("Add you new todo: "))
    elif q=="N" or q=="n":
        z=input("do you want to delete one todo from your todos? Y/N ")
        if z== "y" or z=="Y":
            todos.remove(input("Enter you todo which you would like to remove: "))
        else:
            continue


            
First lines of todo list is empty list which will hold users todos.  Second lines of code is used to show users todos and last lines of code are asking user to delete or add new task.

