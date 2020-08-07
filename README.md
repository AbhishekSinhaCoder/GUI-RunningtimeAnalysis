## Stack-and-LinkedList-GUI-using-JavaFX
This framework will animate your algorithm so that you can watch your code work. If you want to accelerate or slow down the animation, modify the argument of Pause.wait in the handle method of the ArrayAnimationTimer inner class.
***
To test the code, compile RunningTimeController.java and run the RunningTimePracticeAppllication. When the program begins, you will see a text box. Enter the number of elements for the array, and press the “Show array” button to populate the array. Then press the “Selection Sort” button to execute your selection sort code. Because the values of the array are randomly generated, the values will be different each time the program runs.
Troubleshouting
If the animation is incorrect, and you think your method does return the current value for the counter, verify that you correctly incremented the counter inside the inner loop.
In order to derive a closed-end expression for the number of statement executions as a function of the size of the array, follow these tips:
- If n is the size of the array, compare n, n2, n3, n4, …, 2n, to the value of the counter.
- When doing the preceding, divide n, n2, n3, n4, …, 2n by the number of statements executed.
