# gitgud
Allows you to git gudder by marginally simplifying the commit process. 

The useage is similar to regular git commits and pushes. This is what the add in does (if given a commit message):

1) git status (to check if there is anything needed to be done)
2) git add .
3) git commit -m " your given commit message "
4) git push 

- If a commit message is not provided, it will throw an error
- if there is nothing to push, it will throw a warning to the user


## How to use this
Git uses shell scripts you put into your git download folder location. **NOTE**: the file DOES NOT end in '.sh'. it is just 'git-gud'. 

Once you download this file, you can put the file into your git folder location. For example this is where my file lies:
- /usr/local/bin

location image:
![Location of git gud file](https://i.imgur.com/7sQQ05j.png)


## things to work on:
1) making the git cli interface smarter (ability to make force pushes, updating the origin, etc...)
2) error catching scenarios (i.e, if a commit message is only 1-5 letters, reject the commit)
3) Make this a cli package installation! This is very important

Sample usage:
![Sample useage image](https://i.imgur.com/tzLRpGz.jpg)
