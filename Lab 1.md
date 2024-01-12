# CSE 15L - Lab 1
Example 1: cd, no argument

![Image](Screen Shot 2024-01-11 at 3.15.42 PM.png)

I ran the cd command with no argument out of the home directory. Nothing appeared to change, because running cd with no command returns the implementer to the home directory (which I was already in). The directory stayed the same, and there was no output in the terminal. There was no error message produced by this, but this could be considered an invalid argument error as cd requires a directory argument to function as intended.


Example 2: cd, directory argument

![Image](Screen Shot 2024-01-11 at 3.16.09 PM.png)

I ran the cd command with a lecture1 directory argument. The working directory (home) changed to the directory I chose (lecture 1). This occurred because the cd command functions to change the directory. There was no error produced by this.


Example 3: cd, file argument

![Image](Screen Shot 2024-01-12 at 10.35.46 AM.png)

I ran the cd command out of the lecture1 directory with a file argument. I received a message in the terminal stating that the argument is "Not a directory". The working directory was not changed. This could be considered an invalid argument error as the command is specific to directory arguments and will not work with a file argument.


Example 4: ls, no argument

![Image](Screen Shot 2024-01-11 at 3.21.47 PM.png)

I ran the ls command out of home directory with no argument. The terminal listed the directories within the home directory (in this case, the only directory was lecture1, and that was all that was listed. This occurred because the ls command functions to list files and directories. There was no error. 


Example 5: ls, directory argument

![Image](Screen Shot 2024-01-11 at 3.22.11 PM.png)

I ran the ls command with a lecture1 directory argument. The terminal listed the files and directories within the lecture1 directory. This occurred because ls command was assigned to the lecture1 directory and functions to list files and directories within the assigned directory. There was no error.


Example 6: ls, file argument

![Image](Screen Shot 2024-01-11 at 3.23.45 PM.png)

I ran the ls command out of the messages directory (within the lecture 1 directory) with a file argument. The terminal simply repeated the command argument, but nothing else happened. This occurred because there are no files or directories within the file. This could be considered an invalid argument error.


Example 7: cat, no argument

![Image](Screen Shot 2024-01-11 at 3.25.16 PM.png)

I ran the cat command out of the home directory with no argument. The terminal refused to acknowledge the command and only allowed me to continue writing other input. There was no output whatsoever. This occurred because cat functions to either concatenate files together or print the contents of a single file, and there was no file argument in this case. This could be considered an invalid argument error, but  there was no actual error message. 


Example 8: cat, directory argument

![Image](Screen Shot 2024-01-11 at 3.28.42 PM.png)

I ran the cat command with the lecture1 directory argument. The terminal produced a message stating that lecture1 "Is a directory". Similar to the no argument case, this occurred because cat functions to either concatenate files together or print the contents of a single file, and there was no file argument in this case. This could be considered an invalid argument error.


Example 9: cat, file argument

![Image](Screen Shot 2024-01-12 at 12.42.11 PM.png)

I ran the cat command from the messages directory (within the lecture1 directory) with a file argument. The terminal printed the contents of the file. This occurred because cat can function to print the contents of a single file. There was no error produced.



Interestingly, none of this cases produced any messages referring to these actions as "errors". Obviously, these commands have been made to handle all of these exceptions to their ideal functions. I chose to refer to all cases that did not match the explicit intention of tehse commands as "errors". 

