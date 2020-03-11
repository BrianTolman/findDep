# findDep
A brute force method of finding all the deprecated and removed functions in PHP scripts
This requires grep and will search ONE TERM at a time a directory recursively.  It will tell you what its looking for, and then put the results (either nothing or what it found) in a file called deprecated.txt.  

Finally it will run cat deprecated.txt |more at the end so you can look through it and ensure it ran.  Just ^c out of it or comment out the last line if this annoys you.

If you want to use it, just open the file, copy, paste and run.

If you want to add or improve it, fork it.  If you find removed or deprecated functions not found, just send me the function.

No warrenty is expressed or implied.  Use at your own risk.  

Enjoy
