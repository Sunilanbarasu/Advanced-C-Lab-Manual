# Advanced-C-Lab-Manual

EXP NO:11 C PROGRAM TO DISPLAY STACK ELEMENTS USING AN ARRAY.

Aim: To write a C program to display stack elements using an array. Algorithm:

Include Necessary Header Files
Declare Global Variables
Define the Display Function
Main Function (or Other Relevant Code)
Initialize the stack and top as needed.
Perform stack operations (push, pop, etc.).
Use the display function to visualize the stack's contents
Program:
```
float stack[100];
int top=-1;
void display()
{
 for(int i=top;i>=0;i--)
 {
 printf("%.1f ",stack[i]);
 }
} 

```


Output:

![image](https://github.com/user-attachments/assets/b4e05e21-2717-41f9-af36-32cf636c8c28)


Result: Thus, the program to display stack elements using an array is verified successfully.

EXP NO:12 PROGRAM TO PUSH THE GIVEN ELEMENT IN TO A STACK USING ARRAY. Aim: To create a C program to push the given element in to a stack using array. Algorithm:

Declare global variables for the stack size, top index, and the stack itself.
Define the push function to add a floating-point number to the stack.
Initialize the stack size, top index, and the stack itself.
Call the push function as needed.
Program:

```
char stack[100];
int size=3,top=-1,i;
void push (char data)
{
 if(top==size-1)
 {
 printf("stack is full\n");
 }
 else
 {
 top=top+1;
 stack[top]=data;
 }
}
```

Output:
![image](https://github.com/user-attachments/assets/12e5e4d8-c0b3-4d20-9857-d67078ac05d0)


Result: Thus, the program to push the given element in to a stack using array is verified successfully

EXP NO:13 C PROGRAM TO DISPLAY QUEUE ELEMENTS USING ARRAY. Aim: To write a C program to display queue elements using array

Algorithm:

Declare global variables for the queue, rear, front, and iteration.
Define the display function to print the elements of the queue.
Initialize the queue, rear, and front as needed.
Call the display function and perform other queue operations as needed.
Program:
```
int queue[50], rear=-1, front=-1;
void display()
{
 if(rear==-1 && front==-1)
 {
 printf("No elements to display");
 }
 else
 {
 for(int i=front;i<=rear;i++)
 {
 printf("%d\n",queue[i]);
 }
 }
}
```

Output:

![image](https://github.com/user-attachments/assets/71ddfc21-9605-4c66-ac6c-3171d5ef9ded)


Result: Thus, the program to display queue elements using array is verified successfully.

EXP NO:14 C PROGRAM TO INSERT ELEMENTS IN QUEUE USING ARRAY. Aim: To write a C program to insert elements in queue using array.

Algorithm:

Declare global variables for the size, rear, front, and the queue itself.
Define the enqueue function to add a float to the queue.
Initialize the rear, front, and size of the queue as needed.
Call the enqueue function as needed.
Program:
```
int rear,front;
int queue[50];
void enqueue(int data)
{
 if(rear==-1 && front==-1)
 {
 rear+=1;
 front=0;
 }
 else
 {
 rear+=1;
 }
 queue[rear]=data;
} 
```


Output:
![image](https://github.com/user-attachments/assets/822dd275-04b4-47bc-8ad7-ff56d8c124a5)


Result: Thus, the program to insert elements in queue using array is verified successfully.

EXP NO:15 C FUNCTION TO DELETE ELEMENTS IN QUEUE USING ARRAY

Aim:

To create a function in C that deletes an element from a queue implemented using an array.

Algorithm:

Check if the Queue is Empty o If the front pointer is -1, it means the queue is empty, and there are no elements to delete. Print a message indicating that the queue is empty.
Delete the Front Element o If the queue is not empty, the element at the front index is deleted. o Increment the front pointer by 1 to remove the element and point to the next element in the queue.
Check if the Queue Becomes Empty After Deletion: o After deletion, check if the front pointer has passed the rear pointer (front > rear). If this is true, reset both front and rear to -1, indicating that the queue is now empty.
End the Function.
Program:

```
int front, rear;
void dequeue()
{
 front=front+1;
}
```

Output:
![image](https://github.com/user-attachments/assets/5161f7e1-aa2d-46f7-94fe-10c2dac8f3ab)


Result: Thus, the function that deletes an element from a queue implemented using an array is verified successfully.

