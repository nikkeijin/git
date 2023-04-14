# Useful Commands

```bash
git clone https://…
```

```bash
git status
```

```bash
git log
git log -p
git log —oneline
git log --author=“user_name"
```

```bash
git add “app.js”
git add .
```

```bash
git commit “app.js"  -m “qwerty"
git commit .  -m “qwerty”
```

```bash
git push
git pull
```

```bash
git restore —source XXXXXXX app.js
git restore —source XXXXXXX .
git reset --soft XXXXXXX
git reset --hard XXXXXXX
```

```bash
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
```bash
git checkout --orphan latest_branch
```

Add all the files   
```bash
git add -A
```

Commit the changes    
```bash
git commit -am "commit message"
```

Delete the branch   
```bash
git branch -D main
```

Rename the current branch to main
```bash
git branch -m main
```

Finally, force update your repository
```bash
git push -f origin main
```
