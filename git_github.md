# Git_github
now I'm going to show the git commands


## Git comands
When you want see your steps, check that with the next command
`history`

the next command is for inicialitate the program of git
`git init`

![enter image description here](https://cdn.appuals.com/wp-content/uploads/2020/06/intro.jpg.webp)

***"Git bash is a language of programming"***

When you want upload that in the "cloud" put the next thing:
`git add (file1) (file2) (file n)`

If you want to see the current status of the place where you are working, with this command you can see the general status of your files as if they are ready to go to the cloud, or something is missing, etc.
`git status`

it is like make a storage, if you are not logged in, you will have to put your credentials there 
`git commit` `git config --global user.email "your email`
`git config --global user.name "your name`
An important point is that you should to put your cretentials from github.com
when you put `git commit` it will put a screen, for to force the close you should to put `:q!` and wit that it closes down

for create a new commit, put
`git commit -m "name.of.your.commit`

And when you put `git status`, it will say taht is nothing to commit

when you want go in the main part, put:
`git branch -M main`

![enter image description here](https://i.pinimg.com/originals/b4/39/88/b43988ced263be464765cac80ce0880c.png)

***Currently there are a lot of people who do this things, also It could be illegal if you don't use with responsability***



for stablish a conection from another web you need put
`git remote add origin "https://url.com/git"`

`file.py` is another kind of file for edit

when you want upload a lot of files, only you have to do is
`git add *`

This command is used when you need to find a specific version of a project or know what changes will be made by merging into a function branch.
`git log`

when you want a python file, only put
`git commit -m "include a python file`

To upload the files to github, you only have to put the following command, and once you put it, a page will open for you to enter your credentials and grant that permission to upload the files
`git push -u origin main`

![enter image description here](https://i.blogs.es/852403/win10/1366_2000.jpg)

***Windows is an operative system***


To view files from the previous directory, put
`ls ..`

If you want to ignore a file, you should create the following
`nano .gitignore`, once created, within the text you have to put the file to ignore (the name)
to see all your data inside the folder, we must put
`git config --list`

Do you have any doubt about any git command? try putting this
`git help (command)`


`git diff` shows the version differences between one file and another

if you want to see the status of your shorter file, try putting
`git status -s` and then tell me

![enter image description here](https://www.tutsmake.com/wp-content/uploads/2020/01/Essential-git-commands-every-developer-should-know.jpeg)

***Git has a lot of commandes***


The command `git diff --cached` will show the content that has been added to the staging area, that is, the changes that will be included in the history if it is committed.

To delete files, just put `mr filename` and it will have been deleted, and to delete it from git, we must put` git mr filename`, and it will be completely deleted

to create branches you need
`git checkout -b" branch name "`

`git branch` shows branches, (you can use` git branch --list`)

to change branch is `git checkout" name of the wire "`

![enter image description here](https://www.tutorialdocs.com/upload/2018/10/git-basic-command.png)

***Whit that image will be easier watch what is happening***

`git log` shows all changes

`git merge (branch name)` is good for merging branches, but you must be inside one first
and it merges the files

`git push -u" origin "" name of the commit "` send your version to guthub

`git pull` shows changes that were made in github without your knowing it and already does the combios

`git fetch` with this it notifies you of the changes, but it does not make them, it only shows them


 `git diff --base (file-name)` with this we can make a list of conflicts between branches

`git diff (source-branch) (target-branch)` with this, you can see what the conflicts might be in case of merging branches

`git dff` generates flags on release commits

![enter image description here](https://devloteq.com/wp-content/uploads/2020/10/mejores-lenguajes-de-programacion-1024x640-1-640x400.jpg)
