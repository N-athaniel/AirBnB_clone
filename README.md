0x00. AirBnB clone - The console
Group project
Python
OOP

Team project to build a clone of AirBnB.

The console is a command interpreter to manage objects adstraction between objects and how they are stored.

The console will perform the following tasks:
create a new object
retrive an object from a file
do operations on objects
destroy an object

All the classes are handled by the 'storage' engine in the 'filestorage' class.


0. Write a description of the project, description of the command interpreter:
how to start it
how to use it
examples

1. Be pycodestyle compliant!
Write beautiful code that passes the pycodestyle checks.

2. Unittests
All your files, classes, functions must be tested with unit tests.

3. BaseModel
Write a class BaseModel that defines all common attributes/methods for other classes.

4. Create BaseModel from dictionary
Re-create an instance with this dictionary representation(method to_dict()).

5. Store first object
convert the dictionary representation to a JSON string. JSON is a standard representation of a data structure. With this format, humans can read and all programming languages have a JSON reader and writer.

Write a class FileStorage that serializes instances to a JSON file and deserializes JSON file to instances.

6. Console 0.0.1
Write a program called console.py that contains the entry point of the command interpreter.

7. Console 0.1
Update your command interpreter (console.py) to have these commands.

8. First User
Write a class User that inherits from BaseModel.

9. More classes!
Write all those classes that inherit from BaseModel.

10. Console 1.0
Update FileStorage to manage correctly serialization and deserialization of all our new classes: Place, State, City, Amenity and Review

Update your command interpreter (console.py) to allow those actions: show, create, destroy, update and all with all classes created previously.

11. All instances by class name
Update your command interpreter (console.py) to retrieve all instances of a class by using: <class name>.all().

12. Count instances
Update your command interpreter (console.py) to retrieve the number of instances of a class: <class name>.count().

13. Show
Update your command interpreter (console.py) to retrieve an instance based on its ID: <class name>.show(<id>).

14. Destroy
Update your command interpreter (console.py) to destroy an instance based on his ID: <class name>.destroy(<id>).

15. Update
Update your command interpreter (console.py) to update an instance based on his ID: <class name>.update(<id>, <attribute name>, <attribute value>).

16. Update from dictionary
Update your command interpreter (console.py) to update an instance based on his ID with a dictionary: <class name>.update(<id>, <dictionary representation>).

17. Unittests for the Console!
Write all unittests for console.py, all features!
