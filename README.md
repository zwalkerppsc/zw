----------

This repo is now my testing environment for my personal portfolio on GitHub. 

First project being the creation of a Bash script that prints the numbers 1-50 in sequence.

Utilizing a Bash 'for' loop and a variable reference to print the numbers 1 to 50 once per line. 

----------

#!/bin/bash
# Counter.sh - Prints numbers from 1 to 50.

for i in {1..50}; do
  echo $i
done

----------

#!/bin/bash               <-            Shebang line. Tells the OS to use the Bash shell interpreter to run this script. 
# Counter.sh - Prints numbers from 1 to 50. <- Commented out using #, meaning it is not executed. It's just the filename and description.

for i in {1..50}; do      <- 'for'      Starts the loop that repeats a block of code
                              'i'       The loop control variable that takes on the value of each number 'in' the set 
                           '{1..50}'    Uses a Brace Expansion which generates a list from the first value (1) to the second value (50)
                              'do'      Begins the body of the loop, runs once per iteration 
                         
  echo $i                 <- 'echo'     Prints text to the terminal
                              '$i'      Retrieve the current value of the loop variable  
                              
done                      <- 'done'     Closes the loop block that began with 'do'

----------

