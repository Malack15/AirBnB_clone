Description of the project
The goal of the project is to create a replica of Airbnb website using my server.
The final version of this project will have:
- A command interpreter to manipulate data without a visual interface, like a shell.
- A website (front-end) with static and dynamic functionalities
- A comprehensive database to manage the backend functionalities
- An API that provides a communication interface between the front and backend of the system.
## Description of the command interpreter
| Commands  | Description |
| --------- | ----------- |
| ```quit```  | Quits the console  |
| ```Ctrl+D```  | Quits the console  |
| ```help``` or ```help <command>```  | Displays all commands or Displays instructions for a specific command
| ```create <class>```  | Creates an object of type , saves it to a JSON file, and prints the objects ID
| ```show <class> <ID>```  | Shows string representation of an object
| ```destroy <class> <ID>```  | Deletes an objects
| ```all or all <class>```  | Prints all string representations of all objects or Prints all string representations of all objects of a specific class
| ```update <class> <id> <attribute name> "<attribute value>"```  | Updates an object with a certain attribute (new or existing)
| ```<class>.all()```  | Same as all ```<class>```
| ```<class>.count()```  | Retrieves the number of objects of a certain class
| ```<class>.show(<ID>)```  | Same as show ```<class> <ID>```
| ```<class>.destroy(<ID>)```  | Same as destroy ```<class> <ID>```
| ```<class>.update(<ID>, <attribute name>, <attribute value>```  | Same as update ```<class> <ID> <attribute name> <attribute value>```
| ```<class>.update(<ID>, <dictionary representation>)```  | Updates an objects based on a dictionary representation of attribute names and values
## General Execution
Your shell should work like this in interactive mode:
$ ./console.py
(hbnb) help

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb) 
(hbnb) 
(hbnb) quit
$
But also in non-interactive mode: (like the Shell project in C)

$ echo "help" | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb) 
$
$ cat test_help
help
$
$ cat test_help | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb)
$
