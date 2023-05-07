Download Link: https://assignmentchef.com/product/solved-lab-3-2
<br>
Exercise 2

Modify the stack class to include appropriate error messages if invalid conditions occur—for example, trying to pop an item when the stack is empty.

Complete Exercise 13 at the end of Chapter 5 in our textbook: Write Java code that displays all of the objects in a stack (s) in the order in which they were pushed onto the stack. After all of the objects are displayed, s should have the same contents as when you started.

To implement the solution to this problem, use the stack of characters from the previous exercises (1 and 2).

Note: To better understand the problem, look at this situation. Suppose you are implementing a program that requires printing the items in a stack object. Suppose also that the stack class is in a library that you are importing. That is, you don’t have access to the stack class code, so you can’t write a print function inside of the class. In this scenario, you can only use the stack operations pop, push, and peek.

Exercise 5

Modify the class queue to include appropriate error messages if invalid conditions occur—for example, trying to dequeue an item when the queue is empty.

Exercise 6

Write a program to simulate the implementation of a printer interface application. The application should consist of a print server object and document objects to be printed. The print server object should contain a queue to store the documents to be printed (therefore, the item type stored in your queue class should be a document). Each document contains the name, length in bytes, time it was sent to the printer, and the owner. Test your classes by deciding the next action randomly: a document leaves the queue (job completed), a new document arrives to the queue, or simply do nothing (the state of the system remains the same, printing, or idle).