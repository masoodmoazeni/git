# git
git information

```
git remote show origin
```

add .ignore to git 

```
touch .gitignore
echo 'application/cache' >> .gitignore
```

git new branch ---> git branch develop-visiton
reset for lats hash commit -> 

``` git reset --hard 7973f793cab3f2c9d09febdd74076e842a9597a2 ```

pull and commit to another branch
->->->

```
git add -p
git commit
git stash
git checkout new-branch
git stash pop
git push --set-upstream origin new-branch
```

list git log -> 

```
git log
```

switch to branch
```
git checkout -b  postgres-visiton
```

# git push to remote 
```
git remote rename origin upstream
git remote add origin URL_TO_GITHUB_REPO
git push origin master
```

# git config
```
git config --global user.name "My Name"
git config --global user.email "myemail@example.com"
gt config --list
```
