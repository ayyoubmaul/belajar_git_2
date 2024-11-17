# belajar_git
1. Add intial Readme.md file
2. Initial Readme

# Steps
1. git init
2. git config user.name username-github
3. git config user.email email-github
6. Create new file
7. git status
8. git add .
9. git commit -m "adding new file (commit message)"
4. git branch -M main
10. git log
11. git checkout -b add/file
12. Modify file content/create new file
13. git status
14. git add <nama_file>
15. git status
16. git commit -m "adding substitute function"
17. git log
18. karena main tertinggal dengan branch add/file, kita harus merge main dengan branch add/file
19. git checkout main
20. git merge add/file
21. Craete new repository in github
22. git remote add origin https://github.com/ayyoubmaul/belajar_git_2.git
23. git remote -v
24. git push -u origin main
25. untuk melihat perubahan line git diff calculate_sub.py

![Alt text](image.png)

git clone
git checkout -b branch

Create file

git add .
git commit
git push


# Make conflicted commit
1. git checkout main
2. git pull origin main
3. git checkout -b <branch_name>
4. modify some lines
5. git add .
6. git commit -m "add some lines"
7. git checkout main
8. git checkout -b <some_other_branch>
9. add some modification on the same file in the same line
10. git stash
11. git merge <branch_name_in_point_3>
12. git stash pop
