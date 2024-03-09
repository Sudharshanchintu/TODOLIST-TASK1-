# TODOLIST(TASK1)
➼In the first line, we are importing Tkinter which is basically a standard GUI library in Python and every possible object of it.
➼In the second line, we are importing an important widget from the Tkinter library called the message box which is used to display messages in a python to-do list project.
➼entertask() is used to add a task to the listbox. When this function is called another window opens in which we can write our task and it is added to the listbox. add() function is called when the Add task button is clicked in the opened window.
➼Entered input is stored in input_text, if the variable is empty then a warning message is displayed else it is inserted in the listbox of python to-do list.
➼deletetask() is used to delete a selected item, listbox_task.curselection() function returns a tuple in which the first element is the index of the selected item. Then, delete() function is used to delete the item corresponding to the index in python to do list application
➼markcompleted() is used to mark an item in to-do list as completed. In this function, we store the contents of the selected task in a variable called temp_marked.
➼We update the value by adding a ” ✔” at the end. After this, the delete() function deletes the selected task, and insert() function inserts the updated value at that particular index. 
➼Tk() is a top-level widget which is used to create the main application window in which we will be building python to-do list application.
➼The title() method is used to give a name to our application which is basically displayed at the top.
➼Frame() method is basically a container widget within our main window and it is used to hold different widgets. It takes an argument that is our main window.
➼pack() method is a geometry manager which organizes the widget properly before placing it in the main window in a level order fashion until explicitly mentioned.
➼Listbox() widget is going to store all the tasks that we list in python to-do list application. We have given three arguments out of which the first one is where we want our widgets to be placed. If the height and width is not given, it takes the default value. Also it would take the default value as window, if the frame_task is not explicitly mentioned.
➼Scrollbar() widget is used to place a scroll bar in case the total number of lists exceeds the given dimension of the to-do list window. Like every other widget it takes an argument as to where it should be placed. We pack it to the RIGHT of the frame_task widget then we set it on the listbox_task widget and after that we configure it on the vertical axis given by the command listbox_task.yview.
➼Button() widget is used to create a button. We want the buttons in our main to-do list window so the input window is given. Then the text which will be displayed on the button is specified and at last in the command input a function is given which will be called when the button is clicked.
➼The mainloop() method basically runs the Tkinter event loop, it runs and displays everything we have written in our code.
