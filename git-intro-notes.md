![profile picture](https://masonchance.github.io/learning-journal-repo/Buisness Proffessional.jpeg)

# Git Overview

To understand what "Git" is you need to know a little about version control. Version control is a system that lets you look at multiple possible renderings of a file, like a text document for example, compare them and then compile the features of each that you want into your final draft; without losing your original file and it's contents. while there are several version control systems types, we will be looking at a Distrubuted Verson Control System or DVCS called Git. 

The short explaination of DVCS is that it allows multiple mirrored copies of a file to exist on multiple clients independently of the mother copy. The main benefit is that if the mother copy is damaged or lost in some way the data can be restored from any of the clones without a loss of integrity. 

## Git Cycle
  1. Clone original Repository (this is like a giant file cabinet for your files)
    - It is extremely important to clone **into the directory on your computer that you want it to exist in**
    - To check which directory you are in run command `pwd` in the terminal it will return your current directory path
    - To add a new directory run command `mkdir newdirectoryname` be sure not to use spaces, caps or periods
    - To go to the new directory run command `cd nameofdirectory` if you forget exactly how you named your directory run command `ls` before running `cd`
  1. Once created run `git status` this is a command you will use a lot
  1. You can run the command for opening your text editor, in my case for VisualCode: `code .`
    - after making any significant changes you will want to go through Gitflow ACP shown below




## GitFlow ACP: (*add, commit, push*) Terminal Commands

  - `$ git status`
    - `$ git add *(insert file name here)*
  - `$ git status`
    - `$ git commit -m "*insert message inside quotes*"
  - `$ git status`
    - `$ git push origin master`
  - `$ git status`
  
## Impotant Terminology

  - *Tracked:* indicates that a file has been added sometimes noted in the WD as [master !]
  - *Modified:* indicates that the file has been added and staged but has not been commited, sometimes indicated in the WD as [*branch name* `*`]
  - *Working Directory Clean* indicates that all files in the WD have a tracked or modified status. 
  
  

### [Repo Index](https://masonchance.github.io/learning-journal-repo/) (*click to return to README.md)

##### Day 01

- [Mindset](https://masonchance.github.io/learning-journal-repo/main-page)
- [Markdown Notes](https://masonchance.github.io/learning-journal-repo/markdown-notes/)
- [Coders Computer Notes](https://masonchance.github.io/learning-journal-repo/the-coders-computer-notes/)

##### Day 02
 - [Git Intro Notes](https://masonchance.github.io/learning-journal-repo/git-intro-notes/)
 - [Html webstructure notes](https://masonchance.github.io/learning-journal-repo/Html-webstructure-notes/)
 - New project Repo ([Twitch-Coaches](https://masonchance.github.io/twitch-coaches/))

##### Day 03
- [CSS Notes](https://masonchance.github.io/learning-journal-repo/css-notes/)
-
-

I've included a reference to GitHub documentation and Support for ease of access

[documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact)