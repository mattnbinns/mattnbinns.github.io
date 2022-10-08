# Introduction to Git/Github

[Back to home](../README.md)

## What is Git?

Git is a version control system that allows multiple developers to be operating on the same code simultaneously. Git allows you to store your changes made to your code by creating snapshots and storing a reference to that code. This solves the annoyingness of having to use the “save as” method to maintain the original copy of your file but still have the new changes made to that same file.

## What is Committing a Change?

This entire process is done by committing changes which is fancy way of saying “save as”. Every time you commit a change to your code, Git takes a quick snapshot of that code and assigns a snapshot reference to that code.  The most recent snapshot, will **ALWAYS** be given the label “Head”.  Git allows you to assign messages or captions to your snapshots for better reference. This is a practice, that is highly recommended in the industry.

## What is Github?

Now that you know what Git is, what is Github and why do developers use it?Github is a website that developers can use to store their code in a cloud allowing other to access your code and allowing developers to back-up their code.

### What Is A Repository?

A repository serves the same functions as a folder and directory **BUT** the difference is that it is now be tracked by Git.

You can transfer your repository over to your computer by copying the HTML link from your repository and use the command **git clone** followed by the URL link you just copied and paste it in the your terminal.

**Key Note:** To verify or see the GitHub URL of the repository use the command **git remote -v** and hit enter.

## The Process of ACP

ACP, which is acronym for **add, commit, and push**, is the process of taking the changes you made to your repository, confirming those changes by telling Git that you want to track those changes, and then sending those changes off to GitHub, the cloud.

**Key Note:** Using the command **git status** will let you know whether or not you have made changes to your file.

### Add

This is entire process is done by first using the command: **git status**. The text displayed in red represents the files that have recently been modified.

There are two ways you can go about telling Git to track your recent changes. The two commands are:

* ( **Git add .** ) - This command is a shorthand that allows you to confirm and allow Git to track the changes for **ALL** files highlighted in red.

* ( **Git add (file name)** ) - This command gets the same job done, the only difference is that it will add each file name individually.

You can verify that your changes are being tracked by Git by using the command: **git status** once again. You will know Git is tracking, if the output highlights the files in green.

### Commit

This part of the process is where you commit your changes. To do this you will use the command: **git commit -m**. This allows you to commit your changes and add a message to your snapshot for reference.  

**Key Note:** Make sure your message in surrounded by quotation marks ("").

### Push

Once you're done commiting your changes, there still leaves one issue. You will notice a displayed message stating: **“Your branch is ahead of 'origin/main' by 1 commit.”** What this means is that your version copy stored on your computer no longer matches what is on GitHub, it is ahead by one. In order to correct this and make Github up to date with your computer you must now push your version up to Github. To do this you must use the command: **git push origin main**.

[Back to home](../README.md)
