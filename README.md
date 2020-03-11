# findDep
A brute force method of finding all the deprecated and removed functions in PHP scripts
This requires grep and will search ONE TERM at a time a directory recursively.  It will tell you what its looking for, and then put the results (either nothing or what it found) in a file called deprecated.txt.  

Finally it will run cat deprecated.txt |more at the end so you can look through it and ensure it ran.  Just ^c out of it or comment out the last line if this annoys you.

Enjoy
