# How to work, edit and push using Git/RStudio

## Steps for push
1) Make sure you have linked Git with RStudio
2) Go to someone's directory and press up right the 'Fork' option. Now you have your own version of this repository and up left will be like: yourusername/repositoryname
3) Then you go to a local directory that you want to store the Github directory, right click and select Git Bash. When Git Bash opens type 'git clone url' (the url of your yourusername/repositoryname). With this it will clone the depository in the local directory you chose.
4) After that we must open our editor to start editing which in this case is RStudio. After we open we create a new project on Existing Directory and we find the directory we stored our clone.
5) For instance, we can now open a 'README' file and start making changes in the Markdown.
6) When finishing our changes we can save this file and then go to Git Bash and type 'cd' space and 'local directory url' so we make it master directory
7) Then we go to RStudio up right we click on the 'Git' option where we can see all the files that exist in our local directory
8) We pick the README file and we press 'Commit'
9) A new window pops up and we right a comment (e.g. added changes in REAMME), we press commit and then we press the green 'Push' option to push the changes to our Github directory.
10) When we open with the web browser our Github directory the changes have been made!
11) If you want to make a push request to the main directory you cloned then just choose 'Pull request', 'New pull request'... 

## Return to previous file version
1) Go to 'Diff' button and then 'History'.
2) You can see all your commits there, you select the commit you want and then you copy the SHA.
3) Then you go to 'Tools', 'Terminal', 'New terminal' and you get a new terminal window.
4) Type in the Terminal 'git reset --hard SHA' and press Enter
5) Now the file is back to each previous version.



