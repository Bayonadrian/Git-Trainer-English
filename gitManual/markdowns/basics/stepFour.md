In this step I will teach you how to return to the past, this is done through the command:

- <code>git reset --hard </code>
- <code>git reset --soft </code>

This command uses the commit code that the "git log" command gives you instead of "code" and also uses an option which can be "hard" or "soft", hard is much more aggressive and also removes the changes that They may be inside "add", so I recommend you use it only in the case of wanting to go back to the past, since this command will also eliminate all the commits made.

Another command to use to be able to see past commits is the command:

- <code> git checkout </code>

Where the "git log" code is used instead of the other options, thus this command shows how the project was in that "commit", you have to be very careful because if at that moment a " commit" the new changes would be lost, finally if you want to go back to how everything was before the "checkout" use the command:

-git checkout master

In this way you can "return to the present".

-> Continue at /stepFive(branch, checkout, merge)