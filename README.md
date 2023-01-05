# Welcome to My Cat
***

## Task
i am to create a my_cat program which does  the same thing as the systems cat command used in command line
and the program is to read the contents of each file recieved as an argument

## Description
first i started by creating a main function which has two parameters argc and argv, argc is the number of argument while argv is the argument value, like an array of pointers to the argument string
the function begins by checking the value of argc if it is 0 an error message is printed to the standard error out put and it exits with a non-zero exit code.
if argc is 1 the program enters a loop and read one character at a time from the standard input to the standard output until the end of the input is reached.
if argc is greater than 1 the program enters a loop that iterates over the arguments starting with the second argument since the first argument is the name of the file it self. 
for each argument the program attempts to open the file with the given name and read its contents  one characterat a time writing each character to the standard output as it reads.
if the file can not be oped or there is an error the program prints an error messageand exits the program with a non-zero exit code.
once all of the program has been processed the main function returns 0 to indicate a succesfull completeion 
## Installation
this program does not need any Installation
## Usage
this program does not need any Usage


### The Core Team


<span><i>Made at <a href='https://qwasar.io'>Qwasar SV -- Software Engineering School</a></i></span>
<span><img alt='Qwasar SV -- Software Engineering School's Logo' src='https://storage.googleapis.com/qwasar-public/qwasar-logo_50x50.png' width='20px'></span>
