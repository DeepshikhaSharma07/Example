# Example
GIt tutorial
Goal: Review 2 basic git flows to follow - using linux commands
Prerequisite:
If you are using a pc - have gitbash installed
You should have git installed on your computer as well
Agenda:
Putting Git into context
Setting up for the exercise
Initializing a git within a local repository and connecting it to a remote repository 
Update an existing repository
Trials and errors I’ve learned when working with git in the workplace 
Resource to learn git more in depth:
Git commands:
https://www.atlassian.com/git/tutorials/atlassian-git-cheatsheet
https://phoenixnap.com/kb/git-commands-cheat-sheet
https://www.freecodecamp.org/news/git-cheat-sheet/
Learn by doing:
https://try.github.io/
Learn by reading:
https://try.github.io/
https://git-scm.com/docs/gittutorial
Gitlab: https://docs.gitlab.com/ee/gitlab-basics/start-using-git.html
Learn by watching:
https://www.youtube.com/watch?v=SWYqp7iY_Tc
https://www.youtube.com/watch?v=HVsySz-h9r4
https://www.youtube.com/watch?v=8JJ101D3knE
Linux command cheat sheet: https://cheatography.com/davechild/cheat-sheets/linux-command-line/
Bash cheat sheet: https://www.educative.io/blog/bash-shell-command-cheat-sheet
Outline:
What is GIT and why is it important?
A visual of a local repository and remote repository 
An example of using git in the work place
Set up for today’s exercise
Git recipe #1 - creating a new local and remote repository
mkdir {directory name}
cd into directory in terminal
Open up GitHub and create a new repository 
Go back to your terminal and go into your new folder add in the first set of commands - now you are connected and created a readme file!
Refresh GitHub to see your remote repo updates
git status
Add a word to your README file to simulate making a change locally
git status
git add .  -or- git add {file name}
git status
git commit -m “Present tense message to explain what you did”
git status
git push
Now check your repo within GitHub
Git recipe #2 - Updating a remote repository 
git pull to see if there are any new changes to your branch - very helpful when sharing a branch 
Add another word to your file
git status
git add .  -or-  git add {file name}
git commit -m “Present tense description”
git push 
Trials and errors I’ve learned when working with git in the workplace 
Key takeaways: Practice working collaboratively now and communicate as much as possible
Extra practice:
Buddy up with someone from class and share your GitHub repo links
Clone/download their repo on your local repository 
Make a change and push it up - let them know when you push yup a change
Then on their end - git pull to get the latest changes and add a change
Go back and forth and communicate as you do it to get a feel for working collaboratively
Even more extra practice ideas:
Make a new branch on their code and work on that branch. 
Then when you are ready, practice making a pull request to the main owner of the remote repo to simulate what it’s like to work on a team using the same main code base
Some helpful git commands for the extra practice:
git branch
git checkout {branch name}
git checkout -b feature/{new branch name}