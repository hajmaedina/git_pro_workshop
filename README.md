# git_pro_workshop

**BRANCH & MERGE**


Isolating work in branches, changing context, and integrating changes
**git branch**
list your branches. a * will appear next to the currently active branch
**git branch [branch-name]**

create a new branch at the current commit
**git checkout [branch-name-where-you-want-to-go]**
switch to another branch and check it out into your working directory

work.../git add ., git commit -m "bla bla bla"/
**git push -u origin [branch-name]**

**!!stand in the branch where you want to merge your branch!!**
**git merge [branch-name]**
merge the specified branch’s history into the current one
(**git log**
show all commits in the current branch’s history)
