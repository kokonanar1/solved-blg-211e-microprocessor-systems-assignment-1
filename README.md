Download Link: https://assignmentchef.com/product/solved-blg-211e-microprocessor-systems-assignment-1
<br>
<strong style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen-Sans, Ubuntu, Cantarell, 'Helvetica Neue', sans-serif;">QUESTION:</strong>

In this assignment, you are expected to implement two assembly programs calculating Fibonacci series. One program must be implemented with an iterative approach and the other must be implemented using a recursive approach. Both must be implemented with Arm Cortex M0+ assembly language. Pseudo codes and constraints for each approach are given below.

<ul>

 <li>Pseudo Code for Recursive Approach (50 Points):</li>

</ul>




Constraints:

<ul>

 <li>Index value must be assigned as a global value. (You must use EQU directives for declaration).</li>

 <li>The result of the fib(index) function must be returned in R1 register.</li>

 <li>You must use stack to pass parameters to fib(index) function, to store return addresses, and other register values as necessary.</li>

 <li>Your main function name or label must be “__main”.</li>

 <li>Fibonacci series should start at index 1 and an example series is given below: o fib(1)= 1, fib(2) = 1, fib(3)=2, fib(4)=3, fib(5)=5 ….</li>

 <li>Your code should include a comment for each line. Otherwise, points will be deducted.</li>

 <li>The file name for this program must be “recursive.s”</li>

 <li>Your assembly source file is expected to work with Keil µVision IDE v5.</li>

 <li>Default configuration must be sufficient to run your programs. If your program expects any different configuration parameter, please provide a ReadMe file.</li>

</ul>






















<ul>

 <li>Pseudo Code for Iterative Approach (50 Points)</li>

</ul>




Constraints:

<ul>

 <li>Index value must be assigned as a global value. (You must use EQU directives for declaration).</li>

 <li>The allocation of space for the array must use index value (We will only change index value to test your program). You must allocate neither less nor more space from memory. You must allocate enough space.</li>

 <li>Your program should not return any value. The Fibonacci numbers must be stored in the memory. (You must store fib(1), fib(2), …, fib(index) in the allocated array).</li>

 <li>At the beginning of your code, the start address of array must be stored in R0 register and the value of R0 register must remain unchanged for the rest of the program.</li>

 <li>You must use stack to pass parameters to fib(index) function, to store return addresses, and other register values as necessary.</li>

 <li>Your main function name (label) must be “__main”.</li>

 <li>Fibonacci series should start at index 1 and an example series is given below: o fib(1)= 1, fib(2) = 1, fib(3)=2, fib(4)=3, fib(5)=5 ….</li>

 <li>Your code should include a comment for each line. Otherwise, points will be deducted.</li>

 <li>The file name for this program must be “iterative.s”</li>

 <li>Your assembly source file is expected to work with Keil µVision IDE v5.</li>

 <li>Default configuration must be sufficient to run your programs. If your program expects any different configuration parameter, please provide a ReadMe file.</li>

</ul>




<strong>Submission</strong>: Please, compress your source files (recursive.s and iterative.s) and submit a single compressed file. Type your name and student ID at the top of each file as comments. You are expected to submit your homework through the Ninova system before the due date. Late submissions will not be accepted.

Any solution must be your own work. If any plagiarism is detected, disciplinary regulations of the university will be followed.

<strong>Note</strong>: If you have any question regarding the homework, you may contact to teaching assistant of the course ( <u><a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="2942484d405b074653454c4469405d5c074c4d5c075d5b">[email protected]</a></u> ). All questions and answers related to this homework will be shared in a Word file on ninova system. Please check this file regularly.

Q&amp;A Document URL: <a href="https://www.dropbox.com/s/z9xmfz93hxkl1b3/Homework1-Q%26A.docx?dl=0">https://www.dropbox.com/s/z9xmfz93hxkl1b3/Homework1</a><a href="https://www.dropbox.com/s/z9xmfz93hxkl1b3/Homework1-Q%26A.docx?dl=0">–</a><a href="https://www.dropbox.com/s/z9xmfz93hxkl1b3/Homework1-Q%26A.docx?dl=0">Q%26A.docx?dl=0</a>


