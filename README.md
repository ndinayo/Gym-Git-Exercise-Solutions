# TheGym-Exercise 
## Bundle 1 
### Exercise 1
  ```bash 
   2 git init
   3 git status
   4 ls
   5 git branch
   6 git status
   7 git branch --list master main
   8 git branch
   9 git branch -r
  10 git status
  11 git status
  12 git branch
  13 git branch -m master main
  14 git branch
  15 git status
  16 git add .
  17 git status
  18 git branch
  19 git commit -m "Initial Commit"
  20 git remote add origin https://github.com/ndinayo/Bundle-1-Exercise.git
  21 git branch -M main
  22 git push -u origin main
  23 git pull origin main
  24 git remote add origin https://github.com/ndinayo/Bundle-1-Exercise.git
  25 git branch
  26 git push -u origin main
  27 git pull origin main
  28 git pull origin main --allow-unrelated-histories
  29 git push origin main
  30 git status
  ```
  ## Exercise 2
  ```bash
   2 git switch m
   3 git status
   4 git switch main
   5 git history
   6 history
   7 git status
   8 dit add README.md
   9 git add .
  10 git status
  11 git branch dev
  12 git branch list
  13 git branch
  14 git branch -d list
  15 git checkout dev
  16 git branch test
  17 git branch
  18 git checkout test
  19 git branch
  20 git checkout dev
  21 git branch -d test
  22 git branch
  23 git checkout main
  24 git brach
  25 git branch
  26 git status
  ```
## Bundle 2 
### Exercise 1
  ```bash
   2 git status
   3 git stash push -m "home.html Stash" -u
   4 git stash list
   5 git status
   6 git stash pop
   7 git stash push -m "home.html Stash" -u
   8 git stash push -m "about.html stashed" -u
   9 git stash list
  10 git stash push -m "team.html stashed" -u
  11 git stash list
  12 git stash pop "stash@{1}"
  13 git stash "stash@{2"
  14 git stash pop "stash@{2"
  15 git stash pop "stash@{2}"
  16 gist stash list
  17 git stash list
  18 git stash pop "stash@{1}"
  19 git add .
  20 git status
  21 git commit -m "about and home page"
  22 git branch
  23 git push
  24 git stash list
  25 git stash pop "stash@{0}"
  26 git reset --hard
  27 git status
```
## Exercise 2
```bash
28 history
  29 git branch
  30 git pull origin main
  31 git branch ft/bundle-2
  32 git branch
  33 git checkout ft/bundle-2
  34 git add ft/bundle-2
  35 git status
  36 git add services.html
  37 git status
  38 git commit -m "created services"
  39 git push origin ft/bundle-2
  40 git branch
  41 git checkout main
  42 git branch
  43 git pull origin main
  44 git branch ft/service-redesign
  45 git branch
  46 git checkout ft/service-redesign
  47 git branch
  48 git add ft/service-redesign
  49 git status
  50 git add services.html
  51 git status
  52 git commit -m "Add new changes to the service.html page"
  53 git push origin ft/service-redesign
  54 git checkout main
  55 git branch
  56 git status
  57 git add services.html
  58 git status
  59 git commit -m "Added body content"
  60 git push
  61 git add services.html
  62 git commit -m "feat: adding some changes to service"
  63 git push
  64 git branch
  65 git checkout ft/service-redesign
  66 git add services.html
  67 git commit -m "feat: adding previous services"
  68 git push
  69 git push --set-upstream origin ft/service-redesign
  70 git branch
  71 git diff main..ft/service-redesign
  72 git merge main
  73 git branch
  74 git checkout main
  75 git branch
  76 git checkout main
  77 git commit -m "Merge branch 'main' into ft/service-redesign"
  78 git checkout main
  79 git push
  80 git checkout ft/service-redesign
  81 git push
  ```