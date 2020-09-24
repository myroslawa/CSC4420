#CSC4420

## sub heading

Explaination of the code

- Define the  "process" variable used as entry in the process list table.
-Creating an array to store the processes
-Global pid to store the child process.
-Backgroud process array index
-An array to store the processes
-use fork to create a child, child executes command along with parameter then exits, parent shell waits for child to finish and go back to present the prompt again
-Signal handler function
-get the command and store it in args[]
-Get the index of in args in which > appears
-Get the index of in args

  1.in the int main
  -if caught signals ctrl_c
  -if caught signal ctrl_z
  -had first fork create child, closing stdout and replacing it with pipe and closing the pipe read
  -creating a second child and repeat
  
  more comments in the code itself

  
