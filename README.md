# Useful Git Commands

- to see the files that is under tracked of Git
### git ls-files

- to rm a file from being tracked
### git rm --cached [filename]

- update the remote files
### git push [branch]

* error “refusing to merge unrelated histories”
- if you have problem pushing to remote repository, when you firstly worked the file without pulling, you get inconsistent histories. so this forces the pull
### git pull origin master --allow-unrelated-histories


- its best when you first work with a project to clone it, instead of working fresh on your local computer then git remote add later, it will have inconsistent files or history, however could be easily fixed. but just easier to clone it.
### git remote add origin https://<i></i>github.com/tingluhk/projectName
