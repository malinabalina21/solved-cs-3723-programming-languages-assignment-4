Download Link: https://assignmentchef.com/product/solved-cs-3723-programming-languages-assignment-4
<br>



– Call by value, call by reference, call by name, etc.

You have been given 7 C files, each has the same logic, expressed in different ways. Each of the 7 is incomplete, marked by TBD. You must replace each TBD entry with appropriate C code. You must NOT alter any of the existing lines. You are only allowed to replace each TBD line with one or two new lines.




Each of the 7 C programs do exactly the same task. Given a list of numbers on the command line, they find the smallest positive number and the largest negative number. You do not have to add error checking. You can safely assume (1) all numbers are given nicely as integers on the command line, (2) both positive and negative numbers will always be present, and (3) all numbers will be in the range of -1,000 to +1,000.




The output from all 7 will be the same for the same arguments. For example, the smallest positive number in the list (34 82 -4 -22 13 -83 0 3) is 3, and the largest negative number is -4.




The ‘doit.sh’ script is available to use if you choose. It runs on Linux and will compile and run each of the 7 C programs for you. The script is optional and does not need to be submitted.




<h2>Part I: Implementation (5 points each, 35 points).</h2>

Get each of the 7 C files to compile and produce the results as given above. Submit your code (and output) in Blackboard. Please submit a single zip file, called Lastname_abc123.zip, with 7 C files and a transcript called mmm.out which shows the output from all 7 executables.

Part II: Discussion (5 points each, 25 points).

<ul>

 <li>Which version(s) are unsafe when multi-threaded? mmm2, mmm3, mmm5 Why? They have global variables and are not efficient for multithreading.</li>

 <li>Which version is the hardest to read and maintain? mmm5</li>

</ul>

Why? That one uses malloc and can be tricky.

<ul>

 <li>Which version has the most redundant code? mmm1</li>

</ul>

Why? Two for loops for no specific reason

<ul>

 <li>Which version(s) are closest to call-by-name? mmm7</li>

</ul>

Why? These meet the requirements

<ul>

 <li>Which version(s) are closest to call-by-reference? mmm4, mmm6</li>

</ul>

Why? They’re passing the address of variables as arguments

<h2></h2>

<h2>Bonus: Implement in Python (5 points).</h2>

You must calculate the smallest positive and largest negative numbers. You only need to implement one version, and submit one mmm.py file. A partial solution has been provided for you. As above, you can only replace TBD lines.