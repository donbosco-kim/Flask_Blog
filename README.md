# A flask blog application

This application have CRUD features implemented and user data are stored in sqlite3 database.

## Connecting a remote repository to github 
### These instructions are just for my reference
- create a new repo in github
- copy the https url
- type git init command in terminal
- type git remote add origin "your url here"
- type git branch -M main
- type git commit to commit any changes you made previouly (this part is important because you might get this error "error: src refspec main does not match any..." if you run git push -u origin main command without committing)
- git push -u origin main 