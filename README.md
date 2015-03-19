CS 680 - Formal Methods
Kyle Patron
Matt Ping
Project 1

Files
=====
bank.smv 			- The NuSMV source for our banking model
CS680-Project2.pptx - PowerPoint presentation showing what we did and what we learned
result.out 			- A file showing various output from the NuSMV model

How to run the code
===================
Run NuSMV with the "-int" parameter and the path to the file as shown below: 

./NuSMV -int <path to bank.smv>

Once the console appears run the following commands in this order:

go
pick_state
simulate

This will build the model and simulate it.  In order to see a trace of the simulation run the "show_traces" command.