# Useful Commands

```
git clone https://…
```

```
git status
```

```
git log
git log -p
git log —oneline
git log --author=“user_name"
```

```
git add “app.js”
git add .
```

```
git commit “app.js"  -m “qwerty"
git commit .  -m “qwerty”
```

```
git push
git pull
```

```
git restore —source XXXXXXX app.js
git restore —source XXXXXXX .
```

```
git branch

git branch development
git checkout -b development

git switch main
git switch development

git push origin main
git push origin development

git merge development
```

# Clear Commit History

Checkout    
```
git checkout --orphan latest_branch
```

Add all the files   
```
git add -A
```

Commit the changes    
```
git commit -am "commit message"
```

Delete the branch   
```
git branch -D main
```

Rename the current branch to main
```
git branch -m main
```

Finally, force update your repository
```
git push -f origin main
```
