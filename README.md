Download Link: https://assignmentchef.com/product/solved-cse-231-programming-project-1
<br>
<h2>Assignment Overview</h2>

This assignment involves coding and testing of a program that uses Python arithmetic.

<a href="https://www.ankitcodinghub.com/product/cse-231-programming-project-1-solved-2/">View Product</a>

The basic design of your first program that in this class prompts for input, performs arithmetic on that information and then displays the results.

<h2>Background</h2>

This programming project will use the input and print functions along with some simple mathematics for conversion.  The important part of the project is to learn the skills needed to access the class web site to download a project description, create a new program in Python and finally to hand it in.













<strong> </strong>

<h2>Program Specifications</h2>

Conversions are useful both in science and daily life.  Here we examine some obscure, but useful conversions as well as some silly ones.































If you canoe in the <a href="https://en.wikipedia.org/wiki/Boundary_Waters_Canoe_Area_Wilderness">Boundary Waters Canoe Area</a> (BWCA) you portage (carry) your canoe and gear between lakes as you wander deeper into the wilderness (top image is of Dr. Enbody canoeing; middle image is daughter portaging gear; left is Dr. Enbody portaging a canoe).  BWCA maps label distances on portages in <a href="https://en.wikipedia.org/wiki/Rod_(unit)">rods</a><a href="https://en.wikipedia.org/wiki/Rod_(unit)">,</a> an old unit of measurement that is 5.0292 meters, which is approximately the length of a canoe so it is a useful measurement in the wilderness.







Here is a piece of a BWCA map showing portages between lakes (black lines) with the length of the portage labeled in <strong>rods.</strong> (Red triangles are campsites.)










Your program will prompt the user for a floating-point value representing a distance in rods. You will reprint that value along with that value converted to the following values. The most important value for planning a trip is the time to walk the portage.

<ul>

 <li>meters</li>

 <li>feet</li>

 <li>miles</li>

 <li><a href="https://en.wikipedia.org/wiki/Furlong">furlongs</a></li>

 <li>the time in minutes to walk that distance</li>

</ul>




You can find these measures on the web, but so everyone is using the same conversions we require that you use these so testing will yield the same results:

<ul>

 <li>1 rod = 5.0292 meters</li>

 <li>1 furlong = 40 rods</li>

 <li>1 mile = 1609.34 meters</li>

 <li>1 foot = 0.3048 meters</li>

 <li>average walking speed is 3.1 miles per hour</li>

</ul>




<strong> </strong>

<h2>Deliverables</h2>

The deliverable for this assignment is the following file:




proj01.py — your source code solution




Be sure to use the specified file name and to submit it for grading via Mimir before the project deadline




<strong>Assignment Notes: </strong>

<ol>

 <li>To clarify the project specifications, sample output is appended to the end of this document.</li>

 <li>To receive credit your program must take in input, do some simple arithmetic based on that input, and then print results.</li>

 <li>Round all floating-point output to three places, i.e. use round( x, 3 ). Important: do not round intermediate results because rounding differences will compound resulting in a wrong result. Round values only when you print them.</li>

 <li>Testing on Mimir does exact matching of output so we provide a file txt of strings for you to copy to make it easier to get the matching correct.</li>

 <li>Items 1-6 of the <a href="https://www.cse.msu.edu/%7Ecse231/Online/General/coding.standard.html">Coding Standard</a> will be enforced for this project.</li>

 <li>The input function is used to accept a response from the user. The function accepts a string (a sequence of characters between quotes) as a prompt to display to the user.  It then waits until the user types a response (terminated by the user touching the Enter key).  Finally, the function returns the user’s response as a string.</li>

</ol>




If the user’s response is supposed to be processed as a numeric value, the returned string must be converted into a number.  When working with floating point values, a string is converted into a floating point number using the float function.  The function accepts a string as its argument and returns the floating point number which the string represents.  A typical interaction would be something like:




num_str = input( “Please enter a number: ” ) num_float = float( num_str )




<ol start="7">

 <li>The print function is used to display any combination of variables, values and strings in the output window. Each item to be displayed must be separated from another item by a comma.  All the items will be displayed together, followed by a new line.  For example:</li>

</ol>




print( num_int, ” times two is “, num_int*2 )

Three items will be displayed when the print function is called:  the value of the variable num_int, the string ” times two is “, and the result of the calculation.




Assuming that the value of the variable num_int is 26, then the output will be:




26 times two is 52




<ol start="8">

 <li>The file named py in the project directory contains a program which illustrates the use of some standard library functions.</li>

</ol>







<h2>Getting Started</h2>

<ul>

 <li><em>Solve the problem using pencil and paper first.</em> You cannot write a program until you have figured out how to solve the problem.  This first step can be done collaboratively with another student.  However, once the discussion turns to Python specifics and the subsequent writing of Python, you must work on your own.</li>

</ul>




<ul>

 <li>Use Anaconda Spyder to create a new program. Use the required file name (py).</li>

</ul>




<ul>

 <li>Write a simple version of the program, e.g. input the rods and print rods. Run the program and track down any errors.</li>

</ul>




<ul>

 <li>Use the <strong>Mimir</strong> system to turn in the first version of your program.</li>

</ul>




<ul>

 <li>Cycle through the steps to incrementally develop your program:</li>

</ul>




<ul>

 <li>Edit your program to add new capabilities.</li>

 <li>Run the program and fix any errors.</li>

</ul>




<ul>

 <li>Use the <strong>Mimir </strong>system to submit your final version.</li>

</ul>







<h2>Sample Interaction Test 1</h2>







Input rods: 1

You input 1.0 rods.




Conversions

Meters: 5.029

Feet: 16.5

Miles: 0.003

Furlongs: 0.025

Minutes to walk 1.0 rods: 0.06




<h2>Test 2</h2>




Input rods: 10

You input 10.0 rods.




Conversions

Meters: 50.292

Feet: 165.0

Miles: 0.031

Furlongs: 0.25

Minutes to walk 10.0 rods: 0.605




<h2>Test 3</h2>




Input rods: 444.44 You input 444.44 rods.




Conversions

Meters: 2235.178

Feet: 7333.26

Miles: 1.389

Furlongs: 11.111

Minutes to walk 444.44 rods: 26.882







Scoring Rubric




If you correctly run the three sample tests, you will automatically get 12 of the 15 points.  Here is the scoring rubric for this assignment.




Computer Project #1 Scoring Summary







General Requirements




__0__   (3 pts)  Coding standard




Source code format

Source code header and descriptive comments

Mnemonic identifiers (variables and symbolic

constants)




Program Implementation




__0__   (3 pts) Test case 1




__0__   (4 pts) Test case 2




__0__   (5 pts) Test case 3







Note that if you simply “hard code” the results you will earn zero points for the project, e.g. if your code simply prints values without any calculations, you are not really doing the assignment.