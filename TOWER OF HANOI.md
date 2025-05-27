Exp.No:31
IMPLEMENTATION OF STACK
AIM:

To write a Python program to implement a stack using a list and its built-in methods (append(), pop()).

ALGORITHM:

Start the program.

Define a class st with the following methods:

push(self, num): Adds the number num to the stack.

pop(self): Removes and returns the top element from the stack.

Create a stack object s using the class st.

Input the stack size: Take an integer input size to define the size of the stack.

Loop through numbers from 1 to size: Add only the odd numbers to the stack using the push() method.

Display the elements in the stack after the loop completes.

Call pop() to remove the top element from the stack and display the popped element.

Display the stack again to show the remaining elements.

End the program.

PROGRAM
```
stack = []
for i in range(5):
    a=input()
    stack.append(a)

print('Stack before elements are popped')
print(stack)

for i in range(2):
    stack.pop()


print('\nStack after elements are popped:')
print(stack)

```
OUTPUT
![image](https://github.com/user-attachments/assets/35203373-578c-4dc9-8790-f5fd341e5c59)


RESULT:

Thus the python program was initiated and executed successfully.
