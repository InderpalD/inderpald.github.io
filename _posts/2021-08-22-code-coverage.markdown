---
layout:	post

---
Code coverage is measured with respect to the individual lines of code.

Yes, each line.

There are syntax lines such as those that contain curly braces.

And there are logic lines and branch lines consisting of for loop declerations,
if statements, assignments, calculations, and so on...

Though the details may vary from tool to tool,
A simple formula for calculating code coverages is as follows:

code_coverage = non-syntax lines with tests / all non-syntax lines

If it is sincere in one's heart to truly understand.

One may ask, "Yes, but how can a tool ACTUALLY know if a line is being tested or not?"

You need not write an assert statement for each line of code.

Take the static analysis tool, Sonarqube. 

Sonarqube knows whether a line of code is tested or not,

based upon if that line was executed within a unit test.

Farewell. 



