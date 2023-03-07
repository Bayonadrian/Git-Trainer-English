In this step I am going to teach you how to use gitHub, git and github look the same but they are not, git is a versioner, which is initially local, while github is a cloud repository, to create an account and create your first repository I recommend you start with it. In order to upload your local repository to github, use the format:

-git remote add origin <url>

Instead of <url>, use the url of the repository provided by github. Once this is done if you use the command:

-git remote

You receive origin as a response, which refers to your local repository, after this you can use the command:

-git remote -v

Which will return you:

-origin <url> (fetch)
-origin <url> (push)

Which means you can fetch information from github or push information to github. Another quite useful command and more used than "fetch" is the "pull" command, which is used as follows:

- git pull origin master

In case of returning a message saying "fatal: refusing to merge unrelated stories" (this indicates that there are two different types of information between the local repository and the github repository), use the command:

- git pull origin master --allow-unrelated-stories

To take information to the github repository I recommend using the command:

-git push origin master

Note: Master was placed in both push and pull because it works in these cases with the master branch, but in case of using other branches it is possible to put them there instead of master, such as having a branch called beta, this will be You can go up, using the command:

- git push origin beta

So with this you can use github in a basic way, for your personal projects.

Note: In this quick start I will not show you how to generate SSH keys but I recommend you to see that topic to improve the security of your project.