# Projects-Repo

In README, we have 1 '#' to represent the text as heading. So,

This is a training repository for me to understand how the git works. So here in this Projects-Repo we will be adding our projects from undergrad to masters and learn how to work well with git.

## Understanding about README.md

README.md ? -> README file is generally used to describe what we are doing in this project.

'.md' means markdown. It's basically an easy way to format the text in these kind of files.

Let's Understand the commands that we use,

path : https://github.com/venkatasaimanojkumarmadiraju/Projects-Repo.git

 Step 1 : for cloning the repo to local we use, " git clone path (https://github.com/venkatasaimanojkumarmadiraju/Projects-Repo.git) "
 Step 2 : for moving into the folder we use " git cd folderName (Projects-Repo) "
 Step 3 : for listing everything in the given directory even the hidden folders we use " ls "
 Step 4 : To know the status of our changes we use " git status "
 Step 5 : Now for example, inside the Projects-Repo folder I already have a README.md file and is saved so, when I use " git status " command I can see README.md file as modified file. And if I try to make any changes or add a new file then it will not seen in New file section, instead it will be seen in untracked files section.
 Step 6 : To track the file we must use " git add . " command to save the untracked files. Now when we use git status command again we can see the new file in new files section.
 Step 7 : Now in order to commit these changes we use " git commit -m " command and "-m" indicates message saying what and why we are making these changes. So, the command will be like, git commit -m "Added New file (index.html)" -m "Some Description"
 
