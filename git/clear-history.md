On occasion it can be useful to clear your git history. 

Remove the history from local machine
```
rm -rf .git
```

Recreate the repos from the current content only
```
git init
git add .
git commit -m "Initial commit"
```

Push to the github remote repos ensuring you overwrite history
```
git remote add origin git@github.com:<YOUR ACCOUNT>/<YOUR REPOS>.git
git push -u --force origin master
```
