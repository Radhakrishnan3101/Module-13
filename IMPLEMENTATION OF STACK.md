# Exp.No:31  
## IMPLEMENTATION OF STACK

---

### AIM  
To write a Python program to implement a stack using a list and its built-in methods (`append()`, `pop()`).

---

### ALGORITHM

1. **Start the program.**
2. **Define a class `st`** with the following methods:
   - `push(self, num)`: Adds the number `num` to the stack.
   - `pop(self)`: Removes and returns the top element from the stack.
3. **Create a stack object `s`** using the class `st`.
4. **Input the stack size**: Take an integer input `size` to define the size of the stack.
5. **Loop through numbers from 1 to size**: Add only the odd numbers to the stack using the `push()` method.
6. **Display the elements** in the stack after the loop completes.
7. **Call `pop()`** to remove the top element from the stack and display the popped element.
8. **Display the stack again** to show the remaining elements.
9. **End the program.**

---

### PROGRAM

stack = []

class st:

   def push(self,s):
   
   stack.append(s)
   
   return
   

 def pop(self):
    
   print("Element popped : ",stack.pop())
   
   return
    

 def peek(self):
 
 print("Elements in the stack\n",stack)
    
obj=st()

a=int(input())

for i in range(1,a):

 if i%2==0:
 
   stack.append(i)
        
obj.peek()

obj.pop()

obj.peek()
    
 OUTPUT:

 ![image](https://github.com/user-attachments/assets/b42d1eca-1600-46db-9ee8-4d1ed5c19b71)

RESULT:

Thus the python program was initiated and executed successfully.

