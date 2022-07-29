## Git Workshop for the Baker lab on 29/07/2022

This is the Github repository for the git workshop at the Baker lab on the 29th of July 2022. This repository serves is used for the development of a very simple programming task, to practice all necessary git skills. Below you will find basic instructions for the course.

#### Setup for the course

1. Make sure git is installed on your machine. If not installed you can download it here: <https://git-scm.com/downloads> - download it, follow the instructions and afterwards verify that git is installed on your computer by typing the following in the terminal: ```git --version```
2. Configure name and e-mail: 
```git config --global user.name "Your Name"```
```git config --global user.email "your@email.com"```

4. Make a github account so you can be added to the project: <https://github.com/>
5. (Optional) Download a git GUI - I recommend Smartgit or GitKraken, but there a ton of different tools available
6. Clone the git repository to a directory of your choice (use a directory of your choice that you will only use for this project): ```cd directory/of/your/choice``` ``` git clone https://github.com/VHolstein/git_session_bakerlab```

#### Basic git commands

+ Check repo status: ```git status```
+ Track new file: ```git add filename.file```
+ Stage a file: ```git add filename.file```
+ View commit history: ```git log```
+ Clone repository: ```git clone host@repository```
+ Push to remote ```git push <remote> <branch>```
+ Pull from remote ```git pull <remote> <branch>```
+ Checkout remote branch ```git checkout testing```
