In this step I will show you how you can analyze the changes in your git projects.
First you can use the command:

-git show

This command will show you the changes made in the last commit. Later you can use the command:

-git log

This command will show you the commits made. Using the command:

-git diff <first code> <second code>

Using the "log" command returns a list of commits, which has a code, using the "diff" command one can contrast the changes of two different commits, using the code inside "log", it is recommended to use the code of the oldest commit within <first code> and the commit you want to check against within <second code>.

Note: These are only independent commands, it is not necessary that you use one after the other, if there is an order here it is for example, nothing more.

-> Continue at /stepFour(reset, checkout)