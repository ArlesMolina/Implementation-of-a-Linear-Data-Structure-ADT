Implementing a Linear Data Structure ADT in a Team
Overview
In this activity, I’m working on designing and implementing an Abstract Data Type (ADT) that represents a linear data structure. This ADT will support the typical CRUD operations (Create, Read, Update, Delete), and I’ll follow specific guidelines depending on the data structure chosen. Not all operations apply to every data structure, so I’ll tailor my implementation accordingly.

In this repository, you'll find the file list.h, which I’m responsible for modifying. I’ll be implementing the required functions in this file and ensuring that each function is well-documented, properly aligned, and passes all provided test cases.
Operations I’ll Implement
The core operations I need to implement for the ADT include:

insert_at (Create)
I will add an element at a specified index, and ensure elements are shifted correctly to accommodate the new entry.

get (Read)
This function will return the element located at the given index.

indexOf
I will return the index of the element being searched for, or return -1 if it’s not found.

remove_at (Delete)
This function will remove the element from the specified index and update the structure accordingly.

For each function, I’ll ensure that preconditions are met and handle exceptions for invalid inputs.

Testing
To test my implementation, I will use the make command to compile my code. This will generate test files in the format runTest#. To check if my implementation passes a specific test, I’ll execute the appropriate file. 
