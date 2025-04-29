Intro To Git: Learn the foundations of Git and version control | Learn with Dr. G





Introduction to Git Recap | Learn with Dr G



git config --list


git config --global user.email "femero1978@gmail.com"
git init


 touch index.html


git status


git add .
git commit index.html -m "Create an empty index.html file"


code index.html




git commit -a -m "Add a heading to index.html file"


git log --pretty=format:"%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset" -n 2 --author="femero1978" --all


git log --oneline



git diff


code .gitignore



git add -A



git commit -am "Make small wording change



mkdir CSS
touch CSS/ .git-keep


git add CSS





git commit --amend --no-edit



rm index.html


git checkout -- index.html


git rm index.html





git reset HEAD index.html


git checkout -- index.html


git commit -am "Erasing the contents of the style sheet"


git reset --hard HEAD^


git commit -am "Modifying index.html to include dogs -- BIG MISTAKE"


git revert --no-edit HEAD



git commit -am "Modifying index.html to include birds"
git commit -am "Modifying index.html to include fish"



git checkout 72168f9 .


git commit -am "Reverting back to only have cats in index.html"




![image](https://github.com/user-attachments/assets/8c8b26f6-b149-472b-9690-615cf6b3d6b5)
