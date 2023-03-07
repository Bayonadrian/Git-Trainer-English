Once you have the repository initialized, use the command:

-git status

This command will return the status of the repository.

Then you can use the command:

-git add <file>

In order to add documents to your repository, in the place of <file> you must put the name of the document you want to add or in case you want to add all the documents in the folder, you can use a ., as follows:

-git add .

At this point you can use the command again:

-git status

This will tell you the status of the process, now you must not forget to comment on this change in order to make it effective, with the command:

-git commit -m <commend>

Instead of <commend> you should register a comment, never send a commit without a comment. Once again you can see the status:

-git status

If changes were saved, it will give you a result like this:

- "nothing to commit, working tree clean"

So far you have already learned how to save documents in a git repository.

-> Continue in /stepTree(show, log, diff)